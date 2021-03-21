# R programming notes

- [R programming notes](#r-programming-notes)
  - [Todo](#todo)
  - [Description](#description)
  - [Installation](#installation)
    - [Installation in WSL(2)](#installation-in-wsl2)
  - [RStudio/RStudio server](#rstudiorstudio-server)
    - [Starting from the command line](#starting-from-the-command-line)
  - [Useful resources](#useful-resources)

## Todo

- [ ] Work through [Chapter 1 of ModernDive](https://moderndive.netlify.app/1-getting-started.html).

## Description

These notes were taken by [ Matthew Haines](hainesm6@gmail.com) as part of learning R programming.

## Installation

Similar to many programming languages, R programming often occurs within an IDE rather than directly from the command line.

### Installation in WSL(2)

- I recommend using RStuido initially given it is the most popular IDE for R programming.
- As of writing, recent instructions for installing r-base and RStudio server were found on the [RStudio support website](https://support.rstudio.com/hc/en-us/articles/360049776974-Using-RStudio-Server-in-Windows-WSL2).

## RStudio/RStudio server

### Starting from the command line

- Launch from the command line as follows:

```bash
$ sudo rstudio-server start
```

- RStudio server is then available at http://localhost:8787
- 

## Useful resources

- https://cran.r-project.org/doc/manuals/r-release/R-admin.html#Installing-R-under-Unix_002dalikes
- https://moderndive.netlify.app/index.html -- Chapter 1 is recommended by RStudio and it seems to cover a lot of key concepts in statistics and R. 
