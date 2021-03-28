---
layout: post
title: Reflections from TransferWise on Software Engineering Practices and Work Culture
author: Reflections from TransferWise on Software...
description:
image: pic02.jpg
permalink: /:title/
---

<div style="font-size:14px;margin-bottom:20px;"> 13 Oct &#183; 9 min read </div>

It’s been almost 2 months since I wrapped up my summer internship at TransferWise and headed back for my second year at college. Being immersed in academia in school and working in the industry is really different and I wanted to pen down my thoughts and reflect on my growth as a Software Engineer.

This blog post will go into the details of company work culture as well as some of the Software Engineering Practices that I took away from my internship at TransferWise.

During my 3 months at TransferWise, I took on multiple projects to build new route integrations with banks and improve performance bottlenecks in existing routes. Through the process of working on problems together with the team, tackling code and smashing bugs, I’ve come up with 5 ‘C’s to condense my takeaways this summer.


<h3> 1. Code Reviews </h3>

At TransferWise, we practice Code Reviews on our pull requests. This involves having someone from the team look through the code after automated checks have been completed successfully, but before merging it with the repository’s master branch.

As a student, I never really had the chance to perform Code Reviews in school, or while building personal projects. I learnt more about Code Reviews, and how we can perform them to improve code quality and benefit from positive effects on team culture. From my perspective, Code Reviews helped me in the following ways:

1. Committers know that there will be reviewers looking over the request, and tend to clean up loose ends and consolidate TODOs, which generally improves the commit
2. Sharing of knowledge: Someone else with more experience may have a cleaner, more efficient technique or algorithm to suggest to the committer
3. Accidental errors are easier to spot from the reviewers' perspective
4. Improves consistency in code

Through gathering the best practices from other engineers, I was able to write code that was <b><i> effective, efficient and scalable. </i></b> This also presented a chance for collaboration between the other engineers and myself and allowed me to better understand the code base.

<h3> 2. Code Ownership </h3>

Under the mentorship of a great team of senior engineers, I was given the opportunity to push my projects end-to-end; from its planning and requirements stage, through implementation, testing, documentation, deployment, and maintenance. I learnt how to take charge and own my code in production.

<blockquote> Ultimately, I was not only responsible for its operational performance, bugs, but also had to understand if the solution worked and iterate on them based on key takeaways. </blockquote>

Engineers in TransferWise practice weak code ownership. This means that each repository is owned by a team, but other teams can contribute to that code. This setup allows teams to be independent by removing dependencies on other teams, allowing them to iterate at their own pace.

<h3> 3. Communication & Transparency </h3>

One of the things I liked the most about TransferWise was its transparency and feedback culture. On transparency, I was impressed at how much clear, efficient communication there was between cross-functional teams.  

I also enjoyed the daily stand-ups, weeklies, and town-halls that we had. Apart from the chance to update the team on my progress, engage in discussions and listen in on feedback to my approaches to technical problems and listen in to developments, these gave me a wider perspective to my project, and reasoned why certain workflows are prioritised above others. Through these sessions, I realized the importance of being curious and thinking critically, in that I should not take information presented to me at face value, but rather, challenge any assumption presented to me with tact. I also booked side-by-side sessions with teams that I worked closely with and pair programmed with engineers from other teams, so that I could familiarise with their workflow and understand their pain points.

<figure>
<img src="/assets/images/TW2.jpg" style="display:block;margin-left:auto;margin-right:auto;width: 40%;">
<figcaption style="text-align:center;font-style:italic;font-size:12px;margin-bottom:20px">Side-by-side sessions with Wisers from other teams</figcaption>
</figure>

One of the first things that immediately stood out to me was the how fast decisions were made in the office. Engineers were as close as possible to day to day operations and the customer feedback loop. This allowed them to make better decisions, faster, run more tests and iterate quicker on a solution. Fundamentally, the team believed that <b><i> companies that iterate faster, fail faster and learn faster will be more successful long term. </i></b>

Apart from a flat structure within teams, I was fortunate to have regular catch up sessions throughout the week with my mentors and teammates to check in on progress and answer any questions that I had. I also had scheduled monthly meetings, which had more structure to provide feedback on my work.


<h3> 4. Continuous Delivery & Test-Driven Development </h3>

Engineers at TransferWise are customer-centric, and decide how to improve the their product (for internal or external stakeholders) by being close to customer and looking at data.

Something that stuck me the most was the notion of a minimum viable product, which is another important concept in product and engineering. While there are many interpretations, it can be condensed to 3 steps:

1. Starting with a simple product that solves one part of larger problem
2. Iterate on your product, while constantly working on the larger problem
3. Continuously communicate the vision of the larger problem that will be solved

Instead of working towards a huge release, I learnt to improve on my code step by step, and iterate, iterate, iterate, to get to where I want it to be. One of the main reasons for this method is that valuable feedback can be received along the way. This allows engineers to be more connected to customers, get insights on product performance, unforeseen bugs, and gain valuable insights for the next iteration. This information may also allow engineers to consider pivots much earlier.


Another Software Engineering practice that I picked up was the concept of Test-Driven Development. TDD is the practice of writing a test for code functionality before actually writing the implementation code.
<blockquote> Why TDD? TDD results in lower debugging time. Good tests can also be used as a low level documentation for other developers. It also increases control throughout the code base, in other words it makes code easier to maintain and understand. </blockquote>
During TDD, I learnt to consider every now and then if I could safely release what I’ve built. Yes, even if it was unfinished!
TDD also taught me how to write better code. I learnt how to effectively decouple and isolate software components. As simple as it seems, it refocused my work on the overarching idea of decomposition- to break large problems down into multiple smaller, simpler to solve problems. I wrote cleaner and simpler code that was much easier to maintain and scale,  both in complexity and across systems.


<h3> 5. Camaraderie </h3>

Above all, to me, TransferWise really embodied a culture of camaraderie- I could just ask anyone about anything, and they would be more than happy to help, or even, go the extra step to mentor. I felt like I was part of a bigger team with a purpose, and that I could actually make a difference. We worked hard and played hard together, and with these shared experiences, forged meaningful & lasting bonds with one another. The team was also huge on knowledge sharing. One of my favourite activities was the weekly technical exchange sessions (TeX) where engineers came together to discuss technical topics, such as design considerations or new technologies.

<figure>
<img src="/assets/images/TW1.jpg" style="display:block;margin-left:auto;margin-right:auto;width: 40%;">
<figcaption style="text-align:center;font-style:italic;font-size:12px"> Team bonding in Sentosa!</figcaption>
</figure>
---
Fundamentally, I believe that as an intern, taking the initiative is important. <b><i> You decide how much you want to learn. </i></b> Almost all the time, people were more than willing to clarify any doubts I had- which was a great opportunity to learn. Furthermore, I was motivated to ship projects faster and learn without the fear of breaking things. I worked in an environment where I didn’t have to worry about failing, but also understood that I was accountable for my failures and how I recover from these mistakes, to prevent the same thing from happening in the future.

Looking back, while TransferWise wasn’t my first internship in an engineer role, I definitely had some of my best experiences there. Kudos to the team. As an intern, I was empowered and challenged to take on multiple projects and improve various services across TransferWise. Besides being able to deliver code under a great team, this process definitely gave me a starting point to look into a lot more complex concepts that interest me, as I enter my second year in university.

For now, back to school! Thanks for tuning into this post!

<i> Read more about TransferWise <a href="https://transferwise.com/gb/blog/">here.</a></i>

<span class="badge badge-secondary">Code</span>
<span class="badge badge-secondary">Software Engineering</span>
<span class="badge badge-secondary">Start-Ups</span>
<span class="badge badge-secondary">Product</span>
