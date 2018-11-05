# rlstevenson_mod
My update of the rlstevenson Jekyll theme (https://github.com/ExchangeRate-API/rlstevenson-jekyll-theme). Used on my website, julianbell.io.

## Structure
This theme is structured to provide a simple personal portfolio and blog that can be hosted as a GitHub Page. Briefly, the major moving parts on this site are:
- **Projects:** Projects are the primary focus of this website. Each project is contained in its own subdirectory in _projects. Each subdirectory must contain a Markdown file where the project is described and relevant metadata for the project (grid image, grid priority, images for carousel, etc.) is collected. Take a look at the example projects for structure and formatting examples. Images for each project should be contained in the project subdirectory. I find it convenient to contain other linked files in project subdirectories as well.
- **Posts:** Blog posts are written as Markdown files and contained in the _posts directory.
- **Pages:** Pages wind up being a second-class citizen in this template. The only pages that are used currently are the blog and the About pages. You can add more if you want!

## Other Useful Files
Some other places you may want to look:
- **/_config.yml:** Basic Jekyll configuration parameters for site.
- **/_data/menu.yml:** Defines items that show up in menu in sidebar.
- **/_sass/rlstevenson.scss:** Custom CSS for site. There are a bunch of canned color schemes from the original rlstevenson theme, as well as the custom theme that I added (scheme-jlb-invert).

Finally, as I'm sure is abundantly clear to most folks who might look at this, I have almost no idea what I'm doing with HTML/CSS, Jekyll/Markdown, or really web design as a whole. If you find problems with the template; if I've screwed up something related to licensing or attribution (unfortunately, likely); if you have suggestions for how the template could be improved; or if you just appreciate the template, please let me know!

