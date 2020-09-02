---
layout: default
permalink: index.html
---

# GA4GH Cloud Work Stream

The [GA4GH](https://www.ga4gh.org/) Cloud Work Stream focuses on API standards (and implementations from our partner Driver projects and other community members) that make it easier to "send the algorithms to the data".  Specifically, we have 4 API standards that allow you to share tools/workflows (TRS), execute individual jobs on clouds using a standard API (TES), run full CWL/WDL workflows on execution platforms (WES), and read/write data objects across clouds in an agnostic way (DRS). 

<br>

These standards are really inspired by large-scale, distributed compute projects including, for example, [PCAWG](https://pcawg.icgc.org).  Efforts such as these are characterized by data living in many different cloud environments, compute needing to be done across these cloud locations, and a motivation for working with disparate clouds via common and consistent API interfaces.  The net effect is a highly portable analysis code that ultimately enables "[FAIR](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4792175/)" science, e.g. findable, accessible, interoperable, and reproducible tools, workflows, and datasets.

## Presentation

See this [presentation](https://docs.google.com/presentation/d/1_MFTCw1uDrFNtbki2Nvyh2I2IYOlQKTHmrZgMTspdm4/edit#slide=id.g54dc8a46d6_0_0) from March of 2019 for an overview of what we do.

## Standards

Our API standards are defined in Swagger YAML/OpenAPI 2.0 (with an eye toward OpenAPI 3.0) in repositories within the GA4GH GitHub organization:

* [Data Repository Service API](https://github.com/ga4gh/wiki/wiki/Data-Repository-Service) - DRS API
* [Tool Registry Service API](https://github.com/ga4gh/wiki/wiki/Tool-Registry-Service) - TRS API
* [Task Execution Service API](https://github.com/ga4gh/wiki/wiki/Task-Execution-Service) - TES API
* [Workflow Execution Service API](https://github.com/ga4gh/wiki/wiki/Workflow-Execution-Service) - WES API


## Standards Maintenance

### Security Considerations
If a security issue with any of the above specifications is realised please send an email to 
<security-notification@ga4gh.org> detailing your concerns.

### HubFlow and Contributions

The way to contribute development effort and code to the project is via GitHub pull requests. GitHub provides a nice [overview on how to create a pull request](https://help.github.com/articles/creating-a-pull-request).  See the CONTRIBUTING.md document in each schema repo.  We follow [HubFlow](https://datasift.github.io/gitflow/) which means we use a feature branch strategy with pull requests always going to `develop` and releases happening from `master`.

### Voting Process for PRs

See individual schema repos for more details.  In short, the GA4GH has a number of Driver Projects, each of those associated with the Cloud Work Stream will nominate a representative. When a PR is up for a vote the Driver Project representatives will be notified over email and a note made in the PR.  This starts a timer until the PR is accepted or rejected.  None of the Driver representatives may vote against a proposed change for it to proceed. In addition, they must not be overridden by the Cloud Work Stream Leads, Brian O'Connor and David Glazer.

## Our Multi-year Plan

See this [document](https://docs.google.com/document/d/1p7j0AY5CoiQccMTYnjC66OatDau50mbu6xW7cTNPoaI/edit) that describes our plans for the next couple years.

## Meetings

### Weekly Work Stream Meeting

We have a weekly call on Mondays at variable times to accommodate various timezones:

* 10am Pacific time on the second and third Monday of every month
* 2pm Pacific time on the last Monday of every month

We invite anyone interested in these standards and/or the systems that implement them to join us on these calls.

* [Slack](https://join.slack.com/t/ga4gh-cloud/shared_invite/enQtNTI4MzcxNDgwNjU4LTg3NmJhY2Q4OGRlMDc0Yjc3NTZkOThiZTZjZDdiNjIyYTk1YmIyMDMyMzJkNmEyYTM3Mzk2NTYwMDFmMTgzOTg) for real-time conversations, keep decisions and important info in GitHub issues please.
* [Google Group](https://groups.google.com/a/genomicsandhealth.org/forum/?hl=en-GB#!forum/ga4gh-cloud) for discussion and meeting announcements
* [Current Agendas and notes](https://w3id.org/ga4gh/minutes/cloud)
* [2018 Jan-Oct Agendas and notes](https://docs.google.com/document/d/1UyXjHAaqYew4WwgdbJoJCLiWIBslsgWi89GT0xPkI4E/edit#), [2017 Agendas and notes](https://docs.google.com/document/d/1c9r3TAchnM1DUeKNizqspApJ-LLN_kXoJjoewfeOS60/edit?ts=59f74703#heading=h.bfm4lckrdcs8), old [Agendas and notes](https://docs.google.com/document/d/1kP7FzDJ9B7j7GMGeEiGZJazPLF4Z1p8K1a3FJazPigc/edit) from the Containers and Workflows Task Team)
* Upcoming talks: please email [Rishi Nag](mailto:rishi.nag@ga4gh.org) if you want to get on the weekly agenda. Check [the Cloud Meeting topics spreadsheet](https://docs.google.com/spreadsheets/d/1zIXurW0MbQ2rlnWCfFQjEHmjF2ShrQb8r8otlDA4MO8/edit?usp=sharing) for slots

Dial-in details for the calls are available on request to [Rishi Nag](mailto:rishi.nag@ga4gh.org)

## Past Meetings

### GA4GH Connect in Hinxton, April 2019

See [Cloud @ GA4GH Connect 2019 Hinxton](https://docs.google.com/document/d/1XsYCMG2JkJen-ZjPAcy7c9RfA41wbzAmXBkB3iQm6PI/edit#heading=h.em5st38cwrw7)

### GA4GH 6th Plenary in Basel, Switzerland

See [this site](https://www.ga4gh.org/event/ga4gh-6th-plenary/) for more info.

### GA4GH 5th Plenary in Orlando

This meeting happened Oct 15-17th and the Cloud Work Stream had a breakout session for most of the 15th.

For our agenda see [here](https://docs.google.com/document/d/1v-hTt-ZUtxJpk8kjOqU7-IyasIMkU5A0kNLkDbzKhZY/edit)

For the general conference, agenda see [here](https://broadinstitute.swoogo.com/ga4gh5thplenary/agenda)

If you were not able to attend you can watch the Plenary recording [here](https://www.youtube.com/channel/UCmCg1AcAY_qHXfOhePAFAeQ)

## GA4GH-DREAM Infrastructure Challenges, API Test Beds, and Registries

We are working closely with the [DREAM Challenges](http://dreamchallenges.org/) to test our API standards and workflow sharing process.  Essentially, we are attempting to demonstrate API and process FAIR-compliance.  This is a multi-phase effort with the first two challenges focusing on tool and workflow portability and reproducibility.

* [Tool Execution Challenge](http://synapse.org/GA4GHToolExecutionChallenge)
* [Workflow Execution Challenge](https://www.synapse.org/WorkflowChallenge)

We also work closely with our Driver Projects through "Test Beds" that are focused efforts to demonstrate conformance of API implementations with the specifications.

Ultimately we want to have regular API verifications running and a registry where users can see the available services that are conforming to the specifications.  This can be used by researchers to see what services are available and used by implementers to see what software is available for deployment that supports the GA4GH APIs.
