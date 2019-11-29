---
layout: default
title: Engineering
description: “Engineers like to solve problems. If there are no problems handily available, they will create their own problems.”
---

# Communication

Please read [principles and best practices for effective communication.]({{ site.baseurl }}/principles/communication.html)

## Slack
Slack is the primary means of communication within teams at AVL. The main development-focused channels are:
* `#dev`
* `#dev-back-end`
* `#dev-front-end`
* `#devops`

## Engineering Mailing List
You will be added to the relevant email lists as part of your onboarding process.

## JIRA Project Backlog

All engineering tasks and features originate from a JIRA issues ticket. The ticket will describe the features list, deliverables, story points, priority, and relevant manager. JIRA is the **primary software project management tool** used to manage software at our firm.

# Velocity of Work

Delivering value to our customers in the fastest way possible is the driver for how engineering processes are structured at AVL. Being able to execute as a velocity faster than the competition is absolutely paramount to the success of our business. As the old adage goes, time is money.

## Measurement of Velocity

We measure velocity of work by dividing time into **1-week sprints**, and measuring the amount of work completed within each sprint. We use JIRA to manage your Agile sprint process. Each task is assigned a **Story Point**, which is a relative unit of work.

### KPIs

We track the number of story points completed within each sprint, and the summed number is our **Key Performance Indicator (KPI)**.

> KPI: Story points completed in a sprint.

We will compare your KPI across many sprints over sprints, with your peers within the same team, and across the firm.

## OKRs

We will set a goal we hope each individual contributor is able to achive for their KPI number. This goal system that defines a certain KPI value at a certain point in time in the future, is a **Objective and Key Result (OKR)**. Each engineer will have OKRs for their KPIs.


## Velocity vs. Stability

Prioritizing the velocity at which we deliver new value and features to our customers means a cosntantly changing product. We believe in the [**Innovator's Dilemma**](https://en.wikipedia.org/wiki/The_Innovator%27s_Dilemma){:target="_blank"} and the constant need to innovate. 

We believe in launching an imperfect product fast over delivering a perfect product. Iterate fast. Fail fast. Learn.

## Velocity vs Refactoring

Our philosophy on refactoring is that it must serve our customers. If refactoring will demomnstratably allow us serve our customers better, then we will refactor.

In our experience, the best time to refactor is immmediately after a big product launch. Refactoring should be done *before* adding any updates or new features to existing code. Developers also have more time to refactor immediatley after delivering a product to market.

# Code Standards

We are a strong adherent to coding standards, and code quality. 

## Automated Checks

We have **automated processes** for checking compliance with our coding standards. We use open source tools, web hooks that check source code for style and design problems post-commit. Commits with coding standard violations will auotmatically be rejected from the main branch.

## Google Style Guides by Default

We follow [**Google Style Guides**](https://google.github.io/styleguide/){:target="_blank"} for all langauges *UNLESS SPECIFIED OTHERWISE*. 

## Code Review

* Code reviews at done **BEFORE** the code is merged into main branch via a pull request.
* An engineer's direct manager should be added to **every pull request**.
* Code reviews are completed at the reviewer's own time.
* All reviewer's must approve before pull request can be approved.

### Motivation for Code Review

* Committers are motivated to write better code knowing if someone will look at it.
* Learning and sharing knowledge on how to write better code.
* Consistency in design and coding style.
* Catching bugs, anti-patterns, and design flaws early.

# Quality Control & Testing

* Testing should be done by a different person than the one who wrote the code.
* Therefore, testing is the responsiblity of QC / QA Engineers, and not the developers.
* QC Engineers will write automated tests that run after each pull request into the main branch.

# Produciton & Site Reliability

* Production monitoring and troubleshooting is the responsibility of DevOps / SRE.
* DevOps is responsible for escalating issues and bugs to the relevant engineer.
