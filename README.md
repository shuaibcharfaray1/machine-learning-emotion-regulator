# machine-learning-emotion-regulator

This is a project for the Project 301 module in the Durban University of Technology by `The Honourable Members`. This specific project focuses on developing a system that can regulate a person's emotions using color.

# Collaborators

- A.Banoo
- I.Kader
- A.Imrith
- S.Sookdawe
- M.Charfaray
- M.Rasool
- A.Sayed
- M.Yusha

# Components?

This project uses `markdown` for documentation which can be located in the `docs` folder of this project. Other more general information about this document is available in this `README.md` file.

The folder structure is in line with `Flask` and what it requires in terms of the `templates`,and `static` folders.

The `units` folder contains all of the python code required for this project.

# Git & Github

This project uses version control with the main repository stored on GitHub @[Link to repo](https://github.com/azb5499/machine-learning-emotion-regulator.git).
The main repo is managed by `Group leader A.Banoo`.

## Branch structure

- main
  - development
    - front-end
    - back-end
      - ML natural language unit
      - Colour_brain unit
      - main.py
    - documentation

The ``main`` branch is the deployment ready branch with all main changes that have been checked and double checked.

The `development` branch is for all development changes. When the developers create and confirm changes. These changes will be pushed to this branch. This will be the version of the app that will be checked and double checked before being added to `main`.

The `front-end` branch is for all front-end changes. Every new feature or page will be created here and have its own branches created. e.g. You create a branch within `front-end` called `home-page` and design and prototype the home page for an app and once everything is validated and double checked. The changes will be merged with `front-end`.

The `back-end` branch is selft explanatory. For all new back-end features. They will have a branch made here, coded, tested, validated and refined. Once that unit has been tested. It will be merged with `back-end`.

The `documentation` branch is mainly for developmental documentation. This is not for collaborators to work with unless instructed to. These are for project planning, design, and all details.

# Set up and configuration

Due to this project being programmed in the python language. The set up will follow the below instructions.

Please follow the steps available at [W3 Schools](https://www.w3schools.com/git/git_remote_fork.asp?remote=github). Please read these carefully before doing the below steps.

1. Fork the repository.
   1. On GitHub, navigate to the repository you want to fork.
   2. Click the "Fork" button at the top right of the page.
2. Clone the repository to your local machine. Make sure you navigate to the folder where you wish to have the program installed.
3. Navigate to the cloned folder and set up the Virtual environment.
   1. `python -m venv myvenv`
   2. To activate it in both your normal terminal and git bash terminal. Below are the commands for each
      1. windows terminal `venv\Scripts\activate`.
      2. bash terminal `source venv/bin/activate`
4. Install requirements.txt.
   1. `pip install -r requirements.txt`.
5. Configure the environment variables.
    - You'd need to configure the following environment variables. For simplicity sake these will be configured in git bash terminal.
    1. `export FLASK_APP=units/main.py`.
    2. `export FLASK_ENV=development`.
6. Confirm the variables were set.
    1. `echo $FLASK_APP`.
    2. `ECHO $FLASK_ENV`.
7. Run the flask app.
   1. `flask run`

Once the above steps are done, you will be able to collaborate.

