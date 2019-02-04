# ResBaz2019 lesson requirements and install instructions

[Dunedin ResBaz website](https://resbaz.github.io/resbaz2019/dunedin/)

Please check the software requirements for the lessons you want to attend. 

**[Install instructions](#software-install-instructions) are at the bottom of the page.**

## Lessons

### Monday 11th February

__Session 1:__ 10:30 - noon
* _Best practices for data organisation in spreadsheets_ 
    - Lesson: https://datacarpentry.org/spreadsheet-ecology-lesson/
    - Software: spreadsheet software (excel/libreoffice)
    - Data: [survey data](https://ndownloader.figshare.com/files/2252083)

* _Digital notebooks_
    - Lesson: custom lesson
    - Software: web browser (Chrome, Firefox, Safari, Edge, etc.)

* _Introduction to Data_
    - Lesson: https://librarycarpentry.org/lc-data-intro/01-introduction/index.html and https://librarycarpentry.org/lc-data-intro/02-jargon-busting/index.html and https://librarycarpentry.org/lc-data-intro/03-foundations/index.html
    - Software: web browser (Chrome, Firefox, Safari, Edge, etc.)

__Session 2:__ 2:00 - 3:00pm

* _Introduction to R_
    - Lesson: https://datacarpentry.org/R-ecology-lesson/00-before-we-start.html and https://datacarpentry.org/R-ecology-lesson/01-intro-to-r.html)
    - Software: [R](#r) and [RStudio](#rstudio)

* _Introduction to the Unix shell_
    - Lesson: http://swcarpentry.github.io/shell-novice/
    - Software: [Bash](#bash)
    - Data: [data-shell.zip](http://swcarpentry.github.io/shell-novice/setup.html) (*data-shell.zip*)

* _Introduction to pattern matching for text searching_
    - Lesson https://librarycarpentry.org/lc-data-intro/04-regular-expressions/index.html
    - Software: web browser (Chrome, Firefox, Safari, Edge, etc.)
   
* _Using patterns to find and edit files: grep/sed/awk_
    - Lesson: custom lesson
    - Software: [Bash](#bash)
   

__Session 3:__ 3:30 - 5:00pm
* _Data manipulation in R_
    - Lesson: https://datacarpentry.org/R-ecology-lesson/03-dplyr.html
    - Software: [R](#r) and [RStudio](#rstudio)
    - Data: [combined.csv](https://ndownloader.figshare.com/files/2292169)
   
* _Introduction to the Unix shell - Continued_
   
* _Introduction to NZ Open Data_
    - Lesson: custom lesson
    - Software:
        - web browser (Chrome, Firefox, Safari, Edge, etc.)
        - spreadsheet software (excel/libreoffice)
   
* _Breakout session_


### Tuesday 12th February

__Session 4:__ 10:30 - noon
* _Using version control to track changes_
    - Lesson: based on http://swcarpentry.github.io/git-novice/14-supplemental-rstudio/index.html and https://happygitwithr.com
    - Software:
        - [R](#r) and [RStudio](#rstudio)
        - [Git](#git)
  
* _Automating workflows with GNU Make_
    - Lesson: http://swcarpentry.github.io/make-novice/ see also https://kbroman.org/minimal_make/
    - Software: [GNU Make](#gnu-make)
   
* _Cleaning data with OpenRefine_
    - Lesson: https://librarycarpentry.org/lc-open-refine/
    - Software: [OpenRefine](#openrefine)
   
* _Breakout_
    - Advanced Google (Shiobhan custom session)
   
      
__Session 5:__ 2:00 - 3:00pm
* _Making functions in R_
    - Lesson: http://swcarpentry.github.io/r-novice-inflammation/02-func-R/index.html
    - Software: [R](#r) and [RStudio](#rstudio)
    - Data: [r-novice-inflammation.zip](http://swcarpentry.github.io/r-novice-inflammation/setup.html)
   
* _Reproducible computational environments using containers_
    - Lesson: custom lesson
    - Software: 
        - [Docker](#docker)
        - web browser (Chrome, Firefox, Safari, Edge, etc.)
   
* _Research data management_
    - Lesson: custom lesson
   
* _Creating and running scripts on the commandline_
    - Lesson: based on http://swcarpentry.github.io/shell-novice/06-script/index.html
    - Software: [Bash](#bash)
    - Data: [data-shell.zip](http://swcarpentry.github.io/shell-novice/setup.html)
   

__Session 6:__ 3:30 - 4:30pm
* _RMarkdown_
  - Lesson: https://swcarpentry.github.io/r-novice-gapminder/15-knitr-markdown/index.html
  - Software: [R](#r) and [RStudio](#rstudio)
   
* _Reproducible computational environments using containers - Continued_
   
* _Tidy data principles_
    - Lesson: https://librarycarpentry.org/lc-spreadsheets/
    - Software: spreadsheet software (excel/libreoffice)
    - Data: [training_attendance.xlsx](https://librarycarpentry.org/lc-spreadsheets/data/training_attendance.xlsx)
   
* _Breakout session_

    
### Wednesday 13th February

__Session 7:__ 10:30 - noon
* _Data visualisation in R_
    - Lesson: https://datacarpentry.org/R-ecology-lesson/04-visualization-ggplot2.html
    - Software: [R](#r) and [RStudio](#rstudio)
    - Data: [combined.csv](https://ndownloader.figshare.com/files/2292169)
   
* _Introduction to getting data from databases_
    - Lesson: (https://datacarpentry.org/sql-ecology-lesson/)
    - Software: 
        - [SQLite](https://www.sqlite.org/index.html)
        - [DB Browser for SQLite](http://sqlitebrowser.org/)
    - Data: [data](https://doi.org/10.6084/m9.figshare.1314459) (select download all)
   
* _Introduction to Github_
    - Lesson: custom lesson
    - Software: web browser (Chrome, Firefox, Safari, Edge, etc.)
   
* Special topic

__Session 8:__ 2 - 3pm
* _Making packages in R_
    - Lesson: see http://r-pkgs.had.co.nz
    - Software: [R](#r) and [RStudio](#rstudio)
   
* _Introduction to getting data from databases - Continued_
  
* _Introduction to Github - Continued_
   
* _Special topic_

## Software Install Instructions

Instuctions to install the software a required by the workshops are below. 

**If you stike difficulty there will be helpers available during the breaks of ResBaz to assist**

### BASH

[Software Carpentry](http://swcarpentry.github.io/shell-novice/setup.html) has a page with setup instructions for the shell lessons.

Linux and Mac users should already have an appropriate system installed which can be accessed via the Terminal.

Windows systems do not typically have a system installed but options are available. SWC encourages the use of Git Bash that comes with [Git for Windows](https://gitforwindows.org/), current version 2.20.1, choose the appropriate **.exe** and follow the instructions.


### Git

Windows/MacOS users please follow this link and download and install the file that matches your operating system
- https://git-scm.com/downloads

Linux:
- Debian/Ubuntu: sudo apt-get install git-core
- Fedora/RedHat: sudo yum install git-core



### R

Latest Release, 2018-12-20, Eggshell Igloo, R-3.5.2

* go to [Download R](https://cran.stat.auckland.ac.nz/) at the Auckland CRAN mirror site.
* Click on the "**Download R for *YOUR SYSTEM***" link at the top of the page.
* Click on the file containing the latest version of R under "Files."
   - for Mac it is the .pkg file
   - for Windows go to base then the Download at the top
   - Linux have various options and the best is to directly install from the command line.
    
            sudo apt-get update
            sudo apt-get install r-base
            

### RStudio

Before installing RStudio you need to have installed [R](#R)
Latest version 1.1.463

* Go to [www.rstudio.com](https://www.rstudio.com) and click on the "Download RStudio" button.
* Click on "Download RStudio Desktop."
* Click on the version installers recommended for your system, Windows, Mac and Linux are all supported.

after install, R-Studio should recognise your default R installation, if not you may have to direct R-Studio where to go.

[YouTube](https://www.youtube.com/watch?v=9-RrkJQQYqY) has a number of videos to help show the steps. [This](https://https://www.youtube.com/watch?v=9-RrkJQQYqY) one is for Windows 10

### OpenRefine

Please follow these setup instructions to install [OpenRefine](http://openrefine.org/download.html)

### GNU Make

Follow the instructions for the [GNU Make](http://swcarpentry.github.io/make-novice/setup.html) lesson to install the relevant software.

### Docker

(1a) If you have an Apple laptop (running macOS), carry out the four steps on https://docs.docker.com/docker-for-mac/install/ under heading “Install and run Docker Desktop for Mac”. [*1]
(1b) If your laptop runs Microsoft Windows, carry out the three steps on https://docs.docker.com/docker-for-windows/install/ under heading “Install Docker Desktop for Windows desktop app”. [*1]
(1c) If your laptop is running Linux, check out https://docs.docker.com/install/linux/docker-ce/ubuntu/ (see side menu for other flavours), but you may find that Docker is already installed, e.g., if the command `docker —version` does not produce an error. There are guides on the web for installing Docker for various flavours of Linux.

then

(2) Set up a free Docker Hub account at https://hub.docker.com.

and

(3) Set up a free Bitbucket account at https://bitbucket.org/ [*2]

Footnotes:

[*1] Various “Home” editions of Windows and some older macOS versions won't support installing Docker using the links above. You *may* be able to instead install the legacy Docker Toolbox https://docs.docker.com/toolbox/overview/ system but we’re unlikely to know for sure, given we don’t have the infrastructure to test this ahead of time. If you get stuck, bring your laptop along to the workshop anyway, and helpers present may be able to work with you to get a working Docker system on your laptop.

[*2] Bitbucket is akin to GitHub, but offers some functionality relevant to this lesson that is not yet as conveniently available within GitHub yet (GitHub Actions are in closed beta-release, and the alternatives using Travis, etc., are more complex and heterogeneous than we want the risk of taking on within this workshop).


### Other

Check ahead of the lessons you are interested in for any other setup requirements and data downloads. Wifi will be available.




