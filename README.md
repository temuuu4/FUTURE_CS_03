# API Security Risk Analysis

## Objective

This project focuses on analyzing public API endpoints to identify common API security risks and recommend security improvements.

## API Tested

JSONPlaceholder API

## Scope

* Public API endpoints only
* Read-only testing
* No exploitation performed
* Educational and ethical assessment

## Tools Used

* Postman
* Browser DevTools
* JSONPlaceholder API
* Documentation & Analysis Tools

## Endpoints Analyzed

* /users
* /posts
* /comments

## Key Risks Identified

* Excessive data exposure
* Unauthenticated access
* Missing visible rate limiting
* Potential data enumeration risks

## Risk Summary

| Endpoint  | Risk Level |
| --------- | ---------- |
| /users    | Medium     |
| /posts    | Low        |
| /comments | Medium     |

## Recommendations

* Implement authentication controls
* Reduce exposed sensitive data
* Apply rate limiting
* Enforce access control policies
* Monitor API activity

## Ethical Statement

This assessment was performed using safe, read-only testing techniques on publicly available APIs for educational purposes.
