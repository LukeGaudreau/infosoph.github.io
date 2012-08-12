---
layout: project
categories: projects
title: "PAE Server"
tagline: "LIS 469 - Final Project, Spring 2010"
description: "A simple Sinatra-based app for managing Policy Analysis Exercises"
image: "paeserver.png"
link: "http://lis469.infosoph.org"
repo: paeserver
---
{% include JB/setup %}
This site allows managing records for
[Policy Analysis Exercises](http://www.hks.harvard.edu/degrees/masters/mpp/curriculum/pae)
(PAEs) produced by students at the
[Harvard Kennedy School](http://www.hks.harvard.edu/).

### Implemented Features

- Form based on a [data dictionary](http://lis469.infosoph.org/dictionary.pdf)
- Create, List, Show records
- Add multiple authors, advisors, or clients
- Display an XML record
  - generated on the fly
  - styled with [XSLT](http://lis469.infosoph.org/style.xsl)
  - validates against an [XML Schema](http://lis469.infosoph.org/pa.xsd)

### Technologies

This project was originally written in April 2010. It was updated slightly
in August 2012 to allow hosting on Heroku.

- Ruby
- Sinatra
- HAML/SASS
- Datamapper
- PostgreSQL
- HTML5
- XML/XSLT

### TODO

The focus for this assignment was on demonstrating an understanding the
use of XML for expressing a data model. A more complete application
would require more thorough treatment.

- Form validation & error checking
- Build a method for editing/updating records
- Build methods for searching records
- Authentication/User Access
- Adopt some Dublin Core elements
