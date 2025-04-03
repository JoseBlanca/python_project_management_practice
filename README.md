# Python project management with uv

The objective of this practice is to learn how to manage a Python project.

As an example we are going to create a tool to create statistics from a set of fastq sequence files.

## Tools

We are going to use the following tools, so you need to install them:

- [uv](https://docs.astral.sh/uv/) as the Python management tool
- [git](https://git-scm.com/) as the version control system.
- [Visual Studio Code](https://code.visualstudio.com/) as the [Integrated Development Environment](https://en.wikipedia.org/wiki/Integrated_development_environment).

## Clone the github repository

Open a terminal, change to a [working directory](https://en.wikipedia.org/wiki/Working_directory) of your choice, and clone the repository:

```
$ git clone https://github.com/JoseBlanca/python_project_management_practice.git
```

## Run the hello world example

```
$ uv run src/fastq_stats/hello.py
```

uv should have run the script and it will have install Python, if it is not already installed.

Also, uv should have created a virtual environment in the `.venv` directory. This is a directory that contains a copy of the Python interpreter and all the packages that are installed in it. This is useful to avoid conflicts between different projects that use different versions of the same package.
