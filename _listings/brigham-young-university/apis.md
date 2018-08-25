---
name: Brigham Young University
x-slug: brigham-young-university
description: 'Official page for Brigham Young University.   Undergraduate applications:
  https://www.lds.org/church-education/college-application?lang=eng  Graduate program
  info: http://graduatestudies.byu.edu'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1510-brigham-young-university.jpg
x-kinRank: "9"
x-alexaRank: "4887"
tags: API Provider
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/api-provider/master/_listings/brigham-young-university/apis.md
specificationVersion: "0.14"
apis:
- name: BYU Academic
  x-api-slug: byu-academic
  description: The service provides support for courses taught at Brigham Young University.
    It allows creation and updating of course records with links to the university
    curriculum inventory of all courses and student registration records. The service
    allows for control of coursework and student performance across the BYU academic
    calendar.API methods support definition and updating of course sections linked
    to listing from the curriculum inventory, with offering dates and times, student
    registration rolls, and other class schedule variables. Methods also allow updating
    of the official curriculum listings with official title and grading rules, records
    of student course performance and academic status, and dates from the BYU academic
    calendar.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1510-brigham-young-university.jpg
  humanURL: https://byu.edu
  baseURL: https:///
  tags: API Provider
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/api-provider/master/_listings/brigham-young-university/openapi.md
- name: BYU Email Verification
  x-api-slug: byu-email-verification
  description: The service validates email addresses under the internet domains used
    by Brigham Young University. It accepts a character string as input which it compares
    against records for the buy.edu and byu.net domains. The system response either
    confirms that the address string submitted is associated with a BYU user account
    or an error message that the address is not recognized.API methods check whether
    a submitted string identifies a properly formatted email address in domains managed
    by BYU. It then checks the specific address against the university&#039;s login
    databases to confirm whether it is registered for a user account there or whether
    it forwards to a valid BYU address.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1510-brigham-young-university.jpg
  humanURL: https://byu.edu
  baseURL: https:///
  tags: API Provider
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/api-provider/master/_listings/brigham-young-university/openapi.md
- name: BYU Entrance Exams
  x-api-slug: byu-entrance-exams
  description: The service provides access to scores on placement exams reported to
    Brigham Young University on behalf of students applying for admission and to course
    credits awarded on the basis of those scores. Exam scores cover testing programs
    such as Advance Placement (AP), College Level Entrance Placement (CLEP), and others.
    Data is retained within the the university&#039;s student information application
    under substantial confidentiality requirements mandated by the U.S. Family Educational
    Rights and Privacy Act (FERPA).API methods support retrieval of placement exam
    scores for a student based on a request identifying the correct student ID value.
    Separate methods cover entrance exam scores and credits awarded on the basis of
    the scores.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1510-brigham-young-university.jpg
  humanURL: https://byu.edu
  baseURL: https:///
  tags: API Provider
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/api-provider/master/_listings/brigham-young-university/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/brigham-young-university
- type: x-developer
  url: https://developer.byu.edu
- type: x-twitter
  url: https://twitter.com/BYU
- type: x-website
  url: https://byu.edu
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---