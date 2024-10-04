# mkdocs_template
A custom MkDocs configuration set up as a template repository to be used for any future documentation.  
It runs inside a Docker container and has a builtin PDF export through a website.  
The website can be set up to be running and also configured to be connected to the git repository which shows the branches and the last updates. I didn't have a use for it, since I just need a markdown PDF export.  

### Configuration
The template is configured in that way, that all the *name.md* files are to be referenced in the *NAV.md* which is used as a table of contents.  
The allowed depth of the title is three **###**.

### PDF-Export
THe PDF is exported through running the program normal through VS-Code. Opening the created website and clicking on the PDF logo in the top right corner will generate a PDF file.

### Mention
This template is not set-up by me, rather by a friend. You can check his Github: https://github.com/InfinitePain