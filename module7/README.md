# Open Source Project Creation Overview

## Lesson: Introduction

### Section Overview

In this section, we’ll look at the rationale and value proposition for creating new open source projects.  We’ll spend time discussing good and bad reasons to create new open source projects, as well as how to evaluate the business potential of a new project.

### Learning Objectives

By the end of this section, you should be able to:

*   Describe the value proposition for open sourcing internal code or creating new open source projects from scratch
*   Give some good and bad examples of reasons to open source code
*   Explain how to evaluate the business potential of a new open source project

## Lesson: Where To Begin? 

### Ask The Right Questions

It’s important to ask the right questions before you begin the journey of creating a new open source project.  While there may be some additional specific questions you should consider depending on your company’s unique situation, the following picture will give you a great start to help you figure out what to ask.

![Questions to Ask Before Open Sourcing Project](questions-to-ask.png)

The top line of this graphic really deals with the question of understanding what the value proposition is for you to create an open source project.  The first question is one that, unfortunately, doesn’t get asked often enough - you should seriously evaluate whether or not you need to create another open source project.  There are many thousands of projects in existence - will your code provide differentiated value on its own, or would you be better off making an established and successful open source project even better?

If your organization understands the open source development model (covered in previous sections of this course series) and is committed to building a project with that structure, you’ll still need to evaluate **before** deciding to launch the project what constitutes success and what metrics you’ll use.  Just creating a project for the purposes of public relations or to improve internal metrics for the number of open source projects started will usually result in an unsuccessful project.

The second row of questions focuses more on the ability of your organization and the community to build value in the new open source project.  Too many companies have tried (and failed) with the strategy of simply throwing code over their firewall, without internal financial and engineering investment, and hoping that their corporate reputation will attract outside enterprise participation.

Take the time to consider how to make your potential new open source project successful.  It’s ok if you come to the conclusion that creating an open source project isn’t right for a particular piece of code - there are many opportunities to participate in the open source ecosystem or contribute your technology to other open source projects.

### What Should You Open Source?

Just as in the decision you must make on what to contribute back to an upstream open source community (from previous coursework in this series), the decision on what code or technology you’ll build initially in the open, or what proprietary code you’ll release is an important one.  Here are some criteria that can help you consider this choice.

*   Determine what parts of your product are sources of strategic advantage, and what simply supports those parts
*   Non-strategic parts are often great candidates for creating open source projects
    *   Chances are good that other companies feel the same way, and might help you maintain and advance your new project.

Examples:

*   A filesystem or file format widely used in the industry
*   The network stack for connected IoT devices

Another place to start includes secondary coding projects where an enterprise does not need to be an authority, and where there may be a larger group of technologists around the world who can help you solve a problem. If it is not mission-critical code, then it is likely a good candidate to be open sourced. However, it should also be code that your company is still actively using and maintaining. Commercial dependencies on code enable a continuous feedback loop of bug fixes, patches and new features.


### When To Create an Open Source Project

The decision to release or create a new open source project depends on your circumstances. Your company should first achieve a certain level of open source mastery by using open source software and contributing to existing projects (as we covered in previous coursework in this series). 

Understanding how to consume open source can teach you how to leverage external projects and developers to build your products. Participation can bring more fluency in the conventions and culture of open source communities. But once you have achieved open source fluency, the best time to start launching your own open source projects is simply “early” and “often.”

![Release Early Release Often](release-early.png)

This graphic is a bit of a reminder about what we covered in the _Open Source Development Practices_ portion of this coursework series.  It’s not only important when you’re contributing back to open source, it’s important as you consider your first new open source projects.

Not everything has to be absolutely perfect before you create your first open source project.  There are some minimums in terms of process, legal review, etc. (which we’ll cover shortly), but building out the minimum necessary in both code and governance to get started allows you to get earlier participation and earlier feedback to help you evolve your new project.

Before you create that first project though, we should discuss some good (and bad) reasons for creating an open source project...

### Good Reasons to Create an Open Source Project

![Good Reasons to Create an Open Source Projects](good-reasons-to-opensource.png)

This graphic shows five good reasons why you should start an open source project.  While they all come back to business goals, the first two deal with getting a unique business advantage in the market.  It’s important to note, however, that this ‘first-mover’ business advantage can be fleeting (6-10 months) until the rest of the community becomes proficient with the technology you’ve open sourced.

The third and fourth items focus on engaging customers and helping build value for your non open-source products.  Remember that in open sourcing code you provide value on top of, you’re making your products better as a result.

Finally, if you are in an industry with technical customers (or developers) who have the ability to self-support themselves with your technology, you can realize value in not having to provide extra technical or support resources for the code you choose to open source.

### Bad Reasons to Create an Open Source Project

Just as important as open sourcing for the right reasons is making sure you don’t try to create an open source project for the **wrong** reasons.  The open source ecosystem is littered with failed projects from organizations that meant well, but simply didn’t consider fully why they should be open sourcing code or creating a new project.

![Bad Reasons to Create Open Source Projects](bad-reasons-to-create-opensource.png)

Hopefully it’s obvious why all of these are bad reasons to create an open source project, but let’s look at what they all have in common - an inward focus and/or expectation of support from the larger open source community.

Working in open source has often been described (from the corporate point of view) as ‘enlightened self-interest.’  It’s apropos in this case because everyone understands that corporations don’t work with open source necessarily for altruistic reasons - there has to be business value aligned with what goes on in open source.  However, the reasons shown above sow a seed of mistrust with the rest of the open source community, which is, after all, composed of both partners and competitors.

### Evaluating the Business Potential of an Open Source Project

Just like any business decision, determining what, if, and when you should create an open source project comes back to what value is ultimately delivered to the business. As you consider these questions, it’s best to think in terms of building a business case.

First, you must decide if your company wants to create or release the code while maintaining ownership of it and the project, or if you want to donate the code to others to maintain and administer the project. If the code already exists, then there is the related issue of whether you will release all the code in a project or just some of it as an open source project.

To make these decisions, consider stepping back to determine the objectives you have in mind for the code.  Is this code something that will be useful outside of your organization and also transformative to the industry?  Is your company likely to attract partners (and/or competitors) to work on this technology in support of your organization’s product portfolio?

For example, you might want to attract fresh insights from other developers on a part of an application that isn’t core to your work. Or you might seek additional real-life algorithms to detect logs in a system monitoring application. Rather than releasing the whole product as open source, you could release only the code related to the algorithms. This allows you to gain the contributions of others and help others who are needing similar help, without compromising your core business.

Starting a project and maintaining overall control lets you have oversight and gives you the ability to help shape it into what you need, while still giving freedom and control to the contributing developers to do their work.

# Section: New Project Preparations

## Lesson: Introduction

### Section Overview

In this section, we will explore how to prepare for creating a new open source project, including discussion of legal, business and community considerations.  We’ll also discuss required processes, tools and staffing requirements necessary for success.

### Learning Objectives

By the end of this section, you should be able to:
*   Explain the overall steps for preparing to create a new open source project
*   Understand what processes, considerations, tools and requirements are needed for success in project creation

### Lesson: Internal Preparations

### Identify an Executive Sponsor

Since there will be a lot of required investment to create a successful open source project, it’s **critical** to get the buy in of an executive sponsor in your organization.  It can help if you have more than one sponsor, but at a minimum, you should aim for someone who can provide and commit to the following things:

#### Technical and Community

*   Continually reaffirm commitment to the project in public
*   Foster a culture of merit-based recognition
*   Ensure neutrality
*   Commit to following open source methods and processes

#### Financial

*   Internally: Fund enough development to get project going
*   Externally: Commit to funding IT resources and sysadmins

### Allocate Resources

You’ll need to get your executive sponsor to appropriately allocate funds, as noted in the previous page, but also be able to direct appropriate staff time to make the project successful. Developer time will likely be similar initially to the amount of time they spend on internal code efforts. However, you’ll also need to consider what time, materials or help your developers will need to provide to help others in the new community get up to speed on the codebase. 

There will also be resources needed for the legal team that will be involved in creating an open source project that could involve competitors, as well as marketing investments to ensure that the project gains support and contributors after launch.

You’ll also have to set budgets for the infrastructure used to begin and maintain the project. This includes a project hosting and source control website like GitHub, where the code will reside and be maintained, as well as bug resolution, and other needed tools.

We’ll cover tools and infrastructure in more detail shortly.

### Educate Your Workforce

Even if your organization has taken training on open source topics (such as this course series), it’s important to remind engineering teams and managers of particular items that may differ from how they normally approach building products or evaluating work.

#### For Engineers

*   Review open source development methods and processes
*   Review your company's open source policies and compliance rules
*   Integrate open source software within your software development model
*   Follow open source best practices internally if possible
*   Practice and encourage community thinking to help craft more general solutions

#### For Managers

*   Traditional performance metrics may no longer apply
    *   Only results count, not whose code is used
    *   Influencing an outcome is just as valid a solution as writing code
*   Manage your developers, not their maintainers
    *   You can’t control the open source process
*   There is a learning curve for your employees and the community
*   Building influence and respect takes time (even if it’s your company’s project)


### Lesson: Reviews

### Overview

While some audiences don’t necessarily appreciate lengthy reviews before launching efforts such as a new open source project, it’s important to take some time to properly plan for reviews from the legal team, the engineering team and also the marketing team.

These don’t necessarily have to be painful, as a simple set of checklists to verify that the most often missed elements don’t slip through the cracks can be helpful.  Taking this time at the start of the process of creating a new open source project can save a lot of headaches once a project is out and gaining visibility.

We’ll cover some best practices in the following sections for how to streamline these review processes.

### Legal Review

One of the worst things that can happen to a new project is for the community to have distrust in the legal cleanliness of a codebase. It’s important to ensure the code you release has clear licensing and provenance. A full legal review is often helpful in making sure what gets contributed will be acceptable by others in the community.

Your legal review should also include trademark due diligence and registration. Note that if you are contributing the project into a foundation (more on this later in the governance section), make sure you’re aligned on the trademark strategy before open sourcing your codebase. 

You’ll also need to choose a license for your project. It’s important to document any licensing or intellectual property requirements. Projects will typically need to consider both the outbound license (e.g., the license under which downstream users receive the code) and the inbound contribution mechanism (e.g., the process under which contributions are made into the project). Many projects will use the [Developer’s Certificate of Origin](https://developercertificate.org/) (DCO) sign-off process for their inbound contribution mechanism. If you anticipate needing explicit corporate commitments for patent grants, or the ability to relicense the project later, you may want to look at some of the more common Contributor License Agreements (commonly referred to as CLAs). Not all CLAs are alike, so consider this option carefully. Also be aware that CLAs can be an impediment to participation as developers often have to go through arduous approval processes to get them signed. Refer to the _Open Source Compliance Program_s module of this training series for more detailed information on licensing options.

Your project may also produce deliverables that are not software. If your project is producing documentation, discuss whether you should use a specific license for the documentation. For example, many open source projects will use an open source license for the software and a Creative Commons license for the documentation. Additionally, some projects seek to create specifications that may be implemented in various ways by others. Those projects should consider the option to use a specification license. 

Each licensing approach has its advantages and disadvantages, but be aware of the potential for fragmenting your project, which is a particular problem for software that needs to be interoperable or provide portability across various vendor solutions. Often this issue is addressed by creating conformance programs that permit usage of the project trademark if the commercial solutions pass a community created test or set of requirements. Thinking about this up front will help inform your legal review and plans for the project.

In summary, the steps in the legal review process include:

*   Consider the impact of open sourcing on your company’s intellectual property
*   Ensure full compliance with open source licenses
*   Select an open source license for the source code to be released, document all licensing requirements very clearly in your project
*   Decide if you need a contributor agreement
*   Consider the possible non-software outputs from the community and the appropriate licenses, such as documentation and specifications
*   Decide on any trademark related considerations
*   Decide whether there are additional factors to build into your plans for an ecosystem, such as conformance testing

### Technical Review

The technical review verifies that the source code can function without dependencies on other internal code or development practices (including any custom internal build systems), and that it does not include third-party code the company cannot include in the open source release.

The technical review should include verification of all license and copyright notices, and any private or internal code comments should be scrubbed. Steps include:

*   Remove critical dependencies on non-public components
*   Provide documentation and use case examples
*   Remove internal comments, references to other internal code, etc.
*   Ensure coding style is consistent
*   Update copyright notices in source code files
*   Add license notice in source code files
*   Ensure the code compiles and builds on any external target platforms
*   Add license text as a file in the root directory

### Marketing Review

Successful open source projects can’t live strictly on the merits of the code and technology alone - to keep the project moving along, there are a series of additional business and marketing steps that need attention as well. They include promoting the project, laying out a successful operational strategy, providing a realistic budget and project branding, as well as establishing lively social media accounts and useful domain names to bolster long-term success.

A marketing review establishes guidelines for branding. This is particularly important, as it helps to ensure a consistent message in the market. Steps in the marketing review include:

*   Design a project logo, color scheme, website, collateral, etc.
*   Formalize branding guidelines
*   Register social media accounts for the project (Twitter, Facebook, LinkedIn, etc.)
*   Register domain names for the project

By performing this marketing review ahead of the project launch, you can deal with any potential branding issues (like domain names not being available for your preferred name) before they threaten to derail the success of your project.  Make sure that you engage your marketing team early on so that they can help you navigate these (and other) issues.  

You’ll probably find that your marketing team will be excited, because it’s a fun challenge to see how many people you can drive to the project to contribute code, participate in forums, offer bug fixes and report issues.

### Lesson: Governance and Processes

### Governance Models

It’s important to consider what the governance model will be for your new open source project.  But what do we mean by governance? Quite simply, governance is the structure around a project that enables decisions on:

*   Participation guidelines and requirements
*   Architectural changes
*   Nominating maintainers
*   Final arbiter on disputes
*   Suspension of participants

There are several ways that projects can be governed, with varying degrees of business and/or technical leadership.  We’ll cover leadership in a moment, but if you want more details on the different types of governance models, please refer to the "Collaborating Effectively with Open Source Projects" course in this training series.

### Leadership

Setting leadership roles is also important before getting underway. That can mean different things for different projects. If you are starting a multi-company project with several enterprise participants, the project may need more formal governance, such as a governing board or other management group. 

Other arrangements could simply require a technical committee that oversees all facets of the open source project from a technical perspective. The composition of the committee would include mostly technical leadership, as well as a liaison back to the executive team to provide updates about progress and project needs. The legal team can then be brought in as the technical members and executives see fit.

Your top architectural minds will also certainly be there, as well as others who know how the code base will work. Altogether, the members of the committee will have a vision for where the project is going as well as support from within the developer community. Those are the people you want there at the table to plan the process.

### Foundation or Independent

Another question that often comes up as new open source projects are created is whether to donate your code to a vendor-neutral, non-profit organization or retain some control by owning and running your own project. The answer depends on what you are trying to achieve - if you are working with a small number of partners on building a nascent technology for the industry, you probably don’t need to consider a non-profit foundation at the beginning.  

However, if what you are planning has wide applicability across your industry, is cross-industry, or has grown from a small effort into something large and complex, it’s often good to consider a non-profit open source/open standards consortium to host your project.  Besides the value of having a truly vendor-neutral place to host your project, these foundations have legal, governance, marketing and project infrastructure services that can dramatically streamline the process of getting your project on the path to success.

There are many foundations (and sub-foundations) you can choose from, and each offers unique value propositions, pricing and service levels.  Some examples of these foundations are:

*   [Apache Foundation](https://www.apache.org/foundation/)
*   [Eclipse Foundation](https://www.eclipse.org/org/foundation/)
*   [Linux Foundation](https://www.linuxfoundation.org/)
*   [OASIS Open](https://www.oasis-open.org/)

Which foundation you choose depends on what area of speciality your project resides in, as well as considerations like cost, governance models, etc.

### Technical Processes

Prior to launch it is often helpful to create a standard release process to schedule regular releases of the code as changes and improvements are made by the project maintainers. A schedule should be set up with well-defined and visible details for the development community and the business side of the project. 

How often those releases should be made depends on your community’s expectations. If the project is enterprise-focused and you’re trying to build something that is very hardened, your release schedule might be twice a year. If the project is smaller in scope and more agile and you are trying to get pieces of it out there, perhaps you might be releasing the code monthly or weekly. The key to the schedule is that the community must dictate the timeline and understand its ability to support the project from a velocity standpoint, while giving users what they need and expect. If the community provides feedback that the releases are coming too soon or too slowly, then you need to look at the process and make some adjustments. The big thing here is consistency, predictability, and visibility.

You should also have well defined processes for submitting code, patches, feature ideas, documentation, or other project artifacts.  Some of this can be dealt with in the project infrastructure/tooling (a topic we’ll cover shortly), but part of the technical process is not just the tools, but the expectations of workflow - e.g. - how will code be submitted, what kinds of coding standards will be followed, when will new code be accepted in the release cycle, etc.

### Lesson: Project Infrastructure

### Development Tools

Before the launch of your project can ever happen, you need to prepare a repository for the project. This is essentially the infrastructure for a code repository where the project will be available to contributors all the time. Many projects use the well-known [GitHub](https://github.com/) or [GitLab](https://about.gitlab.com/) repositories, or host their own repositories with tools such as [Gerrit](https://www.gerritcodereview.com/). 

There are many other options available as well, but remember it’s often useful to consider making it simple for developers to participate and engage in your project. Choosing a tooling platform that is familiar to the greatest number of developers will help accelerate contributions and growth in your project.

Bug, issue, and feature tracking also should be included as part of a project’s infrastructure plans. You want to provide an easy place for contributors to make reports of problems that need to be fixed as well as requests for new features that might be useful added. Then there are automated build and test system processes which may need to be included as part of your project’s GitHub repository to keep your systems and project flowing smoothly, while scanning and checking the code to ensure its quality.  

You can get more detailed information on things like automated testing and continuous integration by reviewing the _Open Source Development Practices_ module in this course series.

### Website

A critical step is creating a company-neutral web presence for the project. Don’t try to place the open source project website as a subdomain of a company web page - even if you have the best intentions, the visual distinction of a neutral home of the project is important. The webpage provides a place for the community to find information about the project including documentation, links to download the code, and more. The webpage can also provide details about the project’s leadership, scope, users and contributors, budget, governance, and other details.  As a central information repository, your website should also have very clear calls to action/places for new developers to join the community.

### Communication Tooling

Offering communication channels for your community to ask questions for help is critical. You’ll want to find tools that can be integrated into the entire development workflow (for example, receiving notifications for support requests, code check-ins, error logs, and other tasks). You’ll also want to provide critical discussion forums and a mechanism for community members to get quick answers from others who are also working on a project. All are important means of communication that help move projects forward in real-time.

One project tool to consider is [Slack](https://slack.com/) , an online team project management and communications platform where users can access and share messages and files, organize workflows, perform searches for information, and more. However, Slack is a proprietary tool and can cost money to maintain beyond a certain usage threshold. There are open source options out there such as IRC, [Gitter.im](https://gitter.im/), [Mattermost](https://mattermost.com/), [Rocketchat](https://rocket.chat/) and others. 

Depending on your developer and user community, you may also need modern forum tooling. [Discourse](https://www.discourse.org/) is a great option that is fully open source and also provides optional hosting. When choosing a communication system, be mindful about any form of lock-in, financial costs, and how easy it is to migrate to a new system in the future. 

As your community grows, you need to be able to adapt to any new communication channels out there. Make sure you involve your community in tooling decisions as your project evolves - you may find that users and developers naturally gravitate to other tools over time if they find them useful.

### Documentation Tooling

Some form of document management is often useful for open source projects, especially if it makes the process of creating documentation, how-tos and other text-based projects easier.   While many projects feel comfortable using the built-in markdown text tool features of GitHub or GitLab, other projects prefer using wikis or other shared-editing software. 

For a list of potential Wiki tooling options, you can check (not surprisingly), [Wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software).  The same caveats that apply to communications tools also apply here - consider how you can avoid any kind of data or tool lock-in so that when (not if) you users and developers decide to migrate to a different platform, you can migrate your hard-won documentation, Frequently Asked Questions lists and how-to content.

# Section: Successful Project Launch And Sustainment

## Lesson: Introduction

### Section Overview

In this section, we’ll discuss the final steps required for successful open source project launches, as well as present some additional information on how to sustain and encourage adoption and contribution to the project.

### Learning Objectives

By the end of this section, you should be able to:

*   Describe the last steps required to successfully launch an open source project.
*   Explain how to build strong community processes that allow for increased project adoption and a strong contribution pipeline.


## Lesson: Project Launch

### Final Code Review

At this point in the process, it’s always a good idea to take one final pass through the source code in preparation for launching.  If you’ve been following the process outlined earlier, this shouldn’t be a big burden, but it can be very helpful to make sure that no easy-to-fix items haven’t been forgotten.

Specifically, the goal of this final review should be to ensure that all requirements identified by the legal, technical, and marketing reviews are completely met.  Some examples of what to look for are:

*   License, attribution, and copyright texts are all complete and in place
*   Source code scanner reports clean bill of materials
*   Every line of code is licensed appropriately for release
*   Comments are sanitized of casual or unrelated language
*   Source code does not inadvertently reveal internal projects
*   Source code is sufficiently complete that it will build
*   Source code builds using publicly available tools
*   File and function names reflect the project’s name, if it has changed
*   MAINTAINERS file is up to date, if used

### Pre-Launch

Before you go live officially with your new project, there are some things you can do to ensure the best launch experience for your organization and for the community at large. One of the biggest things you can do to ensure success is making sure that you have critical mass before launching.  

You should have identified which partners and customers are going to be there with you when you announce the new project.  They should have had preview access to the repositories so that they can be familiar with the code and ready to contribute (or have already been contributing).

If this is one of your early open source projects, it also doesn’t hurt to have a quick refresher with your own developers to make sure they are following open source development methods and processes in anticipation of interacting with others in the open source community that will be contributing to your project.

After you have verified that all of your project infrastructure is up and running, make sure that your internal developers have joined the project’s communication tools and are beginning to monitor for questions or new contributions.  

Now it’s time for the big moment!  You can upload any final remaining code and flip the switch to make the project live to the world.

### Good Open Source Citizenship

Now that your project has launched, it’s just the beginning of the work ahead.  You’ll need to make sure that your organization continues to be a good open source citizen and operates in a way that encourages others to come alongside you and work together on your project.  Here are some ways you can do that:

*   Have conversations and make decisions in the open
    *   This builds goodwill, and reduces overhead in documenting decisions
    *   This streamlines onboarding process for new participants
    *   Having open archives ensure continuity when participants change
*   Listen to the community
    *   Their experience is invaluable, especially in integration and testing
    *   Encourage generalized implementations that extend what you need
*   Allocate resources as though you will be the only company doing the work
    *   Set goals, and make sure they have resources to get accomplished
    *   This builds momentum until the leveraged development model takes effect

Being a good open source citizen takes work, and it’s not altruistic - it’s good business practice for your organization to get the best return on the investment you’ve put into launching your open source project.

## Lesson: Project Maintenance

### Build the Community

After the project has launched, it is essential to monitor the vitality of the external developer and user community. Community building does not happen automatically. In the early stages of the project, it may be necessary to host developer events or sponsor meetups at major conferences to build momentum. It’s also extremely important to manage expectations and fulfill obligations for project governance and transparency.

Ongoing activities include:

*   Ensure any changes to direction or governance are clearly communicated
*   Follow best practices of other similar communities
*   Encourage and provide opportunities for face-to-face community building
*   Identify appropriate events and have the community submit talks
*   Consider doing local meetups

By building up a diverse group of contributors, you can later decide to move your project to the next level by having discussions with other enterprises and organizations that see the work as valuable to determine if they are interested in investing their time, money and other resources to expand your initial efforts. By gaining input and resources from others, the project can be expanded and grown to do more for additional contributors.

Such growth means that additional businesses may want to contribute more money to bring their own developers in to join the efforts and help move the work forward by putting their weight behind the efforts you’ve begun. That may involve $10,000 or $250,0000 or more, depending on the importance of the project and what it means to other companies. Once your project begins, other companies can come in to contribute funding toward the work if it will aid their missions.

This happens regularly today, as enterprises and organizations realize that the technology problems they are trying to solve are larger than any of them individually. That’s when they can begin to see strategic value in joining together with other companies in vendor-neutral joint projects that are working for the greater good in solving technical problems faced by businesses.

### Designate a Community Advocate

One of the most important roles you can hire for to help a new open source project succeed is a community advocate (also sometimes called a community manager).  This person’s role is to do whatever is needed to make the community successful.  

It’s a challenging role to execute, and can be a challenging role to hire for, because the person needs a wide variety of skills, including marketing, developer advocacy, business development, crisis management, peacemaker, etc.  A good place to start looking for someone for this role is to consider internal development or marketing resources in your organization.  Also, don’t ignore people like technical writers, program managers, or even non-traditional fields of study like sociology, psychology, etc.  

A good community advocate can be the difference between a technically successful project that no one uses, and a reasonably good technical project that grows by leaps and bounds because of the community building and bridging skills deployed.  The Linux Foundation [TODO Group](https://todogroup.org/) is a good place to find help in identifying community management resources.

### Evaluate and Adapt

As with any new project effort, you’ll need to evaluate frequently and be ready to adapt your approach if you aren’t seeing the kind of adoption and contribution you were expecting.  It’s important to remember that your organization’s reputation is only part of the equation in the success or failure of a new open source project.

Remaining flexible and agile when the community provides feedback gives you the opportunity to increase the project’s reputation as a good place to collaborate and be listened to.  You should be looking at a few key metrics as your project gets off the ground:

*   Number of code commits/pull requests from outside your initial developer base
*   Amount of discussion/topics on whatever communications channels you’ve deployed
*   Number of bug reports or feature requests submitted

It’s also important to remember that even negative feedback means that your community is engaging with your project.  By practicing transparency and accountability and trying to fairly address concerns, your project will gain a positive reputation.

Remember the adage that has been repeated throughout this training course series - ‘Release Early, Release Often.’  Your new project doesn’t have to be perfect on day one, but by keeping this adage in mind, you’ll be well on your way to building a successful and robust open source effort.
