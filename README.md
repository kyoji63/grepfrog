# grepfrog 


[![build](https://github.com/kyoji63/grepfrog/actions/workflows/build.yaml/badge.svg)](https://github.com/kyoji63/grepfrog/actions/workflows/build.yaml)
[![Coverage Status](https://coveralls.io/repos/github/kyoji63/grepfrog/badge.svg?branch=main)](https://coveralls.io/github/kyoji63/grepfrog?branch=main) [![Rust Report Card](https://rust-reportcard.xuri.me/badge/github.com/kyoji63/grepfrog)](https://rust-reportcard.xuri.me/report/github.com/kyoji63/grepfrog)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<br>

This repository is a university coursework repository. 🏫<br>
"grepfrog" is a command that aggregates file modification commands.<br>



I will gradually add more functions...

# Usage

The standard function is based on the grep command, which replaces the searched string with the string "frog".<br>

```sh
$ grepfrog -h
grepfrog <COMMON_OPTIONS> [FILE]
COMMON_OPTIONS
    -c, -change <String1> <String2>   Change <String1> to <String2> in the file.
    -e, -encode <String>              Encode to the specified character set.
    -h, -help                         Prints this message.

```


# About
### Logo

<img src = "https://github.com/kyoji63/grepfrog/blob/main/site/static/images/grepfrog.png" width = "150">

This image comes from https://freesvg.org/frog-silhouette-polygonal-pattern .

### Project name come from?
The name of this project comes from the japanese word 'kaeru', which means 'conversion'.


### Development language
Use Rust, the language specified in the class.


