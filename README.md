
#Project organization and how to use Git

##Using Git


##Proposed Project Structure

Every project *should* have a:

- Good, informative title
- README (with many of the things included in the top answer [here](http://stackoverflow.com/questions/2304863/how-to-write-a-good-readme))
- A license (which one, though?)
- Folders for each major class of files, for example:
  - M-files for running the experiment
  - Documentation
  - M-files for running analyses
  - (Empty, or only sample) data
  - Resources that aren't too big, and aren't generated on-the-fly
    - Sounds, images
  - Tests (esp. if moving from machine to machine)
  - Miscellaneous functions, scripts, etc.
- A .gitignore to keep undesirables (large datasets, identified data) out

The goal, I think, should be that each project can be completely run, from start to finish, using only files provided in the repo.

Similar projects (eg. All flavors of the Kinereach) should probably be maintained as separate branches, rather than multiple separate projects.

##Links
###Cheatsheet
https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf

###Starting out with Git
https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control


###Git and Github
https://help.github.com/articles/create-a-repo/


