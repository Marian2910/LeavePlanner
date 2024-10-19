# Introduction

LeavePlanner is a comprehensive solution designed to manage employee leave requests, track leave balances, and organize events. This repository acts as the container for both the API and UI modules, providing a full-stack application for managing leave-related activities within a company.

# Repository Structure
This repository contains two submodules:

* LeavePlannerAPI – Backend API for handling all leave-related data, requests, and user management.
* LeavePlannerUI – Frontend user interface for interacting with the LeavePlanner application.
Each submodule has its own dedicated repository with detailed instructions and documentation on how to use them.

# Getting Started

1. Cloning the Repository
  * To clone this repository along with its submodules, use the following command:
     * git clone --recurse-submodules https://github.com/Marian2910/LeavePlanner.git
  * This will ensure that both the API and UI submodules are cloned alongside the main repository.

  * If you have already cloned the repository without the --recurse-submodules option, you can initialize and update the submodules with:
     * git submodule update --init --recursive

2. Setting Up the Project
  * Once the repository and its submodules are cloned, you can set up the environment by following the instructions provided in each submodule's README:
    - [LeavePlannerAPI Setup Instructions](https://github.com/Marian2910/LeavePlannerAPI)
    - [LeavePlannerUI Setup Instructions](https://github.com/Marian2910/LeavePlannerUI)
  * Make sure to follow the instructions in each submodule to install the necessary dependencies and set up the environment.

3. Running the Application
    * Start the API: Follow the instructions in the [LeavePlannerAPI](https://github.com/Marian2910/LeavePlannerAPI) repository to start the backend server.
    * Start the UI: Follow the instructions in the [LeavePlannerUI](https://github.com/Marian2910/LeavePlannerUI) repository to run the frontend user interface.
* Once both the API and UI are running, you should be able to access the full LeavePlanner application in your browser.

# Updating Submodules

* To pull the latest changes from the submodules:

    - git submodule update --remote --merge
* Then, commit the changes to the main repository:

  - git add LeavePlannerAPI LeavePlannerUI
  - git commit -m "Update submodules to latest versions"
  - git push origin main
