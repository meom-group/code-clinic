# code-clinic
Our internal review for the packages we develop

## Checklist

#### Documentation

The package includes all the following forms of documentation:

- [ ] **A statement of need** clearly stating problems the software is designed to solve and its target audience in README.
- [ ] **Installation instructions:** for the development version of the package and any non-standard dependencies in README.
- [ ] **Vignette(s)** demonstrating major functionality that runs successfully locally.
- [ ] **Function Documentation:** for all user-facing functions.
- [ ] **Examples** for all user-facing functions.
- [ ] **Community guidelines** including contribution guidelines in the README or CONTRIBUTING.
- [ ] **Metadata** including author(s), author e-mail(s), a url, and any other relevant metadata e.g., in a `pyproject.toml` file or elsewhere.

Readme file  requirements
The package meets the readme requirements below:

- [ ] Package has a README.md file in the root directory.

The README should include, from top to bottom:

- [ ] The package name
- [ ] Badges for:
    - [ ] Continuous integration and test coverage,
    - [ ] Docs building (if you have a documentation website),
    - [ ] A [repostatus.org](https://www.repostatus.org/) badge,
    - [ ] Python versions supported,
    - [ ] Current package version (on PyPI / Conda).

*NOTE: If the README has many more badges, you might want to consider using a table for badges: [see this example](https://github.com/ropensci/drake). Such a table should be more wide than high. (Note that the a badge for pyOpenSci peer-review will be provided upon acceptance.)*

- [ ] Short description of package goals.
- [ ] Package installation instructions
- [ ] Any additional setup required to use the package (authentication tokens, etc.)
- [ ] Descriptive links to all vignettes. If the package is small, there may only be a need for one vignette which could be placed in the README.md file.
    - [ ] Brief demonstration of package usage (as it makes sense - links to vignettes could also suffice here if package description is clear)
- [ ] Link to your documentation website.
- [ ] If applicable, how the package compares to other similar packages and/or how it relates to other packages in the scientific ecosystem.
- [ ] Citation information

#### Usability
Reviewers are encouraged to submit suggestions (or pull requests) that will improve the usability of the package as a whole.
Package structure should follow general community best-practices. In general please consider whether:

- [ ] Package documentation is clear and easy to find and use.
- [ ] The need for the package is clear
- [ ] All functions have documentation and associated examples for use
- [ ] The package is easy to install


#### Functionality

- [ ] **Installation:** Installation succeeds as documented.
- [ ] **Functionality:** Any functional claims of the software been confirmed.
- [ ] **Performance:** Any performance claims of the software been confirmed.
- [ ] **Automated tests:**
  - [ ] All tests pass on the reviewer's local machine for the package version submitted by the author. Ideally this should be a tagged version making it easy for reviewers to install.
  - [ ] Tests cover essential functions of the package and a reasonable range of inputs and conditions.
- [ ] **Continuous Integration:** Has continuous integration setup (We suggest using Github actions but any CI platform is acceptable for review)
- [ ] **Packaging guidelines**: The package conforms to the pyOpenSci [packaging guidelines](https://www.pyopensci.org/python-package-guide).
    A few notable highlights to look at:
    - [ ] Package supports modern versions of Python and not [End of life versions](https://endoflife.date/python).
    - [ ] Code format is standard throughout package and follows PEP 8 guidelines (CI tests for linting pass)
     

### General checks

- [ ] **Repository:** Is the source code for this software available at the [{{target-repository}}]({{target-repository}})?
- [ ] **License:** Does the repository contain a plain-text LICENSE or COPYING file with the contents of an [OSI approved](https://opensource.org/licenses/alphabetical) software license?
- [ ] **Contribution and authorship:** Has the submitting author ({{author-handle}}) made major contributions to the software? Does the full list of paper authors seem appropriate and complete?
- [ ] **Substantial scholarly effort:** Does this submission meet the scope eligibility described in the [JOSS guidelines](https://joss.readthedocs.io/en/latest/submitting.html#substantial-scholarly-effort)
- [ ] **Data sharing:** If the paper contains original data, data are accessible to the reviewers. If the paper contains no original data, please check this item.
- [ ] **Reproducibility:** If the paper contains original results, results are entirely reproducible by reviewers. If the paper contains no original results, please check this item.
- [ ] **Human and animal research:** If the paper contains original data research on humans subjects or animals, does it comply with [JOSS's human participants research policy and/or animal research policy](https://joss.readthedocs.io/en/latest/policies.html?highlight=animal#joss-policies)? If the paper contains no such data, please check this item.


### Functionality

- [ ] **Installation:** Does installation proceed as outlined in the documentation?
- [ ] **Functionality:** Have the functional claims of the software been confirmed?
- [ ] **Performance:** If there are any performance claims of the software, have they been confirmed? (If there are no claims, please check off this item.)

### Documentation

- [ ] **A statement of need**: Do the authors clearly state what problems the software is designed to solve and who the target audience is?
- [ ] **Installation instructions:** Is there a clearly-stated list of dependencies? Ideally these should be handled with an automated package management solution.
- [ ] **Example usage:** Do the authors include examples of how to use the software (ideally to solve real-world analysis problems).
- [ ] **Functionality documentation:** Is the core functionality of the software documented to a satisfactory level (e.g., API method documentation)?
- [ ] **Automated tests:** Are there automated tests or manual steps described so that the functionality of the software can be verified?
- [ ] **Community guidelines:** Are there clear guidelines for third parties wishing to 1) Contribute to the software 2) Report issues or problems with the software 3) Seek support
