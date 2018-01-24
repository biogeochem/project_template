# Project Template Repository
This repository is designed to serve as a template for the curation and maintenance of data within a specific project. Projects may either be a thesis chapter or a manuscript publication. 

## Project structure
All project repos are named according to the associated grant and labelled with a short informative tag for the project (e.g. grant_projectname'). In addition, they contain the following folders:

1. **data |** will contain separate folders for raw, cleaned, and processed data, as well as data from databases incorporated as submodules. For more information related to reading in and using submodules, see `UsingSubmodules.md`.
2. **code |** R scripts for processing and analyzing project information
3. **bin |** R scripts containing outside derived code
4. **src |** R scripts containing user derived code
5. **docs |** project notes, etc.
6. **Figs_Tables |** saved figures and tables from analysis

All databases should also contain a **README.md** file which details the following information:

1. Project title
2. Lead HQP
3. Other HQP
4. Lead PI
5. Other PI
6. Data sources
7. Funding sources

See `project_template-README.md` for an example of the information required in a project repository.

## Creating a new project for storage

1. Create new, empty repo on the lab group website: https://github.com/biogeochem, e.g. project_fun
2. Clone --bare the project_template into a folder and give it a new name, e.g. project_fun. Note the .git extension. `git clone --bare https://github.com/biogeochem/project_template.git project_fun.git`
3. Push the new template-based repo to github. `cd project_fun.git && git push --mirror https://github.com/biogeochem/project_fun.git`
4. Remove the clone --bare folder, e.g. project_fun.git. `cd .. && rm -Rf ./project_fun.git`
5. Fork the new repo from the lab group website: https://github.com/biogeochem to your user account.
6. Close the repo from your user account. `git clone https://github.com/USERNAME/project_fun.git`

See also https://help.github.com/articles/duplicating-a-repository/.

## Naming conventions
All files should follow the standardized naming convention outlined below.


## Repository use
Students or collaborators wishing to use data from a repo must abide by the following guidelines.

*For more information about project maintenance, please contact **Kateri Salk** at krsalkgu@uwaterloo.ca or **Jason Venkiteswaran** at jvenkiteswaran@wlu.ca.*

