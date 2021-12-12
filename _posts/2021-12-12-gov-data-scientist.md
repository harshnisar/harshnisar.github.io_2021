---
title: "Does Your Government Department Really Need a Data Scientist? Probably No."
categories:
  - Blog
tags:
  - Government
---

I know, this is contrary to what I've been tweeting or talking about. Don't get me wrong, I am a huge proponent of building in-house expertise for emerging technologies in the government. Over the last 5 years in the Ministry of Rural Development, I've played played the role of a solo data scientist in DDUGKY, PMGSY and now as the founder and lead for the ministry-wide Data & Insights Units. 

Before I begin, I need to clarify what I mean by a data scientist given it remains a contextual definition. I'll differentiate them from data analysts in their ability to code and use algorithms, train ML models etc. I am assuming an analyst can do data analysis, create dashboards and visualizations. 

Why then do I disagree with my own position?
Frankly, I don't think most departments are there yet. 

## ACT ONE
In 2016, when I was hired in DDUGKY, the department was struggling with having a proper MIS. The day-to-day scheme operations were managed by an elaborate and to its merit a very smart system of linked google spreadsheets. Back then, I was the cliche engineer with a hammer in search of solutions, it was just that the walls were not even setup and there was nothing to hammer a nail into. Leaving aside managing two vendor-based ML pilots which were initiated before I joined, most of my time at that department went into helping design the requirements for an actual MIS, figuring procurement and spending time conducting day-to-day operational analysis with the data that already existed. I would say I played the role of an analyst + project manager.

## ACT TWO
In 2018, I moved to PMGSY where the digital systems were mature and the scheme had been functioning since early 2000s. What do I mean by digital systems? Most of the administrative processes under the PMGSY program were digital and largely transactional. Further, the department had invested in digitizing key datasets such as getting all of the rural roads and habitations on GIS in a project that took 3-4 years. Here, I was brought in with the aim on capitalizing on the GIS datasets that had been collected prior to my joining. The timing was suitable as the government was preparing to launch a new road upgradation program and I was tasked with improving the policy for the road selection process. The solution involved conducting stakeholder consultations, writing the rural traffic simulation algorithm, designing new IT modules needed for the overall process, managing development and deployment, directly training more than 6000+ stakeholders, providing tech support, examining and reporting bugs to the IT team, conducting planning audits on the new roads being selected and creating reports/presentations, constantly talking with state IT/GIS heads to ensure they are able to complete the processes etc. In this case, the leadership had an idea of why they wanted a data scientist. there is a broad but clear pathway, and the department had mature digital systems on which these interventions could sit on. Generally, algorithms will be a small part of the whole, and in most cases gains will be incremental. The real gains are to be achieved in first digitizing processes where possible. 

## ACT THREE
Based on learnings and showing merit in using emerging technologies to improve governance, we decided to scale this across government programs within the Ministry of Rural Development. Among many options, two major ones were whether we push for dedicated data scientist's within each scheme or have a common team across the Ministry. 


## Risk of a Common Team
- Difficult to get buy-in within the individual divisions/government programs given you'll operate outside of them
- Scoping of Projects will be less immersive 
- Patchwork projects as against more deeper/systemic projects. PMGSY-III project required a lot of involvement apart from just writing the algorithm. Limited to writing API-able algorithmic projects or low touch changes. 
- Difficult to build relationships with existing technical teams 
- Cannot work on improvement of IT modules etc
 

## Advantages of a Common Team
- Pipeline has a lot of time-lags so the same data scientist can work across more than one projects
- Not every scheme has easily scoped algorithmic projects 
- Can focus on algorithmic projects and will not be pulled into operational IT work
- Can invest in additional common roles such as HCI Researcher etc
- Can bridge data silos across the departments 
- Hiring data scientists is already hard, more-so in in the public sector: low pay, lack of expertise to interview and hire. Common teams usually will mean lesser hiring
- Leadership at the department level may not be there yet for all schemes, so easier to anchor the team with a single senior bureaucrat. 
- Easier to setup ethics board mechanisms, re-direct vendors attempting to sell directly to downstream agencies etc. 

We decided to go for a common team after addressing some of the associated risks.

For one, the team is anchored to the Additional Secretary in the Ministry to which most of the Joint Secretaries in charge of divisions or government programs within the Ministry report to. This helps us get the administrative buy-in and the horizontal view of the schemes and the priorities. 

For technical buy-in, the team sits with the Department's NIC and remains under the mentorship of the DDG, NIC which heads the NIC for our Ministry. NIC develops and maintains most of the division level MIS in our Ministry except for PMGSY and to some extent DDUGKY. 

![image](https://user-images.githubusercontent.com/6428892/145712950-4889549b-90eb-4997-9225-dcacbc591ce5.png)


I have to admit, a large part of why this team is also able to get some early wins since beginning is because of the existing relationships I was able to build within the Ministry over the last 5 years. This includes relationships not just with the bureaucrats, but more importantly with the technical and ops teams in the middle tier. Having had worked in the 2 of the schemes intimately also allowed us to scope a project really quick. The real test will be scoping projects for schemes I've had no context or relationships with. 

### What should your department do?
I think it depends on multiple factors:
- Maturity of IT systems
- Maturity of leadership
- Proven culture of everyday data science
- Funding mechanism available and their flexibility
- Organogram of sub/parent agencies

### Lets get the basics right first
For example, agencies which yet haven't digitized core components of their administration, should instead focus on that first. One can argue that the data science projects can happen in parallel to the basic IT projects and they don't necessarily need to compete. We need to remember that department heads generally are over-burdened and have limited monitoring capacity and in that case they may be better rationed to basic CRUD projects. Once,  that's done, an agency may better benefit by hiring data analysts or upskilling existing MIS professionals on better data-usage before hiring expensive data scientists or procuring commercial AI/ML solutions. A sophisticated algorithm churning out insights may not be useful unless the department has saturated the utility of the basics and has shown a culture of data-driven decision making.

### Conclusion

There are different methods of leveraging emerging technologies within the government and across the world these mechanisms are being experimented with. What will work for a specific department/agency/ministry may depend on the exact circumstances, maturity,  relationships, funding mechanisms available etc. Unfortunately, most public sector agencies are under the pressure to *innovate* and will go through a cycle of experiments before settling into what works for them the best. Failed projects will distract from core priorities, waste public money, erode trust on emerging technologies and at worst lead to shoddy deployments and harmful end-user impacts. 

There is a need for agencies and donors to learn from what has and hasn't worked and figure out less riskier pathways for more responsible and meaningful use of emerging technologies to improve service delivery.  

---
For more government micro-musings, you can check my [tweets](https://twitter.com/search?q=(%23sarkari)%20(from%3ANisarHogaya)&src=typed_query)!

