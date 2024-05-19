---
title: Building an a11y process and practice
metaDescription: A11y process of Dan Bivins
date: 2023-01-01T00:00:00.000Z
permalink: /projects/a11y-process.html
# eleventyNavigation:
#   key: A11y Process
#   order: 3
---


## My role
- Accessibility Specialist

## Background
This project has the client's name and other identifiers removed in accordance with an NDA. The purpose of this case study is to show the types of accessibility (a11y) work I do.

## Building an a11y process and practice

In the large cross-role teams that I work with it is most common for teams to have a lack of process and foundational education. This tends to exhibit itself in these ways: 
- Product: has little understanding of how a11y fits into delivery and how their role should be involved. This leads to no understanding of how to advocate for a11y to stakeholders.
Engineering: inconsistent, or absence of, guidance on testing and “definition done” which creates uncertainty and poor quality work.
- UX: no process of a11y annotations and handoff to engineering which causes churn, tech debt, and poor user experience.

**The final, and very real, outcome is that these teams were short-changing the people who use their products.**

### Educating and collaborating with Product
Designers, engineers, and product folks all tend to benefit from further education on how to build products more inclusively. Product specifically usually needs a little more guidance on how accessibility fits into their role. Starting here, providing a foundation for Product about:
- making sure to plan for accessibility review of designs and code during sprint and program increment planning sessions
- ensure that engineering tickets have a clear definition of done regarding a11y
- how to talk to stakeholders about prioritizing a11y tickets against competing priorities

![Product Leads getting excited about connecting their day to day work to accessibility](/static/img/prod-1.jpg)
*Product Leads getting excited about connecting their day to day work to accessibility*

#### Issue-tracking dashboards per team
Providing simple and clear reporting to our teams and stakeholders is another key win. Being able to provide Product teams with relevant dashboards that display the state of a11y health at a glance. This is also a useful tool in talking to stakeholders about prioritization.

![Product Leads getting excited about connecting their day to day work to accessibility](/static/img/prod-2.jpg)
*Product Leads getting excited about connecting their day to day work to accessibility*

#### Educate and provide guidance for consistency
Understanding where "a11y fits within delivery" has been a key point for all roles, but especially Product-led teams. Below is a screenshot of a visual flow I put together to help teams understand where points of contact are within the formal a11y process.

![Product Leads getting excited about connecting their day to day work to accessibility](/static/img/prod-3.jpg)

### Provide guidance and clarity to Engineering
Most engineers I've worked with want to build and test for a11y before submitting a pull request but they are unsure exactly how to test and what criteria they should test against.

#### Scaling with the design system
Utilizing design systems to scale a11y across multiple teams and organizations is a no-brainer. Your knowledge and effort is now exponentially useful. 

I wrote testing guidance so teams would know how to test their component implementations. This guidance also helps to provide ticket acceptance criteria. 

![Guidance for testing interactions with a keyboard and screen reader](/static/img/eng-2.jpg)

#### Definition of done
To provide the clarity of what constitutes complete, I wrote this definition of done documentation to improve quality and consistency in delivery. This benefits our work by:
- Decreasing “low-hanging fruit” errors in development.
- Providing Product and Engineering and understanding of general testing criteria we use.

![A screenshot of documentation laying out a Definition of done checklist around automated testing, content reflow, semantic HTML structure, etc.](/static/img/eng-3.jpg)

#### Putting testing in its place
As I mentioned above, engineers usually want to know they've adequately tested prior to submitting a PR. They just need guidance on how to set up that testing and what criteria to test against. 

![Conversation in Slack from an engineer who is excited about the manual testing they got off the ground.](/static/img/eng-5.jpg)

#### Provide guidance on how to fix
Don’t only report what’s wrong. Provide suggestions of how to remedy. Using code snippets, Codepen tests, and references I provide a path forward for Engineers. 

![Shoutouts in Slack from teammates thanking Dan for clear remediation guidance and code examples](/static/img/eng-4.jpg)

### Pairing up with and supporting UX
Shifting conversations about a11y as early as possible within the delivery process is key. Getting UX'ers to consider, in the conceptual design and early mockup phase, how their decisions affect those who use assistive tech is always a huge win. This guarantees less bugs once designs are in code and in production. 

Below shows typical a11y annotation notes featuring considerations for the user experience of assistive tech users.

![A screenshot of a mockup with HTML annotation notes](/static/img/ux-ann2a.jpg)
![A screenshot of a mockup with screen reader UX annotation notes](/static/img/ux-ann2b.jpg)
![A screenshot of a mockup with focus order annotation notes](/static/img/ux-ann2c.jpg)

Of all the steps mentioned here, in my experience this step is one of the more time-intensive. Designers tend not to have much understanding of how their designs translate to code so this is a great opportunity to teach them about the basics of HTML like the importance of proper use of headings, lists, links vs. buttons, etc. After walking them through how to put together these annotations, I've found that designers get excited when they begin making these connections and are usually off to running on their own in no time. 

These annotations benefit teams in these ways:
- UX can now hand off designs with concrete guidelines, removing guesswork about interactions from engineers
- It provides criteria for UX, Product, and QA to test against 
- As mentioned above, it is an educational opportunity for designers

## Wrapping up

One of the primary responsibilities of an Accessibility Specialist is to **decentralize accessibility**. 
- Encourage teams to take ownership of the quality of their work.
- Scale a11y literacy and reach through formal and organic opportunites for education.
- Emphasize alertness rather than mastery and progress over perfection. The more teammates we have paying attention the user experience of **all people** then the better quality of products we'll deliver.

These steps will result in a reduction in the bugs making it to production and the time it takes to fix a11y bugs. 

![A dashboard showing a drastic decline of a11y bugs](/static/img/a11y-bugs-dashboard.jpg)

And stakeholders will get excited when they know you're delivering quality code and experiences. 
![A shoutout in Slack from a Project Manager about how happy a client is on the quality of delivery](/static/img/a11y-cin-sh.jpg)



