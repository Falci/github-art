# Github art

## Demo
[![Demo](https://github.com/Falci/github-art/blob/master/demo.png)](https://github.com/Falci?tab=overview&from=2012-12-01&to=2012-12-31)

## Instructions:

* Draw it. You can use this [this spreadsheet](https://docs.google.com/spreadsheets/d/1kzrWc_EYDM-r7eotcGF00HCtFAP8rdbgO6lYU072Cbo/edit#gid=0) to help you.
* Set the initial date. In my case it was 2012-01-01. It's important to be a Sunday. It can be older than your Github account. In the last line of the spreadsheet, in left corner, edit the script and add your initial date.
* Clone this repo: `git clone git@github.com:Falci/github-art.git` (you'd better use ssh)
* `cd github-art`
* Remove the .git folder: `rm -rf .git/`
* Start a new git repo: `git init && git add . && git commit -am "Initial commit"`
* Copy and run the script from the spreadsheet. 
* Create your own Github project.
* `git remote add origin git@github.com:<username>/github-art.git`
* `git push -u origin master`
* Profit

## Undo:
If you regret it, remove the repo form Github.
