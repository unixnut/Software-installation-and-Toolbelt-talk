# Software installation and Toolbelt talk
A talk to be given at the [Perth Linux Users' Group][PLUG] on 8 Feb 2022.

    [PLUG]: http://www.plug.org.au/

## Blurb

The process of ad-hoc system administration, in which lengthy and possibly insecure installation commands are typed/pasted from software project websites or even Q&A sites, is both time-consuming and not recommended from a security perspective.

However, OS-provided software packages are often old versions or not present at all. And modern DevOps approaches like Ansible, Puppet, Vagrant or Docker are not always justified, especially for experimentation or work on one's own workstation.

Toolbelt fills the gap, by automating the recommended installation approach described on the provider's website for each supported piece of software.

This presentation will give an overview of Toolbelt, including a partial code walkthrough and a description of how to extend it to support additional software.

## Outline

1. Introduction
  1. Toolbelt
  2. What is Unix?
  3. Linux distributions and packages
2. Linux Package Security
3. 3rd-party Software Security
4. Toolbelt principles
  1. Complexity level
  2. Verification methods
  3. Entities
  4. Dependencies
5. Risks and trade-offs
6. Toolbelt example
  1. `toolbelt list-entities`
  2. `toolbelt install boring`
7. Toolbelt installation
  1. Remote: bootstrap/install.yaml (requires Ansible)
  2. Local: bootstrap/install.sh
8. Extending Toolbelt
  1. Live demo: Sandstorm
9. Future features
  1. Projects
  2. Components
  3. Riders
10. Conclusion
11. Questions?

## Presenter bio

Alastair is a Software Engineer and system administrator by trade.  He has a BSc in Computer Science from Curtin University.

His computer-related interests lie in various areas within his trade; suffice to say that he is a "geek of many colours". :)  Alastair is a die-hard FOSS user and Linux fan.

He is also a freelancer with his own business.  [Warpspace IT](http://www.warpspace.net/) is a consultancy with a fairly broad focus on the technical side of IT.

### Contact

guru@warpspace.net

1300 881744

## Slides

**TBA**
