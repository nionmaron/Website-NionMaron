# **Creating a website with no hosting cost**

This is an Rstudio-Quarto-GitHub-Netlify project

The resulting website can be viewed here: [nionmaron.netlify.app](https://nionmaron.netlify.app)

## **What is Quarto?**

-   Quarto^®^ is an open-source scientific and technical publishing system built on Pandoc

-   <https://quarto.org/>

## Project Flowchart

![](images/Website%20Nion%20Flowchart.png){fig-align="left"}

## Main steps of the project

1.  Install the necessary tools:

    -   Rstudio: [**https://www.rstudio.com/products/rstudio/download/**](https://www.rstudio.com/products/rstudio/download/)

    -   R: [**https://cran.r-project.org/**](https://cran.r-project.org/)

    -   Git: [**https://git-scm.com/downloads**](https://git-scm.com/downloads)

    -   R: [**install.packages("usethis")**](https://cloud.r-project.org/web/packages/usethis/index.html)

2.  Create a new RStudio project:

    -   Go to "File" \> "New Project" \> "New Directory" \> "Quarto Website".

    -   Choose a name for the project and a folder to save it in.

3.  Commit and publish to GitHub:

    -   Add all files to the Git repository with **`git add .`**

    -   Commit the changes with **`git commit -m "First commit"`**

    -   Create a new repository on GitHub and follow the instructions to add the remote repository and push the changes.

4.  Set up Netlify:

    -   Go to [**https://www.netlify.com/**](https://www.netlify.com/) and sign in or create an account.

    -   Go to "Sites" and click on "New site from Git".

    -   Select GitHub and authorize Netlify to access your repositories.

    -   Choose the project repository and configure the build options:

        -   Build command: **`quarto build`**

        -   Publish directory: **`_site`**

    -   Click on "Deploy site". Netlify will create a URL for your site and start building and publishing the site automatically.

5.  Update your project:

    -   Make changes to your project, commit, and push the changes to GitHub. Netlify will detect the changes and update the site automatically.

## **Author**

This project was developed by **Nion M Dransfeld**
