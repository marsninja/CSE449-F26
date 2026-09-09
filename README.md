# Principles and Practice of Agentic Artificial Intelligence

## Principles and Practice of Virtual Assistant AI

**EECS 449, Fall 2026**

# 

# Summary

The science and art of creating real modern generative AI systems and products spans multiple areas in computer science. Learning about and leveraging advances in these areas to create state-of-the applications leveraging generative and agentic AI is the central focus of this course. Throughout the course, students will put into practice the end-to-end creation of an agentic software solution leveraging modern GenAI models and prompted contextual agentic software engineering. Students will also use the Jac and Jaseci open source ecosystem and tooling that comprises of and supersets popular modern tooling (React, Javascript/Typescript, Python, FastAPI, and k8s) along with cutting edge agentic AI technologies (ByLLM, etc). Students will be inventing their own products, building them out end to end, and actually launching them to end users in the span of one semester. The project culminates in a marketing campaign to the world and demo day at Michigan where creations are shared for others to try. 

In the creation of these virtual assistants, students will form groups of around \~4-5 students to select a use case, design the agentic workflows, train AI capabilities if needed, implement logic, and execute the end to end build out and integration into an existing public API. In class, students will learn about the broad landscape of NLP and Conversational AI from it’s fundamental principles. Students will also learn state of the art techniques for various aspects of modeling language in deep learning, leveraging  transfer learning to solve NLP problem, and gain very important experience understanding and interpreting research papers as the state of the art evolves. As an MDE, the grading of the course is predominantly project-based and students will be presenting the evolution of their project in course. Also students will gain valuable experience presenting technical ideas and evaluation through 2 presentations per group.

**Instructor**: Jason Mars ([profmars@umich.edu](mailto:profmars@umich.edu) / [https://www.linkedin.com/in/drjasonmars/](https://www.linkedin.com/in/drjasonmars/))

**GSI**: Jayanaka Dantanarayana (jayanaka@umich.edu)

**Lecture**: MW 1:30-3, In-Person / 1311 EECS

**Credits**: 4

**Prerequisites**: EECS 280, EECS 281

**Office** **Hours**: 4129 Lien. 3-4 PM Tues/Thurs (GSI or Prof avail)


# What to Expect This Semester

This course is designed to embody real-world AI product development. You are not completing assignments for a grade, you are building something real, working in teams, managing ambiguity, making tradeoffs, and launching publicly. The goal is for every student to finish the semester having built, shipped, and marketed a real AI product.

This course is structured as a hands-on, project-based experience centered on building and launching a real AI product using a cutting-edge open-source AI ecosystem.

* Students will be organized into project teams of 4–5 members.  
* Each team will design, build, and launch a complete end-to-end AI product, not a toy example.  
* All projects will be built on the Jaseci and Jac open-source ecosystem, which:  
  * Supersets and integrates modern industry tooling such as React, JavaScript/TypeScript, Python, FastAPI, and Kubernetes (k8s)  
  * Enables rapid development of agentic AI systems using advanced capabilities such as ByLLM and related AI-native abstractions  
* Teams will have full ownership of their project, including product vision, technical design, and execution decisions.   
* All projects will be publicly launched toward the end of the semester. 

## Team Formation and Development Workflow

Form teams of **4–5 students by Friday, September 18**. Teams will organize their development work using [Flowline](https://github.com/kashmithnisakya/flowline), an open-source tool for experimenting with development as an assembly line of stages. In this course, we will explore this approach as a way to enhance or replace Agile practices in the age of AI-assisted development.

As your team gets started, agree on your development flow and how members will contribute across its stages. You may use a default Flowline template or tweak and customize the stages and transitions to fit your project. **Every issue and pull request should be tracked through your team's flow of stages**, with its current stage, ownership, and handoffs clear. Keep the board current as work progresses so it reflects what the team is actually doing.

**Every team is expected to make progress each week, and every individual is expected to contribute something.** Contributions can include design, implementation, testing, reviews, user research, or launch work. Make those contributions visible in your development workflow and weekly reflections.

# Schedule by Week *(subject to changes)*

Dates below are the Monday starting each week of Fall 2026. University dates follow the [University of Michigan Ann Arbor academic calendar for 2026–2027](https://ro.umich.edu/sites/default/files/calendar/pdfs/Cal_2026-2027.pdf).

Classes begin August 31 and end December 11. There are no classes on September 7 (Labor Day), October 19–20 (Fall Study Break), or November 25–27 (Thanksgiving recess). Study days are December 12–13; the university examination period is December 14–18 and December 21. Any course-specific exam arrangements will be announced separately.

| Week (starting Monday) | Topics and deadlines |
| :---- | :---- |
| **Week 1 (8/31)** | Course Introduction, Natural Language Processing Syllabus and Logistics Introduction |
| **Week 2 (9/7)** | NLP and AI Overview Survey of NLP Landscape and Problems Traditional vs ML based NLP Survey of NLP Landscape and Problems; **Labor Day September 7: no Monday class; Wednesday class meets.** |
| **Week 3 (9/14)** | NLP and DNNs Survey of NLP Landscape and Problems Traditional vs ML based NLP **Group formation due: Friday, September 18.** |
| **Week 4 (9/21)** | Deep Learning Representations for NLP Deep learning applied to NLP Understanding Papers and Metrics |
| **Week 5 (9/28)** | Mini lecture, 5-Min Group Update M(1-8) W(9-16), Snippets Due Fri |
| **Week 6 (10/5)** | Mini lecture, 5-Min Group Update M(1-8) W(9-16), Snippets Due Fri; **[Assignment 1: Personal Planning App in Jac](extra-credit-1.md) due Monday, October 5.** |
| **Week 7 (10/12)** | Mini lecture, 5-Min Group Update M(1-8) W(9-16), Snippets Due Fri |
| **Week 8 (10/19)** | **Fall Study Break October 19–20: no Monday class.** Wednesday: 5-Min Group Updates (all groups), Snippets Due Fri |
| **Week 9 (10/26)** | Mini lecture, 5-Min Group Update M(1-8) W(9-16), Snippets Due Fri |
| **Week 10 (11/2)** | MVP PITCH WEEK, 5-Min Group Update M(1-8) W(9-16), Snippets Due Fri |
| **Week 11 (11/9)** | Mini lecture, 5-Min Group Update M(1-8) W(9-16), Snippets Due Fri |
| **Week 12 (11/16)** | LAUNCH WEEK, 5-Min Group Update M(1-8) W(9-16), Snippets Due Fri |
| **Week 13 (11/23)** | Monday: 5-Min Group Updates (all groups). **Thanksgiving recess November 25–27: no Wednesday class; no snippets due this week.** |
| **Week 14 (11/30)** | Mini lecture, 5-Min Group Update M(1-8) W(9-16), Snippets Due Fri |
| **Week 15 (12/7)** | REFLECTION WEEK, 5-Min Group Update M(1-8) W(9-16), Snippets Due Fri (Last MW class December 9; university classes end December 11) |

# Notes

* **MVP Pitch Week (Week 10, November 2–6)** — Come prepared with a launch-ready MVP that the rest of the class can use. Be ready to demo your product, let your classmates try it, and gather feedback before Launch Week.

* **Launch Week (Week 12, November 16–20)** — Go live. This is when you push the button on your digital marketing campaign and release your product to real users.

* **Reflection Week (Week 15, December 7–11)** — A recap of the semester: what you built, what worked, what you learned, and what you'd do differently.

* **Weekly Group Updates** — Each 5-minute report-out should include 3–5 slides and a **work-in-progress demo**. Frame the update around your team's Flowline stages: show what moved forward that week, what is in progress at each stage, where work is blocked or awaiting a handoff, and what comes next. Use issues and pull requests to make the progress concrete. Include a demo in every group update, even while features are still being built.

* **Individual Weekly Snippets** — Snippets are **individual submissions** due on the Fridays indicated in the schedule. Each student should describe their own development experiences that week: what they contributed, what they tried and learned, challenges they encountered, and their next steps. Reference relevant issues, pull requests, or other work so your contribution is clear. Each snippet should reflect the student's own experience and perspective.

# Tips for the Journey

* **Design early** — Use any tool (Figma, Canva, whiteboard, napkin sketch, etc.). The tool doesn't matter, starting does. Having a visual reference early aligns your team on what you're building and saves you from costly mid-semester pivots. Don't overthink it — a rough wireframe beats no wireframe every time.

* **Identify your hook** — Decide on the one standout feature you'll market first. Lead with what grabs attention. This is the feature that makes someone stop scrolling and say "I want to try that." Your marketing campaign will revolve around it, so pick something compelling and make sure it works flawlessly.

* **Nail the happy path** — Define the golden end-to-end workflow and make it rock-solid before branching out. Map the exact steps a user takes from opening your product to getting value out of it. That core flow should feel seamless. Edge cases and extra features come later, if your happy path is broken, nothing else matters.

* **Build early, build often** — Don't wait until the design is perfect. Get code running as soon as possible. A working prototype with rough edges teaches you more than a polished spec that hasn't been tested. You'll discover the real problems (and the real opportunities) only once something is running.

* **Ship something every week** — Aim to have a working version at all times, no matter how rough. Treat every scheduled group update as a mini-launch. This forces incremental progress, keeps your team accountable, and means you're never more than a week away from a demo-ready state. The teams that ship weekly are the ones that launch successfully.


# Grading

This is a very ‘do based’ course as opposed to ‘study based’. A significant portion of the grade is allocated to the projects. Lets build some amazing stuff\! 😊

**Team-Based Components (70%)**

- Technical implementation and AI integration (Codebase, agentic AI, system design): 20%  
- Product design, usability, and completeness: 10%  
- In-semester group update presentations (slides, demos, clarity, progress): 15%  
- Digital marketing campaign strategy and execution: 10%
  - Landing Page and Demo Video
- Final launch quality, public release, and final presentation/demo: 15%


**Individual Components (30%)** 

- 10 weekly individual reflection submissions (snippets): 2.5% each
  * All, half, or nothing based on clarity, technical substance, honesty, and demonstrated engagement through each student's contributions and development experiences that week
- In-class participation through random pop-up activities: 4%
- [Assignment 1: Personal Planning App in Jac](extra-credit-1.md): 1% participation grade. Individual project with a server, web frontend, mobile app, and CLI. Submit the GitHub repository link via Canvas; include a README with setup and run instructions.

**Additional Extra Credit Opportunity**: Up to 20% Extra Credit

- [Assignment 1: Personal Planning App in Jac](extra-credit-1.md): up to an additional 3% extra credit based on how impressive the project is.



# Logistics and Details

**Late Policy**

The official policy is Late work will not be accepted under any circumstances. That being said if I do make case by case determinations sometimes, though there are no guarantees. 

**Github**

Students will be engaging open source software and the open source community in this course. You will need to have a free github account if you don’t already. You are allowed to make your repositories public and share your code with anyone in the class throughout. 

**MDE Project**

This course will have a large team­based project that will require designing and building an end to end software. After group formation, an initial ‘pitch’ document and in­class presentation will help teams get feedback on their ideas. After that, there will be a few milestones on the way to a final project document, presentation, and demos. The objective of this project is to build a system from the ground up that work really well in practice. Be creative\! 

**Honor Code**

All students (including LS\&A and Engineering) are required to observe the Engineering Honor Code in all assignments and exams. A copy of the honor code can be found at http://ossa.engin.umich.edu/honor­council/. Please make sure that you clearly understand what constitutes cheating. If you are not sure in any specific case, you should ask the teaching staff. 

# 
