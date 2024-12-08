# Technology assessment rubric

This is a way to assess software you might be thinking of using. It works for
software libraries, cloud platforms, online services, etc: any software you
use to conduct your business.

There is no panacea.  There is no way to know some of these answers for sure - 
but an intentional web, news, and social media search will help you find obvious 
red flags. For vendors that become an integral part of your organization's 
processes, it's a good idea to re-evaluate these questions at least annually.

Ideally, every team who buys its own software should be able to run an assessment
on their vendors ahead of time. This isn't something that should be left to
a technology or IT team alone, although they can always be used to *help* answer
some of these questions as required.

## Vendor selection

### The problem

These questions should be answered by the people who will actually use the
software.

- What does this software do?
- What real problem does it solve for your organization?
- What are the costs your organization incurs because of the problem? Can you quantify the costs in measurable terms, like:
  - Extra development staff time to perform workarounds
  - Additional customer support tickets
  - Lost revenue due to delays in shipping product
  - Warranty claims due to product defects
- How do you know it will serve this purpose well?
- Does it work with software and hardware that you already use, or does it require use of a new technology? (For example, does it require an operating system you don't use? If it's a software library, is it written in a programming language your team is not already using?)
- Why is it important that you use it now?

### Alternatives

- What are the _formal_ alternatives to this vendor? (i.e., who else is offering a product that solves this problem?)
- What are the _informal_ alternatives to this vendor? (What else could you do to solve the problem other than a direct technology solution?)
- Why did you select this vendor over the available formal and informal alternatives?

### Suitability

- If the software has a user interface, is it accessible to users with disabilities? (For example, is it ADA and WCAG compliant?)
- Does it comply with any relevant regulations for your location? (For example, GDPR?)
- Does it comply with any relevant regulations for your industry?

## Safety

### Security

- Does the vendor have a published security standard? For example, have they undertaken a [SOC 2 audit](https://en.wikipedia.org/wiki/System_and_Organization_Controls)? Do they undergo regular security scans and/or penetration tests?
- Have there been any known hacks or breaches?
- Have there been disclosures about the vendor's work that suggests they might be insecure? (For example, have there been whisteblowers on social media or news stories about the cavalier culture of the vendor?)
- If this is an online service, does it allow you to create individual user accounts for each member of the team who will use it, rather than a single account for the whole team?
- Does it integrate with your SSO provider and/or offer MFA?

### Privacy

- Does the software have a published privacy policy? Will you be notified of changes ahead of time?
- What data does the vendor gather about its use? Are you even able to determine this?
- Does the vendor share information with third parties? If so, who?
- Will the vendor use its data to advertise to its users?
- Does the vendor maintain a perpetual license to use your data? (For example, some social media platforms do this.)
- Does the vendor store or process data in a different nation? Which one(s)? Which privacy legislation is it governed by?
- Will your data be used to train a neural network that will be shared with other customers?

### Reliability

- What data is available to show that the software is reliable and bug-free? 
- If it's an online service, does it publish uptime statistics?

## Business freedom

- If this software captures data, how easy is it to transport that data to a different vendor whenever you choose?
- To what extent does using this software tether your organization's strategy to the vendor's business policies?
- Does this software depend on a third-party login (e.g., a Google account)?
- Does it integrate with other software you use?
- Does the software adhere to open standards or provide APIs to facilitate integration?
- Can it integrate with emerging technologies that might be adopted in the future?

## Values

What are the values of the vendor that has produced this software? This section 
is intended to help avoid reputational and team safety risks driven by vendors
that may not behave in a way that is in line with your own values.

- Is the vendor's team diverse and inclusive?
- Does the vendor work with hate groups, or has its leadership endorsed them?
- Has the team's leadership endorsed an erosion of civil rights, for example voting rights?
- Does the vendor have an environmental policy, or has it taken concrete steps to reduce its environmental footprint?
- Has the vendor been used to undermine a free and fair election anywhere in the world?
- Has the vendor been used in a genocide, war, or otherwise as a part of intentional loss of human life?
- Is this vendor involved in forced deportations, surveillance, or prosecutions for seeking reproductive healthcare?
- Has the vendor used pirated content as part of its work, e.g. to train a neural network?
- Has the vendor ever engaged in union-busting?
- Are there public reports or is there whistleblowing around treatment of its workers? (Has it ever been sued for wage discrimination, for example?)

## Documentation, training, and ecosystem

- Does the vendor offer comprehensive documentation?
- Is the documentation accessible by the members of your team who will use or gain from your product?
- Does the vendor offer training? For what price?
- Is third party documentation and training available?
- Is there an ecosystem of service providers surrounding this product?

## Cost

- What is the up-front and ongoing price of this product?
- Is the total cost of acquiring and using this product greater or less than the cost of the problem noted above?
  - If greater, how will the additional cost be covered?
  - If less, how will your team utilize the savings?
- What is the impact of using this product on your team? (e.g., setup time, time spent on maintenance, requirement to buy other products / services, need for training, other resource use.)

## Risk

Based on the answers above and your knowledge of the software team and its
business model, consider the risk to your organization.

This is a  common framework for figuring out what the biggest issues might be 
and how you would deal with them if they arose.

Brainstorm the worst things that could happen - a data breach, or the vendor
going out of business - and roughly rate the *likelihood* of this event, and
the *impact* on your organization if it did happen. Multiple those together
and you have the *risk factor* of that event.

Try to describe at least 5 risks, and list them in a table as follows:

|Event            |Likelihood (1-5)|Impact (1-5)|Risk factor (likelihood x impact)|
|-----------------|----------------|------------|---------------------------------|
|Hacked           |1               |5           |5                                |
|Sunsetting       |2               |3           |6                                |

### Mitigations and Contingencies

For the top 3-5 risks as ordered by risk factor, write bullet points for how
your organization could reduce the impact (i.e., what preventative steps could
be taken?) and what your organization would need to do if it *did* happen.

## Go / No-Go

Based on your answers to the above, do you think you should progress with acquisition?
Choose from:

- Strong No
- Lean No
- Lean Yes
- Strong Yes

Explain why you chose this answer.
