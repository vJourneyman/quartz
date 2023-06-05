Welcome to episode 189 of the Nerd Journey Podcast [[@NerdJourney](https://twitter.com/NerdJourney/)]! We're [John White](https://www.linkedin.com/in/vJourneyman/) ([@vJourneyman](https://twitter.com/vJourneyman)) and [Nick Korte](https://www.linkedin.com/in/nickkortenetworknerd/) ([@NetworkNerd_](https://twitter.com/NetworkNerd_/)), two Pre-Sales Technical Engineers who are hoping to bring you the IT career advice that we wish we'd been given earlier in our careers. In today's episode we share part 3 of an interview with Joe Houghes, discussing his transition to working for a technology vendor, communicating business value, Joe's move to Pure storage, and all the considerations he had when making the decision.

Original Recording Date: 07-07-2022

[Joe Houghes](https://www.linkedin.com/in/joehoughes/) is a Senior Solutions Architect at Pure Storage. Catch part 1 of our interview with Joe from [Episode 187](https://nerd-journey.com/dead-ends-and-defining-direction-with-joe-houghes-1-3/) and part 2 from [Episode 188](https://nerd-journey.com/the-surfer-of-technology-waves-with-joe-houghes-2-3/) if you missed them. Follow Joe on Twitter [@jhoughes](https://twitter.com/jhoughes).

# Topics – Moving to a Tech Vendor, Technical Leadership and Articulating Business Value, Moving from Veeam to Pure, Capture the Intangibles and the Must Haves

[[Joe Houghes]]
[[Pure Storage]]
[[Episode 187]]
[[Episode 188]]

## 5:20 - Moving to a Tech Vendor

- Nick speaks to rollback strategy and whether we keep this in mind when we decide to get more specialized (i.e. working for a technology vendor as one example).
- Joe's rollback strategy was that he was confident he could find a new role in a reasonable amount of time if he had to do it, mentioning his reputation in his local area and community.
- Joe's first vendor job was the 3rd job in a row that was handed to him because someone knew his personal and professional reputation (works well on any team, knows how to get things done) and skillset from the technical community.
    - The team lead for this job (at [[Veeam]]) had reached out to someone who said they did not have the skills for the job but encouraged the person to talk to Joe.
    - Joe had been using and evangelizing the technology in question already (in this case Veeam). The hiring manager reached out to and connected with Joe on LinkedIn, wanting to hire him. Multiple people within Veeam wanted to cash in on the referral bonus because they knew Joe and his potential.
    - This is a great way to come into an organization but can also add some pressure. When Joe met his new teammates for the first time he only knew 2 of them with one being the solution architect that Joe had interacted with while he was a customer.
    - Joe had attended VeeamON 2018 six months earlier and gave a presentation called [Automate Yourself out of a Backup Job](https://www.fullstackgeek.net/documents/VeeamON2018_JoeHoughes_Automate-Yourself-Out-of-a-Backup-Job.pdf) to a room of over 200 people.
        - At the time, the architect who led the advanced deployment and optimization course for Joe's employer was one of the session proctors at the time and had put some pressure on Joe to be able to answer questions in the area.
        - The other person on the team Joe knew (and had known for a while through the community) was [Tim Smith](https://twitter.com/tsmith_co). [[Tim Smith]]
        - Joe had to do company and culture fit interviews with people on his team that he didn't know. They wanted to know why he was such a big deal for one thing (which made things a bit awkward).
- Joe joined Veeam to as a pre-sales solutions architect focused on automation and integration.
    - On the team there were 3 people dedicated to different geographies. The rest were nationally focused and more specialized (Joe and some of his peers).
    - This was interesting because to this point Joe was turned down for 6 solution engineer (SE) roles and one technical partner manager role.
        - Joe had been turned down previously due to being too technical and not having enough "sales" experience.
        - But when they needed someone who knew the workarounds at a large scale and had focused on automation, he was at that point a good fit.
    - SEs (solutions engineers / sales engineers / systems engineers) were assigned to a customer based on size of that customer. The customers were spread across segments like SLED (state and local education), commercial, enterprise, etc. A few were assigned to specific key accounts.
    - SAs (solutions architects) were brought in for large deals or large architectures requiring additional expertise (could be the regional SA or the specialist SA depending on the need).
        - For example, Tim Smith might cover Microsoft 365, other solution architects would focus on public cloud, some would focus on product performance at scale, and Joe was focused on automation and integration.
        - Joe says sometimes his role ended up being an interim / handoff to post sales and helping the customer get to implementation of the product. John classifies this as design and technical proof that something can be done with the product.
        - Joe says he and his peers would often work with a data dump from a customer environment (RV Tools or other) that had details of networking, storage, other details, and would combine that with goals and desired outcomes the customer had. Joe and team would also ensure customers knew about the full product capabilities that could add value to the environment beyond just backup and recovery.
        - As an example, Joe liked to share with people that they could do patching against clones of their environment so as to patch on production systems without patching in production.

## 13:26 - [[Technical Leadership]] and [[Articulating Business Value]]

- Nick calls some of this technical leadership (encouraging people to get the most value possible out of the investment).
- John likes the idea of sharing benefits of an investment with multiple organizations inside the company (i.e. benefits to the backup team and benefits to the patching team). John says this also solves the problem he had back in the day of moving to the newest version of a backup product but not being able to articulate why.
- Joe mentions this is a skill lacking for technologists. We are so focused on the things we do for our job role, and because of the organizational structure, the value we provide is our role and how many buttons we click in a day.
    - Joe shares with people that a technologist's value to the organization is the knowledge that person possesses, and if you're focused on automation it's about taking the things you know and the things you can do and presenting them as capabilities to as many others within the organization as possible.
    - Take your skillset and make it a commonly accessible job function that others can do, and you can start working on higher level things.
    - For those who don't like dealing with the business side or don't focus on it enough, we have trouble pitching our ideas (or things we want / need as technologists) and sharing how they are a benefit to the organization even if they cost money.
    - For example, using a technology in a new and interesting way can provide a different type of value to the organization.
    - As technologists working in the trenches sometimes, we don't take time to think about how the organization we work for makes money. That means we do not think about how our daily work can affect whether the company makes money.
    - Increasing revenue is not the only benefit to consider. It may be adding new customers with less effort, reducing friction in a process, etc.
    - Joe feels we should be able to define our role in terms of what it means to the business (a positive enabler of the business or maybe an insurance policy against certain things that could go wrong).
    - Joe learned a lot by working in organizations where IT reported in to the CFO. Joe learned how to pitch (or sell) his ideas / products the team wanted to purchase and bring into the organization in terms of what it meant for the business (intrinsic value or future value in terms of the way the business made money / operated).
        - John suggests we think about how our work / our team's work is directly in alignment with business goals, etc.
        - If we are thought of as an insurance policy, we need to be able to articulate the likelihood of the various scenarios insured against and then the monetary impact that each of the scenarios can have on the organization (i.e. if a machine goes down here's how much money we lose).
        - Do the math on all the possible scenarios you're insuring against. That's a budget justification!
    - Joe says it was empowering at the organizations where he worked when the individuals in IT could explain the majority of what our job functions were or what projects were in flight during an "elevator conversation" with the CEO or CFO.
        - Imagine you have 30 seconds to articulate in executive language that's easily understood without going deep into the tech.
        - In organizations where people could do this, IT was not thought of as a necessary evil but a real part of the business.

## 20:11 - Moving from Veeam to Pure

- Joe wasn't looking to leave Veeam at the time. It turns out Joe moved cross-country as well interviewed for and switched job roles all at the same time during a pandemic.
    - It was about 8 months before Joe even met his boss at Pure Storage in person.
    - People asked Joe about taking off the green hat and leaving Veeam. It had become a large part of his public persona, and people couldn't believe he would so easily hang it up to put on the orange Pure hat.
    - Joe stumbled into it. He saw someone at Pure Tweet that they were looking to hand over the reins on the FlashStack role, and being curious Joe reached out to see if that meant this person was leaving the company.
        - Joe mentions Pure Storage as a company he would have left Veeam for if an opportunity came up being something he had thought about even before this.
        - It turns out this person was moving into people leadership and needed someone who knew the technology and had deployed it in the real world. They also wanted someone who was plugged into the technical community (the VMware community, overall tech community, Cisco community) and could communicate / present well to others.
        - Joe happened to talk to the right person at the right time. Because of his past experience, it was a good fit. It was offered to him after going through the process.
- Joe did not like a lot of the repetitive tasks that were part of his job and mentions he was never a big fan of being a pre-sales solutions architect.
    - Joe feels like he is customer focused, a decent presenter, and can give a lot of passion to folks about using the technology they are using but had trouble seeing himself tied to a sales number (i.e. did not want to lose the sale for someone else because he didn't perform well). In this case it was a national number.
    - Joe really considered taking the counter offer from Veeam that was for more money, would have him doing the same job, and a possibility of taking a different role when it came up.
    - The desire to go to Pure (since he had already been considering them as a future employer), do interesting and different things, and be more involved in the community would allow a shift in focus to technical marketing.
    - There was also more runway to do more automation and expand into the infrastructure as code space (which he really wanted to get more into), and Joe finally decided to make the switch.
- John mentions he had a bit of a parallel experience. For him, Google Cloud was a company he would consider leaving VMware for one day. What made Pure a company like that for Joe?
    - A lot of it was Joe having a personal rubric for this kind of change.
    - The number 1 thing for Joe, especially after having bad roles in the past, was about a 60 / 40 split between the direct manager he would have and company culture (includes fit with the team he would be joining).
    - The culture at Pure aligned with something he had not heard bad things about compared to other technology companies. Joe also reached out to people he knew at Pure to get an idea of what it was like.
    - Beyond these it was the technology and whether people he knew at the company already (or those he could see from the outside) really enjoyed their job combined with whether the company supported people doing things about which they are passionate.
    - Joe wanted to continue leading the PowerShell User Group and VMware User Group and speaking at events.
        - He wanted a company that was very invested in the community aspect of things and letting employees choose their own adventure for their career path. It would need to be a company that says "you're still doing goof things for us and by you doing this stuff on the side it's still going to bring a benefit the organization overall."
        - At other technology vendors where Joe had spoken to employees, he asked about presenting / community involvement / side projects and how many folks were doing those kinds of things. Joe needed to know if it was supposed at the company as well as Veeam had been supporting Joe to that point.
            - Joe calls this a desire / career baggage that he would bring to wherever he landed.
    - John says it is a great thing to have the list of things you want to continue doing as you move to a new company so you can determine if the company will support those activities.
        - If a company seems to be supporting that through what we see from multiple people at that company and you can go confirm that to the best of your ability, you know if that company came calling it is one of the phone calls you would take.
        - Joe says defining his priorities was very helpful. He had been reached out to by multiple companies about publishing a book or some training companies but has not jumped into that due to existing commitments with community participation.
            - Joe also knows doing this the first time is going to be a massive undertaking, and he has to be willing to dedicate the time to do it.
            - But these items became questions to ask hiring managers about whether they and the greater company would support those activities if Joe decided to do them.

## 29:17 - Capture the Intangibles and the Must Haves

- Nick agrees and says having the list of what we might call intangibles (things that don't really show up as part of a compensation package) ready and adding to it over time is important.
    
    - A piece of career advice Joe got years ago was from someone who had retired from IBM and came to work at the hospital where Joe worked.
        - This person came to the hospital to work with his son who was getting into tech. And the person also knew retirement would have been otherwise boring.
        - This person told Joe (about working in tech), "in the end the pay is the same…. In the end, it comes down to your happiness, it comes down to your benefits, it comes down to your work life balance or whatever it is you want to do and if you're company is going to let you do that. Because if not, chances are you can find someone else who will let you do it, and the chances are the pay is the same over there. So think about all the things that come with it…not just the paycheck."
    - Was that our mic drop moment?
        - We all definitely need to think about these things, and it's another pattern we've stumbled across.
        - You can't think about what is important to you as you get a call to get recruited. That is almost too late.
        - Think about it now as you're doing your current job.
            - What is it you wish you could do?
            - What is it you're being supported in now that has become critically important to you (and a need in anywhere you work?
            - What are the freedoms that I miss from previous roles that I don't have now?
        - Make the list of these to form the "must haves." The next tier down you try to get as many as you can, and the bottom tier is more of the "it would be really nice to have this."
        - Joe says take an inventory of things you need, and write it down.
        - We should also be taking into consideration career and personal goals outside the tech we want to work on, the skills want to achieve, or certifications we might be chasing. Think about the long term goals you have, write them down, and review them every so often.
        - See if what you are doing right now is getting you closer to that goal. And if not, you probably need to adjust the journey you're on right now or assess if that goal is really a goal for you any longer (either could change).
        - If you continue to do the same thing and have a set of goals you are not getting any closer to you are going to be unhappy, whether that is now or later.
        - Goals change over time, need to be reviewed, and can help you classify things as negotiable / non-negotiable.
            - Maybe you don't want to write a book but want to have more time to write blogs, for example (i.e. more time to write in general).
            - Or maybe you do really want to write a book and the support for blogging time doesn't help you get there / isn't something that you see as a benefit.
- Should intangibles be part of an offer letter?
    
    - In Joe's case he trusted the hiring manager as much as he trusted others within the organization where many leaders / employees who had been onboard a short time stated there would be support for the types of things Joe wanted to do.
    - Pure was also known for being a very community and individual achievement focused organization, knowing the benefit they would get if employees raised their profiles / made a name for themselves in the technical space.
    - Joe was told he would get full support to do the things he wanted as long as it didn't become a hindrance to his existing responsibilities, and the company would also be watchful of whether the things he is doing might help him break into new areas of expertise (i.e. mindful of his progression).
    - Joe did not have these written into the offer letter. They were personal ambitions of his that may or may not come to fruition.
    - When Joe brought this up it was such a non-issue that it made him even happier. He is glad to have verified and grateful to be supported in these endeavors.
- We'll have to follow up and see where Joe goes from here!
    
- Referenced in the intro
    
    - John and Nick attended [[VMware Explore]] 2022 US in San Francisco last week. Catch the recording of the session Adventures in Technical Career Progression [here](https://www.vmware.com/explore/video-library.html#text=%22VIB1558US%22&year=2022) (requires a free VMware Customer Connect account to view). pp* During the conference they even ran into Joe Houghes briefly.
- Referenced in the outro
    
    - Some of Joe's experiences reminded John of Stephanie Wong's story. You can find her story in [Episode 177](https://nerd-journey.com/follow-the-excitement-follow-the-challenge-with-stephanie-wong-1-2/) and [Episode 178](https://nerd-journey.com/being-a-great-generalist-and-finding-your-voice-with-stephanie-wong-2-2/). [[Episode 177]] [[Episode 178]]
    - [[Andrew Miller]] spoke about continuing to be in the right place, and the right time will eventually come. Check out [Episode 167](https://nerd-journey.com/pause-and-step-outside-with-andrew-miller-3-3/) for more details. [[Episode 167]]
    - We discuss researching a potential employer. Though we did not mention it in the show, HR professional Marisa Eckberg had some additional recommendations for investigating a company's culture in [Episode 49](https://nerd-journey.com/nerd-journey-049-marisa-eckberg-pt-1-paid-time-off-and-company-culture/) and [Episode 50](https://nerd-journey.com/nerd-journey-050-marisa-eckberg-pt-2-hr-and-company-culture/) that are worth referencing. [[Episode 49]] [[Episode 50]]

## [Contact us](https://twitter.com/NerdJourney) if you need help on the journey.