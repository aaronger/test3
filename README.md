testadd package
================

Starter code for a package with the function `add()`. Note that this
readme.md is generated by the readme.rmd file.

Readiness test:

-   Create a new branch “add_test” (either locally or remotely)
-   On this new branch, make the following changes locally:

1.  Edit the function add() such that it returns an error if x or y are
    not numeric

2.  Add a testing set up (as per demo on second last slide in ppt robust
    functions testing)

3.  Add a test for one of the following tasks:

    -   Verify that the function add gives an error when x or y are
        character strings or logicals (TRUE or FALSE), OR
    -   Verify that the function add returns the correct answer for some
        simple calculations, i.e. for x=1, y=2.

4.  Add an R script to run the test and check that the output is as
    expected, or use this readme.RMD file for that.

-   Commit and push these local changes.
-   Issue a pull request to merge your updated branch into your main
    branch.
-   Accept the pull request and then delete the add_test branch on
    GitHub. (You also can/should delete the add_test branch in your
    local repo but we won’t be able to check whether you do this!)
-   Understand that in a “real-world” situation it would usually not be
    a good idea to accept your own pull request. The purpose of a PR (in
    a repo you have access to) is usually to give your collaborators a
    chance to look at your work and agree to the merge…

Some code is added below that may be helpful

``` r
library(devtools)
```

    ## Loading required package: usethis

``` r
load_all("../test3") # with your name added
```

    ## ℹ Loading testadd

``` r
add(1, 2)
```

    ## [1] 3
