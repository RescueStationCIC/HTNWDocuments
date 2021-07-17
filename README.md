# HTNW Documents

This is a Jekyll site. It provides a simple method for publishing documents. 
On the GitHub Pages infrastructure, hosting is free.  
Documents are created in Markdown format. When the site is built, they render as HTML and CSS.  
For example, [here](https://rescuestationcic.github.io/HTNWDocuments/external/markdown/higherford_mill/info_points/new_weaving_shed).  
The decision to use this techmology was based on:  
1. Free. Wordpress site has a cost  
2. Display in iFrame. Google Sites no longer allow this.  
3. Versioning using GitHub - can roll back the entire site to a previous release.

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

Using `max_pic` in the markdown picture reference is a way to tag the picture and apply a style, if needed, in this case, you might use `max_pic` to centre the picture horizontally, and apply a maximum size.

### Using your computer
The advantage of using your computer is that you can run the site locally, and check that all is OK, before publishing. 

#### You will need

* a copy of [GitHub Desktop](https://desktop.github.com/) 
* an installation of [Jekyll](https://jekyllrb.com/). You can find out how to install it [here](https://jekyllrb.com/docs/installation/).
* a markdown editor. I like [Dillinger](https://dillinger.io/)
* (optional, if you're used to Wordpress) Jekyll GUI - you can find more about it [here](https://github.com/jekyll/jekyll-admin)

**NB.1.** Take a little time to learn how versioning with Git and Git Hub works. You can dip a toe in the water [here](https://guides.github.com/activities/hello-world/).  
**NB.2.** Take a liitle time to learn about Markdown [here](https://daringfireball.net/projects/markdown/).  
**NB.3.** Jekyll uses a richer implementation of Markdown, called kramdown, so if you want to find out how to exploit that in your content, have a look [here](https://kramdown.gettalong.org/syntax.html). The thing to remember though, is that it's meant to simplify the way you write content. Take your time, and go at your own pace.

#### Seeing the site on your computer
You will download this repository to a folder on your computer, and go to that folder.

When you want to look at your site locally (on your own computer), Jekyll will start a web-server running on your own computer. 
You can find out more [here](https://jekyllrb.com/docs/#instructions).  
Jekyll will notify you that it's running, and provide you with the URL you can find your site at. You'll copy that to your clip-board go to your favourite browser, and paste it in. As mentioned above this will be the URL to the website holding the documenation. Because we made changes to the them to remove any navigation, you will need to provide the full path to your document.
Here's an example:

`http://127.0.0.1:4000/HTNWDocuments/external/markdown/higherford_mill/info_points/new_weaving_shed`











