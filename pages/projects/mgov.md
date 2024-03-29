---
title: Reviving the Medicare Plan Search and Enroll Experience
metaDescription: Projects of Dan Bivins
date: 2023-01-01T00:00:00.000Z
permalink: /projects/mgov.html
# eleventyNavigation:
#   key: About
#   order: 1
---

## My role
- UX/UI Design
- Accessibility Specialist

## The Challenge

Nearly 15% of Americans are currently enrolled in Medicare and that number is expected to double over the next decade. As this group grows and more people rely on technology to help them access and enroll in government services, it is crucial that reliable and accessible access to these digital services meets their needs.

The process of shopping for and enrolling in a Medicare plan is an intimidating journey due to the importance of the beneficiary's decision which affects their health and drug coverage &mdash; but also due to the incredible amount of data about options and services that flood Medicare beneficiaries every year. Compounding this overwhelming time for millions of Americans is the fact that the legacy app used to sign up for healthcare was not easy to parse or navigate and was not even responsive. We knew this to be true from user surveys, usability testing, and meeting with customer service representatives.

![A screenshot of the legacy tool's Plan Results page](/static/img/mgov_old_plans.png)
*A screenshot of the legacy tool's Plan Results page*

Some of the **foundational issues we needed to resolve** in this rebuild were:
- Outdated: was not built to be responsive, with all types and sizes of devices in mind
- Poor UX: presented an overwhelming amount of information and cognitively overwhelmed the user and did not set up users for success with the forms they had to fill out 
- Not performant: was not built with performance, security, and reliability as a priority

At the core of our design approach, the **big questions we returned to were**:
What can we deliver as an MVP to provide the most impact in the shortest amount of time? Tangentially, what iterations over time can we deliver to continue improving based on user feedback? Continuing to resurface these allowed us to reflect on, and refine, our UX roadmap to iterate on the product.

**Overall Goal:** Improve the flow of finding and purchasing a healthcare plan by reducing friction and cognitive load for users. 

To acheive this goal we need to reconsider the IA of the flow when a user searches for plans available to them and begins to tease out the best plan for their situation.

![Six stages of the design process: Empathize, Define, Ideate, Prototype, Test, Implement.](/static/img/process.png)
*Six stages of the design process: Empathize, Define, Ideate, Prototype, Test, Implement.*

## The Work
Gathering insight from Medicare beneficiaries, customer service reps, and state-sponsored support agencies we were awash with data into how people used, signed up for, and accessed their Medicare services. Through our usability sessions during Open Enrollment we saw how people used Medicare.gov and how they struggled. With this info we explored the highest impact changes we could make to improve the tool. 

![A screenshot from a Mural board at a collaborative workshop session with stakeholders. High fidelity mockups and sticky notes are prevalent.](/static/img/mgov_collab.png)
*A screenshot from a Mural board at a collaborative workshop session with stakeholders. High fidelity mockups and sticky notes are prevalent.*

Our cross-functional team organized workshops with diverse stakeholders around balancing the user improvements, policy needs, and technical feasibility. A real key to this step of the process was listening to call center representatives. These "boots on the ground" workers were able to provide us with a wealth of information that they hear every day from users who call with a myriad of questions and issues while trying to sign up for a plan.

![A service map I created to better understand and share the touchpoints with our user base.](/static/img/service-map.jpg)
*A service map I created to better understand the touchpoints with our user base. This continued to be revised with the more we learned.*

### Our core features of focus

- **Drilling down to the drug and pharmacy search experience** From research, it was clear that drug costs are one of the most stressful and most important decision points for a beneficiary. The pharmaceutical landscape is filled with complexity and is constantly evolving due to policy changes, how a plan and pharmacy covers a drug, what tier that drug is on, and how the drug moves through the Medicare coverage phases. By reducing friction at this stage in the user flow we could ease the tension in the experience and reduce time to complete the action.
- **Reducing cognitive load during the plan search and enrollment experience** Provide just the right amount of information at the right time within the decision making process to allow users to quickly find what they need and make a decision. Some users don't want to log in at first so allow them to find 


## The Outcome
Shown below is the MVP version we delivered in time for Open Enrollment. Further iterations based on usability testing and collaborations with client stakeholders allowed the work to evolve, as it should, but this work allowed for a solid foundation to serve to the American people. 

### Pharmacy search redesign
Repeatedly in user testing our users noted that the redesign was a huge improvement in their experience and now they would gladly use medicare.gov for their healthcare search. 

#### Key design points of pharmacy search redesign
- Allow users to filter results, reducing cognitive load and making it easier to find relevant info
- Allow users to "add pharmacies" to their logged-in experince so they could receive more accurate drug pricing
- Cleaner use of heirarchy, typography, and white space to allow the content to breathe and reduce visual and cognitive load
- Display a map view for contextual setting and alternative method of viewing the data
![The redesigned pharmacy search experience.](/static/img/mgov_PharmacySelection.png)


### Plan Results redesign
The legacy app's plan results designs were honestly a low bar to improve upon. Utilizing our design system, we were able to leverage modern design patterns quickly to solve problems. 

#### Key design points of the plan results page
- Provide users with a simpler and clearer presentation of the data using improved heirarchy of typography, white space, and grouping of data. 
- Provide users with sufficient info, at this point in their search, so as not to overwhelm them yet display relevant info for their healthcare search.
- An accessible and usable mobile experience.

![The redesigned Plan Results page.](/static/img/results1.png)
![The redesigned Plan Results on desktop, showing the filters being used .](/static/img/results2.png)

![The redesigned Plan Results on mobile experience.](/static/img/results-tablet.png){.img-mobile}
*The redesigned Plan Results on mobile experience*

 

## What we accomplished

Since CMS launched the redesigned [Medicare Plan Finder](https://www.medicare.gov/plan-compare/#/?year=2022&lang=en), the tool:
- Has helped **more than 2.6 million Medicare beneficiaries** enroll in a Medicare plan, about 40% more enrollments than the legacy tool the previous year
- Saw an average of **373,000 visitors a day** during the next Medicare Open Enrollment.
- **Zero downtime** for the redesigned Medicare Plan Finder, meaning the tool ran smoothly and did not impact an individual’s ability to find and enroll in Medicare.

Most importantly, we were getting positive feedback from our users:
> “Even I, a 73-year-old guy who’s not very computer savvy can figure it out.”

> “I really like it because it’s self-explanatory and gives things in detail. You know up front what each plan costs a month, what your deductibles are, and what drugs are covered and what drugs aren’t. That’s really important."



[Next project](/projects/partner)