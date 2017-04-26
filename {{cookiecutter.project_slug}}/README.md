{{cookiecutter.project_slug}}
==============================

{{cookiecutter.project_short_description}}

Project Organization
--------------------

    .
    ├── AUTHORS.md
    ├── LICENSE
    ├── README.md                    This README file.
    ├── bin                          Compiled executables and executable secondary scripts.
    ├── config                       Variables used throughout project. Matlab .m file, setenv, ect.
    ├── Makefile                     Makefile that should be able to generate the results from the data.
    ├── *.m, *.sh, *.py              Main driver script files. Run by the Makefile, and use src/ and bin/
    ├── data
    │   ├── external                 Data derived from my other projects. Copy or ln -s.
    │   ├── interim                  Interim data GENERATED as part of this project.
    │   ├── processed                Final data GENERATED as part of this project.
    │   └── raw                      Data directly downloaded or obtained from the field. Copy or ln -s.
    ├── notes                        Documentation files and my technical notes.
    ├── notebooks                    Jupyter notebooks, if I ever start using them.
    ├── docs                         The manuscript, proposal, or final report.
    │   └── figures                  The final figure files. Preferably png and pdf ready to upload for publication.
    └── src                          Source code for Matlab, Python, ect. functions.
