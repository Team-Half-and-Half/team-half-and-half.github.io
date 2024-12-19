---
layout: default
---
# Team Half and Half

## Table of Contents
- [Overview](#overview)
- [Key Outcomes](#key-outcomes)
- [User Guide](#user-guide)
- [Continuous Integration](#continuous-integration)
- [Development History](#development-history)
- [Team Members](#team-members)

## Overview
[SpireBooks](https://github.com/Team-Half-and-Half/spirebooks) is a management decision tool, made with the intent to facilitate and help organizations make informed financial and strategic decisions based on a comprehensive consolidation of financial data and integration of non-financial factors.

GitHub organization page: [github.com/Team-Half-and-Half](https://github.com/Team-Half-and-Half)

## Key Outcomes

* Succeed in building a decision-making management tool that can be easily used by autonomous companies 
* Visualize an interactive fiscal sustainability model spreadsheet
* Make it easy for companies to understand their current financial state based on the historical data
* Utilize features for companies to input their own data which will then allow the web application to do the math and show a visual representation of the forecast
* Visually present the companies numbers as non-static, allowing them to see how different inputs can change the forecast
* Create visually pleasing charts and dashboard that are easy to look at and navigate

## User Guide
<p style="font-weight: bold; text-align: center">Landing</p>
<img src="img/layouts/landing-page-1.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">
<img src="img/layouts/landing-page-2.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

<p style="font-weight: bold; text-align: center">Sign In</p>
<img src="img/layouts/sign-in-page.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

<p style="font-weight: bold; text-align: center">Sign Up</p>
<img src="img/layouts/sign-up-page.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

<p style="font-weight: bold; text-align: center">Dashboard</p>
<img src="img/layouts/dashboard.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

<p style="font-weight: bold; text-align: center">Financing > Audited Balance Sheet</p>
<img src="img/layouts/balance-sheet.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

<p style="font-weight: bold; text-align: center">Financing > Budget P&L Sheet</p>
<img src="img/layouts/budget-sheet.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

<p style="font-weight: bold; text-align: center">Financing > Scenario Profiles</p>
<img src="img/layouts/scenario-profiles.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

<p style="font-weight: bold; text-align: center">Audit > Upload</p>
<img src="img/layouts/import-file.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

<p style="font-weight: bold; text-align: center">Visualize > Compare Projections</p>
<img src="img/layouts/compare-projections.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

<p style="font-weight: bold; text-align: center">Visualize > Manage Projections</p>
<img src="img/layouts/manage-projections.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

<p style="font-weight: bold; text-align: center">Manage > Verification Table</p>
<img src="img/layouts/verify-users.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

<p style="font-weight: bold; text-align: center">User Settings</p>
<img src="img/layouts/user-settings.png" style="display: block; margin-left: auto; margin-right: auto; width: 75%;">

## Continuous Integration
[![ci-spirebooks](https://github.com/Team-Half-and-Half/spirebooks/actions/workflows/ci.yml/badge.svg)](https://github.com/Team-Half-and-Half/spirebooks/actions/workflows/ci.yml)

SpireBooks uses [GitHub Actions](https://docs.github.com/en/free-pro-team@latest/actions) to automatically run ESLint and TestCafe each time a commit is made to the default branch.  You can see the results of all recent "workflows" at [https://github.com/Team-Half-and-Half/spirebooks/actions](https://github.com/Team-Half-and-Half/spirebooks/actions).

## Development History
The development process for SpireBooks conformed to Issue Driven Project Management practices. In a nutshell:

- Development consists of a sequence of Milestones.
- Each Milestone is specified as a set of tasks.
- Each task is described using a GitHub Issue, and is assigned to a single developer to complete.
- Tasks should typically consist of work that can be completed in 2-4 days.
- The work for each task is accomplished with a git branch named "issue-XX", where XX is replaced by the issue number.
- When a task is complete, its corresponding issue is closed and its corresponding git branch is merged into master.
- The state (todo, in progress, complete) of each task for a milestone is managed using a GitHub Project Board.
- The following sections document the development history of SpireBooks.

### Milestone 1
The goals for Milestone 1 were to have several mockup pages and acceptance tests.

Milestone 1 was managed using [SpireBooks Github Project Board Milestone 1](https://github.com/orgs/Team-Half-and-Half/projects/1/views/1).

### Milestone 2
The goals for Milestone 2 were to add functionality to the pages and to setup our databases.

Milestone 2 was managed using [SpireBooks Github Project Board Milestone 2 (Customer Meeting)](https://github.com/orgs/Team-Half-and-Half/projects/5/views/2).

### Milestone 3-4
The goals for Milestone 3-4 were to continue implementing functionality, with a focus on the databases. 

Milestone 3-4 was managed using [SpireBooks Github Project Board Milestone 4 (Customer Meeting)](https://github.com/orgs/Team-Half-and-Half/projects/6/views/1).

### Milestone 5
Milestone 5 was managed using [SpireBooks Github Project Board Milestone 5](https://github.com/orgs/Team-Half-and-Half/projects/10/views/1).

### Milestone 6
Milestone 6 was managed using [SpireBooks Github Project Board Milestone 6 (Customer Meeting)](https://github.com/orgs/Team-Half-and-Half/projects/11).

### Milestone 7
The goals for Milestone 7 were to finalize the application and implement specific roles and permissions for each page.

Milestone 7 was managed using [SpireBooks Github Project Board Milestone 7 (Customer Meeting)](https://github.com/orgs/Team-Half-and-Half/projects/12).

## Team Members
SpireBooks was created for and in collaboration with [Spire Hawaii](https://spirehawaii.com) as part of the [University of Hawaii at Manoa's](https://www.ics.hawaii.edu/) Software Engineering II Fall 2024 course. It is developed and maintained by the following students: [Nicholas Beydler](https://beydlern.github.io/), [Xavier Burt](https://xavierburt.github.io/), [Payton Higa](https://PaytonHAH.github.io/), [Samantha Mallari](https://samallari.github.io/), [Brandon Nelson](https://bksnelson.github.io/), [Christopher Pascual](https://caspascual.github.io/), [Jonathan Sapolu](https://jsapolu99.github.io/), and [Anthony Tirabassi](https://t-tirabassi.github.io/).

View our team contract [here](https://docs.google.com/document/d/1PjFIRw1aXRPUn2tKEE4p0D7bu_I8XHgkIsCQO42zJVk/edit?usp=sharing).
