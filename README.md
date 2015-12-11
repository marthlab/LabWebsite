# How to Update Website

## Getting Started
#### For Small changes
1. Click on the file you want to change in github
2. Click the edit icon
3. Make desired changes
4. Make a commit with a commit message to save the changes

#### For Large Changes and Adding Files
1. Clone Repo
`git clone https://github.com/marthlab/LabWebsite.git`
2. Checkout gh-pages branch
`git checkout gh-pages`
3. Install Jekyll
`gem install jekyll`
4. Run Server
`jekyll serve`
5. Got to website
Paste `http://localhost:4000/LabWebsite/` into the browser

## How To Add Software
1. Go to `_tools` directory
2. Copy any of the files (e.g. freebayes.md) and rename it to the new tool name
3. Update each of the fields in the header (e.g. `toolname`, `homepage` url, `github` url)
4. Add a description after the header e.g in freebayes replace "A Bayesian genetic variant detector designed to find small polymorphisms" with the description of the new software

## How To Add Publications
Same as software (see above) except go to `_publications` directory

## How To Add People
Same as software (see above) except go to `_members` directory
