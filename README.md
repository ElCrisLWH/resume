This README will present the repository, its features and how to use it.

This repo is intended for recruiters interested on my experiences and people who want to see resume examples or templates.

# Latex Resume Template

Modern templates tend to be extremely rigid, making it impossible in most cases to make slight modifications to get a document exactly as you like.
That is why I built my own light template, whose simplicity makes it easy to use and tune.

Basic Latex knowledge might help understanding and developing.

The repo currently has a `resume.tex` which contains all the necessary commands to build your resume.

The other files are my own resumes by desired position and language.

## Features

As every resume should have, the main sections are Contact Information, Education, Work Experience, Teaching Assistantships, Projects, Honors, Computer Skills, Languages, Free Time. Any of these can be skipped if not relevant or if you do not have that kind fo experience.

The commands are:

-   `\contactinformation`: builds the header with your name and desired position as title, and contact links as mail, linekdin profile, personal website and github.
-   `\concept`: begins a section building its title.
-   `\job`: builds the job title, location and date.
-   `\desc`: free space to explain the impact you had at that position. When possible, recommended to follow the pattern: Accomplished x as measured by y, by doing z.
-   `\data`: builds a one-line experience with its location or date.
-   `\map`: begins a two columns table, intended to be used a map listing properties related to a concept.
-   `\entry`: builds the concept and its related properties.

## Setup

You can either clone this repository and work with it in any text editor of your choice, provided that you have a tex compiler, or download and use directly on any latex editor as [overleaf](https://www.overleaf.com/).
