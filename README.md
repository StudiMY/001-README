READ THIS IF YOU'RE NEW: Overall description of StudiMY curriculum and project structure.

# What
StudiMY is an initiative by MARIMORE ENGINEERING SDN. BHD. (925539-H) with
help from [Xoxzo Inc](https://info.xoxzo.com/en/) to create
and maintain a study curriculum and materials for the teaching of programming in a classrom
environment, guided by a mentor. These curriculum and materials are licensed under the
Creative Commons and is available for anyone to use.

## What is this repository
This repository will contain the overall idea on what StudiMY is and how you
can use the materials in the project.

Go to [StudiMy: A practical curriculum to programming in Python](https://studimy.github.io/001-README/)
to read it.

# Making changes
We use Sphinx to produce the documentation for this repository. You can add new
text or change the current text by making changes to files in the
**docs/source** directory.

Files for themes such as .css files should be placed in **docs/source/static**
while images should go to **docs/source/images** directories.

Once you're done making changes, run
```
cd docs
make html
```
to produce the html files, which will replace the files in the docs directory.
You can verify your changes by accessing the **docs/index.html** file.

## Publish to GitHub
If you have access to the *master* branch, commiting and pushing the master
branch after *make html* will automatically publish the changes to GitHub Pages.

Remember that we need to have the file *.nojekyll*  in the *docs* directory in
order for GitHub to correctly read our \_static and \_images files.

# Licensing
All materials produced by StudiMY are licensed under [Creative Commons Ver
4.0](https://creativecommons.org/licenses/by/4.0/)
(CC BY 4.0). You are free to use the materials released under this project provided that
you agree to adhere to the  terms of the license.

# Questions? Requests?
If you have a specific request or a fix to a particular part of the curriculum,
please file an Issue or Pull Request in the specific repository.

Any other questions can be directed to help@studi.my
