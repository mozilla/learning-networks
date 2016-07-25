# Welcome!

This folder contains Mozilla Clubs guides & resources.

### Adding a new guide via drag & drop!

**Note** - Drag & drop does not work in Firefox! Please use Chrome.

1. Download the [Template Folder zip file](https://dl.dropboxusercontent.com/u/109902/blank-template.zip)
2. Unzip it
3. Edit the ``content.md`` file only
  * Try the [Brackets Editor](http://brackets.io/) - it's cool!
  * It's in markdown, here's a [handy syntax guide](https://guides.github.com/features/mastering-markdown/).
4. Rename the folder to match the content title, this will be a part of the URL so...
  * Make it all lowercase
  * Don't use special characters
  * Replace spaces with dashes (like-this)
5. Drag and drop the finished folder into the ``clubs`` folder on the ``gh-pages`` branch - [Right Here](https://github.com/mozilla/learning-networks/tree/gh-pages/clubs).

### Viewing a Published Guide

Your new page will be available at

``http://mozilla.github.io/learning-networks/clubs/name-of-your-folder``


### Editing existing pages

##### If you already have the  folder & files on your computer
1. Edit the ``content.md`` file on your computer and save it.
2. Drag the folder into the ``clubs`` folder (just like outlined above).
3. **Warning** - your content will totally override what is in the repo
4. Basic syntax guide https://guides.github.com/features/mastering-markdown/

Here is a handy **[Markdown Guide](http://mozilla.github.io/learning-networks/clubs/markdown-guide/)** to help you with formatting your content.


##### If it is not
1. Navigate to the ``content.md`` file you want to edit in the Github UI
2. Click the Pencil icon near the top right of the file contents
3. Use the **Preview** tab to check your changes.
4. When you're ready, click the **Comitt** button to save your changes

### Changing the name of the folder
Unfortunately, you can't do this within the Github UI, so you'll have to upload another folder with the correct name.
* You can delete the original folder by using the Github UI to delete the files within in (see below)

### Adding images

To display an image in a guide, use the following markdown syntax...

``![image alt text](https://example.com/image.jpg "Image Title Text")``

You can also add an image file to the folder that contains your guide, and then use the following markdown syntax to display it...

``![image alt text](image.jpg "Image Title Text")``

### Deleting Guides
1. Navigate to the specific file you want to delete
2. Click the **Trash** icon in the top right of the file content
3. If you delete both files in the folder, the folder will be deleted automatically

## Updating resource links on the Learning site

The links on the [Guides & Resources](https://learning.mozilla.org/clubs/guides) page on the Learning site are generated from the ``clubs-resoucres.json`` file found in this folder. When you make changes to this file, they will take effect immediately on the Learning site.

####Tips for editing this file

* The categories and links appear on the page in the order they are listed in the JSON file
* Before committing changes to the JSON (and thus making it live) please make sure the JSON is valid
  * To do so, you can copy and paste your JSON into a syntax helper like (JSONLint)[http://jsonlint.com/]
  * If there is an error in your published JSON, the entire list will fail to load