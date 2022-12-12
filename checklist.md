## DPG Repo Guidance Checklist

A social sector open-source project is slightly different than a typical open-source project. We've put together this checklist to help you prepare your GitHub repositories for contributors. Below the checklist, you'll find suggestions and ideas for each of the items.

Note that much of this checklist is covered in [this video](https://www.youtube.com/watch?v=SIhiXdy_6Zo&t=4s) if you'd prefer to watch instead of read.

* [ ] The repository has a README that explains the project's mission, impact, and story
* [ ] The repository has a Code of Conduct to create a safe and welcoming environment
* [ ] The repository has an Open Source License to explain how the software can be used, modified, and shared
* [ ] The repository has a Contributing file that explains how to contribute to the project, including technical requirements and process
* [ ] The repository has Issue templates to help contributors create new issues
* [ ] The repository has Pull Request templates to guide contributors when submitting code

Not required but nice to haves:
* [ ] The repository has set up GitHub actions to automate tasks and improve project management
* [ ] The repository has set up GitHub Sponsors to support open source development
* [ ] The repository is using project boards to organize and prioritize work
* [ ] The repository has used the DPG generator tool to create a consistent structure and setup
* [ ] The repository has information about skills-based volunteering opportunities
* [ ] The repository has information about NGO adoption of the project


#### Readme

Your project's README and description are a great opportunity to showcase the mission of your social sector project. In addition to discussing the technologies involved, we suggest highlighting your project's impact on the world and sharing a compelling story about the people your project helps. If your project spans multiple repositories, consider setting up an organizational README and pinning repositories to highlight their importance. You can learn more about organizational READMEs and pinning projects [here](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile).

#### Code of Conduct

A code of conduct is important for an open source project because it sets clear expectations for behavior and helps create a safe and welcoming environment for contributors. It can help establish ground rules for how people should interact with each other, both online and in person at events. This can be especially important for open source projects that involve a diverse community of contributors with different backgrounds, experiences, and perspectives.

Having a code of conduct can also help to prevent harassment and other harmful behavior, which can discourage people from participating in the project and hinder its growth and success. It can also help protect the reputation of the project and its contributors by showing that they are committed to creating a positive and inclusive community.

If you are having a difficult time choosing a code of conduct we recommend the [Contributor Covenant](https://www.contributor-covenant.org/).

#### Open Source License

An open source license is important because it allows people to access, modify, and distribute the source code of a software project. This helps to promote collaboration and sharing within the open source community, and allows anyone to contribute to or use the project, subject to certain conditions.

In short, an open source license helps to ensure that the project remains freely accessible and usable by anyone who is interested in it. This can help the project grow and thrive, as it enables more people to get involved and contribute their ideas and expertise.

Overall, an open source license is a key part of the open source movement, and helps to support the principles of collaboration and openness that are central to the open source community.

The Open Source Initiative has an [excellent write-up](https://opensource.org/licenses) of the various licenses as well as answers to many frequently asked questions about them.

_Note: Some people may be prohibited from contributing to open-source projects by their employers if the project lacks a Code of Conduct or an Open Source License._

#### Contributing File

A contributing document for a software project should outline the process for how to contribute to the project, as well as any technical requirements or guidelines that contributors need to follow. Some key things to include in a contributing document are:

An overview of the contribution process, including how to claim and have work assigned, and the steps for submitting code.
Technical requirements and instructions for setting up the project locally, including any external services or APIs that need to be accessed or signed up for.
System requirements, such as any specific dependencies or setup instructions for different operating systems (e.g. Mac, Windows, Linux).
Any coding standards, guidelines, or best practices that contributors should follow when writing code.
A link to the project's code of conduct, which sets expectations for behavior and helps to create a safe and welcoming environment.
A link to the project's open source license, which explains how the code can be used, modified, and distributed.
Overall, a contributing document should provide clear and concise instructions for how to contribute to the project, and should help ensure that contributions are consistent with the project's goals and standards.

#### Issue Templates

GitHub issue templates are used to simplify the process of creating new issues for a project. They provide a pre-defined structure and set of fields for contributors to fill in, which can help ensure that issues are formatted consistently and include all the necessary information.

This can be especially useful for larger or more complex projects, where it may be difficult for contributors to know exactly what information to include in an issue. By providing a template, project maintainers can help ensure that issues are well-structured and easy to understand, which can make it easier for others to contribute and help resolve the issue.

Overall, GitHub issue templates can help to streamline the process of creating and managing issues, and can make it easier for contributors to get involved and contribute to the project.

#### Pull Request Templates

GitHub pull request templates are used to simplify the process of creating and reviewing pull requests for a project. They provide a pre-defined structure and set of fields for contributors to fill in when submitting a pull request, which can help ensure that pull requests are formatted consistently and include all the necessary information.

This can be especially useful for larger or more complex projects, where it may be difficult for contributors to know exactly what information to include in a pull request. By providing a template, project maintainers can help ensure that pull requests are well-structured and easy to review, which can make it easier for others to contribute and help improve the code.

Overall, GitHub pull request templates can help to streamline the process of creating and reviewing pull requests, and can make it easier for contributors to get involved and contribute to the project.

#### GitHub Actions

GitHub Actions are a powerful tool that can be used to automate a wide range of tasks and processes within a GitHub repository. Some common uses for GitHub Actions include:

* Building, testing, and deploying code
* Running automated checks and tests
* Formatting and linting code
* Releasing and publishing new versions of the project
* Closing stale issues and pull requests
* Updating dependencies and managing dependencies

Overall, GitHub Actions can be used to automate a wide variety of tasks within a GitHub repository, and can help to improve the efficiency and reliability of the project. By using GitHub Actions, project maintainers can save time and effort, and can focus on more important tasks, such as developing new features and fixing bugs.

Some that we recommend getting start with are:
* [Close Stale Issues Action](https://github.com/marketplace/actions/close-stale-issues) - There is an emotional burden to asking people if they are still working on issues and what the status is. This allows you to offload that burden to a GitHub Action.
* [Issue Notifier](https://github.com/marketplace/actions/issues-notifier) - This action will notify maintainers when someone opens a critical issue that has a particular label.
* [Many More](https://github.com/marketplace?type=actions&query=issues+) - There are additional actions to manage pull requests, translate the language in issues, and much more.

If you'd like to develop your own actions the [GitHub Skills](https://skills.github.com/#automate-workflows-with-github-actions) site has several tutorials to get you started.

#### GitHub Sponsors

GitHub Sponsors is a program that enables people to support open source development by making financial contributions to the developers and maintainers of open source projects. Through GitHub Sponsors, users can choose to sponsor specific developers or organizations, and can make regular or one-time contributions to support their work.

GitHub Sponsors is an important program that enables people to support open source development, and can help to ensure that open source projects continue to thrive and evolve. You can find out if GitHub Sponsors are available in your region/area and learn how to sign up [here](https://docs.github.com/en/sponsors).

#### Project Boards

GitHub project boards are a tool that can be used to organize and manage the workflows and tasks within a GitHub repository. They provide a visual representation of the project, and allow users to create and assign issues and pull requests to specific columns, which can represent different stages of the development process (e.g. "To Do", "In Progress", "Review", "Done"). They also provide visibility into the project and its progress, and can make it easier for project maintainers and contributors to track and manage the work that needs to be done.

In addition, project boards can be used to organize and prioritize tasks, and can help to ensure that important issues and pull requests are addressed in a timely manner. They can also be used to collaborate with other contributors and stakeholders, and to discuss and review the work that is being done.

By using project boards, project maintainers and contributors can work more efficiently and effectively, and can help to ensure that the project remains on track and meets its goals.

Consider adding a project board to your project, check out a quickstart guide [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects).

#### Use the DPG Generator Tool

This tool provides "at a glance" information for contributors and potential contributors of your project. It gives contributors a sense of how active and what the community around your project is. You can use the tool [here](https://socialimpact.github.com/tech-for-social-good/hacktoberfest2022#generator) to generate this information for your project.

You can see the results of a project who has used the tool [here](https://github.com/rubyforgood/human-essentials#-the-digital-public-goods-alliance-recognizes-human-essentials-as-a-digital-public-good-dpg).

#### Skills-Based Volunteering Information

Consider adding instructions for companies that are interested in having their devs participate in skills-based volunteering. Many large companies like GitHub, Intel, Google, and others offer their employees time to volunteer. A Skills Based Volunteering document provides information on how a larger team could engage with your project. See an example [here](https://github.com/rubyforgood/human-essentials/blob/main/sbv.md).

#### NGO Adoption Information

To make it easy for NGOs to adopt and begin using your software, or to tell them how the project can be customized to solve their problems, you should consider creating an NGO document. Here is an [example](https://github.com/rubyforgood/human-essentials/blob/main/ngo.md) of how one DPG is doing it.
