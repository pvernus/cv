```{r}
#| echo: false
library(fs)
sink("README.md")
dir_tree(recurse = TRUE, type = "any")
sink()
```
