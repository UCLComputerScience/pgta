# UCL CS PGTA process information

## About the GitHub pages

All files are in the **gh_pages** branch.

The site uses a modified version of the [jekyll minimal theme](https://github.com/pages-themes/minimal).

The pages are visible at <https://uclcomputerscience.github.io/pgta/>

## To edit an existing page

Edit the markdown files in the root. 

When you commit the change a GitHub Actions workflow runs that updates the web pages. 

## To add a new page

Create the text content for the page in a markdown file and save it in the root.

To add it to the sidebar menu then edit [/_includes/sidebar.html](./_includes/sidebar.html) and follow the syntax.

As above, commit the change which will trigger the workflow to update the site.

## To edit the theme
Edit [_layouts/default.html](./_layouts/default.html)
