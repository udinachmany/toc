# Project Description

Habitus is a build workflow tool for Docker images. Using Habitus, users can:

- Build multi-stepped Docker images across a shared cluster of build servers.
- Use and move build artifacts between different steps
- Provide secrets during build (for example private SSH keys to pull build dependencies in private repositories) without leaving trace
- Squashing layers in Docker images after build
- Enforce build step dependencies
- Building images on a multi-tenanted environment like a SaaS CI provider

Through these features Habitus makes the following possible:

- Construction of complex multi-stepped builds
- Reduction of attach surface and image size by moving the build artifacts from a build-time image to a runtime image
- Keeping their private repositories secure by preventing secrets being left inside of images by mistake

**Sponsor from TOC:** ---

**Preferred Maturity Level:** Sandbox

**License:** Apache License v2

# Source Control
https://github.com/cloud66-oss/habitus

# External Dependencies

A complete list of dependencies can be found here: https://github.com/cloud66-oss/habitus/blob/master/Gopkg.lock

**Initial Committers:** Khash Sajadi, Daniël van Gils and Vic van Gool from Cloud 66 (since creation) and KUOKA Yusuke

**Infrastructure Requests:** None initially. CI is currently hosted on Codeship and covered by the free tier for open source projects.

**Communication Channels:**
Slack: https://communityinviter.com/apps/cloud66ers/cloud-66-community

**Issue Tracker:** https://github.com/cloud66-oss/habitus/issues

**Website:** http://www.habitus.io/

# Release Methodology and Mechanics

Habitus uses Semantic Versioning. It is written in Golang and can be compiled independently. The release process involves tagging the release and running Habitus to generate cross-platform compilations of the binary. Those binaries are then uploaded as part of a Github Release here: https://github.com/cloud66-oss/habitus/releases. Changelog is kept and maintained here: https://github.com/cloud66-oss/habitus/blob/master/CHANGELOG.md

**Social Media Accounts:**
None

# Community Size and any Existing Sponsorship

Adopters:
Cloud 66
VMware
Sony
Bank of America
More: A great deal of Github users at their respective companies: https://github.com/cloud66-oss/habitus/stargazers

Integrations:
Docker (Use cases: Docker engine for the builds)

**Sponsors**
https://cloud66.com/

**Numbers:**
5 active contributors currently (3 from Cloud 66), with 5 other contributors over past 12 months.
843 stars
69 Forks
24 releases

# Statement of Alignment with CNCF Mission

With containers being a core tenant of cloud native computing, a flexible, easy to use and robust tool to facilitate building of container images is a critical part of developing a successful cloud native infrastructure setup at any company aiming to use containers.

# Benefits to the CNCF

By making it possible, safe and simple to build container images, Habitus lowers one of the first and big barriers of entry into cloud native infrastructure for many users by promoting and simplifying best practices around secret control, facilitating build of compiled languages like Java or Golang in multiple steps and improving operation security by reducing attack surface of runtime images.

# What does Habitus need from the CNCF

Habitus needs a well respected, vendor-neutral home that can help serve as a starting point for promoting better standards for building containers. In addition to increased visibility, we hope that inclusion in the CNCF will foster communication between Habitus and other projects in the ecosystem. As the project grows, we would want to leverage the CNCF’s expertise around project governance and community standards as those are fundamental to the long term success of the project.

The project does not have any infrastructure requests at this time. CI is currently hosted on Codeship and covered by the free tier for open source projects.

