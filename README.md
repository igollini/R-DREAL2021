# Introduction to R at D-REAL summer school June 15th 2021

Organiser and instructor: [Isabella Gollini](https://sites.google.com/site/isabellagollini/)  <isabella.gollini@ucd.ie>, Assistant Professor in Statistics, University College Dublin, Ireland.

**Topic covered:**

*Part 1: Introduction to R and RStudio*: This session will give an overview of R and RStudio as well as an introduction to dynamic documents with R Markdown. The session will continue by providing practical examples to help users get the most out of the data import and handling tools.

*Part 2: Data manipulation and exploration with R*: This session will demonstrate how to use the R package `dplyr` to perform data manipulation by filtering, selecting and mutating variables, and to obtain summaries. This talk will continue with an overview of visualisation techniques using base R and the package `ggplot2`. Throughout this session we will make use of R Markdown to create automating reproducible analysis.

## Computing requirements

During the sessions there will be limited time for the students to practice, and they need to have the following installed **prior** to attending the sessions:

- R (>= 4.0.5)
- RStudio (>= 1.4.1106)

If you have older versions of R/RStudio installed, it is recommended that you
install the latest versions if possible. Instructions for installing all these
software is given below.

In addition, please install/update the following R packages available on CRAN:

- `rmarkdown`
- `tidyverse`
- `skimr`
- `rio`

## Installing R

Download the pre-compiled binary for your OS from https://cloud.r-project.org/
    and install. More specifically:

**For Windows**

Click "Download R for Windows", then "base", then "Download R 4.1.0 for Windows". This will download an `.exe` file; once downloaded, open to start the installation. If you do not have administrator rights, the installer will default to install in your Documents folder - if you prefer, you can change the location to another folder that you have write access to.

**For Mac**

Click "Download R for (Mac) OS X", then "R-4.1.0.pkg" to download the installer. Run the installer to complete installation.

**For Linux**

Click "Download R for Linux". Instructions on installing are given for Debian, Redhat, Suse and Ubuntu distributions. Where there is a choice, install both `r-base` and `r-base-dev`.

## Installing R Studio

Downloads are available from <https://www.rstudio.com/products/rstudio/download/#download> (scroll to the end of the page to see the downloads).

**For Windows with no admin rights**

Download the `.zip` source archive under "Zip/Tarballs". Extract the files to a folder where you have write access, e.g. `C:\Users\username\RStudio`. In this folder, open the `bin` directory and find the RStudio program: it is named `rstudio.exe`, but the file extension will typically be hidden, so look for `rstudio`. Right-click this executable to create a desktop shortcut. Double-click the executable or use the shortcut to open.

**For all other operating systems**

Download the relevant installer for your OS listed under "Installers for Supported Platforms". Run the installer to complete installation.

## RStudio Cloud

If you cannot get your computer set up, you will be able to use RStudio Cloud <https://rstudio.cloud/>.

