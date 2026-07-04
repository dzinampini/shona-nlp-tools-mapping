# Shona NLP Ecosystem Mapping

An open, community-maintained catalogue of **Shona Natural Language Processing (NLP) tools, datasets, and related resources**.

The goal of this project is to provide a single, searchable location for researchers, students, developers, and organisations interested in Shona language technologies.



# Study Aim

This review aims to systematically review and map the existing ecosystem of Shona language processing tools and datasets.

The project consolidates information from academic literature and publicly available resources into a structured database that can be easily searched and expanded by the community.



# Why this Project?

Shona remains a low-resource language in Natural Language Processing. Existing tools, datasets, and publications are often scattered across journal articles, conference papers, theses, and software repositories.

By creating an openly accessible ecosystem map, this project aims to:

- Improve discoverability of existing Shona NLP resources.
- Reduce duplication of research efforts.
- Highlight gaps in the current ecosystem.
- Encourage collaboration between researchers and developers.
- Support future development of Shona language technologies.



# Repository Structure

```text
.
├── index.html          # Website
├── data.json           # collection of NLP tools, applications and datasets
├── README.md
└── assets/
```



# Contributing

Contributions are welcome from researchers, developers, linguists, students, and members of the wider community.

Please ensure that all additions are supported by reliable references.



# How to Update the Dataset

All project data is stored in **data.json**.

When adding new entries:

1. Fork this repository.
2. Create a new branch.

```bash
git checkout -b add-new-resource
```

3. Locate the appropriate section inside `data.json`.

Examples include:

- Tokenisation
- Morphological Analysers
- POS Taggers
- Lemmatisers
- Named Entity Recognisers
- Parsers
- Lexical Resources
- Raw Corpora
- Annotated Corpora
- Domain-specific Corpora
- Parallel Corpora
- Literary Texts
- Applications *(if applicable)*

4. Add the new entry following the existing JSON structure.

Example:

```json
{
    "title": "",
    "description": "",
    "sources": [],
    "approach": "",
    "model_or_algorithm": "",
    "link": ""
}
```

5. Validate that the JSON is valid.

Useful validators:

- https://jsonlint.com
- https://jsonformatter.org/json-validator

6. Commit your changes.

```bash
git commit -m "Added new Shona POS tagger"
```

7. Push your branch.

```bash
git push origin add-new-resource
```

8. Submit a Pull Request.



# Contribution Guidelines

Please ensure that:

- Information comes from published papers, repositories, or official project websites.
- Descriptions remain factual and objective.
- Original authors receive appropriate credit.
- Sources are included for every entry.
- Existing entries are updated rather than duplicated whenever possible.



# Reporting Errors

If you notice:

- Missing tools
- Missing datasets
- Broken links
- Incorrect descriptions
- Duplicate entries

please open a GitHub Issue or contact the project maintainer.



# Contact

For questions, corrections, collaborations, or contributions:

**Email**: dzinampini@gmail.com
**Call/WhatsApp**:  +263 774 756 502 or +267 74 099 422



# Citation

If you use this ecosystem map in academic work, please cite the accompanying publication (when available).

Additionally, please cite the original publications describing each tool or dataset where appropriate.



# License

Unless otherwise stated, this repository is released under the **MIT License**.

Please note that the original NLP tools, datasets, and publications referenced in this repository remain the intellectual property of their respective authors and organisations.

This repository serves as an index and ecosystem map of those resources and does not claim ownership of the referenced works.



# Acknowledgements

This project exists because of the many researchers, developers, linguists, and organisations that have contributed to the advancement of Shona Natural Language Processing. Their work forms the foundation of this ecosystem map.

Community contributions are warmly welcomed.

