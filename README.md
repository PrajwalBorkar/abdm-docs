# ABDM Docs - README

This is the repository for the new ABDM sandbox documentation currently under development. 
You can preview the documentation produced by this repo at [https://kiranma72.github.io/abdm-docs](https://kiranma72.github.io/abdm-docs)

If you want to contribute to improving the documentation, write with your github id to kiran.anandampillai@ispirt.in and we will add you as a collabrator to this project 

## For contributors

- This documentation uses [Hugo](gohugo.io) to build the final documentation site.
- The folder structure is very important. All pages are under the directory "content"
- Each folder under content represents a chapter
- The _index.md page contains the content for the chapter's starting page
- You can add as many pages to a chapter or create a new folder to create a sub-chapter
- The order of the pages are controlled by the "weight" parameter in the header of each page
- All pages are written using Markdown - Editor: [dillinger markdown editor](https://dillinger.io) and [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/) 
- Put images and other resources under the static folder. If you add to static folder reference your image using a path like /abdm-docs/img/<filename>
- Put images in the same content folder as the page your are editing. Reference the image using the path ../<filename> 


## Documentation Output 
Every time you checkin / update a file on this project, a action is automatcially (see the Github Actions tab). Hugo is used to build the final documentation set and this is pushed back into the repository under the **gh-pages** branch. 

To deploy the final site on your own domain you can fetch the **gh-pages** branch  
