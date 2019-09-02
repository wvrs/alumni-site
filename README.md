# WVRS Alumni Website
This repository hosts the code for alumni.wvrs.org. Currently, this website is hosted via Github Pages.

## Running Locally
_Advanced_

This project uses Jekyll. Jekyll is a static website generation tool. To run this project locally, follow instructions to [install and run Jekyll](https://jekyllrb.com).

Make sure to set your baseurl when running Jekyll locally to an empty string.
```
bundle exec jekyll --baseurl ""
```


## Updating Visually
If not developing locally, use the built-in visual file editor to Github.com. Read [this tutorial](https://help.github.com/en/articles/editing-files-in-your-repository) to learn how to edit a file. Best practices dictate someone else review your proposed changes before merging, however, if it is just you, you can commit the changes directly to the master branch.

Once your changes are made, your changes will be automatically deployed to Github Pages within a few seconds.

It would be helpful to understand what Markdown is and how to write it. Markdown is just a way to take a piece of text and format it to look a little nicer. [This amazingly easy yet useful tutorial](https://markdowntutorial.com/) has some educational materials.

## Common Changes
Most pages are located in the root directory. Edit the file to make your changes, using Markdown tags where needed.

### Adding Photos
1. Add your image to the [assets/images/gallery](https://github.com/wvrs/alumni-site/tree/master/assets/images/gallery) folder. 
2. Add the file name, and new section if desired, to the [gallery.yml](https://github.com/wvrs/alumni-site/blob/master/_data/gallery.yml) file.

### Adding Minutes or Forms
1. Add your file to the [files folder](https://github.com/wvrs/alumni-site/tree/master/assets/files).
2. Edit the appropriate data YML file in the [data folder](https://github.com/wvrs/alumni-site/blob/master/_data/).
