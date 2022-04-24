# mtfyma-bfy
This repository contains documentation about the goals of the study programs MTFYMA and BFY and how they are achieved.

# Git structure
There are several permanent branches in the repository
- main: This branch contains versions of the document that are complete (i.e. without 'fill in more here' or empty section headers). They need not be final versions, i.e. they can be used as versions that are sent out for feedback. Official versions that are used to create and manage course contant are marked with a tag and given an official version name as yyyy-n.
- develop: This branch contains the the up to date version of the document and is the source for branches and merges for particular sections. Most work originate from here.
- proof: This is branch from develop that is proofread before being merged into main as an official version (it is merged into develop at the same time).
- errata: This branche is branched from and merged to main to fix typos that are foundin the official branch main.

In addition to these four branches, feature-branches are branched from develop to work on specific parts of the document. These branches should be named feature-some_feaure. Unless there are specific reasons not to, thise branches should be deleted after merging into develop.

# LaTeX structure
The document is written in LaTeX to facilitate version controll. 

The document class is memoir


# Language
