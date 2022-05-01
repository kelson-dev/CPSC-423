# CPSC 423 - Programming Language Implementation

Prereqs: [CPSC 423](https://github.com/kelson-dev/CPSC-423)

 * [Overview](#Overview)
 * [The Books](#The Books)
 * [License](#License)
 * [Code Style](#Code Style)

## Overview

This repository will follow 4 books about programming language implementation chapter by chapter by implementing their concepts in C# 10. 
The goals are as follows:

 1. Force myself, the maintainer of this repository, to actually read and learn the material in these books in great detail.
 2. Provide excellent educational material to other autodidacts wishing to learn about the design and implementation of programming languages.
 3. Provide an excuse to employ the latest C# language features.

The content here is a work in progress. Work will be done whenever I have time, as well as **every Tuesday at 6pm US Pacific Time** on my [twitch](https://www.twitch.tv/greendolph_).

## The Books

Here are the books I have chosen to cover in this repository. Prices listed here may be out of date, so check the commit history of this document if they are wrong.


### 1) Crafting Interpreters

**Crafting Interpreters** is an excellent free blog/book about the implementing `interpreters`.

| Key   |               Value |                                                                                           Link (not affiliated) |
|:------|--------------------:|----------------------------------------------------------------------------------------------------------------:|
| ISBN  |       9780990582939 |                                                                                                                 |
| Price | **FREE** to $60 USD |                                            Free at [craftinginterpreters.com](https://craftinginterpreters.com) |
| | | Paperback at [Barnes & Noble](https://www.barnesandnoble.com/w/crafting-interpreters-robert-nystrom/1139915245)                           |
| Authors |      Robert Nystrom |                                                                                                               |
| Copyright Date |                2021 |                                                                                                        |


### 2) Compilers: Principles, Techniques, and Tools 2nd By Alfred V. Aho

**Compilers** covers the general principles of implementing and utilizing `compilers`.

| Key   |           Value |                                                                                                Link (not affiliated) |
|:------|----------------:|---------------------------------------------------------------------------------------------------------------------:|
| ISBN  |  978-9332518667 |                                                                                                                      |
 | Price | $31 to $150 USD | Used or New at [Amazon](https://www.amazon.com/Compilers-Principles-Techniques-International-Economy/dp/9332518661) |
 | Authors | Alfred V Aho, Monica S. Lam, Ravi Sethi, Jefrey D. Ulman |                                                                          |
 | Copyright Date | 2007 |                                                                                                                       | 

### 3) Language Implementation Patterns

**Language Implementation Patterns** covers practical implementation patterns that allow you to "Create Your Own Domain-Specific and General Programming Languages"

| Key   |         Value |                                                                        Link (not affiliated) |
|:------|--------------:|---------------------------------------------------------------------------------------------:|
| ISBN  | 9781934356456 |                                                                                              |
| Price |       $24 USD | eBook at [pragprog.com](https://pragprog.com/titles/tpdsl/language-implementation-patterns/) |
| Authors |  Terence Parr |                                                                                            |
| Copyright Date |          2010 |                                                                                     | 

### 4) Types and Programming Languages

**Types and Programming Languages** specifically covers the theory and behavior of `type systems`. It is light on practical implementation insights and heavier on math, hence it will be the last book covered.

| Key   |             Value |                                                                            Link (not affiliated) |
|:------|------------------:|-------------------------------------------------------------------------------------------------:|
| ISBN  |     9780262162098 |                                                                                                  |
| Price |   $63 to $127 USD | Hardcover from [Powell's](https://www.powells.com/book/types-programming-languages-9780262162098)|
| Authors | Benjamin C Pierce |                                                                                                |
| Copyright Date |              2002 | | 

## Code Style

Each chapter of each book will have a pair of C# 10 projects targeting .NET 6.X.X. The first project will contain code that follows along with the chapter's content, and the second project will contain xUnit tests to "drive" the chapter code. Nothing IDE-specific will be included.

For C# coding style, everything is ["default"](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions) unless specified otherwise here:

 * Exceptions and Attributes should *not* be suffixed with the words "Exception" or "Annotation".
 * Local variables scoped to a function or method should be in `snake_case`.
 * Curly-brackets (`{` and `}`) should be ommited wherever possible.
 * Redundant parenthesis (`(` and `)`) should be included when they increase clarity or reduce ambiguity to a human reader not familiar with C#'s operator precedence.
 * File scoped namespaces should be used.
 * Global imports should be avoided.
 * "Nullable" reference type feature should be enabled.


## License

This repository is entirely educational and serves no commercial purpose. The content of the books will not be hosted here and are the property of their respective copyright owners.
All additional educational material here authored by Kelson Ball are licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

![CC](https://creativecommons.org/images/deed/cc_icon_white_x2.png) ![BY](https://creativecommons.org/images/deed/attribution_icon_white_x2.png) ![SA](https://creativecommons.org/images/deed/sa_white_x2.png)