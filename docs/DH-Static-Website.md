# Static Websites

I decided to use MKdocs since I am more familiar with Python and this is what we use at work to create internal wikis. I have never set up a project for this or managed the configuration, so this will be a fun learning experience.

[https://www.mkdocs.org/getting-started/](https://www.mkdocs.org/getting-started/)

I already have python installed so I can easily add this package and use it.

- `python -m venv .venv` Create python virtual environment
- `source .venv/Scripts/activate` Start the virtual environment
- `python -m pip install mkdocs` Install the Markdown Docs tool
- `python -m mkdocs new .` Create a new project in my existing repo/folder

I then moved all of the existing markdown files I had into the docs/ folder.
In the mkdocs.yml, I can then register the different markdown files as locations on the site.

And finally I get to build the markdown into a static site: `python -m mkdocs build`