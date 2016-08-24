# Solace Samples Template

The goal of this project is to host all common files for a Solace Samples repo gh-pages branch. This should mean that new projects simply merge from here into their gh-pages branch, updates a few tutorials and their up and running with samples. Additionally changes to the template can be pushed out by merging from this repo into the gh-pages branch. Nothing should overlap.

To merge changes to a Samples project from the template, you would use the following commands:

    git remote add samples-template https://github.com/SolaceSamples/solace-samples-template.git
    git fetch samples-template
    git merge samples-template/gh-pages
    git remote remove samples-template
