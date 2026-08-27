# Technology Core Documentation Template

This repository provides a template of documentation that we ask scientists and engineers to fill out together when developing new software

_Please write exactly one sentence explaining what this software does. Update the section heading to match the repository name._

**Principal Investigator:** Adam Bosen

**PI Email:** adam.bosen@boystown.org

**Lead Engineer:** Seth Bashford

**Engineer Email:** 

**Date Project Started:** 8/24/26

# Purpose
## What does this program do?
This template is intended to provide a standard framework for documenting research software developed at Boys Town.

_Please describe at a high level what this program is designed to do when used. Your target audience is other scientists and your goal is to tell them just enough information to decide whether they want to use this software for their own research. Aim for 3 - 4 sentences at most. Detailed descriptions belong in the project's associated [wiki](../../wiki)._

## What problem does this program solve?
Software has been inconsistently documented in the past, which limits reuse of existing solutions and can make maintenance much harder in the future. It is difficult to fix bugs in software if we do not know what the intended behavior is.

_Please describe in a little more detail the premise of the project, including scientific background and the need for this software in your work. Try to keep this description to no more than 3 - 4 paragraphs. You can embed pictures and links to other parts of the project. You can link to the [premise section](../../wiki/1.-Premise) of the project's wiki if you want to elaborate with more detail._

# Typical use
## Overview of typical uses
Scientists and engineers will collaborate to develop documentation that describes the premise and essential features of the project before any code is written. The engineer will convert the list of required features into a list of issues that will guide development of software. Working through an issues list provides regular milestones for progress, provides a prioritized timeline, and provides tangable critera for project success. The issues list can be revised to add, remove, or reorder issues during the development process by both the scientist and the engineer. During development, the engineer will document details of implementation manually or by using code markdown to autopopulate documentation. The scientist and engineer will together describe how the code should be used. Once the software has been successfully used in a research product (e.g. a manuscript or conference poster) the scientist will addd a section describing those research products.

_Please describe how you envision the software being used, and describe the specific set of steps that are required for that use. This can be as long as you need, but technical details should probably be saved for the wiki. You want to convince interested scientists that their team is capable of using your software and precisely describe what that use entails._

## Example use
Scientist Adam has an idea for a web-based speech recognition platform he would like to develop. Adam writes a description of the scientific premise of the project and a list of key features and requirements and shares those details with Engineer Seth. Seth then asks for clarification on that feature list until he is confident that he understands the requirements. Seth proposes a framework for an implementation and Seth and Adam work together to develop a list of issues and prioritize those issues for development. Seth implements the features described by each issue in order and regularly shows progress to Adam. Adam's lab team tests the software at each milestone and provides feedback by revising and reorganizing the issues list. Once the software has hit a release milestone Adam's lab starts using the software. Whenever a research product is created that uses the software Adam updates the wiki to provide a reference to that product.

_Please provide a concrete example of what typical use looks like, including reference to example diagrams, a description of the intended workflow, and guidance on decisions that the user may need to make._

# Setup
## Prerequisites
A GitHub account linked to the BoysTownOrg Organization.

_Please list any requirements or dependencies with links or instructions to obtain those dependencies._

## Installation
This repository can be cloned or files can be manually copied to existing projects as needed.

_Please describe the steps required to begin using the software._


## License
This work is licensed under the [MIT License](LICENSE.txt).

_Please provide a relative link to your License.txt file: [License](LICENSE.txt). If you do not know what license to use please talk to the tech core, we can provide recommendations._
