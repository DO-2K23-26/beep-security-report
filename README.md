# beep-security-report

Tasks:

- [X] Have a project with a CI (Beep) and 3-4 components communicating together (such as API, frontend, database, vault... Anything), plus preferably Dockerfile.
- [X] Add scans to the CI.
- [X] Create a project description and deployment diagram (deployment diagram)
- [X] Create a threat modeling.


## Generate the dock

```sh
asciidoctor -r asciidoctor-pdf -r asciidoctor-diagram -b pdf diagrams/deployment.adoc
```
