# eis1600.github.io

## Project website

- switching to a monolingual website (too much work otherwise and no resources for that);

- the website data is in the subfolder `./theme_stack/`

- you can open the entire project using the *.Rproj file in RStudio

- `blogdown` library must be installed; information on this library and how to use it: <https://bookdown.org/yihui/blogdown/> (the book is downloadable; created with `bookdown` package, developed by the same person, Yihui Xie, in collaboration with some others);

- you can start the live server with `blogdown::serve_site()`;
- the server can be stopped with `blogdown::stop_server()`

- posts and pages are created in subfolder `content`;

  - `post` :: create a subfolder using the same pattern as those that are already there (starting with the date! The post will be made available on that date; using date from the future will make the post published on the future date (I think...)); inside the folder one must create `index.en.md` (the easiest might be to copy-paste);
    - changing `en` to other languages to make translations (`de`, `ar`, `fa`, `ru`, etc.); 

- to edit tags and categories: `./theme_stack/i18n/` --- language-specific files;

- **IMPORTANT**: for any dsynamic processing (like references from bibliography), the file must be `.Rmd`, from which `blogdown` will generate a static `.md` file.

## References

- they work only in Rmd files, not in md files; so, make sure that all the page and post files are `*.Rmd`, if a citation is needed.


## Notes

- [x] add "peer-reviewed" to keywords;
- [x] add information on TY current position;
- ...