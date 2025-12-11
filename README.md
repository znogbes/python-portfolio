*This file documents learning from building portfolio website (updated as website evolves)*

**Website's purpose:** serve as a curated space to display data science projects in python (i.e., code and outputs)

**Structure:**
- website is using github pages' theme minimal: https://github.com/pages-themes/minimal
- this theme has a pleasing layout, but requires repo follow a very specific structure for site to render correctly
- code is run via jupyter notebooks (which jekyll, the website generator, doesn't render)
- at the moment, using `_posts` folder which requires files to be named in `YYYY-MM-DD-file-name.md` format 

**Options to add python code:**
1. convert jupyter notebook to html (or markdown)
    - open anaconda prompt
    - set cd to location where jupyter notebook is 
    - run `jupyter nbconvert --to html book-name.ipynb`
    - if converting to markdown `jupyter nbconvert --to html book-name.ipynb`
2. reference markdown on website:
    - as its own page
        - markdown-generated file can be saved in a folder `_posts`
        - minimal theme is applied to file 
        - *disadvantage* : rendering plots is complicated, because reference paths have to be handled (folders like `assets` might need creating). This might generate a lot of manual fixes down the line.  
3. reference html on website:
    - as its own separate page
        - requires the html file to be saved under a `docs` folder
        - *disadvantage*: opening this file from website takes user to an isolated page with no theme applied, which makes it look disjointed from site
    - embed as part of a markdown page
        - this is the **preferred approach** so far because it renders code blocks and plots (it also seems to preserve interactive features from notebook, like table hovering)
        - create new `.md` file in `_posts` folder
        - in new file:
        
        `<div class="html-content">`

        `<!-- paste HTML content here from html-converted jupyter book between div's -->`

        `</div>`

        - make sure to remove first line from html-conversion `<!DOCTYPE html>`