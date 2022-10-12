# Hugo on GitHub Pages with Forestry and Netlify

![1665573005176](image/README/1665573005176.png)

Smartworkz's static (web) site is based on the following integrations:

- [Hugo](https://gohugo.io/) a static site generator installed on your local machine for rapid static site design and development
- [Github](https://github.com/) to store backups
- [Forestry](https://forestry.io/) a static site CMS hosted service for daily content creation/editing
- [Netlify](https://www.netlify.com/) a static file hosting serviice to watch Github for any changes and build/deploy as needed

  ![1665575738841](image/README/1665575738841.png)

## Prerequisites

* If not already done, *Install [Hugo](https://gohugo.io/getting-started/installing/)*
* If not already done, *Install [Visual Studio Code](https://code.visualstudio.com/download) (VSC)*
* If not already done, *Install [Git Bash](https://git-scm.com/downloads)*
* *(Optional) Configure Git Bash as the default terminal for VSC*

  1. Click View, Terminal
  2. After the Terminal appears, press the F1 key
  3. Type the following, Terminal: Select Default Profile
  4. Select from the dropdown, Git Bash

## Getting started

* *Navifate to your local Git repository*

  ![1665575311635](image/README/1665575311635.png)
* `cmd` *in your File Explorer path and press the Enter key*

  ![1665575439078](image/README/1665575439078.png)

  The command window prompt opens:

  ![1665575506979](image/README/1665575506979.png)
* `code .` *in the prompt and press the Enter key*

  ![1665575649406](image/README/1665575649406.png)

  The Visual Studio Code (VSC) application opens
* *Trust the Authors and on the Menu click View and select Terminal*

  ![1665575940981](image/README/1665575940981.png)

  The Git Bash terminal appears:

  ![1665576000232](image/README/1665576000232.png)
* *Clone a Hugo Template of this site*

  This contains all the files used to generate the site, not the site itself. Later, will create another separate repository to host the static (web) site files

  ![1665576136976](image/README/1665576136976.png)

  `git clone https://github.com/smartworkz-kyriacos/smartworkz-site.git`

  Clones the repository in the local git repository path

  ![1665576298128](image/README/1665576298128.png)
* `cd` into site

  ![1665576668407](image/README/1665576668407.png)

  `cd smartworkz-site`
* Check status

  ![1665576391255](image/README/1665576391255.png)

  `git status`
* *Check directory structure*

  ![1665576509518](image/README/1665576509518.png)

  ```
  ls
  ls -la
  ```
* *Check smartworkz-site tree view*

  ![1665576788318](image/README/1665576788318.png)
* *Open and log in to your [GitHub account](https://github.com/)*
* *Create a GitHub repository for the generated static (web) site files*
  Let the repository itself to remain as default Public
  ![1665578273247](image/README/1665578273247.png)

  The name of this repository follows the format `<USERNAME>.github.io`
* 
* 
* 
* 

### Local hosting

To start, use the following command: hugo server This will set up the site locally and allow it to be viewed at the address specified in the shell (usually http://localhost:1313).


[![Netlify Status](https://api.netlify.com/api/v1/badges/6eac4cea-1da3-46fd-9213-24c3114d204e/deploy-status)](https://app.netlify.com/sites/boring-heisenberg-e4c346/deploys)
