# Examples

<!-- TODO: -->
<!-- Create a navigation example, nested folders -->
<!-- Explain dynamic Table of Contents -->

## Table
<!-- Notice: There can be spaces or no spaces between the words and column pipes '|' -->
| Content | Source | Link |
|---|---|---|
|Backstage|TechDocs FAQ|[TechDocs FAQ](https://backstage.io/docs/features/techdocs/faqs/)|
|MkDocs|MkDocs User-Guide|[MkDocs Configuration](https://www.mkdocs.org/user-guide/configuration/)|
|PyMdownX|Exentions Documentation|[PyMdown Extensions](https://facelessuser.github.io/pymdown-extensions/extensions/arithmatex/)|

## Task List

- [X] item 1
  - [X] item A
  - [ ] item B
    more text
    - [x] item a
    - [ ] item b
    - [x] item c
  - [X] item C
- [ ] item 2
- [ ] item 3

## Nested Admonitions + Tabbed + Task List
<!-- NOTICE: A tab of 4 spaces is required for this formating syntax to render correctly -->
??? info "Example Pillar"
    ???+ question "Question Group"
        === "Basic"
            - [ ] Item1
            - [ ] Item2
        === "Bronze"
            - [ ] Item3
            - [ ] Item4
        === "Silver"
            - [ ] Item5
            - [ ] Item6
        === "Gold"
            - [ ] Item7
            - [ ] Item8

    === "Basic"
        - [ ] Item1
        - [ ] Item2
    === "Bronze"
        - [ ] Item3
        - [ ] Item4
    === "Silver"
        - [ ] Item5
        - [ ] Item6
    === "Gold"
        - [ ] Item7
        - [ ] Item8

[Solid Button :fontawesome-solid-download:](URL){ .md-button .md-button--primary}
[Outline Button](URL){ .md-button}