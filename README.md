# Data Cleaning for Rehabilitation Education Data

This repository contains a Quarto-based training lesson designed to introduce foundational data cleaning concepts using examples relevant to rehabilitation education.

The lesson is part of a broader initiative to build data literacy among rehabilitation faculty, students, and academic leaders through practical, discipline-specific training modules.

## Lesson Overview

Educational and programmatic datasets are often messy, incomplete, or inconsistently labeled. This lesson introduces structured approaches to preparing such data for analysis in R.

Topics include:

* inspecting datasets before analysis
* renaming and organizing variables
* cleaning inconsistent categorical values
* identifying and interpreting missing data
* detecting duplicate records
* creating derived variables for interpretation
* producing simple summaries and visualizations

The lesson uses a simulated rehabilitation education dataset representing pathway enrollment, assessment performance, and attendance patterns.

## Audience

* Rehabilitation faculty and academic leaders
* Entry-level doctoral students
* Clinical education teams
* Researchers working with educational or workforce datasets

## Technology

* R
* tidyverse
* Quarto

## Project Structure

```
data-cleaning-rehab-education/
├── index.qmd        # Lesson source file
├── docs/            # Rendered site for GitHub Pages
│   ├── index.html
│   └── index_files/
└── README.md
```

## Viewing the Lesson

The published lesson site is available at:

https://madelineratoza.github.io/data-cleaning-rehab-education/

## Rendering Locally

To render the lesson locally:

```
quarto render index.qmd --output-dir docs
```

## About This Training Series

This lesson is part of a growing open training series focused on:

* foundational R skills
* applied data workflows in rehabilitation education
* spatial reasoning and GIS applications
* responsible interpretation of program and assessment data

Additional modules are in development.

## Author

Madeline Ratoza, PhD
Health equity researcher and rehabilitation educator
