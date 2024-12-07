# diffeqr

<details>

* Version: 2.1.0
* GitHub: https://github.com/SciML/diffeqr
* Source code: https://github.com/cran/diffeqr
* Date/Publication: 2024-12-04 18:30:02 UTC
* Number of recursive dependencies: 44

Run `revdepcheck::revdep_details(, "diffeqr")` for more info

</details>

## Newly broken

*   checking installed package size ... NOTE
    ```
      installed size is 10.8Mb
      sub-directories of 1Mb or more:
        doc  10.8Mb
    ```

## Newly fixed

*   checking whether package 'diffeqr' can be installed ... ERROR
    ```
    Installation failed.
    See 'D:/GitHub/JuliaCall/revdep/checks/diffeqr/old/diffeqr.Rcheck/00install.out' for details.
    ```

# knitr

<details>

* Version: 1.49
* GitHub: https://github.com/yihui/knitr
* Source code: https://github.com/cran/knitr
* Date/Publication: 2024-11-08 09:30:02 UTC
* Number of recursive dependencies: 85

Run `revdepcheck::revdep_details(, "knitr")` for more info

</details>

## Newly broken

*   checking running R code from vignettes ...
    ```
      'docco-classic.Rmd' using 'UTF-8'... failed to complete the test
      'docco-linear.Rmd' using 'UTF-8'... failed to complete the test
      'knit_print.Rmd' using 'UTF-8'... failed to complete the test
      'knitr-html.Rhtml' using 'UTF-8'... failed to complete the test
     ERROR
    Errors in running code in vignettes:
    when running code in 'docco-classic.Rmd'
      ...
    Error in loadVignetteBuilder(pkgdir) : 
      vignette builder 'litedown' not found
    ...
    
    ... incomplete output.  Crash?
    when running code in 'knitr-html.Rhtml'
      ...
    Error in loadVignetteBuilder(pkgdir) : 
      vignette builder 'litedown' not found
    Calls: <Anonymous> -> loadVignetteBuilder
    Execution halted
    
    ... incomplete output.  Crash?
    ```

*   checking package dependencies ... WARNING
    ```
    Skipping vignette re-building
    Packages suggested but not available for checking: 'litedown', 'targets'
    
    VignetteBuilder package required for checking but not installed: 'litedown'
    
    Files named as vignettes but with no recognized vignette engine:
       'inst/doc/datatables.Rmd'
       'inst/doc/knit_expand.Rmd'
       'inst/doc/knitr-intro.Rmd'
       'inst/doc/knitr-markdown.Rmd'
       'inst/doc/knitr-refcard.Rmd'
    (Is a VignetteBuilder field missing?)
    ```

*   checking files in 'vignettes' ... NOTE
    ```
    Files named as vignettes but with no recognized vignette engine:
       'vignettes/datatables.Rmd'
       'vignettes/knit_expand.Rmd'
       'vignettes/knitr-intro.Rmd'
       'vignettes/knitr-markdown.Rmd'
       'vignettes/knitr-refcard.Rmd'
    (Is a VignetteBuilder field missing?)
    ```

## Newly fixed

*   checking package dependencies ... ERROR
    ```
    Package required and available but unsuitable version: 'xfun'
    
    Packages suggested but not available for checking: 'litedown', 'targets'
    
    VignetteBuilder package required for checking but not installed: 'litedown'
    
    See section 'The DESCRIPTION file' in the 'Writing R Extensions'
    manual.
    ```

