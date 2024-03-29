
# Data Toolkit project - Market Prediction

This application is a demonstration of collaborative development using Git,
showcasing basic commands for a smooth version control utilization to
effectively manage a project.

## Table of Contents
- [Description](#description)
- [Structure](#structure)
- [Branches](#branches)
- [Contributing](#contributing)


## Description

This repository contains a simple example on how to properly use git commands,
illustrated on txt and py files. It includes the creation of branches, committing and pushing files, 
and merging changes. 
```
IMPORTANT: The file 'description.txt' contains all the used commands.
```

## Structure

The project structure is as follows:
1. **main.py**:  The main python file with basic python code.
2. **description.txt** :  A text file containing the used git commands for different purposes
3. **appinfo.txt**: A file containing info about the application, added on a separate 
feature branch

## Branches

1. **main**:  Main branch containing the stable version of the application. It is the branch on which code was added in the main.py file,
in order to simulate a pull in the feature branch.
2. **feature/add-about-project**:  Branch for adding the ’About the application’ section, more specifically the appinfo.txt file.

## Contributing

In order to contribute to this project, follow the steps below:
1. Fork the repository on Github
2. Clone the forked repository: `git clone <fork_url>`
3. Create a new branch from main for your feature: `git checkout -b feature/added-feature`
4. Make changes and commit them with descriptive messages: 
  ```bash
git add .
git commit -m "suggestive commit message"
  ```
6. Push your branch to your forked repository: `git push origin feature/added-feature`
7. Open a pull request on GitHub in order to merge your changes into the main branch.