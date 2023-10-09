[![OnInstall](https://github.com/nogibjj/Osama-Matrix-Testing/actions/workflows/install.yml/badge.svg)](https://github.com/nogibjj/Osama-Matrix-Testing/actions/workflows/install.yml)

# Github Actions Matrix Build, using multiple versions of Python against multiple Operating Systems

The primary objective of this project is to establish a robust foundation for matrix building, installation, and testing. By orchestrating this comprehensive testing environment, we aim to guarantee compatibility across a diverse spectrum of projects and platforms. This endeavor involves the integration of multiple operating systems and Python versions, allowing us to assess the performance and reliability of our code under various configurations. Ultimately, our pursuit of compatibility ensures that our project seamlessly adapts to the intricacies of different software environments, providing a solid, dependable solution for a wide range of users and projects.



# Github Actions Matrix Build

This GitHub Actions workflow is designed to automate the testing and building process for a project by utilizing a matrix that includes three different versions of Python and two distinct operating systems. This setup allows you to ensure the compatibility and reliability of your code across multiple Python versions and operating system environments.

## Overview

Testing your code across different Python versions and operating systems is essential to guarantee that your project works seamlessly for a wide range of users and setups. This GitHub Actions matrix build configuration simplifies this process by running your tests and builds on the specified combinations of Python versions and operating systems.

## Features

- **Python Version Compatibility**: Test your code against multiple Python versions to catch potential compatibility issues early in development.

- **Operating System Compatibility**: Ensure that your project works on different operating systems, such as Linux and Windows.

- **Automated Workflow**: This workflow automates the testing and building process, making it easier to maintain and enhance your project.

- **Matrix Configuration**: Easily customize the matrix to include additional Python versions or operating systems as needed for your project.

## Usage

To incorporate this matrix build workflow into your project, follow these steps:

1. **Create a `.github/workflows` directory** in your project repository if it doesn't already exist.

2. **Create a new YAML file** (e.g., `Install.yml`) within the `.github/workflows` directory.

3. **Copy and paste the following matrix strategy install configuration** into the YAML file from the install.yml in this repo and adjust as necessary to include the desired versions of Python and operating systems to be tested for compatibility.


## Use Case

This project builds upon the foundation of the previous Continuous Integration setup in our previous individual project [linked here](https://github.com/nogibjj/Osama---Continuous-Integration-using-GitHub-Actions-of-Python-Data-Science-Project). It aims to ensure the compatibility and reliability of our code by running the desired descriptive statistics and Python versions across the latest Ubuntu and Windows operating systems. We achieve this by testing our code against three different versions of Python, thereby broadening the scope of our testing matrix.

By expanding our testing matrix to encompass a range of Python versions and operating systems, we enhance the robustness of our project, making it more accessible and dependable for a diverse user base.

## Below is a demonstration of the various OSs and python versions that we have used. You can also view them by clicking the provided `OnInstall` badge and expanding the workflow run

![Matrix Image](/output/matrix.png)

