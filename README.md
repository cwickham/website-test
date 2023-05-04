## Steps to Create this Website 

```{.bash}
quarto create
```
`project`>`website`


```{.r}
usethis::use_git()
```

```{.bash}
quarto render
```
Adds right things to `.gitignore` if it exists (?)


```{.r}
usethis::use_github()
```

```{.bash}
quarto publish gh-pages
```

Works great!
