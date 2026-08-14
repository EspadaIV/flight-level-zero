# Flight Level Zero

**Beginner-focused aviation education and technical writing project**

Flight Level Zero is an aviation education project designed to make the fundamentals of flight accessible to learners with little or no prior aviation knowledge.

The project explores aircraft, aerodynamics, aircraft systems, weather, navigation, and other foundational aviation concepts through clear, progressively structured technical content.

Alongside its educational purpose, Flight Level Zero serves as a working technical writing and documentation project. The repository demonstrates research, information architecture, audience-focused writing, source management, revision control, and docs-as-code practices using Git and GitHub.

## Project Goals

Flight Level Zero is being developed around several core objectives:

* Explain technical aviation concepts accurately without assuming prior knowledge.
* Break complex systems into understandable components and processes.
* Introduce aviation terminology progressively and consistently.
* Maintain traceable sources for technical information.
* Use feedback from beginner readers to identify unclear explanations and knowledge gaps.
* Maintain documentation through a structured, version-controlled workflow.
* Create educational material that encourages learners to continue exploring aviation.

## Intended Audience

The primary audience is beginning aviation learners, including younger learners and adults who are interested in aviation but do not yet have formal flight training or an aerospace background.

Content assumes curiosity, not prior expertise.

Technical terminology is introduced when necessary, defined in context, and reinforced throughout the project.

## Documentation Approach

### Research

Technical claims and aircraft information are researched using authoritative or reputable aviation sources whenever possible.

Sources are tracked so information can be reviewed, verified, and updated as the project develops.

### Drafting

Content is organized around the needs of a beginner reader rather than the structure of the source material.

Each section attempts to answer three questions:

1. **What is it?**
2. **How does it work?**
3. **Why does it matter in aviation?**

### Beginner Review

Selected material is reviewed by a learner within the project's intended audience.

Reader feedback is used to identify:

* unexplained terminology
* confusing descriptions
* assumed background knowledge
* unanswered questions
* sections requiring additional examples or visual support

Feedback informs subsequent revisions while technical accuracy remains the priority.

### Technical Verification

Specifications, terminology, system descriptions, and other factual claims are checked against project sources before material is considered complete.

When information cannot be adequately verified, it is flagged for additional research rather than presented as established fact.

### Revision and Version Control

The project uses Git and GitHub to maintain revision history and document significant changes.

Commits are intended to describe the purpose of documentation changes rather than simply record that a file was edited.

Examples:

```text
docs: add four forces of flight overview
docs: clarify angle of attack explanation
docs: expand aircraft terminology glossary
fix: correct aircraft specification
refactor: reorganize weather section for progressive learning
```

Major documentation changes are recorded in the project changelog.

## Repository Structure

```text
flight-level-zero/
│
├── manuscript/        # Primary educational content
├── aircraft/          # Aircraft-specific educational material
├── reference/         # Sources, terminology, and glossary
├── style-guide/       # Writing and documentation standards
├── assets/            # Diagrams and supporting material
├── README.md          # Project overview
└── CHANGELOG.md       # Significant project revisions
```

The repository structure may evolve as the project grows.

## Documentation Standards

Flight Level Zero follows several general writing principles:

* Accuracy before simplification
* Plain language where possible
* Technical terminology where necessary
* Define specialized terms before relying on them
* Maintain consistent terminology across documents
* Separate verified information from interpretation
* Prefer authoritative sources for technical claims
* Write for the knowledge level of the intended reader
* Revise when reader feedback reveals ambiguity

Additional standards are maintained in the project's style guide.

## Project Status

**Active development**

Flight Level Zero is an evolving educational and technical writing project. Content may be reorganized, expanded, or revised as research continues and material is tested with beginner readers.

## About the Author

**Lindsey Petty / E.V. Thomas**

Technical writer, systems-focused operator, software developer, and published author with experience in technical documentation, AI-assisted workflows, backend development, program management, and operational systems.

Flight Level Zero combines an interest in aviation with a broader focus on making complex technical information understandable and useful.

## Copyright

Copyright © 2026 E.V. Thomas. All rights reserved.

Unless explicitly stated otherwise, the written content and original materials in this repository are not licensed for redistribution, republication, or commercial use.
