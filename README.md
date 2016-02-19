# Welcome!

This repo is for tracking initiatives of the Mozilla Learning Networks team.

### Adding new pages the Easy! way

1. Download the [Template Folder zip file](https://github.com/mozilla/learning-networks/releases/download/1/clubs-blank-template.zip)
2. Unzip it
3. Edit the ``content.md`` file only
4. Rename the folder to match the content title
5. Drag and drop the finished folder into the ``clubs`` folder on the ``gh-pages`` branch - (Right Here)[https://github.com/mozilla/learning-networks/tree/gh-pages/clubs].
6. Your new page will be available at ``http://mozilla.github.io/learning-networks/clubs/name-of-your-folder``

### Adding new pages using the template

This assumes that you are already familiar with how to make changes in this repo. If you're not, read the section below.

1. Duplicate the ``blank-template`` folder and rename it to match the new page title
2. Edit the ``content.md`` file in that folder.
3. The navigation items in the left-side navigation will be automatically added for every primary and secondary heading
  * Keep these headings short if possible
4. The ``<title>`` tag in the HTML will set to the content in the main title in ``content.md`` file
5. When you're done and push your changes to the main repo, your new page will be available at ``http://mozilla.github.io/learning-networks/clubs/name-of-your-folder``

### Setting up your environment & making changes to content

This briefly describes the steps you'll need to take in order to make changes to this content on your local machine. It's also possible to make changes directly on the Github UI - which is also an option.

1. Create a personal copy of this repo using the **Fork** button in the top right corner of this page.
2. On the commend line in your terminal, clone your forked version
  * This creates a version of the files in this repo on your computer
3. Switch to the folder that contains the repo on the command line command and check out the ``gh-pages`` branch
  * Run ``git checkout gh-pages``
4. Create a new branch for your edits
  * Run ``git checkout -b your-branch``
  * Use a name that describes your changes
5. Make your edits and changes
6. Commit your changes and push them to your fork
7. On the Github website, create a Pull request from your branch to the original repo's ``gh-pages`` branch
