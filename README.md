![alt text](https://github.com/ljchang/dartbrains/blob/master/images/logo/logo.png)
[![DOI](https://zenodo.org/badge/171529794.svg)](https://zenodo.org/badge/latestdoi/171529794)
[![deploy-book](https://github.com/ljchang/dartbrains/actions/workflows/deploy-book.yml/badge.svg)](https://github.com/ljchang/dartbrains/actions/workflows/deploy-book.yml)
[![sphinx-linkcheck](https://github.com/ljchang/dartbrains/actions/workflows/sphinx-linkcheck.yml/badge.svg)](https://github.com/ljchang/dartbrains/actions/workflows/sphinx-linkcheck.yml)

# Stats Psy

Ressources ouverte pour l'apprentissage des statistiques en psychologie.

# Contributions

XXX

# Getting Started

Le projet est hébergé sur XXX. 


If you notice any mistakes or have idea for new content, please either open an issue or submit a pull request for us to review.

The website is built using [jupyter book](https://jupyter.org/jupyter-book/intro.html), which creates a jekyll website from markdown and jupyter notebooks. Please read their materials to learn more about this neat resource.

# Updating Book

X
1. **Clone the repo into your desired directory**

`git clone https://github.com/ljchang/dartbrains.git`

2. **Install packages**

`pip install jupyter-book`

3. **Build website locally**

By building the website locally you can preview any changes you make in your web browser. In other words, you will need to re-run this build command each time you make changes to the book to view them locally in your web browser. We are using the new version of jupyter-book which will run the notebooks to generate the figures by default. I find it helpful to keep 1-2 subjects in `~/Github/dartbrains/data/localizer`, which is in .gitignore so it will not get pushed to GitHub.

Before running the below command, make sure you are one directory up from the cloned repo `dartbrains` folder (i.e., do not be inside the `dartbrains` repo folder when running this command as it will throw an error).

`jupyter-book build dartbrains`

4. **Push updated book to GitHub on the master branch**

This will automatically trigger a workflow to sync the updated book to the `gh-pages` branch of our github repository, which ultimately deploys the website on DartBrains.org.
If you would like us to review your changes before pushing or deploying them, you can submit a pull request to the `master` branch and add `@ljchang` as a reviewer.

# License for this book

All content in this book is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0) license.

# Acknowledgments

Dartbrains was created by Luke Chang and supported by an NSF CAREER Award 1848370.

Our jupyterhub server was built and maintained by the Research Computing staff at Dartmouth. Special thanks to Arnold Song, William Hamblen, Christian Darabos, and John Hudson.
