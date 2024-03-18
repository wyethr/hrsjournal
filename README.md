# hrsjournal

## Instructions for Website Editors

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

### Brand Guide

[ NEED TO MAKE ]

### Formatting 

See the sampleWebsiteFormat for a basic outline on the naming conventions and format for author pages and articles! You can also always look into the issue1 folder to understand the outline

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