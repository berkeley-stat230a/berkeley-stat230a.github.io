---
layout: home
title: "Stat 999: Course Overview"
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: "Stat 999: Course Overview"
---

# Stat 999: Course Overview
{: .mb-2 }
UC Berkeley
{: .mb-0 .fs-6 .text-grey-dk-000 }



## Offerings

1. [Spring 2025](/spring-2025)




## Overview

This is a GitHub Pages template based on Just the Class, developed for the
purpose of quickly deploying course overview websites. Such websites link to
previous course offerings, provide a summary of what the course is about,
and may list learning goals and prerequisites. This overview section would
normally be replaced by the description of a specific course, and could
include information from the [Berkeley Academic
Guide](https://guide.berkeley.edu/courses/stat/).

### Configuration
After instantiating this template, set the following secrets and variables
in the new repository.

| Type     | Required | Name                 | Value |
|----------|----------|----------------------|-------|
| Secret   | Yes      | SIS_COURSE_API_ID    | `app_id` of [Course API credential](https://developers.api.berkeley.edu/api/100/credentials) |
| Secret   | Yes      | SIS_COURSE_API_KEY   | `app_key` of [Course API credential](https://developers.api.berkeley.edu/api/100/credentials) |
| Variable | Yes      | SIS_SUBJECT_AREA     | SIS subject area code, e.g. `STAT` |
| Variable | Yes      | SIS_COURSE_NUMBER    | SIS course number, e.g. `243` |
| Variable | Yes      | GIT_NAME             | Git `user.name` for GitHub Action commits, e.g. `GitHub Actions` |
| Variable | Yes      | GIT_EMAIL            | Git `user.email` for GitHub Action commits, e.g. `unit@dept.berkeley.edu` |
| Variable | No       | GOOGLE_ANALYTICS_TAG | Google Analytics tag(s), e.g. `G-...` |
| Variable | No       | AUTHOR               | Jekyll website author, e.g. `Course Staff` |
| Variable | No       | COURSE_DATA_FILE     | Path to YAML file, e.g. `.github/scripts/override.yml`, containing SIS course data. Data in this file will override anything retrieved from the SIS. |


## Logistics

(Example from SIS) Three hours of lecture and two hours of laboratory per
week. Six hours of lecture and three hours of laboratory per week for 8
weeks.


## Prerequisites

(Example from SIS) Mathematics 1A, Mathematics 16A, Mathematics 10A/10B,
or consent of instructor.

