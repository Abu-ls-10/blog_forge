# SEO Content Engine / WeWantTwo
> _Note:_ This document will evolve throughout your project. You commit regularly to this file while working on the project (especially edits/additions/deletions to the _Highlights_ section). 
 > **This document will serve as a master plan between your team, your partner and your TA.**

## Product Details
 
#### Q1: What is the product?

We are partnering with Marc Gaudett - High Ticket Closing Agency Inc. to build an SEO Content Engine that helps automate the creation of SEO-optimized blog posts, meta tags, images, and social posts — so that user’s sites can rank higher on Google and drive more traffic, backlinks, and revenue.

Many businesses rely on SEO content to drive visitors and revenue, but manually creating high-quality SEO content is time-consuming, expensive, and hard to scale across multiple websites. 

Our system allows site owners to automate this process, producing content that attracts visitors, earns backlinks, and supports business growth. For example, if the user owns a book publishing site, they can use our SEO engine to generate high ranked articles like “Top Books for Passive Income” to advertise their products, drive book sales and grow an email list.

We’ve created a figma design:
https://www.figma.com/design/neuzbWx7xeU5zuvUGT6xAs/SEO-Blog-Generator?node-id=0-1&t=IWf9p1LYUqFzmiMN-1 


#### Q2: Who are your target users?
Our first target users are initially just our partner, Marc Gaudett, and a possible internal user but there are potential use cases for every small business owner and some big businesses that want to automate their content generation to be SEO-optimized. 
These users run multiple web properties, including a Pet Insurance Directory Website and a Book Publishing Website tied to Amazon-published books, and need a fast, easy way to generate SEO content that drives traffic and revenue.

Example persona:

Name: Website/Author

Background: Entrepreneur running several websites (pet insurance, books)

Need: Wants to easily create SEO optimized articles that bring more people to his sites so he can earn money through ad (adsense), partnerships, book sales, and email list growth or other methods

#### Q3: Why would your users choose your product? What are they using today to solve their problem/need?
Right now, many businesses either write SEO content by hand (which takes hours per article) or pay external writers and SEO services (which is expensive and slow) or even worse because time and money is limited we may not even create the SEO content but it is one element in providing value and ensuring the site can be found.

The SEO Content Engine will save time (articles can be created in minutes instead of hours), save money (no need to hire writers), and allow teams to easily scale content creation across multiple websites. Even if a human is involved in having the final check on the content 80 percent of the process can be automated and done for essentially pennies on the dollar.

It also helps them discover profitable keywords and content opportunities that they may have missed manually.

Other generic AI writing tools exist, but they do not focus on SEO optimization, do not generate backlink-friendly content, and do not produce multi-channel outputs (blog + social + meta data) as our tool would.

This project directly supports our mission of building scalable online businesses through systems and automated methods.

#### Q4: What are the user stories that make up the Minumum Viable Product (MVP)?
We have attached a link to five user stories, there's a screenshot of approval from our partner:  

https://docs.google.com/document/d/1RnGoEbugSLzIgE2I4Lva-qrpjjSqsYjl0JT1RvniWis/edit?usp=sharing


#### Q5: Have you decided on how you will build it? Share what you know now or tell us the options you are considering.
The details on what tech stack we will be using is not set and left for us to decide. So for frontend, we will use whatever is comfortable for most of the team members, which is React + HTML/CSS + TailwindCSS. There is one main tool that the partner wants us to use for the backend n8n, which is a workflow automation tool that will handle backend logic and integrate different API services like OpenAI into our product. We will handle the API layer using Django.

Overall architecture will look like the following: 
![ques5_diagram_seo](https://github.com/user-attachments/assets/e0b63b4e-5889-4ccd-952b-3109c3f6e729)


----
## Intellectual Property Confidentiality Agreement 
We have discussed with our partner and we will only reference the work you did in your resume, interviews, etc. We agree to not share the code or software in any capacity with anyone unless our partner has agreed to it.

----

## Teamwork Details

#### Q6: Have you met with your team?
We played the game Skribbl.io together. The game has one person drawing a word that no one else knows. The people not drawing have to try and guess the word being drawn. We each took turns drawing and played for a total of three rounds.  

![Skribbl.io](https://github.com/user-attachments/assets/75130d15-486f-49d8-88a3-597f99e6101a)

**Fun facts**:  
* We have 2 Kevin’s (2 members) and 2 Abu’s
* We have a member in the Canadian Armed Forces, more specifically the Navy. They know morse code. They have guns & missiles! She lived in a submarine. Canadian Submarines sucks. 
* Everyone is born in different countries - Bangladesh, South Africa, India, USA, Taiwan, China, Canada


#### Q7: What are the roles & responsibilities on the team?
Abu Zahed  
**Roles**: Full Stack Developer (Backend Focus), Product Manager  
**Responsibilities**:  
* Backend development with a focus on API setup and integration.
* Leads overall product planning and ensures project direction aligns with user needs and team goals.
* Rationale: Abu has prior experience with API development through CSC309 and enjoyed the process. His interest in expanding backend and leadership skills makes him a strong fit for the product manager role.

Abuzar Ansari  
**Roles**: Full Stack Developer, DevOps Support  
**Responsibilities**:  
* Frontend: Webflow CMS Development
* Backend: OpenAI API connection, frontend-backend communication, and n8n workflow pipelining.
* DevOps: Available to assist with deployment pipelines if needed.
* Rationale: Abuzar brings personal project experience in API work and a strong interest in learning more. His knowledge of chatbot development with pipelining technologies will be strongly beneficial to this project.

Akshat Oza  
**Roles**: Backend Developer, Development Manager  
**Responsibilities**:  
* Backend: Leads backend architecture and n8n workflow usage. 
* Manages team development process, assigning tasks and ensuring technical consistency.
* Rationale: Akshat has hands-on experience with Flask/Django which is what our tech stack is based on and is highly interested in using n8n. 

Barron Jiang  
**Roles**: Full Stack Developer (Frontend Focus), Meeting Minutes Notetaker  
**Responsibilities**:  
* Frontend: Assists with page layout and web interactions.
* Backend: Provides support for backend tasks when needed.
* Keeps detailed meeting records and ensures key decisions are documented.
* Rationale: Barron has some prior experience with web development and is interested in deepening his frontend skills while contributing to backend work and team coordination.

Kevin Lee  
**Roles**: Full Stack Developer (Frontend Focus), Scrum Master, Partner Liaison  
**Responsibilities**:  
* Works on frontend components and ensure smooth UX flow.
* Coordinates sprint planning, task tracking, and retrospective meetings.
* Rationale: Kevin has a strong interest in frontend development and is organized, making him a natural fit for both scrum master and frontend responsibilities.

Kevin Umaiyalan  
**Roles**: Backend Developer, Frontend Support  
**Responsibilities**:  
* Works primarily on backend components and supports n8n setup.
* Contributes to frontend implementation when required.
* Rationale: Kevin has prior backend experience with Django and is eager to learn about n8n.

Yucan Miao  
**Roles**: Frontend Developer
**Responsibilities**:  
* Implements web pages based on Figma designs and detailed interaction documents.
* Works with React / Next.js to create clean, styled user interfaces.
* Rationale: Yucan is enthusiastic about frontend development and brings collaboration skills through working closely with designers. Her interest in React/Next.js aligns well with the project needs.


#### Q8: How will you work as a team?
Team meetings will be held on Tuesdays and Thursdays in the afternoon via Discord. These will be recurring meetings, with additional ad hoc meetings scheduled as needed. The purpose of these meetings is to communicate each team member's current progress and identify any support they may require. Additionally, a weekly meeting with the partner will be scheduled based on availability using When2meet, and will be conducted online via Zoom.


#### Q9: How will you organize your team?
* **GitHub Kanban Board**: Tasks are tracked using a Kanban board with columns for To Do, In Progress, In Review, and Done. Both the TA and the partner have access to the board.  

* **Task Prioritization**: Tasks are prioritized based on deadlines, dependencies, and overall impact. Each task is labeled and ordered accordingly on the board.  

* **Task Assignment**: Assignments are discussed during team meetings and allocated based on individual expertise and current workload.

* **Work Tracking**: Progress is tracked through GitHub Issues and regularly updated on the board. Each issue serves as a log for task-related progress and updates.  

* **Communication**:  
  * Internal (Team): Discord is used for team communication, with dedicated channels for stand-ups, development support, and meeting planning.
  * External (Partner): An email chain is used with the partner and mostly Google Suite as that is what the partner is comfortable using. 

* **To-Do Lists**: Each team member maintains a personal to-do list for managing smaller micro-tasks.  

* **Codebase**: We are planning to use a shared Git repository. 


#### Q10: What are the rules regarding how your team works?
The team maintains constant communication for general issues via Discord, with 1–2 major weekly check-ins to monitor overall project progress. For partner communication, a shared Discord group with the entire partner team allows for ongoing and timely interaction.  

The Development Manager is responsible for tracking meeting attendance and monitoring each team member’s task assignments and progress.  

If a team member is not contributing or becomes unresponsive, the issue will first be addressed through a private check-in to understand any challenges they may be facing. If the situation does not improve, it will be escalated to the Development Manager and, if necessary, discussed with the TA or partner to determine appropriate actions—such as task reallocation or formal intervention.


## Organisation Details

#### Q11. How does your team fit within the overall team organisation of the partner?
Our partners organization consists of one person, Marc Gaudett. He acts as a consultant to tech companies helping the SaaS process. We will act as the product development team for the SEO optimized content generator. We have been given lots of freedom as to what we want to use as a tech stack, as he does not want to micromanage our team. We will be responsible for the full development of this website, from frontend to backend infrastructure. We feel we can do this as we have many team members who already have some background with the technologies that we will most likely use as well as members who are eager to learn about this space.

#### Q12. How does your project fit within the overall product from the partner?
**Project Fit and Scope**  
We will make the first prototype for the product. There is no existing frontend or backend for the product. However, the partner has clearly established that the frontend is not so important. Most of our tasks are related to backend features that will become the core of the product. 

There is no other contributor besides our team and the partner will guide us in creating the product, but will not make any technical contributions. 

**Definition of Success**  
As for success, the partners main goal is to have a usable product by the end of semester. We believe that means that we will have a proper landing page with user account system as well as the core functionality which is to allow for SEO Optimized blog posts to be easily created. 


## Potential Risks

#### Q13. What are some potential risks to your project?
- **Unclear content quality expectations**  
  Without a shared definition of what “high-quality SEO content” means, the generated articles may be technically optimized but lack readability, engagement, or credibility. This could result in low search rankings, poor user experience, and reduced business value.

- **Over-reliance on automation for accuracy**  
  Automated content may include outdated or incorrect information, especially in sensitive niches like insurance or finance. Relying solely on AI without fact-checking could lead to reputational damage, misinformation, or even legal consequences.

- **Scalability and integration complexity**  
  The automated workflow might work well for one website but fail to scale across different CMS platforms, tech stacks, or domains. Custom integrations may become increasingly difficult and time-consuming as the product expands.

- **Changing SEO algorithms**  
  Search engine algorithms (especially Google’s) are frequently updated. If the system doesn’t adapt to these changes, the content it generates could quickly become outdated or ineffective, reducing its ability to drive traffic and rankings.


#### Q14. What are some potential mitigation strategies for the risks you identified?
- **Define and test content quality standards**  
  Create a detailed content quality checklist based on SEO and readability best practices. Involve SEO/content experts early and run test articles through human review to ensure the generated output aligns with expectations before scaling.

- **Add human oversight and trusted data sources**  
  Introduce a lightweight human review step for high-stakes content and integrate data from trusted APIs where possible. Include prompts or checks to catch potentially inaccurate or misleading information before publication.

- **Start with a modular and flexible system**  
  Build an MVP that works with one or two common platforms (like WordPress), and use abstraction layers or plugins to simplify future integrations. Design the n8n workflow to be adaptable to varying tech environments.

- **Stay responsive to SEO changes**  
  Monitor SEO news and Google algorithm updates through trusted sources. Regularly evaluate content performance and keep prompts and templates modular so they can be quickly updated to reflect evolving SEO best practices.
