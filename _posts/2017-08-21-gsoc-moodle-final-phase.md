---
layout: post
title: "GSoC’17 Journal: Final Phase"
date: 2017-08-21
author:     "Diwakar"
header-img: "https://image.ibb.co/hYvGVk/zjx_EZsc6a_JEd.png"
tags:
  - GSoC'17
  - Moodle
  - Web/App Dev

---


Google Summer of Code 2017 Development Period is about to conclude in next few days. Final phase has started on 28th July and ends on 21st August,  approximately 3 weeks, and Student Work Product Submissions are due by 29th August.

### E2E Documentation

Documentation for MoodleMobile End-to-End testing is done and published on Official Moodle Docs. It explains the E2E Testing of MoodleMobileApp in three different testing environments - on SauceLabs via Travis, on SauceLabs via Local Machine, on Local Machine. All the prerequisites, steps required for successful setup  and testing are described along with common errors and How-to-Write-E2E-Tests procedures.

### New and Improved TestSuites

New TestSuites are added to test remaining/new functionalities. Exisitng testSuites are improved and optimised. The E2E test code(earlier & current) is brushed up to improve code quality following jslint guidelines. All the tests are now working w.r.t latest release MoodleMobile v3.3.1 (up-to-date with  Mobile Team development workflow).

### Total Work Done
* All the existing failing test suites are corrected
* New test suites for new activities/modules/functionalities are added
* Tests to test the new/updated features are added 
* All tests are passing in SauceLabs via Travis CI
* E2E documentation is done and published.
* Travis build greatly optimised by generating build matrix (7 jobs currently) and caching the node packages
* Protractor Config files for all 3 testing environments are now available

### Current Stats

* 167 E2E Tests
* 41 Test Suites
* 4hr of actual Travis Build/Test time
* 40-50 min Travis Build/Test time after optimization
* 7 Travis jobs
* 51 Git commits

### Few related Links

* [Git branch for the GSoC'17 work](https://github.com/magician03/moodlemobile2/tree/gsoc2017)
* [Moodle Mobile Official E2E Documentation](https://docs.moodle.org/dev/Moodle_Mobile_End_To_End_Testing)
* [Travis Build History for MoodleMobile2 Build & Testing](https://travis-ci.org/magician03/moodlemobile2/builds)
* [Earlier blogpost: GSoC’17 Journal: Phase 2](https://magician03.github.io/2017/07/22/gsoc-moodle-phase-2/)
* [Earlier blogpost: GSoC’17 Journal: Phase 1](https://magician03.github.io/2017/06/28/gsoc-moodle-phase-1/)
* [Earlier blogpost: GSoC’17 Journal: Community Bonding Period](https://magician03.github.io/2017/05/24/gsoc-moodle-community-bonding/)
* [Earlier blogpost: GSoC'17 Journal: Moodle Mobile, Collaboration, Project Proposal](https://magician03.github.io/2017/05/12/gsoc-moodle-intro/)
