## Steps to Create this Website

1.  Terminal:

    ``` bash
    quarto create
    ```

    `project`\>`website`

2. R:

    ``` r
    usethis::use_git()
    ```

3.  Terminal:
    
    ``` bash
    quarto render
    ```

    Adds right things to `.gitignore` if it exists (?)

4.  R:
    
    ``` r
    usethis::use_github()
    ```

5. Terminal:

    ``` bash
    quarto publish gh-pages
    ```

Works great!
