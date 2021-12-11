# ProjectX

*Just a public GitHub Pages Website of the term project [(GVSU-CIS641-ProjectX)](https://github.com/aksth/GVSU-CIS641-ProjectX). ProjectX is the code name for my project that I'm doing as a part of my course [CIS 641 at GVSU](https://www.gvsu.edu/catalog/course/cis-641.htm).* 

## Overview

ProjectX is a classified advertisement posting website. The application would feature a simple and elegant user interface to manage the classifieds. The users could log in using their email or use social sign-on options such as Facebook and Google.

This project has been implemented using Java Spring Framework in the backend and Angular for the frontend. To maintain the contract for these, we have used the API-first approach, with OpenAPI specification and its generators. We have used IAM/IDP for user management and access controls. The project also uses GitHub Actions for CI/CD pipeline that runs build and deploy jobs.

The project is deployed to Google Compute Engine's VM. The test server to which the application is deployed can be accessed at http://35.196.123.107:8090. At the moment, the social sign-on doesn't work in this server as Facebook requires HTTPS connection and Google doesn't allow IP address as the authorized JavaScript origins.

## Some Important Links

[Main Repository](https://github.com/aksth/GVSU-CIS641-ProjectX)

[Documents](https://github.com/aksth/GVSU-CIS641-ProjectX/tree/main/docs)

- [Project Proposal](https://github.com/aksth/GVSU-CIS641-ProjectX/blob/main/docs/proposal.md)
- [Prototype Software Requirements Specification](https://github.com/aksth/GVSU-CIS641-ProjectX/blob/main/docs/software_requirements_specification.md)
- [Mid-term Project Presentation](https://github.com/aksth/GVSU-CIS641-ProjectX/blob/main/docs/mid-term-presentation.pdf)
- [Software Requirements Specification](https://github.com/aksth/GVSU-CIS641-ProjectX/blob/main/docs/software_requirements_specification_final.md)

[Artifacts](https://github.com/aksth/GVSU-CIS641-ProjectX/tree/main/artifacts)

