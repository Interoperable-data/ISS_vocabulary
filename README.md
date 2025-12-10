# ISS vocabulary

> [!CAUTION] 
> ##  This repository is archived and no longer maintained.

Thank you for your interest in **ISS_vocabulary**. As of **December 10th, 2025**, this project is no longer actively maintained in Github, and the repository has been archived. This means:

✅ The repository is now **read-only**.  
❌ No further updates, bug fixes, or new features will be added.  
❌ Issues and pull requests will **not** be reviewed or accepted.  

---

## 🔍 New GITLAB repository
The new repository is available **[on GitLab here](https://gitlab.com/era-europa-eu/public/interoperable-data-programme/era-ontology/iss_ontology)** 

---
> [!WARNING]
> **We are migrating this repository to our new Gitlab instance. We will archive this repository in the coming weeks.**
> **The URI for our public Gitlab is https://gitlab.com/era-europa-eu/public/interoperable-data-programme**. **Sorry for the inconvenience.**
> 
This is the repository where the ISS vocabulary (ontology) governed by the European Union Agency for Railways is being developed and released. It represents the concepts and relationships linked to the Information Sharing System (ISS) in accordance with the draft delegated act of the future CSM ASLP Regulation (hereinafter the ‘CSM’ or ‘CSM ASLP). The online documentation for this vocabulary is available at [https://dev.ld4rail.fpfis.tech.ec.europa.eu/iss-vocabulary](https://dev.ld4rail.fpfis.tech.ec.europa.eu/iss-vocabulary), and its URI is http://data.europa.eu/949/iss. All ontology components (classes, properties) use this base URI and are dereferenceable (e.g., http://data.europa.eu/949/iss/SafetyRelatedEvent).

The repository is organised as in the following folders:
* governance. This folder contains a description of the main principles that have been followed for the development of the ERA vocabulary, including decisions on URIs, design patterns, update mechanisms, etc. It will be updated to reflect specific principles for the ISS vocbulary.
* iss-skos. This folder contains all the SKOS concept schemes (authority tables) that are used as values for some properties in the ISS vocabulary.
* public. This folder contains the HTML version of the ISS vocabulary, which is published in the following URL: [https://dev.ld4rail.fpfis.tech.ec.europa.eu/iss-vocabulary](https://dev.ld4rail.fpfis.tech.ec.europa.eu/iss-vocabulary)

## Issues

We welcome issues and enhancement requests that follow these guidelines:

1. Issues opened in this repository should concern the [ISS vocabulary definitions](https://github.com/Interoperable-data/ISS_vocabulary/issues).
2. Please label your issues using the corresponding version tag. For example, using the label `v1.0.0`.

## Contributing

For contributions we follow the "fork-and-pull" Git workflow:

1. **Fork** this repository on GitHub.
2. **Clone** the project in your local machine.
3. **Commit** the changes to your own branch.
4. **Push** your changes back up to your own fork.
5. Submit a [**Pull request**](https://github.com/Interoperable-data/ISS_vocabulary/pulls) to the **dev** branch so we can review your changes.

NOTE: Make sure to merge the latest "upstream" version before submitting a pull request.

## Validation procedure for user requests
1. Any actor can request improvements to the ISS Vocabulary.
2. The Vocabulary team evaluates if the request is technically sound and its impact in the current deployment of the Vocabulary itself.
3. ERA evaluates its impact from the business and project management point of view and ultimately approves (or not) the request. 
4. The actor who requested the improvements is informed on when the request will be attended, including an indication of the Vocabulary release number that will include the request.
5. The request, if approved, is implemented by the Vocabulary team.
