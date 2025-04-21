# CI/CD Tools and Practices Final Project Template

This repository contains the template to be used for the Final Project for the Coursera course **CI/CD Tools and Practices**.

## Usage

This repository is to be used as a template to create your own repository in your own GitHub account. No need to Fork it as it has been set up as a Template. This will avoid confusion when making Pull Requests in the future.

From the GitHub **Code** page, press the green **Use this template** button to create your own repository from this template.

Name your repo: `ci-cd-final-project`.

NOTE!: Project instructions says 'https' tp clone but that method is deprecated so use ssh and keys instead - just saying

## Setup

After entering the lab environment you will need to run the `setup.sh` script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks


## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

Skills Network

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>
    1  ls +la
    2  ls -la
    3  export GITHUB_ACCOUNT=https://github.com/jss653
    4  ls -la .theia/
    5  git clone git@github.com:jss653/ci-cd-final-project.git
    6  ssh-keygen -t rsa -b 4096 -C "jonas.strindlund@outlook.com"
    7  cat ~/.ssh/id_rsa.pub
    8  git clone git@github.com:jss653/ci-cd-final-project.git
    9  cd ci-cd-final-project
   10  bash ./bin/setup.sh
   11  exit
   12  git config --global user.email "jonas.strindlund@outlook.com"
   13  git config --global user.name jssedu
   14  history
   15  pwd
   16  cd ci-cd-final-project/
   17  history > commands.log
   18  git status
   19  ls -la
   20  cat README.md 
   21  history >> README.md 
