# hackerspace.gent docs

We ran into the issue that our Wiki got stale and became unmaintainable. After several failed attempts at making something better, we settled on mkdocs hosted on Github Pages. 

The mkdocs site should be automatically be rebuilt on push to main. Just add/update your pages and push.

## Steps to edit content
### Option 1: quick edit
On the page you want to edit, click the top right link to go to the Markdown file on Github and edit the page live at the github web front-end.

#### New page
When you add a new page, for example in the infrastructure section, update the `nav` section in [mkdocs.yml](https://github.com/0x20/docs/blob/main/mkdocs.yml) to expose the new page in the navigation. Example [commit](https://github.com/0x20/docs/commit/a3ea03642fe5ae08b4fd9196ddddc3189b56d596#diff-98d0f806abc9af24e6a7c545d3d77e8f9ad57643e27211d7a7b896113e420ed2)

#### Images
See [electricity page](https://github.com/0x20/docs/blob/main/docs/infra/electricity.md?plain=1) for an example how to add images. Take into account to reduce the size of the image, optimal for web usage, instead of raw pictures. Proposed convention: Use, or create when needed, an `images` folder, in the folder where the markdown file lives. (uses the [GLightbox plugin](https://squidfunk.github.io/mkdocs-material/reference/images/#lightbox).

#### Reference
Want to add diagrams, formatting,...? All options and documentation can be found in the [mkdocs reference](https://squidfunk.github.io/mkdocs-material/reference/).

### Option 2: bigger change with local review
Follow the steps at https://www.mkdocs.org/getting-started/

Summary:
- Clone this Git repo and enter the directory
- Install mkdocs `pip install -r requirements.txt`
- Run `mkdocs serve` and open up http://127.0.0.1:8000/ in your browser to see the generated pages
- Make your changes
