# hrsjournal

## Instructions for Website Editors

### How to Start

1. Make a [Python virtual environment](https://github.com/dkessner/CSProjects/blob/main/hello_venv/readme.md)
2. Install the required software into the virtual environment (see requirements.txt)
3. Explore the Github repository to get a sense for the site's organization

### Terminal Commands

#### To Test Journal Locally

1. Navigate to hrsjournal folder
2. Run these two commands in Terminal: 
```
jb clean journal
jb build journal
```

#### To Publish Journal Online

1. Navigate to hrsjournal folder
2. Run these three commands in Terminal: 
```
jb clean journal
jb build journal
```

If you are getting an error about password authentication when trying to run ghp-import, you'll need to make a personal acccess token via Github. Then, after you run the command, copy the personal access into the space where it prompts you to insert your password.

### Formatting 

#### General JupyterBook Formatting

In the root directory, sampleJupyterBook is the sample Jupyter Book that Jupyter provides in its tutorial - you should look in here if you have questions, or check out Jupyter's online documentation.

##### Changing the Sidebar

All changes to the sidebar should be done in the toc.yml file - 'toc' stands for 'table of contents.' Copy the formatting of Issue 1 to make updates to the sidebar. If a file is not listed on toc.yml, it can still be accessed via its URL or a button on the page, but it will not appear in the sidebar. For example, author pages are not included in the sidebar, but they can still be accessed online.

All issues and articles should appear on the sidebar. See the formatting of Issue 1 for more questions.

#### MARS-Specific Formatting

In the static folder, there is a file called custom.css. Here is where you should put any changes you want to make to the css.

See the sampleWebsiteFormat for a basic outline on the naming conventions and format for author pages and articles. You can also always explore the issue1 folder to get a feel for how each issue should be organized.

### Brand Guide

*Dr. Ponzio is hiring a graphic designer to do a CEI rebranding, so speak to her on updated logo, color, and font information.**

Look in the marlboroughBrandGuide folder for general information on Marlborough's color palette and fonts.

#### Logos and Other Images

Look in the images folder for logos (currently we are using the floral one). Also included are two decorative lines. 

#### Colors

The colors used on the site are currently close to but not exactly the same as those recommended by the Marlborough brand guide. See custom.css for the most updated color palette.
- **HEX260859**: *dark purple.* Links, H1, H3, H5
- **HEXffd200**: *yellow.* Hovered links, accent color
- **HEX7d6b9b**: *light purple* H2, H4, H6
