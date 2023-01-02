name: Bug Report
description: Report for any bugs that may of been found in the server
labels: ["bug"]
title: "Bug Report - "
body:
  - type: markdown
    attributes:
      value: "Before opening a new issue, use the search feature for any previous topics opened here: https://github.com/newhaven-rp/Issue-Tracker/issues"
  - type: dropdown
    id: assurance
    attributes:
      label: Have You Read The Read Me?
      description: Confirm that you have read the README.md in this Github Repository to ensure all rules have been followed?
      options:
        - I have read the Rules
    validations:
      required: true
  - type: input
    id: playerid
    attributes:
      label: User Information
      description: What is your Name?
      placeholder: ex: Sas Quatch
    validations:
      required: true          
  - type: textarea
    id: summary
    attributes:
      label: Bug Description
      description: Write a short summary of what you are experiencing.
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: How To Reproduce This Bug:
      description: Include what steps that are needed in order to reproduce this issue.
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: Expected Results From This Activity:
      description: When doing this activity, what is the expected result before experiencing the bug?
    validations:
      required: true
  - type: textarea
    id: actual
    attributes:
      label: Actual Results
      description: What are the actual results you experience?
    validations:
      required: true
  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots/Videos
      description: Provide any screenshots of your console or videos of the bug you experiencing.
    validations:
      required: false             