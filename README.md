<a href="https://doi.org/10.5281/zenodo.24104392"><img src="https://zenodo.org/badge/1451126720.svg" alt="DOI"></a>

# R Research Software Management Training - testRepro

<div align="center">
  <img src="img/UT_Logo_0072_Black_EN.png" alt="logo">
</div>

This repository documents my learning process during the Research Software Management Training at the University of Twente.

The project is intended for educational purposes and provides hands-on experience with Git, GitHub, research software documentation, reproducibility, software licensing, citation, and software management planning.

## Folder Structure

This repository is based on the University of Twente R Research Software Template and is used to practice research software management, version control, documentation, and reproducibility.

The local project directory contains the following files and folders:

```text
testRepro/
├── code/                   # R scripts and functions
├── data/                   # Research data
├── docs/                   # Project documentation
├── img/                    # Images and visual resources
├── my_research_project/    # Additional training project directory
├── outputs/                # Generated outputs
├── renv/                   # R environment management
├── tests/                  # Directory for software tests
├── .Rprofile               # R project startup configuration
├── .copier-answers.yml     # Template configuration
├── CHANGELOG.md            # Record of project changes
├── CITATION.cff            # Software citation metadata
├── LICENSE                 # Software licence
├── README.md               # Project documentation and SMP
├── codemetadata.json       # Software metadata
└── renv.lock               # Recorded R package dependencies
```

## Research Software Management Plan

1. The software's purpose is educational and intended for personal training. The primary user is the developer. The project is designed to provide hands-on experience with Git, GitHub, writing a Software Management Plan (SMP) and applying principles of research software reproducibility.

2. The project uses Git for version control and a public GitHub repository for hosting and managing the source code.

3. The software is made publicly available using GitHub and Zenodo.

4. The software is distributed under the MIT License.

5. Not applicable. This is a small-scale training project intended for educational purposes rather than long-term software development.

6. Not applicable. No formal user support or continued development is planned after completion of the training.

7. Not applicable. No dedicated funding, infrastructure or personnel are required for this training project.

8. Not applicable. No additional sustainability measures are planned beyond the existing documentation and repository.

9. The software is documented through the README.md file in the public GitHub repository.

10. The project uses Git, GitHub, R, and the renv package to support version control and reproducibility. The R dependencies are recorded in renv.lock and can be restored using renv::restore().

11. The software is archived on Zenodo and has been assigned a Digital Object Identifier (DOI): https://doi.org/10.5281/zenodo.24104392

12. Since this is an educational project rather than a fully developed software application, no automated software testing framework has been implemented.

13. The project is distributed through its public GitHub repository and archived on Zenodo.

## Installation

This repository was created as a training project for the Research Software Management Training at the University of Twente.

To reproduce the R environment:

1. Install R and Git.
2. Clone this repository using git clone https://github.com/iamaresearcher/testRepro.git
3. Open the project directory in R or Positron
4. Install the `renv` package if necessary using install.packages("renv").
5. Run renv::restore() to restore the package versions recorded in renv.lock.

The project uses Git for version control and renv for dependency management and reproducibility

[Describe the steps that users (not developers) should follow to install the code in each of the intended platforms (e.g. Window 10, MacOS, etc.).]

**Requirements** 

- R
- Git
- The R package renv
- An internet connection to download dependencies

No special hardware requirements are needed for this training project.

## License
This software is distributed under the MIT License. 

## Copyright

Copyright (c) 2026 iamaresearcher.

## Citation

This project is archived on Zenodo and can be cited using the following DOI:

https://doi.org/10.5281/zenodo.24104392

Citation metadata is provided in the [CITATION.cff](CITATION.cff) file.


## Acknowlegdements

- [Best practices for sustainable software project, TDCC NES](https://github.com/SS-NES)