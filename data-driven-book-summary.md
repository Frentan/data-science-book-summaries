# Data Driven by DJ Patil & Hilary Mason - Notes
Data science is not fundamentally new. What's innovative is how it combines several different fields and skills in a single professional. The first of these is mathematics, with an emphasis on statistics and linear algebra. The second is computer science, including programming and infrastructure design. It's essential to be able to extract data from a database and into an analysis package and back again. Finally, a data scientist *must* be able to communicate effectively and create coherent narratives around their work. Insights that are not actionable are next to useless. Asking the right questions, domain expertise, a keen ability to see the problem, and empathy to join it all (a concept so often neglected) are all of paramount importance.

Data scientists should never be isolated from business areas and decision makers. Companies and governments are increasingly aware of the need for "a Spock on the bridge".

## Working with Data
> A data-driven organization *acquires*, *processes*, and *leverages data* in a timely fashion to create efficiencies, iterate on and develop new products, and navigate the competitive landscape...
> 
> [Emphasis added.]

Just acquiring and processing is not the whole story. Data quality is crucial. Data must be organized, consistently formatted, well-documented and, as much as possible, error-free. Cleaning data is often 80% of the job.

Many organizations invest heavily in data processing without a clear goal, resulting in large expenditures to create and maintain a vault of data that ends up being rarely used. Successful organizations don't expect that people will create value from a large store of data just because it's available. *They put their data to use*, to understand their customers and their business, to develop experiments and test hypotheses that improve their processes, and to build new products.

![Match](https://assets.amuniversal.com/a08d25406cbc01301d46001dd8b71c47)
## Democratizing Data
> Everyone in an organization should have access to as much data as legally possible.
> 
> [...]
> 
> One challenge of democratization is helping people find the right data sets and ensuring that the data is clean. [...] To help employees make the best use of data, a new role has emerged: the data steward. *The steward's mandate is to ensure consistency and quality of the data by investing in tooling and processes that make the cost of working with data scale logarithmically while the data itself scales exponentially*.
> 
> [Emphasis added.] 

## Managing Research
Diving into a new data set is not just a matter of checking off statistics, but of developing an intuition for any possible flaws in the data, any unexpected things it might explain, and building a mental model of what it says about the world. After this initial approach and the definition of the problems to be tackled, a robust process for managing research is needed. Without it, you risk wasting time and effort on unimportant issues or getting drawn into the engineering side of things, where research is not a priority.

**A loose framework for tackling data science problems:**

 1. ***What is the question we are asking?*** Companies have diverse teams, so make sure to state the question in a way everyone can understand and see why it might be relevant and useful.
 2. ***How do we know when we've won?*** You need to define the metrics by which you will evaluate your answer, be they quantitative or qualitative, and everyone must be on the same page about what a successful outcome looks like.
 3. ***Assuming we solve this problem perfectly, what will we build first?*** This is intended to clarify the solution's potential to impact your business. After defining the first thing, it's good to come up with more and look for both short- and long-term value.
 4. ***If everyone in the world uses this, what is the impact?*** Reinforcing once more the relevance criterion, resources should only be invested in projects that will have a significant impact on business.
 5. ***What's the most evil thing that can be done with this?*** This works on two fronts. Your colleagues are probably *not* evil. But imagining what would happen *if you abandon all constraints* can help to think outside the proverbial box. Secondly, good and lawful people generally don't see the potential uses a tool can have for evil. Scientists are often making ethical decisions, even if inadvertently. Just because you *can* do something doesn't mean you *should*. When uncertain, refer to experts on privacy and legal matters, such as the [Electronic Frontier Foundation](https://www.eff.org/) and [The Center for Internet and Society](https://cyberlaw.stanford.edu/).

## Designing the Organization
Data science is a team sport. Even a single person with access (and skill with) data can have a great impact, but that's hardly scalable. You have to think about both the composition and organization of data science teams. On LinkedIn, instead of a conventional team under the CEO or CTO, a decentralized model is used, with at least three data scientists supporting a given area.

## Daily Dashboard
Starting every day with a review of the data has to be a habitual practice. There are two common complaints about dashboards: they either don't contain *enough* data or they have *too much*. Let's look at some hints to avoid both:

 - Adding more information at greater density creates **data vomit** (gross). Don't fall into the temptation of adding "just one more thing". This will only cause everyone to ignore all of it.
 - Remember to review not only the data, but the dashboards themselves. You should look at them like living entities. As an organization's data sophistication changes, it's probable that the same processes of measurement will become outdated. Dashboards must always bring **real value**.
 - This might sound obvious, but it's surprising how many dashboards are just plain ugly. Data has to look beautiful and be readable. Don't underestimate the **visual** side of things.
 - **Alert fatigue** can also be a problem. With too many alarms, the team becomes desensitized. They can even end up ignoring alerts, as their frequency renders them meaningless. Constantly review both the alerts and the actions to be taken once they happen, and don't be afraid to get rid of them when they don't serve a clear purpose.
 - **Never follow data blindly.** Completely ignoring your common sense and instincts can lead to "letting the data drive you off a cliff". A surprising number of people have crashed their car by blindly following their GPS. *Just think about that: how much bigger is the windshield compared to the GPS screen?* Make a habit out of asking yourself "are we driving off a cliff?" This also contributes to a culture that challenges the status quo.

![Dogbert](https://assets.amuniversal.com/096f45406cc901301d50001dd8b71c47)
## Standup & Domain Meetings
Long and unnecessary meetings kill both creativity and productivity. Standup meetings (defined by the maximum time a person is willing to stand) help keep everyone on the same page, while questions and issues become action items to be addressed later. We review these items at the next standup, and if they're not resolved, a time goal is defined.

Domain-specific meetings are longer and more specific. They should be open forums where everyone can contribute with constructive criticism and help. Examples include product review, design review, architecture review, and code review meetings.

## Tools & Democratizing Data Access
A big secret of data science is that the specific tools used are almost irrelevant. An expert can do more in Excel than a neophyte can manage with R. Understanding the problem, formulating an experiment, collecting data, asking good questions, and verifying the accuracy of a result are all more important skills than mastering the tools. Nevertheless, tools will be used for all of this. Here are some attributes to look for when choosing what to use:

 1. The best tools are **powerful**. Think about limited dashboard applications versus complete programming languages.
 2. The best tools are **easy to use and learn**, without conflicting with the first point. For programming languages, look for robust learning resources, support, and community.
 3. The best tools **support teamwork**. They should make it easier to collaborate and reproduce the work.
 4. The best tools are **community beloved**. An open source tool popular in the technical community will have much more support than a proprietary one.

Democratizing data access has its costs, often involving rethinking an organization's tools and practices. But it has a big upside too. Bureaucracy in the way of accessing data is sure to halt democratization. Train users to get the data themselves. Solutions are often evaluated on speed, but when supporting a large number of users, raw speed loses relevance. Almost anything will be quicker than going through a data warehouse staff request.

## Creating Culture Change
> Succeeding with data isn't just a matter of putting some Hadoop in your machine room, or hiring some physicists with crazy math skills. Succeeding with data science requires real cultural change. It requires learning how to have a discussion about the data --- how to hear what the data might be saying rather than just enlisting it as a weapon in company politics. It requires spreading data through your organization, not just by adding a few data scientists (though they are critical to the process), but by enabling everyone in the organization to access the data and see what they can learn. [...] **Good data science gives organizations the tools to anticipate and stay on the leading edge of change.**

> Written with [StackEdit](https://stackedit.io/).

