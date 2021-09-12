### [RStudio](https://www.rstudio.com/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/rstudio.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/rstudio/archive/master.zip) option and unzip them.

#### Activating theme

From RStudio click Preferences, Appearance, Add, and then navigate to the rstheme for the theme that you'd like to install. Click apply.

If you're comfortable installing from the console and have [Devtools](https://github.com/r-lib/devtools) installed then you can copy and run the following in your console:

```r
rstudioapi::addTheme("https://raw.githubusercontent.com/dracula/rstudio/master/dracula.rstheme", apply = TRUE)
```