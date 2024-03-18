# hrsjournal

## Instructions for Website Editors

### How to start

1. Make a [Python virtual environment](https://github.com/dkessner/CSProjects/blob/main/hello_venv/readme.md)
2. Install the required software into the virtual environment (see requirements.txt)
3. Explore the Github repository to get a sense for the site's organization

### Terminal Commands

#### To test journal locally

1. Navigate to hrsjournal folder
2. Run these two commands in Terminal: 
```
jb clean journal
jb build journal
```

#### To publish journal online

1. Navigate to hrsjournal folder
2. Run these three commands in Terminal: 
```
jb clean journal
jb build journal
ghp-import -n -p -f journal/_build/html
```

If you are getting an error about password authentication when trying to run ghp-import, you'll need to make a personal acccess token via Github. Then, after you run the command, copy the personal access into the space where it prompts you to insert your password.

### Formatting 

#### General JupyterBook Formatting

sampleJupyterBook is the sample Jupyter Book that Jupyter provides in its tutorial - you should look in here if you have questions, or check out Jupyter's online documentation.

##### Changing the sidebar

[ NEED TO MAKE ]

#### MARS-Specific Formatting

In _static_ folder, there is a file called custom.css. Here is where you should put any changes you want to make to the css.

See the sampleWebsiteFormat for a basic outline on the naming conventions and format for author pages and articles. You can also always explore the issue1 folder to get a feel for how each issue should be organized.

### Brand Guide

[ NEED TO MAKE ]

## Miscellaneous Stuff

### Old - Staff Positions

<div style="text-align: center; border-width: 3px; border-style:dashed; border-color:#E7D2FF; padding: 1em;"> 

<p> </p>

<div class="row">

<div class="column">

***Sciences***

Sciences Editor-In-Chief

Sciences Editors

</div>

<div class="column">

***Humanities & Social Sciences***

Humanities & Social Sciences Editor-In-Chief

Humanities & Social Sciences Editors

</div>

<div class="column">

***Website***

Website Editor-In-Chief

Website Editors

</div>

</div>