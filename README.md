# LectureSeek

LectureSeek is a recorded-lecture learning platform for students and instructors. Its requirements describe lecture playback, searchable transcripts, slides and chapters, summaries, quizzes, translation, dubbed audio, and personal study resources.

This repository contains the project definition and requirements-analysis documents. It is a documentation package; the files do not represent a completed software implementation.

## Project documents

| Document | Description |
| --- | --- |
| [Problem definition](docs/requirements/lectureseek-problem-definition.docx) | Initial project problem and context. |
| [Software Requirements Specification 0.1](docs/requirements/lectureseek-software-requirements-specification-0.1.docx) | Draft functional and quality requirements. |
| [User Stories 0.2](docs/requirements/lectureseek-user-stories-0.2.docx) | Student and instructor stories with acceptance criteria. |
| [Use Case Analysis and Diagram 0.1](docs/requirements/lectureseek-use-case-analysis-and-diagram-0.1.docx) | Actor analysis, 32 high-level use cases, detailed use-case mapping, UML relationships, traceability, and outstanding assumptions. |

## Use case diagram

- [Editable draw.io source](docs/requirements/lectureseek-use-case-diagram.drawio)
- [PNG preview](docs/requirements/lectureseek-use-case-diagram.png)

The PNG is the same image embedded in the Use Case Analysis document. Open the draw.io file with [diagrams.net](https://app.diagrams.net/) to inspect or edit the diagram.

The model includes Student and Instructor actors, an abstract shared `User` role, and four confirmed external service actors: Video source platform, Media-processing service, Supported LLM service, and Translation service. The database is modeled as an internal system responsibility, not as an external actor.

## Repository layout

```text
docs/
└── requirements/
    ├── lectureseek-problem-definition.docx
    ├── lectureseek-software-requirements-specification-0.1.docx
    ├── lectureseek-user-stories-0.2.docx
    ├── lectureseek-use-case-analysis-and-diagram-0.1.docx
    ├── lectureseek-use-case-diagram.drawio
    └── lectureseek-use-case-diagram.png
```

## Status

These files document the current analysis baseline. The use-case analysis records unresolved policy questions and integration details that still need review before the requirements are treated as final.
