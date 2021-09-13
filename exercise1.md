# Exercise 11.1

## Cloud vs. Self-Hosted

A small application being developed by 6-people team would certainly be better in a cloud-based service (SaaS, or IaaS with self-installed server software), if at all possible. Even if technological aspects allow this, law and confidentiality might still prevent it in case the resources related to the project are required to be stored in a certain area or space, such as a country or even a restricted area in the development company's building. Naturally, the cost of commercial-grade CI/CD solutions might be an issue as well.


## Alternatives for Jenkins and GitHub Actions

Other CI/CD tools include the following:

* [GitLab CI](https://about.gitlab.com/)
* [TravisCI](https://travis-ci.org/)
* [CircleCI](https://circleci.com/)
* [Bitbucket](https://bitbucket.org/)
* [TeamCity](https://www.jetbrains.com/teamcity/)
* [Bamboo](https://www.atlassian.com/software/bamboo)
* [GoCD](https://www.gocd.org/)
* [Azure DevOps Server](https://azure.microsoft.com/en-us/services/devops/server/) (the old Team Foundation Server)

CruiseControl was an early option. In addition, Jenkins was earlier called Hudson and co-existed some time as its fork, but ironically—considering the history with Oracle—Hudson has moved to the heaven of CI/CD systems.


## Build tools for Java Projects

The term _building_ _(koonti)_ encompasses everything from setting up build environments and acquiring source resources to testing the produced deliverables. Thus, things such as compiling/transpiling, linking, minification, various kinds of packaging, many kinds of automated static and dynamic analyses (e.g., linting and computing quality metrics; learning, unit, integration, system, acceptance, smoke etc. testing; as well as calculating testing coverage), and reporting are all included.

Java has a large ecosystem of tools. Traditional build automation tools include Ant, Maven, and Gradle. The usual compiler for Java is javac from Java Development Kit (JDK), but other compilers exist as well. Static analysis tools include CheckStyle, FindBugs, PMD, and SonarQube, in addition to the numerous checks integrated in the usual IDEs (Eclipse, IntelliJ, etc.). JUnit and TestNG, with their plugins, integrations, and supporting tools (such as Mockito, JMock, and EasyMock), are traditional choices for test runners. Other kinds of testing tools (such as Cucumber, JBehave, Spock, FitNesse, Selenium, and Robot Framework) can be choosen based on specific needs and tastes.
