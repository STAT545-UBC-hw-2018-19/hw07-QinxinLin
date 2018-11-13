# Building your own R package

* This is the link to the [powers](https://github.com/QinxinLin/powers) package in github

* Install this package with `devtools::install_github("QinxinLin/powers")` in Rstudio and then load it with `library(powers)`.


# Reflection

* I spent a lot of time on writing Box_Cox transformation and log transformation functions, especially Box_Cox transformation. There are a lot of if-else statements to ensure it all works. Actually when I test Box_Cox function, it always shows errors with `expect_identical()`. Then I try to use `expect_equal()` instead of `expect_identical()`, no errors.

* Creating a package is not an easy task with so many steps and components. I have to check my package without errors all the time. It has two warnings of , but I think it is ok.  






