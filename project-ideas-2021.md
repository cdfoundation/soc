
## Jenkins

List of the project ideas is available on the [Jenkins website](https://jenkins.io/projects/gsoc/2021/project-ideas/).

## Ortelius

Ortelius is a microservice management platform that integrates into CI/CD to perform automated configuration management, versioning and tracking of microservices and other cloud native components providing visibility before you deploy.  This year Ortelius will participate in GSOC with 3 projects, two focused on interoperability and one around data visualization. 

Project Description:
- Spinnaker and ArgoCD - add integration to allow [Spinnaker](https://github.com/ortelius/ortelius/issues/105) and [ArgoCD](https://github.com/ortelius/ortelius/issues/215) to call Ortelius for updating deployment configuration data and relationships.
- [Relationship Visualization](https://github.com/ortelius/ortelius/issues/216). Research and implement updates to the Ortelius Visualization Maps to expand the data for Domains, Component Blast Radius and Application Bill of Material reports.

Recommended Skills: 
- Javascript
- Java
- Python

Mentor(s): 
- [Steve Taylor](https://github.com/sbtaylor15)
- [Karamjot Singh](https://github.com/karamjotsingh/)
- [Sacha Wharton](https://github.com/sachajw/)
- [Neetu Jain](https://github.com/Neetuj/) 

To learn more view the [Ortelius Project Page.](https://ortelius.io/2021/01/18/ortelius-joins-gsoc/)

## Screwdriver



### Improve build workflow

Major theme for Screwdriver GSoC project is to enhance the build workflow capabilities to improve Developer Productivity.

#### Enable running build steps in Parallel

Enable running steps in a build to run in Parallel to improve build speed.

Recommended Skills: golang, javascript

Mentor(s): [Pritam](https://github.com/pritamstyz4ever/), [Jithin](https://github.com/jithine/)

Issues: https://github.com/screwdriver-cd/screwdriver/issues/2344

#### Enable retry functionality for failed build steps

Failed steps in a build should be optionally retried to improve build resiliency.

Recommended Skills: golang, javascript

Mentor(s): [Pritam](https://github.com/pritamstyz4ever/), [Jithin](https://github.com/jithine/)

Issues: https://github.com/screwdriver-cd/screwdriver/issues/1645

#### Support Matrix Jobs

Provide matrix build capability which allows developers to use concise syntax to express their build pipeline.

Recommended Skills: javascript

Mentor(s): [Alan](https://github.com/adong), [Tiffany Kyi](https://github.com/tkyi/)

Issues: https://github.com/screwdriver-cd/screwdriver/issues/1309



#### Trigger job on a failed build

Enable developers to build rollback workflows based on failure of a previous job in the build event.

Recommended Skills: javascript

Mentor(s): [Alan](https://github.com/adong), [Tiffany Kyi](https://github.com/tkyi/)

Issues: https://github.com/screwdriver-cd/screwdriver/issues/1080
