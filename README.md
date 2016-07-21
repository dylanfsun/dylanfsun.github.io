# dylanfsun.github.io
## How-to
1. Downloaded RStudio preview
2. Created an RStudio project; set the directory as the dylanfsun.github.io directory
3. There are two panels on the right side: Build and Git
  * In the git panel click the items you've edited to mark them and then click commit. After committing, push using the up arrow.
  * In the build panel, click "Build Website" when you're done editing Rmarkdown files to generate .html files that you can then commit and have show up on the website
4. The RMarkdown files are _site.yml, index.Rmd, and any other .Rmd files. Clicking "Build Website" creates .html versions of any .Rmd files.
  * _site.yml contains information for the table of contents panel
  * All .Rmd files, once built into .html files, produce pages that can be accessed via the table of contents panel.
  * To edit individual pages, just knit the .Rmd when you're done (or directly edit the notebook and just save)

I followed instructions found [here](http://rmarkdown.rstudio.com/rmarkdown_websites.html).
