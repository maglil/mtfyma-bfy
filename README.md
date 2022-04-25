# mtfyma-bfy
This repository contains documentation about the goals of the study programs MTFYMA and BFY and how they are achieved.

Information that is related to creating the content of the document (structure of document, plan for development, evaluations, etc.) are placed in the appendix of the document. 

# Git structure
There are several permanent branches in the repository
- **main**: This branch contains versions of the document that are complete (i.e. without 'fill in more here' or empty section headers). They need not be final versions, i.e. they can be used as versions that are sent out for feedback. Official versions that are used to create and manage course contant are marked with a tag and given an official version name as *[yyyy-n]*.
- **develop**: This branch contains the most up to date version of the document and is the source for branches and merges for particular sections. Most work originate from here.
- **proof**: This is branched from *develop* and is proof-read before being merged into *main* as an official version (it is merged into *develop* at the same time).
- **errata**: This is branched from and merged to *main* to fix typos that are found in the *main*.
- **translation**: This branch contains translations into english of official versions in *main*.

In addition to these four branches, feature-branches are branched from develop to work on specific parts of the document. These branches should be named *feature-[some_feaure]-[username]*. Unless there are specific reasons not to, this branches should be deleted after merging into develop.

## Git practice
- It is good practice to start modifications by first creating a new branch.
- It is a good idea to open an issue and get feedback before starting a revision of a specific topic. 
- It is also a good idea to talk to other contributors in person if you think they might give valuable feedback.

# LaTeX structure
The document is written in LaTeX to facilitate version controll. 

## Key principles
- Keep it simple!
- Keep all preamble commands in a separate file *preamble.tex*
- All general layout modifications, custom commands should be placed in preamble.tex. No layout commands in section files.
- Avoid packages if possible
- Use packages rathern than custom commands if possible
- Comments that relate to latex coding are written in english. Comments that relate to the actual content are written in norwegian.

## Specific Latex choices.

The document class is *memoir*. Sectioning commands to be used are \part, \chapter \section \subsection \subsubsection.

Each section should be placed in it's own file. Subsections can also be in separate files if necessary. Use \include to include the subfiles in the main files.

The seperate files for each level are placed in a nested folder structure.

# Language

The document is written in norwegian.

# Code of conduct

- Be friendly and supportive. It will most often lead to better quality.
- Critique is important, but only in a constructive and friendly manner.

