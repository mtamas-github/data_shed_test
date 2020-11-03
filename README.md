# The Data Shed Technical Test

## Overview

This document contains a set of instructions for engineering candidates to follow in order to complete The Data Shed technical assessment.

The purpose of the assessment is to gain an insight into the candidate's approach to translating a set of system requirements into functioning code.

## Instructions

The completion of this technical test should result in the creation of a fully functioning application that meets the requirements outlined by the below objective.

No constraints are imposed with regards to the framework or programming language chosen, nor is it expected that the assessment is to be completed within any set time frame.

If the candidate requires any further information or encounters any issues in completing this assessment, please contact [talent@thedatashed.co.uk](mailto:talent@thedatashed.co.uk).

Once complete, the generated codebase (including all source files) should be zipped and emailed to [talent@thedatashed.co.uk](mailto:talent@thedatashed.co.uk).

The source code must **not** be made available via a public code repository (e.g. <github.com>).

## Objective

At the DataShed we process a lot of data, sometimes this data can arrive in many formats and at varying levels of data quality. Given [a subset of personal data](./profile-data/DataShed_Technical_Test.csv), you are required to create a simple application that meets the below user story and acceptance criteria.

### User Story

> As a user, I want to understand the number of duplicate and unique records I have in my data, so I can be sure that I can identify unique and related records in the data that I hold.

### Acceptance Criteria

The application should:

- Read data from [the source file](./profile-data/DataShed_Technical_Test.csv)
- Output:
  - the number of records in the source data set
  - the number of unique records\* in the source data set
  - the number of different people\*\* in the source data set
- Write the data that is considered duplicated/related to a [CSV file](https://en.wikipedia.org/wiki/Comma-separated_values) called `relateddata.csv`
- Consider data that is similar and classify it as a duplicated/related. For example "Wilyam Premadasta" and "William Premadasa" should be considered the same person.

\* _exact duplicate records should be eliminated from this measure._

\*\* _the number of records following your de-duplication processing._

### Considerations

Your application should meet the above requirement and acceptance criteria.

The code should be maintainable and written with consideration to testing, performance and future enhancements.

The application should be relatable to real world experience and include appropriate tests, code practices and error handling.

The application can be created using any suitable programming language and should include clear instructions on how to execute the application to obtain the expected results.

The application may be marked by someone using a different operating system to the one you use. It is therefore recommended that you provide some documentation (e.g. a `README.md` file) to assist the reviewer in the running of your code.
