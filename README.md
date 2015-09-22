python-project-template-with-pip-conflict-checker
=================================================
This project is a template showing how to do effective dependency management in Python with
pip-conflict-checker and pipdeptree.

This template is minimal, including only the ingredients that you'll need to do dependency
management effectively. In almost all cases, you'll want to add in additional tools for unit
testing, linting, documentation generation, build automation, and many other things. Sean Fisk's
[python-project-template](https://github.com/seanfisk/python-project-template) is a great place to
start for incorporating more build tools into your project.

Usage
-----
To use this as a template, clone it, modify the files to your liking, and you're good to go! Each
file is documented to explain how it works, so you can also browse the files to learn more about how
to set up dependency management for a Python project.

To install dependencies and run tests, run `tox`. Running `tox -r` will recreate all virtualenvs.

If you want to add a tool that's only needed to test this project, add it to `requests.testing.in`,
then regenerate `requirements.txt` from `pip freeze`.

If you want to add a Python library that is needed by the code itself, add it to `requirements.in`,
then regenerate `requirements.txt` from `pip freeze`.

Philosophy
----------
For a more detailed explanation of how this project works, see [this blog post](link to second blog post).

