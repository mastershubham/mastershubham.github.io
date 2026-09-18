+++
title = "Bill Thies' Talk"
date = 2026-09-07
draft = false
summary = "Lessons for technologists trying to improve quality of life for the poorest billions."
math = true
categories = ["Computing", "Global Development"]
tags = ["Direct Social Impact", "Digital Technologies", "ICTD", "Public Health"]
+++

> _AI usage disclosure_: No AI was used for writing this article. Use of em-dashes are deliberate and at the discretion of the author.

{{% annotate side="right" note="Bill's exposure through education was to Maths + CS + Econ, then to Biology and further to Systems." %}}
As part of the [ICTD Course](https://act4d.iitd.ac.in/ictd-2026/index.html) at IIT Delhi, [Prof. Aadi](https://www.cse.iitd.ac.in/~aseth/act4d-website/aseth.html) had invited [Bill Thies](https://billthies.net/) to give a talk on his work in the field of ICTD and the lessons learnt. Bill has worked extensively in the area of ICTD and developed solutions that have helped people in India. After his PhD at MIT (2009), he came to work at Microsoft Research, Bangalore which was quite a new lab (having been set up in 2005). There he worked on solving some of the problems related to public health, education, and other direct social impact domains by using technologies, and finally working on problems related to scaling them. He later co-founded [Everwell](https://www.everwell.org/), which is a digital solutions provider and a software company based in Bangalore, aimed at solving problems related to public health.
{{% /annotate %}}


#### 99DOTS: A frugal approach to supporting treatment adherence

Bill introduced us to the [99DOTS](https://www.everwell.org/99dots), a digital adherence technology built by him and his team that helps patients adhere to TB (Tuberculosis) medicine prescription. To each pill there is an associated phone number that the patient has to call, confirming their intake of the medicine. If they are not taking medicine, then a local healthcare provider approaches them to remind them of their medication. This method also helps track the consumption of TB medicines by a population group and thus also helps in planning the logistics around it. 

After enough trial and error and getting all the stakeholders involved, Bill and his team have been able to make this program adopted by the government of India (GoI) at a national scale. The initiative of government is known as Ni-Kshay and Everwell labs had a role to play in setting up the digital infrastructure to make the other schemes under National Tuberculosis Elimination Program (NTEP) such as [Direct Benefit Transfer (DBT)](https://en.wikipedia.org/wiki/Nikshay_Poshan_Yojana) to patients having TB, etc. possible. 

This paves a good blueprint for other technologies aimed at direct social impact to gain scalability and sustenance. Quite a lot of novel causes do not see the light of national or global adoption and thus the way of solving problems related to education, public health, poverty, etc. remain still primitive. 

#### Technology amplifies human intent and capacity. It does not substitute for them.

{{% annotate side="right" note="Kentaro Toyama is also a pioneer in ICTD and he helped setup the Technologies for Emerging Markets Research Group at Microsoft Research, India. Also [he was advisor of Bill at MSR India](https://blogs.microsoft.com/blog/2012/12/03/microsoft-research-india-the-faces-behind-the-fight-against-tb/)." %}}
Bill also cited the _[Kentaro Toyama](https://en.wikipedia.org/wiki/Kentaro_Toyama)\'s Law of Amplification_.  After having enough experience overseeing projects related to solving problems like poverty, healthcare, education, etc. with use of technology, Kentaro Toyama came to the conclusion that simply providing or scaling technology would not solve these problems. What is required is [institutional and human intent, human capacity building](https://drive.google.com/file/d/1UfpgQPt4dP8v-aM4WFqjkyZYZ3G8Jn4q/view?usp=sharing), etc. which is difficult and often the overlooked thing by the development organizations and bureaucrats. Technology in his view, only amplified the underlying social forces and thus sometimes exacerbated the deep entrenched inequality in the society.   
{{% /annotate %}}


#### Another Problem Discovery: Logistical Burden on Doctors 

Why did Bill and his team choose to solve some aspect of the problem related to eradicating tuberculosis? It is because at that time (and even today) [tuberculosis had killed more than any other infectious disease in the history](https://drive.google.com/file/d/1psuV5chh97XiPxV0u_LUomH6urAVv2rG/view?usp=sharing). This was despite the fact that the treatment and vaccine for tuberculosis has long been identified and is mature. It goes on to show that the mere existence of the solution does not mean that its benefits are getting translated in improving society — one has to ensure that logistical problems related to large scale procurement, tracking of the disease and distribution of the medicine and care are also solved. 
 
The mention of tuberculosis and how it is being dealt with led me to share another story and question that I had personally felt. I shared the story and question with Bill and the class. Here is slighly elaborated version of the story.

At the start of the year, the father of my partner died due to a prolonged condition. The disease progressed initally from immune system dysregulation, which made it easier for any infection to attack him. The goal and plan for his treatment was to treat him using appropriate dose of immunosuppresive therapies  together with treating any infection that comes during this. We were having him treated and consulted with doctors from [AIIMS Delhi](https://en.wikipedia.org/wiki/All_India_Institute_of_Medical_Sciences,_Delhi), [Apollo Indraprastha](https://en.wikipedia.org/wiki/Apollo_Hospital,_Indraprastha), and [AIIMS Patna](https://en.wikipedia.org/wiki/All_India_Institute_of_Medical_Sciences,_Patna) (because it was nearest). We have been holding on for more than a year and had achieved stability and it appeared that he would recover soon. At the start of this year he was contracted with tuberculosis, and the doctors despite noting down his condition and symptoms did some tests except the test for tuberculosis and were giving different antibiotics instead without knowledge of the infection. This was happening at AIIMS Patna, an institute of national importance. Left undiagonosed and untreated of TB, his breathing system was being burdened. He was rushed to [CMC Vellore](https://en.wikipedia.org/wiki/Christian_Medical_College_Vellore), where the doctors took congisance of the past medical history and assessing the situation ran comprehensive tests. They identified that he had contracted TB for past few months. Despite their best efforts, his condition kept worsening and this lead first to lung failure, then to brain death and finally to heart failure. This was a terrible loss for us. 

If one runs many errands around AIIMS, the first problem they natuarally feel is the overwhelming logistical difficulty due to large number of patients and lower doctor to patient ratio. Also, digitization has penetrated there only upto them having a website and an online booking system (which does not work reliably). There is no comprehensive software that lets one to view and store a patient's disease history and case — all of this is stored in a paper based file. CMC Vellore has solved these problems to a large extent. 

So, the question that naturally comes up is: how do we design softwares and systems that helps the doctors in managing a particular patient and make the most out of the time while attending a patient? How do we design these solutions so that patients have it easier to navigate the system and avail services? Definitely a lot of the problems can be alleviated using digital solutions. Again, problems related to availablity of personnels and management related problems can only be solved with institutional redesign and resutructuring. 


#### Sustaining is even harder than scaling.

One of the message by Bill was that after having certain user base, keeping the operations running was not so easy thing. Also, not easy is keeping the inflow of finances from different funding agencies. Many things that make the sustenance hard are:

- Tech stack drift: The technologies and the way of doing things keep on changing and is ever in flux. What was built with a specific set of tools, and tech stack, etc. that may not relevant in few years. Also the user specifications might change. This will require maintenance which drives up the cost. This is true particularly for digital technologies. 

- [Post-pilot funding gap](https://pmc.ncbi.nlm.nih.gov/articles/PMC12894408/): Funders help with finances during pilot and scaling up to realise a particular idea and not so much on maintaining it. The recurring cost of keeping things operational does not attract funders. 

- Institutional turnover: People in the government, field partners etc. keep on rotating. A tech platform should be such that retraining them is easier (or they should be doing it on their own) and it should receive sustained policy support from the government irrespective of the person in a particular office.  



#### Can technologists improve quality of life for the poorest billions? 

Even after AI making easier to write codes and build software, technologies are far afar from solving daunting problems like poverty, public health, better education, etc. The final question posed in front of us was not whether a particular **technology** can solve some of these problems but whether **technologists** with their systematic approach, programmatic thinking, deep understanding and analysis of systems, etc. can come together and design better systems? 

A general tendency for technologists is whether using this particular method will solve the problem. Like, we keep on saying that a particular app, a particular ML model, a particular decision support system, etc. will have a huge impact but as discussed earlier, the deep entrenched social problems can be alleviated with participation and co-designing better systems from the ground up. 


-------------------------------------------------------------------

*Acknowledgements:* Thanks [Shreya](https://www.linkedin.com/in/shreya821/) for reading drafts of this article and permitting me to share publicly the personal story of loss.  

*Comments:* The article was written from memory without the availability of slides of the talk. So the article might have been tainted by the author's thoughts and his notes. 

*After-thoughts:* How does the personality of Microsoft as a company reconcile with the personality and work of people like Bill Theis and Kentaro Toyoma? Also there is this AI for social good labs inside several of its branches? It is interesting to note that goodness can emerge inside structures (here corporate) that on the outside seem to be not particularly directed towards it (corporate are noted for being directed towards profit maximization for the shareholders). 

To comment and engage further write me an email at [professorshubham8625@gmail.com](mailto:professorshubham8625@gmail.com).



