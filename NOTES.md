# Notes
## Chapter 1
A definition of DevOps could be the union of people, process and products to enable the continuous delivery of value to the end users/customers. #defintion

The most important task in a transformation movement is addressing the people within the organisation and change the culture for everybody. The goal is 100% alignment in continuously delivering value to the customer in every possible way. #approach

The process of the company need to delivery fast feedbacks while maintaining a high code quality (e.g. Agile). #approach

Products to help enable the DevOps philosophy are out there. #approach

One of the limiting factors is when the rest of the organisation still behaves the traditional way. This only leads to only incremental improvements due the conflicts of culture, goal. #lessonlearned

You can’t copy of company x to ours. This is simply “cargo cult”ing and the values and goals of those companies are different. Approaches like this are a guaranteed way to fail miserably. #lessonlearned

There is no “best practice” there is only better practice than yesterday. #lessonlearned

You need to make the work visible of the team to prevent siloization and foster the ability to collaborate. #suggestion

If involved in a heavy emotional discussion remember, when you say those words, those angry words, you can’t unsay them. #behaviour

The business has the rights *what* to do, but not *how* to do it. That’s your job. Don’t ask for permission. #suggestion

Aim for a good balance between velocity and safety. #approach

What would mean a list of a production server to you? How long does a rebuild take? Is every configuration in your version control. #provokingthought

Socratic questioning and the scientific method #research

Socratic questioning, asking instead of “best practices”. #defintion
Scientific Method, everything is a hypothesis. #defintion

Socratic questing and the scientific method should always be top of your mind! #suggestion

If you want good people in your company, you need to be serious about learning, experiments and more.

Technical debts can be seen as problems in the system left unfixed. A nice metaphor could be that your systems charges interest. So technical debts could lead you to more manual work and other unpleasant slow work. But there should be also the thinking about different types of technical debts. #defintion

Bug-to-Engineer ratio as a mechanism to deal with technical debts. #suggestion

Dysfunctional groups thrive on secrets. Always aim for honest, open discussions, even when this involve conflicts in the short term. #suggestion

Learn to speak the language of the business to get buy-ins. #behaviour

Don’t call DevOps as revolutionary concept in the company. Better just say that you are striving for delivery of business value, flow and elimination of wast and take an experimental approach, one tiny evolution at a time. #suggestion

To be successful put one step for the other and look up the mountain (work ahead) and stop comparing yourself to others. #behaviour

To build a habit try to be 1)committed, have skin in the game. 2) it should be habit oriented not outcome oriented (e.g. I want to program everyday for 25 minutes against I want to solve everyday a problem). 3) it should be simple and clear to be understandable 4) small and achievable, no epic level but something small. #behaviour

Make problems visible so they can’t hide anymore (see Scott Hanselman article about the Maslow Pyramid). #suggestion

To achieve flow within the team, try to capping work. Look out for the most loudest people about this approach (maybe Brent type of team members and a Limiting Factor/limfac!) #suggestion

See good reviews like a family dinner. Chefs cook new experimental thinks to improve. They serve it to people and looking for feedback. #suggestion

Practice and culture will eat just tools for breakfast. A consistently green build requires more work but the pain should decrease with more practice and will make the way for better quality.

Continuous Integration (CI), work in small batches and use automated test to detect and reverse changes that introduced a regression error. #defintion

Everyone thinks they are doing CI but check the definition in “Continues Delivery book”. #provokingthought

Strive for short-lived branches (1-2 days). #suggestion

Look into Trunk Based Development. #research

Look into Monorepos #research

1) merge to trunk daily 2) branches shorter than 3 days 3) less than 3 active branches #provokingthought

Don’t try to separate where code is being written and tested due to the danger of “someone else job”. #suggestion

Postmortem example setup could be 1) What happen slot, gather log files, chat discussions and more, at best in a timeline manner 2) Open Discussion, looking for gaps in knowledge, tooling or configuration 3) Remediation items, actionable goals within 30 days and following the SMART concept would be a first idea. #suggestion

Try to cultivate a culture where failures are seen as opportunities to be better. #behaviour

If you are not ashamed of your MVP, it is not a MVP. #provokingthought

Take a value stream analysis to make waste visible. Try to determinate your lead and cycle time. #suggestion

Lead time and cycle time. Two metrics to maybe look after. #suggestion

A definition of success should be customer driven, not team driven (e.g. development team, ops team, …) #suggestion

A common queue for all team members, not separating by role, but just show “work” could lead to a real cross functional team. #suggestion

A chance to implement a success DevOps movement have DevOps team, even when often seen as an anti pattern and let them show on regular basis a demo to the company to achieve a learning friendly environment. Don’t let it look like they could play around with the new shiny toys and everyone else is left with the real work. #suggestion

Ops team are often pressured with the urgent stuff to fix and have no time for the important things which require time, focus and creativity. #lessonlearned

Disable SSH to achieve true Infrastructure as code embracement. #provokingthought

Mojito Test, all day everyday. #provokingthought

Any strategy that depends on people to change they behaviour will fail. Stop talking about what you care about, talk about what the people want to care about. #provokingthought

Netflix charter of the tools team is to support the engineering team innovation and velocity. #lessonlearned

Google heavily use on-call playbooks and prepare they engineers with the “Wheel of Misfortune”. #lessonlearned

Teams don’t trust each other (dev, ops, management). That could be the source for example that ops prevent developers to access the production environment. This lack of trust results in a not effective communication and collaboration. #behaviour

Keep visible your metric around reliability and SLA coverage, exposing the cost caused by pass-through tickets and long remediation times. #suggestion

Determine what success looks like and then generate metric that give you the view of how the team is working. Never create metrics out of the blue because you will run into the danger of getting what you measure. #suggestion

Before setting up a KPI ask yourself what the team will do differently based on the metric. #provokingthought

Be aware of vanity metrics, easy to gather and essentially local problems and encourage to cheat. #lessonlearned

Keeping the build pipeline green should be priority #1 for a team, not delivering new features. #provokingthought

Strive for a mission-driven team, which will choice the tools to achieve they goals not a tools-driven team. #suggestion

An anti pattern for a release process to look for are releases at night or the weekend. #behaviour

Defect to zero is a myth and just generates a culture of distrust, manual handovers and blame. #provokingthought

Embrace the cattle not pets thinking, that it is far more easy to destroy something an rebuild it, than manually fix it by hand. #suggestion

To find good people provide a customer design problem. Look for technical expertise but also for the approach they are taking. Are they curious? Are they immediately jumping into a solution or are trying to really understand what the customer is asking for? #suggestion

Micro service should be a well discussed decision. They embrace good thing like small teams, learning culture e.g. but also have the downside of wrong service boundaries. #suggestion

Simon Wardleys “Settlers of Catan” with the Pioneers, Settlers and Town planners. All starts with a single spark, one person or team as pioneers, are catch up by settlers which improve those practices and maybe build tools around it. Town Planners finally operationalize. #suggestion

The standards you walk by are the standards you accept. Keep on hammering on problems until they are gone. You are responsible as a professional to eliminate waste one step at a time. #suggestion

Good leaders are defined by two things 1) protect they people 2) hold them accountable. #behaviour

Information flows down the organisation easily but takes effort to get up again. #provokingthought

Slow down to a level that the organization can handle. #provokingthought

A resilient team is made of the elements of 1) Autonomy, 2) Mastery, 3) Purpose. See Drive book. #suggestion

Change is inevitable in the software world. We need to live with it and need to come up with solution on the fly to win. #suggestion

To get business buy-ins talk the language. Connect your asks to dollars and use more often the word waste. #provokingthought

Use monitoring reduce the most common errors for customers, this build empathy. #suggestion

Don’t expect to get everything right from the start. Patience and experiments are the key. #provokingthought

Use feature toogles to separate deployment and release. #suggestion

Consistency is more important than perfection. #suggestion

There is no silver bullet. Just hard work. And the only one who can do it, is you. #provokingthought

The second year of transformations are the hardest. Watch out! #suggestion

Don’t get involve in discussions about pro and cons about a tool. There is always a solution but the problems arising with people, process and culture are more challenging. #suggestion

