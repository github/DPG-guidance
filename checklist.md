### DPG Repo Guidance Checklist

A social sector open source project is slightly different than a typical open source project. To help you prepare your GitHub repositories for contributors we've put together a checklist of items to think about when doing so. Below the checklist we've also included suggestions and ideas for each of the items. 

Note that much of this checklist is covered in [this video](https://www.youtube.com/watch?v=SIhiXdy_6Zo&t=4s) if you'd prefer to watch than read.

- [ ] Repository has a README
- [ ] Repository has a Code of Conduct
- [ ] Repository has an Open Source License
- [ ] Repository has a Contributing file
- [ ] Repository has Issue templates
- [ ] Repository has Pull Request Templates

Not required but nice to haves:
- [ ] Repository has set up GitHub actions
- [ ] Repository has set up GitHub Sponsors
- [ ] Repository is using project boards
- [ ] Repository has used the DPG generator tool
- [ ] Repository has skills based volunteering information
- [ ] Repository has NGO adoption information


#### Readme

Your project's README and description are a great place to hook people into the mission of your social sector project. While it is a good idea to talk about the technologies involved we suggest that this is your opportunity to focus on your project's mission, how your project is impacting the world, as well as telling a good story about who it helps.

If your project spans multiple repositories we recommend setting up an organizational readme as well as pinning repositories you'd like to highlight. You can read more information about organizational READMEs and pinning projects [here](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile).

#### Code of Conduct

This is needed to create a safe space and welcoming environment for your project. If you are having a difficult time choosing a code of conduct we recommend the [Contributor Covenant](https://www.contributor-covenant.org).

#### Open Source License

An open source license lets people know how the software can be used, modified, and shared with others. The Open Source Initiative has an [excellent write up](https://opensource.org/licenses) of the various licenses as well as answers to many frequently asked questions about them.

##### Note: Some people may be prohibited from contributing to open source projects by their employers if they lack a Code of Conduct or an Open Source License.

#### Contributing File

A contributing file should explain the process of how to contribute to your project as well as any technical requirements that may block someone from contributing. Your contributing file should answer:
* How does someone claim and have work assigned to them?
* What the process for submitting code? Do they fork and submit that fork? Do they request to be a member and submit at PR? Something else?
* How to run the project locally.
* External services or apis the contributor needs to access/sign up for in order to contribute.
* System requirements -- are there any gotchas to contributing on a Mac? Windows? Linux?

#### Issue Templates

These simply the creation of issues for your contributors. Issues are also a fantastic time to connect your contributors to the mission of your organization by letting them know how the issue they will be working on is going to be making someone's life better. This is a unique opportunity for social sector organizations that other open source projects don't have to connect contributors to your mission. We recommend that your issues let people know the following:
* A summary of what the problem is and what needs to be solved. Ideally including information on how it will help end users.
* Any specific technical or process requirements that will aid in solving the issue.
* Clear and unambiguous acceptance criteria for the issue so the contributor will know what is needed to solve the problem.

#### Pull Request Templates

Your projects pull request template should outline and provide sections for contributors to fill in the when submitting their pull request. For example, if you require screenshots with your PR, include a screen shot section. 


#### GitHub Actions

There are a lot of great actions for making the management of your project easier. Some that we recommend are:
- [Close Stale Issues Action](https://github.com/marketplace/actions/close-stale-issues) - There is an emotional burden to asking people if they are still working on issues and what the status is. This allows you to offload that burden to a GitHub Action.
- [Issue Notifier](https://github.com/marketplace/actions/issues-notifier) - This action will notify maintainers when someone opens a critical issue that has a particular label.
- [Many More](https://github.com/marketplace?type=actions&query=issues+) - There are additional actions to manage pull requests, translate the language in issues, and much more.

#### GitHub Sponsors

If sponsors is available in your region/area you should consider signing up. You can find out more information [here](https://docs.github.com/en/sponsors).

#### Project Boards

Project boards are a great way for contributors to see how issues link together, the larger chunks of work, and where a project is going. Consider adding a project board to your project, check out a quickstart guide [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects).

#### Use the DPG Generator Tool

This tool provides at a glance information for your project. It is useful for contributors as it gives them a sense of how active and what the community around your project is. You can use the tool [here](https://socialimpact.github.com/tech-for-social-good/hacktoberfest2022#generator).

You can see the results of a project who has used the tool [here](https://github.com/rubyforgood/human-essentials#-the-digital-public-goods-alliance-recognizes-human-essentials-as-a-digital-public-good-dpg).

#### Skills Based Volunteering Information

Consider adding instructions for companies that are interested in doing skills based volunteering. Many large companies like GitHub, Intel, Google, and others offer their employees time to volunteer. This document provides information for how a larger team could engage with your project. See an example [here](https://github.com/rubyforgood/human-essentials/blob/main/sbv.md).

#### NGO Adoption Information

To make it easy for NGOs to adopt and being using your software, or to tell them how they can customized to solve their own problems, you should consider creating an NGO document. This is an example [here](https://github.com/rubyforgood/human-essentials/blob/main/ngo.md) of how one DPG is doing it. 
