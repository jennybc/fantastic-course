# fantastic-course

The goal of fantastic-course is to demonstrate how

``` r
usethis::use_course()

# and its less pedantic friend

usethis::use_zip()
```

can help an instructor drop students into a well-named, organized set of files for a painless start of a course or workshop. If there's an `.Rproj` file, it
will even open in RStudio.

How to call `use_course()` (or `use_zip()`):

``` r
library(usethis)

# GitHub "Download ZIP" URL
use_course("https://github.com/jennybc/fantastic-course/archive/master.zip")

# GitHub repo spec
use_course("jennybc/fantastic-course")

# DropBox folder
use_course("https://www.dropbox.com/sh/12345abcde/6789wxyz?dl=1")

# Put any of the above behind an easy-to-type shortlink
use_course("rstd.io/yaasss")
```

Full details in the docs:

  * [`use_course()`](https://usethis.r-lib.org/reference/use_course.html)
  * [`use_zip()`](https://usethis.r-lib.org/dev/reference/zip-utils.html) *dev version only*
