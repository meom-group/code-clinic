# code-clinic
Our internal review for the packages we develop

## course of the session

1. introduce the package
2. split the group to get 4 subgroups
3. each subgroup works on 1 of the 4 items of the checklist for about 10-15 minutes
   1. chek the boxes associated with the checklist
   2. comment on the associated issue on the package
4. meet up with the full group to describe what is missing (and what was good)
5. open issues on the package repository to propose easy and precise fixes for the missing items



## Checklist
### general structure (having a readme, a licence, contributing guide, etc)

- [ ] Package has a README.md file in the root directory.
- [ ] Package documentation is easy to find.
- [ ] The package is easy to install
- [ ] **License:** Does the repository contain a plain-text LICENSE or COPYING file with the contents of an [OSI approved](https://opensource.org/licenses/alphabetical) software license?
- [ ] **Community guidelines:** Are there clear guidelines for third parties wishing to 1) Contribute to the software 2) Report issues or problems with the software 3) Seek support
- [ ] **Metadata** including author(s), author e-mail(s), a url, and any other relevant metadata e.g., in a `pyproject.toml` file or elsewhere.


### tests

- [ ] **The package has tests:**
  - [ ] Tests cover essential functions of the package and a reasonable range of inputs and conditions.
- [ ] **Continuous Integration:** Has continuous integration setup (We suggest using Github actions but any CI platform is acceptable for review)


### Documentation

- [ ] **Vignette(s)** / **Example usage:** demonstrating major functionality (ideally to solve real-world analysis problems).
- [ ] **Function Documentation:** for functions used in the examples.

### README

The README should include:

- [ ] The package name
- [ ] Short description of package goals.
- [ ] Package installation instructions
    - [ ] Brief demonstration of package usage (as it makes sense - links to vignettes could also suffice here if package description is clear)
- [ ] Link to your documentation website.
- [ ] If applicable, how the package compares to other similar packages and/or how it relates to other packages in the scientific ecosystem.
- [ ] Citation information
