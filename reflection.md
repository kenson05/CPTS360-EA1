# Reflection

## Activity Description
The extracurricular activity that I participated in was the 2026 Crimson Code Hackathon at WSU. I worked in a group of 4 people and our goal was to design, create, and demonstrate a working prototype of a project that solved a real-world problem. The theme of this year's hackathon was to "re-invent the wheel" and we decided to reinvent how hospitals currently operate. We built an AI-powered assistant/tool named "Nursley" that helps nurses manage their patients and answers questions they have about the patients current conditions. 

## Technical Decisions
We created a cross-platform desktop application that was built with Electron for Mac and Windows. The frontend uses React, Tailwind CSS, and Shadcn UI for a modern, responsive interface. We used Supabase for authentication and backend services and Snowflake was used as the cloud data warehouse for structured patient data and real-time SQL queries. An AI layer sits on top of all of this to provide contextual and cited responses. 
<br>
<br>
The biggest decision we had to make was how we were going to implement RAG into our project. One of our members had previous experience with RAG and would have been able to implement it fairly easily. However there was a track that awarded the best use of Snowflake and we saw that Snowflake had an option to use their built in RAG system. We decided to challenge ourselves and learn a new technology during the hackathon and ended up using Snowflake.

## Contributions
We split roles into authentication, business logic, and two full stack roles. I took on the role of one of the full stack developers and initially I started researching Snowflake and drafting our schemas. As the hackathon went on however, I pivoted into being in charge of frontend while the other full stack teammate took charge of the Snowflake backend. I designed and implemented the UI/UX and also implemented features such as patient summary and lookup end-to-end.

## Quality Assessment
I would say that I am overall satisfied with our performance of this event. Going into it I just wanted an opportunity to learn and meet new people. I learned a lot through this experience and I think that we were able to get a lot of good work done. I did not expect much but we ended up winning the track for the best use of Snowflake, which I am very proud of. If I were able to redo the event though, I would have researched the different tracks that there were and got myself comfortable with the technologies so that I could have allocated more time into building the actual product and thinking of the actual logic rather than spending hours on learning something from scratch.
