# hackerspace.gent docs

We ran into the issue that our Wiki got stale and became unmaintainable. After several failed attempts at making something better, we settled on mkdocs hosted on Github Pages. 

The mkdocs site should be automatically be rebuild on push to main. Just add/update your pages and push.

## Steps to edit content
### Option 1: quick edit
On the page you want to edit, click the top right link to go to the Markdown file on Github and edit the page live at the github web front-end.

### Option 2: bigger change with local review
Follow the steps at https://www.mkdocs.org/getting-started/

Summary:
- Clone this Git repo and enter the directory
- Install mkdocs `pip install -r requirements.txt`
- Run `mkdocs serve` and open up http://127.0.0.1:8000/ in your browser to see the generated pages
- Make your changes