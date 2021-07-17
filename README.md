# HTNW Documents

This is a Jekyll site. It provides a simple method for publishing documents. 
On the GitHub Pages infrastructure, hosting is free.  
Documents are created in Markdown format. When the site is built, they render as HTML and CSS.  
The decision to use this techmology was based on:  
1. Free. Wordpress site has a cost  
2. Display in iFrame. Google Sites no longer allow this.  
3. Versioning using GitHub.

## Modifications from the default theme.
This site uses the Jekyll Minima them, which supplies a menu, header and footer. Since documents are meant to b displayed in an iFrame on a dependent site, these featres have been turned OFF. This is so that the end user can only view the document provided, and not navigate to any other.  

## Maintaining the site
The site is owned by the RescueStationCIC organisation within GitHub.
The easiest way to maintain the site, is to become a collaborator on this specific project, by supply the project owners with your GitHub username.

The relavent files to change are all held in 

`HTNWDocuments/external/markdown`

### GitHub Pages
When published on GitHub Pages, the site is available at: 

`https://rescuestationcic.github.io/HTNWDocuments/`

It not advised to change the owning organisation: if this happens the GitHub Pages site address will also change, breaking any links which are dependent on it.

### Using the GitHub website 
This is the easiest way to maintain the site. 
Any file changes or additions cause an automatic rebuild of the site, and are avilable almost instantly.

You can edit files with the .md (markdown) filename extension.  
You can upload new files. 
If adding pictures, it's easiest to add them to the same directory as the markdown file they are referenced from and refer to them with a relative path. For example:

`![max_pic](./my_picture.png)`










