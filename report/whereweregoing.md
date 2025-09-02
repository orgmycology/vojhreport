# Where We’re Going: Recommendations for JupyterHub’s Future Directions

The JupyterHub project has many pathways available for improving leadership and management structures, ensuring the long-term health of the community, and otherwise addressing the challenges expressed by interviewees. Engaging in these efforts will help the project to generate an increase in newcomers, to improve the newcomer-to-contributor pipeline, and to reduce the burdens experienced by a few key individuals.

## **1\. Taking Pride in the Project: Tell the Stories of (and Market\!) JupyterHub** 

JupyterHub is a technically solid and complex project that has delivered impact in education and research, from improving the classroom learning experience to enabling Nobel Prize-winning research. If we look at JupyterHub's public-facing platforms, though, there is a distinct lack of championing these impacts. Occasional blog articles or social media posts highlight some of the project’s impact, but there are no permanent, centralized places listing the many accomplishments the community has achieved. 

Moreover, it is difficult to get a sense of where the project sits in relation to the interactive computing market as a whole. A potential user or contributor encountering the website, for example, may not be able to answer questions like, “Who are JupyterHub’s competitors?” “Which of my organization’s tools or services could I replace or augment using JupyterHub?” “How is JupyterHub different from other interactive computing tools?”

In some ways, these are difficult questions to answer even for core members of the project because JupyterHub has unique capabilities that are not entirely amenable to comparisons with alternatives. As Fernando, a founder of the Jupyter project, explained, the broader Jupyter ecosystem can perhaps be best described with an operating system metaphor:

> “And I think what happened was, over time, JupyterHub became in its own right kind of complex and rich enough, and also as the infrastructure of the project ended up effectively requiring very different skill sets and focus. As a whole, Jupyter is a nasty, complicated beast. It's a lot, right? … **Jupyter is probably better thought of thinking as an operating system than thinking as an application for any particular task.** Like, well, you have JupyterHub. You have Myst. You have Binder. You have JupyterLab. And JupyterLab is being used to build GIS systems and CAD engines. And like, my god, in some ways that makes no sense at all. Under the light of a thinking partner, yes, it makes sense, but based on the original vision of running python interactively it makes less sense. **And yet, and yet, to me, there's a continuous thought line between the original little IPython lines that I've posted on GitHub, right? Up to today's massive complex architecture, which is, it's all about interactive computing. It's all about people using the computer as a thinking partner to explore problems.**” (Fernando Pérez)

Yet describing how these component parts of the “operating system” fit together is not easy. JupyterHub is enmeshed in an ecosystem of tools that make defining and marketing it as a distinct project a task that has, to date, been intractable:

> “I think one of the issues, and we've talked about this extensively with people in the project, is that operating system vision, right? **That map is only in the heads of a few people. We literally haven't had the time to really describe and document that map of ideas fully**. And in a way that then presents the map, it presents the connecting paths, and then examples of how to do it.” (Fernando Pérez) 

According to interviewees and our own thinking, there are multiple other factors driving this absence of a broader championing and marketing of the project:

* The JupyterHub project specifically has a narrow technical focus: 


> “I always feel like JupyterHub's first line of users are actually  IT professionals and institutions who are deploying this for themselves. And then their users are the people who are looking at Jupyter notebooks and clicking through, right? It's like a tree of users going on.” (Sarah Gibson) 

    
* The software works “invisibly” when successful, like utilities:


> “I would say that I think for engagement is that it's an infrastructure project and that's a part of the challenge to engage. I would say that at least for me and my experience, like for anyone who's trying to go into coding as a like developing kind of career or prospection of career, people want to see things happening. So people are very excited about building their first blog, their first website, or their first phone app. So that's very exciting. **The part of infrastructure is not that exciting and visible thing**.” (Raniere Silva)

> “That's the challenge of infrastructure. It's very invisible. I mean, people know that our website exists, like. UC Berkeley students will know that they can go to this internal address, open the browser, and **they'll be like, ‘Ta-da, JupyterLab is working\!’ But it's very invisible what is behind it**.” (Raniere Silva)


> “**JupyterHub is a weird project in the scope of Project Jupyter as a whole, because it's very sysadmin-y, right?** There's only like three pages it generates that are shown to an end user, right? And as soon as the user's server is started, we hand over to the notebook and the Lab app. And that's actually a whole different team of people. In a way, I kind of don't care what's coming down the pipeline in terms of machine learning, data science or whatever, because at some point, humans are going to want to use computers. And that's the problem that JupyterHub solves.” (Sarah Gibson) 


* The core team has not formalized marketing and structured communication processes.

On the first two points, the project’s technical focus is very specific and supports a number of other tools that are much more “visible” than JupyterHub. JupyterHub works to bring the capabilities of other Jupyter projects to users via multi-user web-based interfaces using notebook runtime environments, authentication, and proxying tools. The combination of the utility of the project and the relative invisibility of its existence means that many users do not know they are using JupyterHub, and few understand how the tool does what it does. 

When JupyterHub is working properly, nobody notices it–it is only recognized when something breaks. This situation is simultaneously a testament to the project’s importance as a core utility for the broader Jupyter ecosystem and a major organizational challenge: Invisibility makes it difficult to draw attention, funding, and recognition to the project and to attract new contributors. Based on our interviews with JupyterHub community members, it appears that most people have become users and contributors via word of mouth, existing relationships, recruited internships, experiences with tools like [mybinder.org](http://mybunder.org), or simply by demand for JupyterHub environments.

JupyterHub itself does not do any overt or intentional marketing of the project that we have seen. 2i2c, the leading provider of managed JupyterHubs, has done a bit of work in this area, but role confusion and key personnel holding multiple roles in both 2i2c and JupyterHub communities has created confusion about who and what roles should be responsible for things like project marketing. Rick, who is keenly aware of JupyterHub’s potential to serve broader markets, introduced some questions these stakeholders could begin discussing:

> “The other one is acknowledging that a lot of places, you know, JupyterHub is not the only mechanism to provide a multi-user interface to Jupyter notebooks. And what I've seen, even what our own center uses, is basically there's other folks that spin up mechanisms to provide the HTTP proxy capability. You know, we talked to a research institute, biomedical research institutes, here, elsewhere, it's like they're smart engineers who know as long as I can connect the networking plumbing from the end user through the web to the container or whatever is running their Jupyter environment, it doesn't have to be JupyterHub. **And, you know, it's kind of like a, well, how does JupyterHub say like, ‘Why didn't they use us? Could we have done something differently for them to adopt us?’**” (Rick Wagner) 

> “And I think that that is probably within a lot of our high-performance computing centers, the primary way that Jupyter functionality is being accessed is through Open On-Demand instead of JupyterHub. And I think that's because Open On-Demand is very flexible and supports a variety of use cases. **So I would say that that promoting the ability for JupyterHub to be an interface to other backends, you know, should be considered as a priority.**” (Rick Wagner)

Furthermore, as we discussed earlier, Jupyter and JupyterHubs have been instrumental in recent scientific advancements. Yet when we see breakthroughs illustrated in plots, screenshots, and citations, these artifacts routinely call out Jupyter and its community with little to no mention of JupyterHub. The community has not had a focused conversation about how this interrelated set of tools and infrastructure can be more explicitly credited for its important contributions to modern open science:

> “I think maybe the thing that's lacking is visualizing the impact. So maybe success stories … **What made me feel like the work that I'm doing is really important is seeing how the people are actually using the hubs, the end users, what they are achieving with the hub.** Because the impact is there. We just need to surface it more for people thinking if they should use it or not, for people wanting to join the open source project or not.” (Georgiana Dolocan) 

Each of the above challenges are understandable and, in some ways, have been transcended in some ways by a relatively small team of developers to create a tool that is continually evolving and changing. Yet it is critical to take steps toward resolving these broader issues: Open source contributors often want to feel like what they are contributing is making a positive impact, and communicating the impacts JupyterHub has had on scientific advancement in the last decade will attract more skilled people who can help sustain and advance the project. Doing so will require letting go of some of the humility that has been at the project’s core since its creation and getting contributors bragging about what they are contributing to.

**Next Actions:**

- Develop communications that share the big-picture story of what the hidden work of JupyterHub has enabled.  
- Facilitate a conversation which seeks to define the bounds of what  JupyterHub is, should be and should **not** be.  
- Conduct a SWOT analysis to both introspect on the project and look at how its landscape has evolved.

## 2\. Recognizing JupyterHub as a Model Subproject: Be Intentional about JupyterHub’s Relationship to the Broader Jupyter Ecosystem

JupyterHub as a sub project of Project Jupyter acts as a lynchpin for bringing Jupyter environments to hundreds of thousands of learners, researchers, and scientists worldwide. The project provides the necessary “glue” that makes it possible to run Jupyter kernels, Jupyter Notebooks, JupyterLabs and other environments within cloud and container environments. Under many layers of abstractions, JupyterHub enables users to simply log in and be presented with a prepared environment for their learning or data exploration without the common frustrations experienced by users of other tools.

That being said, JupyterHub is also a lower velocity project than some of the other Jupyter ecosystem projects, in part because it is working on and adding features and capabilities that work in the background. This means that the project does not have the same velocity of issues, forum posts, and bug reports that some other Jupyter projects. Users often don’t even know they are using JupyterHub. 

Having a lower velocity of direct user interactions can be seen as a feature, not a bug, and it stems from the scaling of access that JupyterHub environments provide. These environments polish the rough edges that other Jupyter sub-projects have when deployed by individuals or on local machines. Despite its lower velocity, the JupyterHub project team and its members should see themselves as essential contributors to the mission of bringing notebook environments to more people in more places. 

Taking credit for being the infrastructure that delivers access to the foundation of the broader Jupyter ecosystem may not be something that the project’s leaders are comfortable doing, but will likely become more important as Jupyter grows in size and scope. Ongoing information sharing with other subprojects, for example, would help the project anticipate and adapt to ongoing changes. Furthermore, the creation of the Jupyter Foundation is likely to generate opportunities to bring funding to JupyterHub, to have JupyterHub’s voice heard in decisions about Project Jupyter’s strategic direction, and to draw in contributors from the Foundation’s member organizations. Being aligned on JupyterHub’s priorities and goals will be an important part of positioning the project as a model subproject in the broader ecosystem.

The JupyterHub subproject has a history of being a welcoming place for technical work and exploring difficult technical challenges “without drama” as one interviewee said. At one point when JupyterLab’s development was skyrocketing, JupyterHub separated itself from the rest of Jupyter largely because the team working on JupyterHub could no longer keep track of all the changes taking place in JupyterLab. JupyterHub has few dependencies upstream to JupyterLab itself, and JupyterLab has few explicit dependencies to JupyterHub itself. This creates a social environment between the projects where both projects feel like they don’t necessarily need the other. While this may be true in some ways, it is possible to have a more nuanced reading of what each project offers to the other. JupyterHub makes it possible to deploy JupyterLab and other Jupyter tools at scale, and JupyterLab provides the most frequently deployed/used environment used within JupyterHubs. 

The lack of technical explicit dependencies can be seen as a feature when looked at under the right light, not a bug. This kind of loose coupling between projects, rather than tight technical coupling, enables both projects to move relatively independently of each other. This can also lead to significant cultural differences in how work is prioritized, distributed, and completed across sub-projects. It was clear from this research work that the culture of JupyterHub and the culture of other Jupyter projects are quite different. In fact, some interviewees talked about avoiding the larger Jupyter project because of past challenges and conflicts with leadership.

Recognizing that people come to JupyterHub for certain types of culture, working practices and community, it is also important to recognize that other Project Jupyter subprojects also have their own practices and norms. Throughout our research and interviews, the work and culture in JupyterHub was socially positive–that is, people enjoyed working with those in the JupyterHub community. That is not necessarily the case for the broader Jupyter ecosystem, as we learned in conversations with members of both JupyterHub and other Jupyter subprojects in this work. 

#### Social  {#social}

* Group-level (e.g., toxicity, belongingness, DEI)  
  * Carol’s story/concerns  
* Individual level (reputational benefits, personal harms, DEI)   
  * Some people mentioned that it is a recognizable, professionally-beneficial thing to be associated with Jupyter

#### Technical  {#technical}

Community members have expressed that dependencies are largely one-way, Jupyter is a user of JupyterHub’s technology and not always vice versa. Users of JupyterHub also recount how flexible it is and that it can be used for bringing a myriad of other tools (not just notebooks) to users in a secure manner.Notebook offerings (such as marimo) which can be seen as competitors to JupyterLab have been run using JupyterHub. This has caused some community members to ask themselves what the relationship is like today with the larger Jupyter Project and how it might evolve in the future. It was clear during an exercise to “Draw JupyterHub” at the June Leadership retreat that most people’s view of JupyterHub was that of a utility enabler of science and collaboration across a myriad of tools, not just JupyterLab. 

#### Structural/Sociotechnical {#structural/sociotechnical}

> Changing financial and governance structure in Project Jupyter has implications for the subprojects (Paul)  

Multiple stories of the relationship becoming more complicated at the time of the arrival of JupyterLab 

**Next Actions:**

- Lean into what JupyterHub enables and is good at: creating prepared notebook environments delivered directly to users eyes and keyboards, at scale, regardless of deployment type (e.g., in education, science, or corporate environments).  
- Strengthen connections to other sub-projects in ways that innovations happening in them and in JupyterHub itself are complementary, so as to continue to enable scaling access to tools for assisting in the acceleration of education and science. Be sure to protect JupyterHub’s positive culture when interacting with other groups, such as by holding JupyterHub-only debriefing sessions to discuss what went well and didn’t go well in these engagements.  
- Teach what works well in JupyterHub’s workflows/processes to other Jupyter subprojects, and learn from what other subprojects do well.

## 3\. Developing a More Unified Voice: Enhancing Communication

Communities with highly-technical capabilities can have forums where the topics are hard to understand without context and experience. With JupyterHub’s wide range of possible deployments, the differences in key architectural components, and software capabilities are at times advancing faster than documentation can keep up, the JupyterHub community could benefit from some regular communication channels that are authoritative and which summarize community progress, vision, and capabilities. 

JupyterHub could work to develop a more regular cadence around broadcast communications that can be interleaved with key development output cycles. This could take many forms, but the key is for it to be a channel that community members can subscribe to and have pushed to them. Discourse, an email mailing list, blog post, or other mechanisms would be sufficient. When developing these communication avenues, it may be helpful to consider which forms of project communication are dynamic, which are relatively static, which are technical, and which are non-technical. Thinking through these dimensions of communication can help the project make informed decisions about “what goes where,” given the currently-fractured system of communication. We offer some ideas for categorizations below, but these categorizations should ideally be developed in conversation with the community and responsive to its needs. 

**Community and Celebratory Communication \-** Community communication is a way that the project can invite and welcome newcomers, celebrate its people and successes, and share the diverse stories of how JupyterHub is used, deployed, developed, and improved. Community communications should reflect the tone and content of interactions that the core team wants to encourage, support and sustain. This form of communication should always have the goal of showing off the “human side” of the work: how people contribute, how it connects to others’ work, how JupyterHub participation improves their lives and advances their ambitions. Community communications should also serve to show how others can take up the challenge of contributing to JupyterHub, particularly in non-technical ways (e.g., meeting leadership, outreach initiatives, and community-building events). Celebratory communication, in particular, brings the successes of the project to the forefront. Who is newly deploying JupyterHub this week? What research / capabilities are now enabled by these deployments? What breakthroughs have been made using JupyterHub? 

Often in open source projects, these forms of communication fall under the responsibilities of a community manager:

> “I think what a community manager does is look to, ‘What are the motivations of the people who are contributing? And how can I recognize them, celebrate them, find some skills for them, and do a bit of matching? And do a bit of mentorship, and smooth out some of those pathways?”  (Kirstie Whitaker) 

In the absence of a community manager, leadership must find ways to distribute the work of community and celebratory communication. This can take the form of making space for community members to share their own successes and stories, such as in dedicated channels or forum topics, via invited blog posts, or during allocated time in each Collaboration Cafe. 

**Technical Communication** \- This form of communication intends to summarize and share key technical outputs/changes, challenges, and topics that need input and action. Technical communication enables community members to stay up-to-date on the state of the project and often involves pointing people to vibrant GitHub Issue conversations or Discourse threads (i.e., cross-promoting conversations happening elsewhere).   
Content includes breaking changes, new features, upcoming releases, roadmapping, needs for development effort, release cycles and more. 

Holding these types of conversations in public places and making an effort to document them is a key way that projects can begin to develop a community-driven, concise technical vision. Given interviewees’ discussion of conflicting definitions of what JupyterHub is and isn’t and the challenges of its growing complexity, unifying technical communication can be immediately beneficial to demystifying the project’s inner workings. Being an infrastructure project, JupyterHub touches a wide range of technologies, components, and technical choices, which are difficult for even the most experienced maintainers to keep track of in the current state of communication:

> “Ideally, if you had infinite resources, we'd be able to say, answer issues on GitHub on every, on over a hundred odd repos. Plus Gitter when it still existed, plus Zulip now, plus Discourse, plus Stack Overflow, plus Reddit, plus wherever the others are. Realistically, we just can't do that.” (Simon Li)

To date, users and newcomers tend to keep track of these conversations in ad-hoc, word-of-mouth ways. As one respondent explained, he relies on a combination of Collaboration Cafes and his colleagues to stay current on JupyterHub news, and leadership could consider ways to make this even easier: 

> “One is, I read all the Jupyter blogs, like whatever the latest news that comes out. And I also sometimes attend the community meeting, or at least if I don't attend, I watch the video, or at least read the community meeting notes, just to get a sense of how things are unfolding. And also my colleagues, they also share a lot of the latest updates. So that way I keep getting these updates on a regular basis.” (Balaji Alwar) 

Documentation can also be considered a form of technical communication, and interviewees found that JupyterHub’s documentation was adequate in some ways and inadequate in others. The main area it could use work, in Rick’s estimation, is being better-targeted toward intended audiences:  

> “Documentation is always the hardest, right? You know, I know it's up to date. I know it's accurate. I just, my gut feeling is it could use a revamp from, you know, you do that classic thing is like, let's take a few personas and work through them and reframe our documentation.” (Rick Wagner) 

> “I think to improve the value of JupyterHub to a broader audience, to basically elevate those capabilities. The JupyterHub documentation is a little bit scattered. And the narrative is a little bit disorganized. Different elements show up in different places between examples versus administration, system administration, stuff like that.But making that functionality more prominent and well supported, I think would really ensure that JupyterHub addresses the other critical factors, which is its competition.” (Rick Wagner)

**Informal Communication** \- While people who work in open source are always relaying a sense of being time poor, our interviews suggest that one-on-one and in-person time that JupyterHub community members have spent together serves as a key type of community glue. We feel that JupyterHub can and should find ways to bring more of this kind of informal interaction into community times and spaces. From creating informal get-to-know you times such as community calls, to finding times and spaces to network across groups (e.g., users, contributors, maintainers, leadership), to taking the initiative to celebrate successes and people in random moments, these activities need not be highly-structured. Organizations dominated by only informal communication have problems, but those that balance a mix of formal and informal can be very effective. 

**Next Actions**

- Develop periodic (fortnightly, monthly, quarterly) communications which touch on community, technical, celebratory and informal communications engagements for community members  
- Work to embed invitations for contribution–both technical and non-technical–into various communications focus areas  
- Set aside time to discuss ways of working and sharing and aligning on collective goals, and measuring progress toward those goals. 

## 4\. Sustaining Project Development: Improve Onboarding, Retention, Offboarding, Engagement, and Contributor Pathways

Bringing in new contributors is a persistent challenge mentioned across interviews with core team members. Issues persist across the entire pipeline: Recruiting new individuals into the community, onboarding them into the community’s workflows and practices, mentoring them to grow into contributors and maintainers, and growing their skills toward leadership positions. The drivers of these issues are, we hope, well-documented above (e.g., technical complexity of the project, JupyterHub’s invisibility to many users). Accordingly, there is no single answer to improving the health of contributor pathways, but there are various opportunities.

Enrolling and mentoring an Outreachy intern has worked well in the past, and JupyterHub should consider ways that it can replicate some of the process on its own. The core challenge with participating in Outreachy seems to be the time commitment for mentoring, but that time investment has paid dividends in many cases. Finding ways to make the mentoring experience easier for mentors and mentees, perhaps by sharing mentoring responsibilities, is a potential way forward:

> “More valuable than this would be to do co-mentoring, like actually mentor alongside somebody that has mentored before and split tasks … have somebody to ask questions when you're facing some challenges.” (Georgiana Dolocan) 

Issues with mentoring time commitments, though, speak to a broader issue at hand: JupyterHub lacks formalized onboarding processes beyond documentation on its website, and the result is low volunteer engagement. In the absence of individuals taking the lead on improving onboarding processes, JupyterHub must find ways to share the responsibility and invite newcomers in more informal ways. Part of this process could involve the core team sketching out “personas” for newcomers, then tailoring onboarding strategies to those personas:

> “We need to identify these different personas pretty clearly and then devise or develop strategies to be able to actually onboard people in those different personas that we believe will grow the project somehow.” (Damián Avila)

A good example might be the “highly-engaged user.” We observed an instance in which the project team missed an informal onboarding opportunity. A user facing challenges with his deployments attended a Collaboration Cafe call, presented his problem to the team, and asked for guidance in how to resolve it. Whereas the core team could have extended the user the opportunity to learn how to resolve the issue and potentially make a contribution, they instead added the issue to their backlog of things to address and assured the user that they would act on it. In reality, the time commitment for soft-onboarding this experienced user may have been similar to the time it would take to resolve the issue internally with the added benefit of inviting another contributor to the community. Leadership is, according to interviews, aware of these missed opportunities, but lacks structure for acting upon them:

> “I think there probably are more people who could help maintain. I can't name individuals, but I think the amount of contributions that we've gotten. But the trouble, I think the trick is that there's a lot of people contributing like this one small thing. Like I fixed my problem and I moved on. But I think there are a number of people with relevant expertise who are adjacent, who maybe haven't stepped in and we haven't helped them do that.” (Min RK) 

This is a common anti-pattern in open source communities where the community would like to be inviting and accepting of new volunteer members, but instead choose to resolve the issue themselves. In this case, the missed opportunity to onboard a new contributor also moved the tone of the Collaboration Cafe towards highly-technical conversation in the main call room (as opposed to in a breakout room), an incident that can be off-putting to newcomers hoping to learn more about the project:

> “I worry about our community call. And one of my reasons for trying to turn it more into a collaboration cafe is because … is that discussion can get really technical really quickly. And I think if you're a brand new person trying to figure out, ‘What is this project? Do I want to? Jumping into that meeting and that being what you hear is like super off-putting. Not in like a... Well, I guess maybe in like, ‘I'm not welcome here ‘kind of way, but it's subtle, right? … And so the idea of the collaboration cafe was taken from the Turing Way, and the idea was to use more breakout rooms so that there's still space for those deep technical discussions to have, but we can have parallel conversations that are maybe not so overwhelming. Onboarding places where people could just sit and go through issues. The problem I faced was that Jupyter is just not as big as the Turing Way, and you've got six people turning up to a call, and they all want to be involved in all of the conversations, and it's just not worth opening up the breakout room.” (Sarah Gibson) 

Making space for newcomers to have an easier entry point to learning about the project can help with onboarding, and so too can making pathways through the community more transparent. Newcomers show up to communities with some expectations about how they might get involved, but often are in an exploratory phase where they are figuring out what they are capable of contributing. A key aspect of making newcomers feel that they have contributions to offer is to visualize pathways through the community: What are the various roles one can have? What skills are needed to go from user to contributor? Contributor to maintainer? To date, these pathways are not visible to potential community members and can make involvement a daunting task.

Skills maps can be a useful way to visualize these pathways, an idea that has taken hold among some members of the JupyterHub community:

> “I think there needs to be medium issues as well. I think I have a desire for a middle step, and there isn't one… ultimately what the project needs is more maintainers at all of those levels that I mentioned before. Whatever that means, we need a sharper description of what those levels mean, but we need people at the strategic decision making level… I don't know what that middle step is. It doesn't exist yet, but I feel like I want there to be one.” (Sarah Gibson)

> “One thing might be worth doing is just saying what skills are needed before you can have push commit access to a particular repo.” (Simon Li) 

Developing a skills map requires first defining what the various community roles are, then listing the progression of skills needed within and across each “step.” These steps often take the form of “novice, intermediate, expert, mastery” within a given role, with some level of proficiency being needed to cross the threshold into an advanced role. Such visualizations can make the learning curve feel more manageable, especially in highly-complex projects like JupyterHub:

> “I think it's fine if the high point of contributing is high and complex. I don't think that's a problem. I think it's legitimate and I think that's intrinsically a complex and sophisticated project. My concern is that the path, that high point is a vertical wall, right? That path needs to be a smooth ramp with plateaus at different stages where people can say, ‘I go here and this is where I work’ and some people then choose to go to the core where things are harder and more complex.” (Fernando Pérez) 

We have provided an example of what a starting point for a skills map might look like for JupyterHub in the Appendix.

In addition to newcomers and individuals who traverse community pathways to advanced roles, community members unfortunately leave projects as well. Offboarding is often an afterthought for OSS projects, yet it plays an important role in sustaining activities. 

JupyterHub community members described many instances of project members leaving, and most often these departures were because individuals’ life circumstances had changed: They had children, advanced their careers, left postdoctoral positions, moved across the world, had health concerns, and various other developments that caused them to step back from JupyterHub. 

> “So he stepped down from Jupyter a year or two ago just because he was too busy with other things” (Simon Li)

> “And then I believe they decided to step back a bit from the open source world and do something else.” (Georgiana Dolocan)

> “The group, the community grows, and it needs to grow. It's part of the journey and the process. But as it grows, it also becomes more challenging because there's more people, there's more code, there's more tasks, and people move among different life stages. Some people, they were already on the mid work career kind of thing. So they might have a rather more stable life circumstance in terms of job security and other things. But there are people that start engaging in the project when they were high school or undergrad, bachelors and moving careers, jobs, marrying, having kids, all these kind of impacts.” (Raniere Silva) 

Building reasonable expectations around contributor engagement, availability, and disengagement in an ever-changing personal landscape of contributors is needed to help to build a more vibrant and robust community. Is the project considering the evolving needs of the project and its contributors? How can people remain involved in a reduced capacity? What are the project’s processes for ensuring the person’s expertise and institutional knowledge are not lost, but instead passed on to their replacement? Tim Head, who championed the idea of continually looking for and training replacements for maintainers, indicated that JupyterHub may not have adequate processes for productive offboarding:

> “And eventually I just say, okay, I don't have the capacity to do this and did less and less and less and nothing. Until I think people had realized that I was not interested or didn't have the time or I don't know what they thought … then I think when I started my current job about two and a half years ago or so I was like, ‘Okay, my job is now to become a scikit-learn maintainer and that's going to be what I do and I for sure have no time to help with JupyterHub.’ And within scikit-learn we just had a discussion about people who should retire or not and what do we do about the long list of maintainers who are no longer active.” (Tim Head) 

Having clear, productive offboarding processes ensures the health of the project’s contributor and maintainer pathways. It also serves the project’s reputation and social cohesion, as acknowledgment and appreciation for an individual leaving can make them more likely to come back, to speak positively about the project to others, and to otherwise comfortably remain in the network of their peers:

> “Also to give people permission structure to leave, because a lot of people feel really awkward about saying, ‘I am stepping down from the project,’ because they feel there's a big social penalty to pay.” (Chris Holdgraf)

Making space for frank conversations about roles, expectations of those roles, and how to onboard and offboard from these roles will be an important part of the community growing and inviting new contributors. 

**Next Actions**

- Work to develop a plan for revitalizing community building and deepening contributor engagement. Draw from the rich advice and community recommendations quoted above.

## 5\. Have Frank Conversations about Technical and Organizational Debt

Technical debt accrues when multiple types of users, contributors, and maintainers interact with a project over time, each making choices that have downstream effects. The same can be said for project organization: Decisions get made at a particular stage of project growth and retain inertia far beyond their utility, slowing down decisions and making organizational change a difficult and time-consuming task.

Understanding the types of users and contributors in the JupyterHub community has been an ongoing challenge. In the early stages of development, many of the users of the project were also code contributors. Yet as the number of JupyterHub deployments grow, there are a large number of administrators who are not contributors. The project could be well served by introspecting and spending time to identify the technical and organizational debt that are vestiges of these past growth stages, focusing first on the vestiges that make contribution, maintenance, and project management difficult. 

Project leadership could, for example, examine what aspects of installation or administration of a JupyterHub were designed during a time when the user base looked completely different than it does today (e.g., Did we design this for all users or for specific academic instructors?). On the organizational side, leaders could examine what choices they made about project delegation and role structure when the team was smaller and/or had closer interactions (e.g., When did we develop the Team Responsibilities page, and is it still sensitive to our project’s needs?) 

These conversations must begin with leadership and be gradually inclusive of the broader community. This top-down approach is not something we often recommend to open source projects; however, as we have explored throughout this report, the complexity of JupyterHub necessitates that people with appropriate historical context lead the discussion and decide which debts are worth absorbing/necessary to absorb and which can be winded down:

> “When you have a complex either language or project like JupyterHub where it isn't necessarily outward facing, the challenge is there's a lot of context that's needed to become effective as a contributor.” (Carol Willing)

Resolving technical and organizational debt will require reimagining the abstractions used to communicate about and work on the project. The project, in other words, has grown beyond the organization’s abilities to manage and maintain clear abstractions that make sense to a sufficient breadth of stakeholders. The most telling way this manifests is that newcomers have a hard time leaning into the the project and understanding its component parts, and team members have a hard time articulating how newcomers could lean in more substantively in a domain of their choice. 

These abstractions are around if you look for them; they simply have not been articulated or discussed. The “Install JupyterHub the Hard Way” effort most clearly (to this research team) articulates some of the subcomponents an aspiring JupyterHub administrator should be concerned with. Finding ways to surface these kinds of resources in ways that give aspiring JupyterHub administrators mental models for the project would be useful to make the project more accessible to newcomers. There is a lot of nested complexity, and therefore a high-level block diagram of the project and its various components and how they interact with each other would pay immediate dividends. Across our interviews, there was a sense that there is no big picture “map” of what JupyterHub is: 

> “I mean, when I put that pull request up, I had this hit, I did ask for help. I was like, ‘I'm not really sure how to integrate this.’ So ideally, someone would have been like, ‘Hey, I have time for a call.’ And they kind of would have walked me through the code base. And, ‘In this part, this is what's happening in that part. That's what's happening. And what you're trying to do kind of fits in here.’ And kind of given me the conceptual overview of that code base.” (Sarah Gibson) 

At the same time, diving into the work of accepting and merging contributions, and how those map to a big-picture release cycle / roadmap could pay significant dividends as well. As the Jupyter Foundation seeks more corporate contributions, administrators of JupyterHubs inside of corporate environments are looking to de-risk updates and new version releases of JupyterHub. Spending some time and effort to develop the project’s poise and goals / milestones here would be helpful and serve the project’s broader goals. 

There is existing work to draw on from community members who are at organizations that depend on JupyterHubs who have built their own processes for their deployments. This has largely been a stop-gap and would benefit from a project-wide conversation with those managing large scale deployments as to the best ways to back-port these capabilities into a community-wide capability. As the project has grown and there have been more and more deployments in diverse environments, it has become even more difficult to imagine the commonalities that could exist. Even 2i2c, with many core contributors, seems to have created a kind of shadow architecture to expediently meet its own needs. Yet none of these existing abstractions from “outside” of the project are reflected back into a reference architecture or implementation guide that is helpful to others deploying JupyterHubs or contributing to the codebase.

What would it look like for JupyterHub development efforts to consolidate around these user and (potential) contributor needs? Between large government agency deployments, statewide higher education deployments, and 2i2c deployments, perhaps there is a missed opportunity to support and engage those who manage these deployments directly. 

**Next Actions** 

- Invite periodic conversations where challenges to the project and community (technical and social) are safe to discuss.  
- Develop a list of the roles in the community, and how community members can become onboarded in them. (See Skills Map in appendix as one way to approach this)  
- Reimagine the ways in which JupyterHub can both invite participation and deepen existing participations as it works through existing technical debt to build updated systems that can meet the community’s strategic goals.

## 6\. Leading the Field: Make Commitments to Diversity and Community Health

All organizations and communities have a responsibility to ensure that both newcomers and existing members feel welcomed, included, and well-treated. JupyterHub has done a commendable job of meeting this responsibility in terms of personal connections and group dynamics, particularly when compared to other similarly-impactful open source software projects. Sustaining this culture, however, is not a given, and requires intentionality. Anecdotally, ensuring inclusion of anyone interested in joining the community gets more difficult over time, especially for high-skill, high-impact communities like JupyterHub. Without sufficient inflow and support for people with diverse backgrounds, communities can fall into a “unicorn trap”: Active leaders and maintainers acquire increasingly specific knowledge and skills about the project that are difficult to communicate, so the job of finding and mentoring new key personnel becomes a search for a non-existent unicorn. Exacerbating this condition is the reality of homophily: A wide range of similarities (e.g., educational background, race/ethnicity, gender identity, hobbies, modes of working, technology preferences) shape closeness of ties between individuals and groups within a social network[^4] (and within organizations, including volunteer organizations[^5]), so we are more likely to form ties with those who are similar. 

[^4]:  See McPherson, M., Smith-Lovin, L., & Cook, J. M. (2001). Birds of a feather: Homophily in social networks. *Annual review of sociology*, *27*(1), 415-444.

[^5]:  See McPherson, J. M., & Smith-Lovin, L. (1987). Homophily in voluntary organizations: Status distance and the composition of face-to-face groups. *American Sociological Review*, 370-379. Contact the authors of this report for additional resources if interested in learning more about this phenomenon.

As pointed out earlier in this report, 1:1 relationships have been a critical avenue for the inflow of new community members to JupyterHub, so it is worth paying attention to how homophily might influence the project’s intellectual, social, cultural, and various other forms of diversity going forward. To be sure, this is not a criticism of the status quo per se–JupyterHub has active, engaged community members *and* de-facto leadership from an astounding variety of backgrounds. But where it may not have been a conscious decision to ensure diversity in the past, it may become necessary to be more intentional about it in the future.

Signs of this future need are already present. In both interviews and at the 2025 Leadership Workshop, community members and leaders alike reported feeling confusion or experiencing gaps in knowledge related to the project’s social and organizational history. Non-technical “benchmarks”–meaning both positive and negative social and organizational events–were known too well to long-tenured members and not enough to relative newcomers:

> “That actually kind of reminds me that there's another challenge is that there's a lot of history that this that I was not… would anyone just, like, tell a new contributor the entire history of the project? To understand the history of why certain things are the way they are, why certain attitudes are the way they are for certain people, and who has been pushed away historically… I think from the DEI perspective, I'm really challenged by figuring out how to approach that. How do I approach the history of all of it? How do I approach making it better in general?” (Martha Cryan) 

\[Name above\]’s explanation brings the practical limitations of sharing project history into sharp relief: Experienced community members have their hands full with technical and non-technical tasks, and each individual experiences an event from a different perspective. Telling complete, nuanced project histories, then, is a somewhat intractable problem. Perhaps more importantly, telling stories of the project’s history can be actively harmful to both the storyteller and the recipient, reactivating uncomfortable or even traumatic experiences without appropriate resources for doing so safely. 

There are no easy solutions to telling the social and organizational history of a project to newcomers. One of the JupyterHub community’s strengths, however, is abstracting away *technical* details that may be counterproductive in favor of explanations that provide maximum benefit to the community of leaders, maintainers, contributors, deployers, and users. Taking a similar approach with the social and organizational history of the project–without sweeping difficult experiences and realities under the rug–may be a good first step. An incomplete but truthful explanation of what newcomers and active members of the community want/need to know about project history is likely to make them feel more comfortable and engaged with the project than having no context at all.

**Next Actions** 

- Consider asking the broader community for their recommendations for making the environment more inclusive and engaging. There are a variety of ways to do this (e.g., via focus groups, workshops, surveys, interviews, requests for feedback and more).   
- Find ways to connect newcomers to project leadership, whether 1:1 or in newcomer community calls/events.   
- Continue discussions around code of conduct enforcement and ways to ensure that people who are in the community are kind and welcoming.   
- Document and share project history in ways that are understandable, at an appropriate and safe level of detail, and useful for both technical and social context.

## 7\. Getting into a Strategic Mindset: Identify and Move Toward Long-term Goals

A key takeaway from the 2025 JupyterHub Leadership Workshop centered around how the articulation of the project’s mission and vision has changed over time. To be sure, this is both normal and healthy: Projects should actively revisit, discuss, and revise statements about goals and values. Through facilitated conversations, however, the core team found that published statements in various places (e.g., on the project website, in documentation) varied quite a bit: Statements had similarities, but often differed in how they explained the project’s target audience and use cases. The project should therefore take the time to align on up-to-date, unified descriptions of what the project intends to do and the impacts it brings to the world.

Strikingly, participants in the interviews and the workshop are fairly aligned on what the mission and vision of the project should be. This reality suggests that revising statements about the *current state of the project* would not be a contentious or time-consuming effort. One or two more facilitated conversations, along with a mechanism for community feedback and input, would enable project leaders to update public-facing and internal documents with unified statements. 

What is slightly more challenging, according to interviewees, is deciding what the future of JupyterHub looks like and setting a strategic direction toward it:

> “So I think, yeah, there is complexity about how we make that trade-off, I mean, good enough so we continue serving the people that we currently serve. And at the same time, bring more people trying to do more exciting, new, shiny stuff. And if we are successful in that trade-off, I think that will, yeah, make the project grow into the future.” (Damián Avila) 

Strategic planning sessions can be useful for reaching consensus on the direction of the project. These sessions can range anywhere from several hours to several days, where participants talk through opportunities and threats to project sustainability (e.g., via SWOT analyses) and how to navigate them. Project leadership should be sure to gather input from the community during the process, either by inviting them into the strategic planning sessions or by surveying them ahead of time.

**Next Actions**

- Hold dedicated discussions about the project’s mission and vision, including how it has changed over time, what it should be at the current moment, and what it might look like in the future.   
- Consider engaging in a strategic planning process, which can be combined with or separated from technical roadmapping activities.   
- Regularly revisit how JupyterHub talks about itself in public-facing communications, adapting language and representations based on what project leadership knows about its contributors, maintainers, users and deployers.

## 8\. Organizational Capacity Building: Making Time and Space for Non-Technical Discussions

The JupyterHub project has, throughout its history, often been in “react” mode–given the small team of maintainers and other personnel, there has not been adequate time to discuss organizational processes and structures. As noted throughout this document, this predicament can create negative feedback loops in which the lack of discussion about organizational development worsens the burdens felt by active contributors and maintainers. While it may seem like a waste of time at first, talking through and acting upon what the project wants its processes to look like (e.g., prioritization and triage) pays dividends in the long run.

JupyterHub should also consider what types of support it needs to improve the codebase, the experiences of contributors and maintainers, and community health. The Jupyter Foundation is relatively new, but it is likely that there will be opportunities to request financial resources to address some of the project’s most pressing issues. To date, JupyterHub has thrived with relatively little funding and support as compared to other projects of its reach and impact; thinking about lightweight ways to attract more resources would aid in taking on some of the challenges identified in this report and in the project’s Issues repository.

These discussions about resources and what they might be used for can be wrapped into other efforts, such as technical roadmapping and strategic planning sessions. It is also possible to hold resource allocation discussions asynchronously to better include a wider swath of the project community. As \[redacted name\] pointed out, members of open source communities who are not able to attend synchronous meetings (e.g., because of timezone differences) often don’t get as much input as they should:

> “where synchronous meetings are expected and a natural part of like, oh, this is your job. Like, we're going to get this together. We're going to meet weekly, whatever it is. That's fine. That's not acceptable for volunteers to impose on volunteers time to be like, oh, you want something through? You got to show up at our time…. And so that's like one of the things that I've explicitly pushed back against synchronous meetings within the project, where it's like, if you want to continue to have participants that aren't, where this isn't their job, you should lean on asynchronous modes of communication, because that gives a chance for people to participate on their own time. Whereas synchronous meetings, though they may be higher bandwidth and allow you to make quicker decision making sort of and consensus building, it's consensus among the people that showed up to the meeting and that have the ability to consistently show up and allocate their time. And that tends to be people who have this as their job and not volunteers.” (Paul Ivanov) 

Whether synchronously or asynchronously, the project community should be consulted in decisions about what resources to pursue and how to use them. Project leadership might consider, for example, posting a to-be-submitted proposal draft for feedback during a comment period. In addition to gathering a more diverse set of ideas, this process makes community members feel as if they had input to resource allocation and therefore more content with outcomes than if funding is acquired and spent without communication. 

**Next Actions**

- Develop ideas for acquiring resources and how to allocate them. Consider a proposal to the Jupyter Foundation as a starting point in these efforts.  
- Ask leadership, contributors, maintainers, and the community what types of new roles or resources would help them be as engaged as possible.  
- Develop a regular cadence for revisiting funding needs, labor needs, resource allocation, and funder reporting.

## 9\. Develop a More Productive Approach to Engaging (and Working With) Users and Deployers of Hubs

JupyterHub is used a wide variety of academic and industry settings, meaning that one group of users and deployers learn things about the software that other groups do not (and that the project team itself may or may not be aware of). Developing processes to engage these users and deployers in a more consistent, productive fashion can help the project grow and sustain itself in a number of ways.

Engaging users and deployers allows them to talk to one another and share insights. This has two main effects. First, users and deployers can naturally develop small communities, such as those already present at UC Berkeley’s DataHub, at NASA, and at consulting organizations like Development Seed. These communities enable users and deployers to help one another when they encounter problems, reducing the burden on the project team to address community concerns:

> “There's opportunities to like enhance the administrative experience of a Jupyter hub. There's nothing that the hub developers need to do to enable me to do that, like to enable me to add those features.” (Ryan Lovett) 

Second, engaging these groups also helps to build a pipeline of potential new contributors and maintainers. Users and deployers become highly-skilled and knowledgeable over time, but both interviews and the 2025 Leadership workshop demonstrated that these groups often do not feel like they are part of the JupyterHub community. Dedicated methods for engaging these groups might aid in addressing some of the labor supply issues facing JupyterHub.

Engagement with users and deployers need not be a burdensome or time-consuming process. Setting up sessions at JupyterCon and inviting these groups, for example, can become a yearly exercise for meeting these groups and facilitating meetings between groups. Collaboration Cafes or quarterly user and deployer-specific calls might also be venues for holding these discussions.

**Next Actions**

- Develop mechanisms for regular (e.g., yearly, quarterly, and/or monthly) engagement with users and deployers, ideally in settings through which groups of users and deployers can meet one another.  
- Conduct a discussion with users/deployers about upgrades and the desire for more regular release dates, specifically.   
- Consider how onboarding processes might change to enable users and deployers to upskill themselves to the level of contributors or maintainers.
