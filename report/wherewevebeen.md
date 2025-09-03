# Where We’ve Been: Celebrating JupyterHub’s Successes and Impact

> *“I think that is probably the thing I'm most proud of with Jupyter, it's not the awards and all of that. It's how many people we've actually touched.” (Carol Willing)* 

> *“Honestly, it's used. It's used. It's amazing. It's used by thousands around the world every day. And it's cloud agnostic and it's open source. And that's just really cool.”  (Kirstie Whitaker)* 

> *“It is about empowering people to use the computer to think interactively about data, about the world around them, about a computational question, about an algorithm, and to do that work openly, collaboratively, and to share the results of their work. And therefore, oh, well, if I want to do that work, but not on my laptop, but on a shared resource, I'm going to need something like JupyterHub.” (Fernando Pérez)*

The survival of an OSS project over a ten-year period is reason enough to celebrate: Few projects garner the support, usage, and development effort necessary to reach maturity, and **JupyterHub’s community should be proud of its continued successes.** Below, we discuss JupyterHub’s impact in two domains–education and scientific research–where the project has delivered access to interactive computing to users of diverse backgrounds. We then celebrate its success in cultivating a community of people who have grown their skills and made contributions to both JupyterHub and to broader computing and scientific communities.  

## Meeting the Project’s Original Goal: Improving Education with JupyterHub

The original team of JupyterHub developers aimed to solve a teaching challenge: People learning to do scientific computing struggled with access to computing resources and installation of software stacks, causing frustration for instructors and disengagement for learners. JupyterHub enabled ad-hoc system administrators–in many cases teaching assistants or instructors–to develop Jupyter Notebook environments that could be accessed and used via web-based interfaces by anyone with a web browser. 

### Reducing Barriers to Teaching Computing

Building on prior work supporting software development in small teams, Min RK and Brian Granger kickstarted work to create a tool that would enable learners to simply log in and have everything they needed to begin interacting with a computing environment, making it easier for them to begin learning essential computing skills. 

A key feature of early JupyterHub deployments enabled Instructors to predefine and install the software requirements for what they were teaching in their courses, reducing the time and cognitive intensity required to get learners set up. As Min explained, what started as a few deployments soon grew into a service that got instructors excited about future possibilities:

> “Initially, it was mostly Brian and myself because people were deploying Jupyter for students … The first big user of it was Jessica Hamrick at Berkeley, teaching classes in computational models of cognition, I think, in psychology … Brian was starting at Cal Poly, as a physics professor, and was teaching programming to engineering undergrads. 

> "And so Brian was working with Jess on NBGrader and exploring these tools of, **‘I have access to computers. I want my students to be able to log in and do stuff.’** Because one of the big challenges, one of the reasons that people want to bring their users to different computers is that it's one way to solve the installation problem, right? You can have a person who's responsible for setting up your environment and the students only need to log in. **And you don't have to deal with installing a scientific Python stack on everybody's laptop, which was another big source of pain in educational environments.** Because students… it was usually a fairly safe assumption that they had access to a computer, but it might be old, it might be Windows, it might be slow. Then, plus, even if there's nothing wrong with their computer, there's lots of ways to get your Python environment all messed up." 

> "And so for the kind of early adopter teachers, in this teaching scientific programming with Python, a huge amount of energy was spent on installation issues. Like, ‘Why is just everything broken on my computer?’ Answering those questions from students. And when you've got one or two or three hundred students, that can be a real pain. It eats a lot of time. \[JupyterHub\] is about being able to have a controlled execution environment… **And so a big motivator for this was serving, hosting environments for students. And I think a lot of instructors got excited.**” (Min RK)

Indeed, as word spread about JupyterHub’s ease of use and time-saving capabilities, other instructors sought their own deployments. Early educational deployments were heavily concentrated in California, owing to much of the early development taking place at the University of California, Berkeley and CalPoly. Today, JupyterHub is used in classroom settings across the globe: Universities and high schools are delivering data science and computing education using JupyterHub deployments, granting access to technical learning in ways that remove long standing barriers:

> “And so what I think is really cool about JupyterHub is seeing universities that are able to deploy their own infrastructure where they make all the decisions about how it operates. It's all running on technology that they have control over, and that **they can expose what feels like a really cool, magical user experience where you just go to a website and you get access to all of this environment.** And they can do that, you know, in a totally self-contained way.” (Chris Holdgraf) 

> “And for them, Jupyter is Jupyter deployed in a way that they can reach students. So yes, it's the notebook, but it's also **JupyterHub running in the cloud so that they can actually teach half of Berkeley, right?** And the fact that it’s not just Berkeley, it's not like we built something that is like ‘the Berkeley platform,’ but it's **completely open to the world**. And that same experience, when I go to Colombia, my former classmates in physics are now running JupyterHubs in Colombia for their students, right? And when Stefan goes to South Africa, he finds the same thing. And when I go to France, they're running a version of Jupyter for high school students. **That makes me very proud because we really did break that barrier to education in modern computation and data for everyone**.” (Fernando Pérez)

> “UC Berkeley, they're using Zero to JupyterHub and they’ve got **16,000 people**–primarily students and faculty, but also staff–using it each semester.” (Shane Knapp)

Given the initial vision of the project, the success of educational deployments became core to JupyterHub’s identity: Leaders and contributors to the project continue to think about the software as a catalyst for access to computing, even as deployments have taken hold in other research and business domains. Pedagogically, having JupyterHub environments available to learners makes it much easier for sharing code, context, and documentation, all of which help to accelerate learning. These common environments, accessible via web browsers from anywhere in the world, are a great democratizer in the scientific computing landscape. 

Carol Willing explained that JupyterHub lowers barriers to access for learners from a wide range of socioeconomic backgrounds. A JupyterHub environment can give access to computational resources (CPU, RAM, GPUs, storage) that might not be available to a learner or researcher on their laptop or at their institution. In this way, JupyterHub acts as a gateway to resources and enables multi-user computing environments that have lower barriers to entry:

> “Expanding access to education materials to everyone. Enables everyone to have a Jupyter notebook regardless of the system they have \- **it evens the playing field: wealthiest students at the same level of someone with a Chromebook.**”  (Carol Willing)

Just as JupyterHub helps democratize access to computing resources, it also lowers the barrier to computing skills for learners and researchers whose home disciplines are not traditionally computing-centric. Rick Wagner, Chief Technology Officer at the San Diego Supercomputer Center and board member for the Jupyter Foundation, pointed out that JupyterHubs are being deployed far beyond data science and computer science education settings; they are also being deployed in domain science education. JupyterHub gives professors the ability to prepare computational environments with pre-installed tools and pre-prepared notebooks that can guide learners in their exploration of computing, data analysis, visualization as part of an interactive pedagogy for sciences of all kinds: 

> “A growing number of researchers and a growing number of professionals, I'll say, are aware of Jupyter. That's largely because it's become a platform for teaching and training. I know that even here in the psychology department, students that want to get a … Bachelor's of Science have to take basically a ‘how to program for research’ type of class. So they use Jupyter and they use JupyterHub. … **which is amazing because it's just saying like, even folks that may end up becoming therapists or psychiatrists or something like that have used Jupyter.**”  (Rick Wagner)

Similarly, Rainere Silva drew attention to JupyterHub’s ability to scale compute environments to hundreds or thousands of users with clear isolation and varied configurations, thus enabling new ways of teaching and supporting learners:

> “I remember lots of promotions of the massive course that UC Berkeley did run. So having hundreds of students with all the teaching material and computation environment pre-configured on the university cloud computing environment should run **without any student being left behind because of different configurations.**” (Raniere Silva) 

Going forward, JupyterHub’s impact on education appears poised to expand even further via an increasing number of deployments to a broader range of learners. Shane Knapp, who previously managed JupyterHub educational deployments at UC Berkeley, described the emergent [CAL-ICOR](https://cal-icor.org/) initiative. This initiative aims to bring JupyterHub deployments and support to colleges and universities across the state of California, including under-resourced community colleges:

> “Cal-sponsored and California Learning Lab-sponsored JupyterHubs for UCs, Cal States, and California Community Colleges **that can't afford a tech team.** So we're actually going to start hosting users this summer with some summer classes as our test, and then we'll have probably at least a couple thousand users across a few different hubs in the fall.” (Shane Knapp)

### Enabling “Centralized Decentralization”

Initiatives like CAL-ICOR demonstrate a key strength of the JupyterHub project: a unique balance between centralization and decentralization. On one hand, CAL-ICOR is somewhat centralized, with the initiative offering support to institutions in getting learners and researchers set up to begin working with the tool. On the other hand, participating institutions can adopt and adapt the tool to match their needs and institutional realities. As Chris Holdgraf explained, this flexibility is an example of “centralized decentralization,’ enabling communities to decide how independent or interactive they’d like to be with the broader JupyterHub ecosystem:

> “I'm a big fan of what I call ‘centralized decentralization,’ in the sense that you need some centralization, right? Otherwise, it's ‘everybody's responsible for everything.’ And nobody's got the time, not everybody needs to become their own cloud infrastructure expert. **But you also don't want to just rely on the Googles and the Facebooks and the Microsofts out there. So this is a way of giving communities more control over how much they want to centralize.** Do they want to do it at the team level, at the department level, at the university level? They have a lot of fluidity there. People can belong to multiple hubs at the same time. And so seeing the impact that that has had at a systemic level in the university world, has been really cool.” (Chris Holdgraf)

In this way, the JupyterHub project demonstrates a principled approach to expanding access to computing. Users are free to deploy in any way that suits their goals, but can learn from other deployments and depend upon support from the project’s core team of maintainers and contributors. Over time, we might expect these deployers to learn and innovate in ways that will be generative for the JupyterHub project going forward.

## Catalyzing Scientific Innovation: JupyterHub’s Impact on Research

> “Well, to me, the role of Jupyter is to help the humans think about the world with computing and data resources wherever they are.” (Fernando Pérez)

> “The research that people can do, and the things that they can write and produce with those notebooks … it's mind-blowing.” (Georgiana Dolocan) 

JupyterHub’s early developers realized that scientific research teams at institutions deploying the tool for learners experience many of the same pain points as university students and instructors. The team therefore made a gradual, concerted effort to bring its tools and resources to small labs and large scientific collaborations.

### Providing a New Way to Innovate and Collaborate

In some ways, JupyterHub and scientists was a natural pairing, and one that the founding team always believed could be transformative: Scientists who rely on computational methods require tools that enable them to collaborate beyond their personal computers and integrated development environments. They need to share their code and visualizations within and outside of their teams, quickly iterate on and visualize results, share/allocate computing resources, and otherwise develop flexible approaches to doing science. 

Existing methods such as using SSH did not accommodate multi-user collaboration in efficient ways, prompting the early team to try bridging the gap:

> “So I come from physics, so does Fernando, so does Brian, where we're very used to the scientific computing world. And we have all these nice interactive visual tools. And then you SSH to a computing cluster, **and you're confined to the terminal, and you can't do anything.** You have to use a totally different tool set, totally different workflow, and it's **a lot more tedious.** But people started, in the situations where it was allowed… if you tunnel a port, you only need to forward one port from your computer to the machine. And so your standard SSH tooling, like log into the machine and then I can start a Notebook and then I can open my browser and everything's the same as if it were running locally. 

> And so that was really attractive for getting a nice visual, you know, more friendly for a lot more users’ environment for remote computing, whether it's on clusters or the cloud, which was increasingly used, or just like a workstation at your desk, like I used it. I had a big computer at my desk at work. And then I had my laptop that wasn't as powerful. So I could run simulations and things in a notebook that I spun up the browser on my laptop at home. And I could start to look at things on my big machine at my desk without having to be sitting at it … And we saw people were already doing this with SSH tunnels and various kind of shenanigans. And so building a tool that did exactly that, right? There were a lot of ideas at the time of building like a multi-user Jupyter server, like a single server that actually has the notion of different users … And so when a user logs in, they get their server. And it's theirs. When they run code, it's as them. When somebody else logs in, they get their own server, and they run code as them. **And in the beginning, the whole point was to keep those separate from each other. There was no idea of collaboration or sharing or anything like that.**” (Min RK)

JupyterHub, as is now evident in its wide range of scientific use cases, successfully solved this problem. The tool serves a critical role in catalyzing and enabling this type of collaboration and innovation, with uptake across disciplines ranging from geosciences to biosciences to astronomy. Organizations that deploy JupyterHub at scale include, but are not limited to: 

* **Research universities and colleges**: University of California, Berkeley; University of California, San Diego; Cal Poly; Harvard University; University of Chicago; University of Oslo; University of Sheffield; Université Paris Sud; University of Versailles; University of Portland  
* **Research laboratories**: NASA; NCAR; NOAA; the Large Synoptic Survey Telescope; Brookhaven National Lab; Minnesota Supercomputing Institute; ALCF; CERN; Lawrence Livermore National Laboratory; HUNT  
* **Online communities**: Pangeo; Quantopian; mybinder.org; MathHub; Open Humans  
* **Computing infrastructure providers**: NERSC; San Diego Supercomputing Center; Compute Canada  
* **Companies**: Capital One; SANDVIK code; Globus; Apple; Google; Snowflake; Bloomberg; Data Bricks  
* **Public authorities**: Skatteverket (Sweden), Finansinspektionen (Sweden)  
  ([Source: JupyterHub Docs](https://jupyterhub.readthedocs.io/en/latest/faq/institutional-faq.html), consultant interviews, consultant observations)

The wide range of applications illustrates JupyterHub’s utility. But when open source tools are deployed across multiple disciplines, industries, and settings, we often see consternation among at least some of these groups about shortcomings in solving context-specific challenges. According to members of the JupyterHub community, however, interactions with scientists who use JupyterHub have largely been positive. Perceptions and evaluations of the tool reflect an appreciation for how it enables faster, higher-quality scientific research. JupyterHub community members in turn appreciate being able to contribute to high-stakes research endeavors: 

> “I think they generally have a positive impression of JupyterHub's capabilities, how it should be used. I know on the researcher side, it would be generally very positive.” (Rick Wagner)

> “One of the stronger memories I have is, at some JupyterCon or somewhere, the IPCC \[Intergovernmental Panel on Climate Change\] people were using a MyBinder link to demonstrate some of their stuff.” (Yuvi Panda) 

### Reducing Computing Costs

The sustained deployment of JupyterHub across these various domains is in some ways surprising. JupyterHub was among the first tools to enable distributed, efficient collaboration in scientific computing, but in recent years, JupyterHub is not without “competitors”: Proprietary software and computing systems offer similar utility, particularly for enterprise applications. One key way in which JupyterHub has sustained its presence in a wide range of contexts is cost. As Yuvi Panda pointed out, JupyterHub delivers value to users that would otherwise be quite expensive, particularly at scale:

> “I remember talking to the Azure Notebooks people and I realized that **the JupyterHub I was running for UC Berkeley for a fraction of the cost that they were spending, was so much bigger than the entire Azure Notebooks customer base.** And somehow that felt fulfilling as well.” (Yuvi Panda) 

JupyterHub’s impact on scientific work is also evident in the demand for services related to setting up, deploying, and supporting hubs at major scientific innovation centers, including those that may not have the same resources as major enterprises. Tarashish Mishra, a software engineer with Development Seed, spoke about his work assisting scientific organizations in developing cloud infrastructure using JupyterHub. A JupyterHub contributor himself, Tarashish enjoys helping these organizations make the most out of open source tools and contributing to a project that is advancing scientific research: 

> “I'm lucky to have an employer, a job that lets me work on JupyterHub as part of my day job. So we work with a bunch of teams within NASA that deploy their own JupyterHub instance, in collaboration with 2i2c, of course. And they all have this common problem where they need a lot of storage for their users.  **And the general solution was to use something offered by Amazon, which is kind of pricey, also doesn't let you kind of limit the amount of storage that users get. This is a common problem that all the hubs that run for NASA had and I got involved trying to solve this problem.**” (Tarashish Mishra) 

### Generalizing OSS’s Scientific Impact

Tarashish noted that doing this kind of work to enable better science within major research centers has positive knock-on effects for the rest of the scientific community, owing to the project being open source:

> “Working with Yuvi and Sarah from 2i2c on a solution that we can use to solve this specific problem for our users at NASA, **but can also kind of generalize it to solve this specific problem for other users of JupyterHub and the broader community.** I think a lot of the credit here goes to the folks at NASA Impact, who kind of manage the scope of the funding they have, where to spend them, and they spend that on JupyterHub, on solutions that can cater to the broader community in addition to their own problems.” (Tarashish Mishra)

Participating in these efforts to solve specific, interesting research challenges while benefiting a broader community has been a source of fulfillment for Tarashish and other community members. We repeatedly heard some version of “I value contributing to something that helps solve interesting, important challenges” in our interviews–perhaps a motivation of most open source software contributors, but one that helps sustain JupyterHub nonetheless:

> “Just contributing to a project like JupyterHub, which is so widely used, is also satisfying in a sense.” (Tarashish Mishra) 

> “If I'm doing this voluntarily, most of the time, if I'm going to do anything substantive, it's going to be something that I think is interesting.” (Simon Li) 

### Making Scientific Computing Skills More Accessible

Beyond utility, cost, and contributions to important research endeavors, JupyterHub community members also valued the tool’s ability to make scientific computing more accessible and inclusive. Computational science can be an intimidating and challenging undertaking, particularly for those who are domain scientists first and computational scientists second (or third or fourth). The JupyterHub project and Jupyter in general offer various avenues for working with the tools and making open source contributions even if writing code is not a scientist’s strongest skill. Likewise, JupyterHub makes transitions from older systems and workflows to newer processes easier to manage for experienced scientists:

> “Most of the users are fairly familiar with the Jupyter interface, \[but\] they don't really know a lot about the hub. They just care that they can log in and get the Jupyter interface. So some of the users are kind of migrating from an existing system to JupyterHub. We try to give them the same functionalities they had with the earlier systems, which often kind of vary a bit. So that is mostly about storage, having a shared storage between different groups of people and stuff like that. So those vary a little, \[and\] users are often confused initially, but after like a training or two, they're comfortable. I think the main pain point I have seen in terms of JupyterHub usage is the story of sharing notebooks, and sharing their work with other users is not that great. So people do get confused there. Like, ‘I have a notebook, how do I share it with someone who doesn't have access to this particular closed hub that I'm on?’ So that's something people get confused by a lot. Yeah, **so having services that are open to the public helps a lot there … where you can just send a link and anyone can access the same notebook and just run it.**” (Tarashish Mishra)

In addition to making scientific computing more approachable, JupyterHub has also made commitments to ensuring that non-code contributions are welcomed and valued in the community.[^1] As Rick Wagner explained, the orientation toward non-code contributions and usage is a cultural pillar of the project that makes JupyterHub a more inclusive community than others:

[^1]:  This report also argues that these efforts to value non-code contributions can be improved; see the recommendations section for more detail.

> “The community, you know, and then this goes back to Fernando setting the bar and then everyone else aligning with him, fortunately is very inclusive, very supportive of contributions in a lot of different ways. **Not everything is about code, even though we know that's fundamental. Without that attitude, I don't think Jupyter as a whole would have succeeded as far if it was all strictly about the code.**” (Rick Wagner)

JupyterHub’s commitment to supporting science has had major, fundamental impacts on human knowledge creation. This holds true at every scale, from undergraduates working on their first research project to Nobel Prize-winning scientific endeavors. JupyterHub serves as critical infrastructure for personal, learning-oriented breakthroughs as well as for societal-level scientific innovation:

> “And at the same time, what I see in research when the 2017 Nobel Prize in Physics was awarded, it was for the discovery of gravitational waves, right? That was the LIGO collaboration. The first figure of that big paper is six panels made with scientific Python, with NumPy, with matplotlib. The color map in the bottom two ones of the spectrogram is [Viridis](https://how2matplotlib.com/viridis-colormap.html).  The LIGO collaboration put out all of the coding data in Jupyter notebooks from day one, Min made a binder out of it.” (Fernando Pérez)

As we note in the recommendations section, JupyterHub’s leadership and community members have demonstrated humility in communicating these contributions to modern science. Humility is admirable, but the project may benefit from championing and marketing its accomplishments to a broader audience: Being part of something so impactful is undoubtedly attractive to potential newcomers and makes requests for funding and other resources easier to justify.

> “I could see how much people enjoyed Jupyter as their front end experience over using something like SSH for terminal access to HPC.And so we deployed JupyterHub on top of our Slurm cluster And just using JupyterHub in that way really helped the user. It really satisfied a need that I don't think users knew that they had. So learning how to do that, it kind of It just made things easier.” (Ryan) 

## The People Behind JupyterHub’s Success: Culture of Sustaining Impact

> *“For me, open source and open science has always been about participation, not about access.” (Fernando Pérez)* 

> *“So I think, you know, the other thing that JupyterHub has done… Early on, we made a conscious decision to try and be inclusive and not just say it, but actually do something about it.” (Carol Willing)*

The above accomplishments and continued impacts depend upon a committed, small team of contributors and maintainers. As noted earlier, we asked the JupyterHub community what kept them engaged and active on the project. Almost universally, respondents mentioned the fulfillment they felt in contributing to improvements in education and research. These improvements span nearly every field, as is reflected in the makeup of the JupyterHub community: Our interviewees included people with backgrounds in physics, psychology, computer science, neuroscience, electrical engineering, astrophysics, biochemistry, archaeology, mathematics, and photography, and the broader community is even more diverse than this subset.

This interdisciplinary group of people is brought together by its desire to bridge across research and education disciplines, focusing on building structures and environments that bring access to interactive computing to more people in more places. Keeping the momentum going, however, depends upon sustaining the welcoming and inclusive culture regardless of disciplinary differences or variations in skills. 

### JupyterHub’s Welcoming Culture

Interviewees spoke positively about the general culture of collegiality and welcoming in the JupyterHub community. Georgiana Dolocan, who began her JupyterHub involvement via an Outreachy internship, picked up on this culture right away when interacting with members of the community:

> “So there was that contribution period \[during the internship\], which I think was awesome. People were very welcoming. I was just like, ‘What's this new world?’ It was my first interaction with open source.” (Georgiana Dolocan)   

The broader Jupyter ecosystem has also benefited from JupyterHub’s attention to fostering a welcoming and inclusive environment. Specifically, leaders of the Jupyter ecosystem noted that the JupyterHub project pays attention to aspects of project health that other Jupyter subprojects and non-Jupyter open source projects often neglect. Thinking about and developing governance structures, for example, helps community members understand where they might fit in the project (see the recommendations section for ideas for further improvement). As Fernando explained, speaking about and implementing these often-underdeveloped components of a healthy project facilitates a “positive tone”:

> “All of the actual work of really growing, that was done by them: by Min, by Chris, by Yuvi, by many others. We kind of set, hopefully, a positive tone within Jupyter of trying to think about governance, of trying to think about community participation, of trying to think about a culture of being open and welcoming to others. But that team really put it in practice in a very thoughtful and deliberate way. And I think that has been impressive. And in fact, I would say today, **the rest of the Jupyter community learns a lot and benefits a lot from some of the practices and activities and example that the JupyterHub team kind of sets**.” (Fernando Pérez) 

Still, Project Jupyter should do more to learn from JupyterHub’s culture. In our interviews and other conversations, we found that at least one distinguished member of the Jupyter community experienced Project Jupyter to be a toxic environment in which individuals can feel excluded, pushed out, and mistreated through both public and private interactions. The community member has, as a result, withdrawn much of their effort from other Jupyter subprojects while remaining active in the JupyterHub community. Understanding why JupyterHub is a relatively safe space when compared to Project Jupyter or other open source projects should be a goal for JupyterHub’s community so that it can sustain and build upon the conditions and actions that keep it inclusive. We offer some insights into those reasons below.

JupyterHub’s positive culture is perhaps most evident in how interviewees spoke about their relationships to their peers and how those relationships have been beneficial both personally and for the project. These anecdotes about relationship-building spanned all sorts of career stages and backgrounds: Early-career folks described the benefits they derived from working with experienced developers and leaders, advanced contributors enjoyed having peers who shared similar values and work practices, and leaders appreciated opportunities to receive mentorship from others who had led open source projects.

Certain members of the JupyterHub community appear to provide (or have provided in the past) social “glue” that moved the project along at key moments in its development and in the development of individuals’ careers. Sarah Gibson, one of the earliest developers of JupyterHub (and its related project, Binder), described how Tim Head came to her in a time of career transition to take on a leadership role in the growing project:

> “And then at the end of my paid time on the Turing Way, which was probably only about nine months or so, I said to the team, ‘Been lovely to work with you all, but my paid time is over now, so I'll probably be around a bit less.’ And that was the time when Tim messaged me and said, **‘Well, if you're not gonna be working on like little Binders anymore, how about running the biggest Binder in the world?’** Which was when I got the keys to the castle for mybinder.org.” (Sarah Gibson)

Carol Willing, a longtime contributor to the broader open source software world, is another good example of a “social glue” figure in the project’s development. Carol’s attention to the ideas and challenges of JupyterHub’s early contributors offered support for the project getting off the ground and in ensuring that the culture remained positive:

> “When I started seven, eight years ago, then it was in a Gitter chatroom and I mean, I had a very welcoming spirit and people were like, ‘Oh, Look at what Erik did, amazing job,’ et cetera. I can recall maybe Carol Willing and Chris Holdgraf and Yuvi Panda perhaps saying in that chatroom and **that boosted my mental morale and engagement and interest in contributing in general.**” (Erik Sundell)

> “**Carol was very aware, you know, of what assholes look like, or rather what asshole behavior looks like,** and how you need to… you can't fix it after the fact, right, like you need to be like, ‘Well we don't do that here,’ and all of that from the very start, or it's not going to go well.” (Yuvi Panda)

> “I remember interacting with Carol with Tim and other people there. I was like, ‘The people here are so nice,’ and they were using lots of hearts emojis and I just love this … **And I felt that people were very, very welcoming and supporting. And they were answering the questions in such a way that I felt encouraged to continue** rather than feeling just like, ‘Oh, I shouldn't have asked this,’ or feeling bad that I don't know something.” (Georgiana Dolocan) 

Carol’s attention to relationship-building and a positive environment is also illustrated by interviewees mentioning her as the driver behind some of the project’s key personnel management and communication improvements. It was her suggestion, for example, to begin developing a Team Compass–a centralized place for identifying team members and their roles, describing work practices and norms, sharing resources, and documenting project policies and governance:

> “We have a Team Compass that defines the organizational policies and the organizational structures in a more explicit way. That was an intentional outcome of those early days on the project. Initially, the idea of Team Compasses came from Carol Willing, who's another collaborator on the JupyterHub project. She's also been in the Jupyter ecosystem writ large. She's what I would call a first-generation Jupyterian. **But, you know, it was the idea that we need to have more structure as an organization to help define these pathways, define the roles, things like that**. So the team compass was a big part of that.” (Chris Holdgraf)

Like any other organization or group, JupyterHub is not perfect. Challenges and conflicts have arisen in the past and will continue to arise in the normal course of everyday work. But the efforts of early leaders to be conscious of building a positive culture has helped the project retain key contributors and leaders for over a decade–a feat worth celebrating. 

> “And everyone that I met that was on the JupyterHub side was... the best way I can articulate it is that they were kind of trustworthy. I felt there was an almost directness to a lot of them.” (Martha Cryan) 

### Newcomer Engagement with Leadership

As OSS projects grow, leaders often lose contact with newcomers and generally lose sight of the importance of the onboarding process. The reasons for this lack of attention to the newcomer experience are largely practical: Leaders get busy, and newcomer volume, remoteness, and activity patterns mean that leaders cannot get to know every person who works on a project. Yet JupyterHub leaders have, according to interviewees, done a good job of getting to know newcomers and staying in touch with them during their formative early experiences. 

Prolonged, one-to-one engagement between newcomers and project leadership has been a key component of this newcomer experience. Several interviewees noted that their “beginner” experience in the JupyterHub community benefited from this relationship-building:

> “I went to SciPy. I got to meet Fernando, which was actually a really lovely story because I was like nobody. I think this was 2014 or whatever. And, you know, it's a whole room of mostly men or maybe all men, I don't know, but maybe like 40 people. And at some point, Fernando, who was sort of leading the discussion, was like, ‘Oh, what do you think?’ **And it was just so gracious that, and as a woman in science or tech, oftentimes that doesn't happen. So it really had a nice impact on me and we got chatting about how I was using the notebook.** And that was about the same time Jupyter got their $6 million big grant. So they asked me at some point in that, would I work at Cal Poly on the grant? And so I did, which was fantastic.” (Carol Willing) 

At the abstract level, this process has happened many times throughout JupyterHub’s history. A leader meets a (potential) new community member at a conference, event, or workshop, discusses what the project was building, and invites the newcomer to join the effort. Interviewees who had this experience noted that the conversations continued after these events and developed into a close working relationship, often centered around a particular domain of software development.

Beyond making newcomers feel welcome, direct engagement with leadership also played a role in enabling community members to feel as if they could progress toward advanced contributions and leadership positions themselves:

> “This is where, you know, the privilege of living in the Bay Area comes into the picture because Wikimedia has an office in San Francisco. And Fernando was invited to the Christmas party, because he's just around here and he is very generous with his time, sometimes to a fault. So he says yes to everyone. So he was there at the party and then we were able to talk, and then he mentioned, ‘Oh yeah, there's a bunch of us at Berkeley. If you want to just come say hi, you should do that.’ I was like, ‘Yes, I will come say hi.’ **And then that just kept escalating to the point where I was spending three days a week at UC Berkeley. And then eventually I was just running their infrastructure,** because you know, I had all that expertise \[from working on large-scale deployments at Wikimedia\].” (Yuvi Panda)

While this form of engagement from leadership is perhaps not scalable in that leaders cannot devote equal time to every new community member, it is worth thinking about how JupyterHub can build structures to support similar experiences for all newcomers. Ideas might include:

* Monthly or quarterly meet-and-greet sessions for newcomers, attended by all or some of the JupyterHub leadership team  
* Leadership office hours, where one or more newcomers can meet leadership and discuss ideas or experiences  
* Leadership welcome messages to newcomers in various forums (e.g., Discourse or Zulip)

### JupyterHub as a Launch Point: Impact on Community Member Careers

Stories of newcomers building relationships with project leaders and core team members, building skills, and becoming leaders within the Jupyter ecosystem are encouraging signs that community pathways are available and traversable. Additionally, one focus of our inquiry was to understand how working in the JupyterHub project impacts community members beyond the project’s boundaries: What do they gain from their involvement in terms of their careers? We found that working with the JupyterHub ecosystem has a positive, advancement-enabling impact on the careers of contributors and helps them to grow as software developers. 

This form of practical, on-the-job skill-building enabled project members to take on increasingly complex work and tackle new problems facing the project. One interviewee, for example, noted that exposure to an increasing variety of deployment types–in educational settings, in academic labs, and in federal government and private industry research contexts–prompted new skill development because the needs of the users in these settings demanded changes to the software. Likewise, JupyterHub community members actively stay on top of innovations in the software space to facilitate the growth of the project, which benefits their personal careers in substantial ways:

> “I think the other benefit has been, it has sort of kept me on the forefront of technology in many ways, at least, you know, when we moved over to Kubernetes, it was very early days with Kubernetes. **So it gave me the foundational knowledge that I then needed when I went and worked at a startup and became their VP of engineering.** You know, we were offering a SaaS product. So I was familiar with the ecosystem and the terms and the, you know, where the gotchas were.” (Carol Willing) 

Skills are valuable to one’s career, but they are less impactful when they are not attached to certification or concrete experience. Several interviewees noted that their involvement in the JupyterHub project acted as a credential in their careers and opened up opportunities that they may not have otherwise enjoyed. Georgiana, for example, noted how her Outreachy internship served as a pathway into the technology field. Coming from a background where such opportunities are hard to access, participation in the JupyterHub community provided a foot in the door. She is now employed by 2i2c, a nonprofit that provides stewardship in developing interactive computing systems (largely running on JupyterHub) for research and education: 

> “I joined via an internship through Outreachy, which is a program that supports people in underrepresented groups in tech to join projects. And to be honest, I wasn't like a Jupyter power user before any of this. I saw the project. I had some relevant background. The project was about implementing some form of proxy and I had done this before in a prior internship. And I said, ‘Why not give it a go?’ … While I was doing the contribution period and interacting with the community, **I got so hooked.** I actually didn't try another project. I had it in mind to try other projects, but **I was just so convinced that I wanted that internship and to get involved so much. I just poured all my efforts into JupyterHub only**.” (Georgiana Dolocan) 

Participation in JupyterHub was an empowering experience for Georgiana, particularly in how her work translated directly into impact for the broader community:

> “All the things that we had to do in JupyterHub were things that the community was actually going to use if they got merged. **And I felt the importance of the work that I was supposed to do, even in the contribution period. I felt it would have meaning**.” (Georgiana Dolocan) 

Similarly, Damián Avila, a former employee of 2i2c and a contributor to JupyterHub explained his reasons for contributing to JupyterHub in terms of the impact that he could make. 

> “I like to participate in the open source arena because I think that is a way to be transformative and have an impact on other people's lives. So that is my driving force to actually join all these projects. And JupyterHub particularly has been super impactful, and to be able to further the impact on others' lives. I was able to help provide the infrastructure for people in different areas to actually do research analysis and have essentially decisions on top of those analyses that somehow impacted their lives, their environment, their community.” (Damián Avila) 

Likewise, Sarah Gibson, Rick Wagner, and Tim Head noted that the reputational benefits to participating in the JupyterHub community helped them and their peers become notable figures and establish credibility in the open source and technology communities more broadly:

> “There is a certain amount of social capital I get as well in the open source community. You know, having my name attached to a Jupyter project.” (Sarah Gibson) 

> “I've had this opportunity to cover the security topic for primarily the National Science Foundation research community and centers and using JupyterHub as one of the framing devices. It is very focused on a JupyterHub deployment, but it's Jupyter so complex that JupyterHub itself, like here, here's a model, I can draw you some lines and boxes that this is how this component talks to this component. You can run it in different places. **And by doing that, it helped to establish my credibility as somebody that is not just \- I'm one of those classic folks. I'm an astrophysicist by training. I'm currently working as a Chief Technology Officer, but I've got this interest in security. So like a lot of folks you talk to, we find different lanes over time to work in. And the opportunity to be one of the few people that have basically collected this disparate information into a reasonably cohesive whole to talk about security in Jupyter.**” (Rick Wagner) 

> “Working on the open source project gets your name out there.” (Tim Head) 

Similarly, Raniere noted how his trajectory toward his current career as a Research Software Engineer began with a small interaction with the Binder/JupyterHub project at a workshop held by Sarah Gibson. His contributions signaled growing expertise and credibility in his domain of engineering: 

> “Attending the one day workshop that Sarah Gibson led like many years ago and having \[to\] submit a small pull request, like the Binder Hub interface should change types or something, I think, **contributed to me being hired for the position that I have at the moment**.” (Raniere Silva) 

Martha Cryan had a similar career-advancing experience when presenting with Damián Avila at a conference. Martha was, at the time, looking for employment, and Damián's on-stage endorsement added credibility to her already-impressive track record of being a high-quality job candidate in the software development field: 

> “At the end of the talk, he \[Damian\] was like, by the way, Martha's awesome and you should hire her… That was when I walked off stage and like three different startups had already emailed me. And like, that was how I got a job actually like was literally just because he said that.” (Martha Cryan)

Project leadership recognizes and is proud of this feature of JupyterHub participation. Although turnover can be difficult to manage, seeing maintainers and contributors take on new jobs and roles is a gratifying experience and one that serves the purpose of attracting more people into the project:

> “And certainly being able to attach the Jupyter brands to yourself is, I think, useful as a part of your own career advancement. **So seeing ways in which we've been able to allow maintainers to leverage the Jupyter project for their personal advancement is a really important part of open source, and it's a part of the value that we need to be delivering to maintainers and contributors.** And so seeing a few success stories of that has been really gratifying.” (Chris Holdgraf) 

> “I mean, to me, that's one of the beauties of open source is that it gives us a pathway for people to gain a level of, however you want to define it in the abstract, **a level of status in society that for people who aren't from fancy universities in the US, is virtually unattainable in any other way, right?**” (Chris Holdgraf) 

Indeed, involvement in open source projects is often an avenue through which individuals can gain the skills needed to pursue and advance careers at a faster pace and work on projects they enjoy. The JupyterHub community is the exemplar of these types of stories. Project members past and present work in fascinating and diverse fields as their primary form of employment, often as leaders of their companies or disciplines:  

* Academic careers, including faculty and staff positions  
* Non-profit careers, including opens source software organizations  
* Careers at major, well-known tech companies    
* Careers as small business owners  
* Scientific innovation center careers

As we point out in the recommendations section, highlighting the career paths that JupyterHub community members have traversed during and after their involvement in the project is perhaps one way to encourage more contributions and engagement. These stories are known by those inside of the project, but they haven’t been tools in ways that could attract others to see themselves and their own potential growth in the context of JupyterHub. Likewise, as JupyterHub explores increasingly diverse deployments and use cases, it is likely that individuals who work in these diverse areas will see new opportunities to create impact in those fields using JupyterHub’s capabilities.
