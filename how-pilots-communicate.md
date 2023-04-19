![](https://media0.faz.net/ppmedia/aktuell/928556993/1.3391316/width610x580/hier-der-umgang-mit-problemen.jpg)

„Dealing with problems“ – © Yang Liu, Taschen Verlag, Köln

# Andreas Rau – How pilots communicate

... and what we as Software Engineers/ Designers and Businessmen can learn from it

## TLDR

In this article you will learn about miscommunication pitfalls in aviation and that the same pitfalls occur in software development, design and business. We will dive deeper into topics like the aviation decision making (ADM) process. Have a glance at intercultural communication. How it dictates the way we speak and understand our world. Further an introduction to my own personal experiences and how you can sabotage the productivity of your organization effectively.

In the end we will apply the ADM to foster and improve your communication.

## How miscommunication can trigger disasters

On 25th January 1995, the Avianca flight from Bogota, Colombia, to JFK Airport in New York, was running out of fuel. Air traffic control (ATC) at the JFK kept the airplane in a holding position until their plane's fuel tank was running dangerously low.
When revisiting the conversation between the airplane and the ATC at no point in time the word "emergency" or "mayday" was communicated by the pilots. The captain reportedly told the first officer to "tell them we are in an emergency". instead of letting ATC know that the airplane is in a serious situation, the word "emergency" was not communicated. Instead, the first officer told ATC "We're running out of fuel"
"With air traffic control unaware of the gravity of the problem, the plane crashed just nine minutes later. **Out of the 158 people on board, 73 died, including the pilot and the co-pilot."**

## The complexity of reality

The Austrian philosopher, Ludwig Wittgenstein already shared with the world in 1921 in his famous book "Tractatus logico-philosophicus".

> "Ordinary language is imperfect and cannot capture the full complexity of reality."

From this, we can derive that even under calm conditions the human language fails. In the before shown example, it gets even worse under stressful conditions.

## From Aviation to Software Development

First of all a disclaimer. I am a software developer and paragliding pilot. I am well aware that in airline aviation serious mistakes can endanger passenger lives and software development in most cases does not. What I am interested in, are the circumstances of mistakes and the diversity of people involved as well as their communication. When I was revealed how many aviation accidents happened because of miscommunication I started to question if the same situations occur in my day-to-day job and even in my private life.
In both worlds, we face time-critical decisions. We both need to react to events that happen while we are executing tasks. I see only a few differences. One of them is that there are more decisions and events to consider in aviation. This means that there are more of them in a shorter amount of time. Both worlds make decisions. In software development, those decisions and their effects as well as their execution by 3rd parties take more time than in aviation. Think about this statement for a moment. Compare a 2h flight with all the decisions that you might need to take as a pilot to a software development sprint of two weeks.

I am a paragliding pilot, so nothing close to a real pilot, but in my experience, the amount of decisions I have to take in a 2h flight compared to a two week sprint is about the same. In the next part we will dive deeper into how the aviation industry takes decisions.

## The aeronautical decision-making (ADM) process

The airline industry has identified a process that every aircraft pilot has to obey. Aeronautical decision-making (ADM) is a five-step process that a pilot needs to conduct when facing an unexpected or critical event. Adhering to this process helps the pilot to maximize his success chance.

1. Start to **identify your situation**, this is the most important step. Accurately detecting it enables you to make correct decisions and raise the probability of success.
2. **Evaluate your options** and in my experience, there are often more than I expected to be in the beginning.
3. **Choose** from your generated options while accessing the risks and viability.
4. **Act** according to your plan.
5. **Evaluate if your action was successful** and prepare for further decisions. You will always have further decision points where you need to start the process of ADM again.

This process is only one of many more in aviation.

Let's apply this to a software bug.

1. **Identify your situation**
   - What is the real cause for the bug?
   - Is it reproducable, part of my product scope or not?
   - Did this bug occur because of our code changes or of dependency updates?
   - Is this bug on live systems?
   - Can I resolve the bug?
   - Do I need help?
   - Can I get more information?
   - ...
2. **Evaluate your options**

   - Patch the bug with a new version.
   - Ask for help.
   - Investigate further
   - Decline because it's a feature and the user is using it incorrectly.
   - ...

3. **Choose**

   - Let's assume the bug is on a live system and needs to be fixed asap -> Patch the bug with a new version.

4. **Act**

   - _Please enter your routine for fixing a bug here_

5. **Evaluate if your action was successful**
   - Is the live system running as expected and was the bug resolved?
   - Should we establish a standardized process to fix bugs?
   - Did I resolve the bug in time? If not practice time management.
   - Is there anything we can do to mature the product?
   - Feedback to QA.
   - Share your insights.
   - Improve test procedures.
   - ...

This is an easy example to illustrate how the ADM process can be applied to software development. A lesson I learned from paragliding and software development is to always finish your plan even if the circumstances change during your action. Trust in your abilities and execute your plan. If you followed the previous steps correctly your actions cannot be severely wrong. Given that the information you based your analysis on was correct.

Which language we use is an important part of correct communicating with each other, let's have a look at aviation english next.

## Aviation English

Pilots and crew, regardless of their own native language or any other languages they speak, travel across the world. They have to be able to communicate with every airport and every ATC they face, on a daily basis. This was a challenge to solve, which occurred with the rise of civil aviation in the mid-20th century. There was already an unspoken agreement in place. The language of the sky at that time was Aviation English. Now Aviation English is, as misleading as it sounds not the English language that we know. In fact, it is a separate language compared to what is spoken on the ground. Even native English speakers have quite a long road to learn it ahead of them. It uses standardized phraseology in radio communications to ensure aviation safety.
Since the manufacturing, as well as the operation of air crafts, was dominated by English-speaking countries. The International Civil Aviation Organization (ICAO) slowly but steadily understood one thing.

`Good processes and procedures themselves will not solve the issue.`

In 1951 they suggested that English should be the de facto international language of civil aviation.
Let me emphasize that ICAO in 1951 only **suggested**, that English should be the language of the sky. It took them 50 more years, in 2001, to actually determine English as the standardized language of air transport. With said standardization, they published a directive. It stated that all aviation personnel, including pilots, flight attendants, and aircraft controllers must pass an English proficiency test and meet the requirements. Before that, the language skills were **not checked in any standard way**.

Now let that sink in for a moment.

## Tech/Design/Business English

In Tech, Design and Business we do have our own set of languages. I am not talking about programming languages. Try to explain to your grandma/grandpa what exactly was decided in the last SAFE PI planning. You can substitute PI planning with almost every other meeting we have in our company. Now ask for honest feedback: "Can you summarize what I just told you?" Be prepared, it might be the case, that your elderly relatives are very kind to you and try to avoid the task you just gave them. But they will most likely not be able to summarize what you have explained to them. I already have issues trying to explain such things to my parents. I can already sense while speaking, that my parents won't understand a word.

Although you and I were using English as a language. Our terminology, acronyms, processes and neologism makes Tech/Design/Business English very complex languages.

## ¿Habla español?

I had the luck to work with many great people in my career so far and I am more than grateful for every one of them.
Nevertheless, I discovered a couple of things for myself over the years. We are all working in the field of Information Technology, Design, and Business. We are all speaking the same language and share the same enthusiasm and skills. And still, we are different. We are all shaped and formed during our private and professional lives in ways one can only imagine. We all have a wide range of different religious, social, ethnic, and educational backgrounds. Living close to our families or far away from them. These differences became more and more visible to me with the amount of time I have spent with them. Differences in how colleagues perceive what you are trying to tell them. Differences in how people value their pursuits and sometimes sacrifice their benefits for the sake of the group. Differences in how authorities communicate with subordinates and vice versa. And these are only the people that I had the chance to work with. You have made your own experiences and shared time with so many more great souls.

What we are now tapping into is the field of intercultural communication. Gert (Gerard Hendrik) Hofstede (Dutchman, was born on October 3, 1928, Haarlem, Netherlands) is a Dutch sociologist who proposed an indicators set that determines the various peoples cultural characteristics based on research conducted in the 1960-70s. The subject was part of my studies for one semester. At that time my brain did not understand the extend of the topic and how important it will be for my future life.
Intercultural communication describes the discipline that studies communication across different cultures and social groups. In other words, how culture affects communication. There is an impressive amount of research done in the field of intercultural communication which investigates topics like:

- Collectivist versus Individualistic
- High Context versus Low Context
- Power Distance
- Feminity versus Masculinity
- Uncertainty Avoidance
- Long-term Orientation versus Short-term Orientation
- Indulgence versus Restraint

All of them are worth investigating and I encourage you to do so. I have gathered [further readings](https://uniwork.buxdu.uz/resurs/12547_1_254C840264D12E1ED12D280C545FD07FDF196E34.pdf) which should get you started.

## Personal

On top of every culture, there is you, you how you perceive the world around you, and you, how you make sense of everything which is shaping you. Your personal touch might very well steer you into a counter course of what your culture tried to induce into you for the entirety of your childhood and more. I hereby am not suggesting that you are all rebels. I want to highlight that the personal level of communication can be far off from how the folks back in your hometown used to talk. If you haven't already met a vast variety of people during your school time you will definitely do so in your professional life. In Software Development I have had the chance to work with many great people from all over the world. Although at some point already familiar with the concept of intercultural communication I often unknowingly said or did something I thought would be appropriate at this exact moment in time... it wasn't.
Having the basics of intercultural communication in mind is necessary but not sufficient. Get to know the person you are talking to and discover a new level of communication.

## Interim

We have learned a couple of things about communication, let's take a second look at the introductory example. The first officer, in disregard of what the pilot told him, made a severe mistake in not properly communicating the extent of the situation. Maybe, in her/his culture, it is common to understate issues and it can be rude to talk about severe issues or problems directly. Nevertheless, the situation required clear and fact-based information. Correct identification of the situation was therefore not possible. All further steps in the aeronautical decision-making process of the ATC were from then on based on false information and we all know the outcome.
I often find myself in meetings where colleagues or superiors introduce me to a brand new process that will revolutionize how our company works, solve all the problems and issues at once and make us all happier. Thanks to good marketing everybody is excited and eager to implement the new processes with huge costs in time, money, and motivation only to find out that in the end, it didn't work — again.
I do not want to sound pessimistic, I want to tell you my perspective.
Looking into software development and all the processes we have,
`I want to learn from aviation and invest more time and effort into educating our colleagues on how to properly and fruitfully communicate in a standardized and organized way.`

Important factors for this, in my opinion, are honest, transparent, and truthful communication where hidden agendas or intercultural communication pitfalls are avoided.
And to make one point clear, more communication is not equal to better communication. I think based on this foundation, processes can be fruitful.

## Lost in translation

An enterprise company operating in multiple countries spread over multiple continents. What is the first thing that comes into your mind? For me, it is a rich and diverse project team over as many timezones as possible. During my early career, I was exposed to a trend in IT where teams could not be diverse enough. I know many companies which still steer 100% in this direction, but I also know many who are not. What I am trying to do here is to make you as a reader think. Think about your current circumstances, where are you working? Who are your colleagues? Do you work effectively together? Is communication easy for you or is it a burden? Do you have the feeling that meetings actually create useful artifacts or are they mostly a waste of time? Ask yourselves these questions and assess. I can only speak for myself and I have observed both. In my work, a rich and diverse team can accelerate me, but there have also been times when it slowed me down. When looking at the example I showed you earlier. Aviation English is a language that was an agreement on communication but it was not part of any training or checks. It is important to say, that this has nothing to do with the people per se.
When I came to college, in Germany, I had the opportunity to choose if I wanted my studies and lectures in German or English. I was motivated and although my mother tongue is German, I wanted my studies to be in English. This was exciting to me and silly young me thought it would be good to already study in English since the language of IT was English. Now I really regret my decision. During all of my studies, I was confronted with a lot of bad English. Many interesting topics got lost in translation, simply because the lecturer was not proficient enough in her/his language skills. Please do not get me wrong here, my English at that time was not better either. I am just trying to make the point that the content of a message can be severely harmed when not communicated properly. During my career, I often did applicant interviews and had to clearly state my veto. The applicant might have had the best CV, and great experience, but bad English skills.
In the IT industry, we have the great opportunity to have rich and diverse teams. This is a circumstance not exclusive to IT but it is still in my opinion a gift we should be thankful for. To make sure we respect and maintain said privilege I have a suggestion. I am suggesting that if we put so much emphasis on what technologies an applicant knows, for how many years she/he has worked with tech stack a, b or c. We should also check thoroughly if her/his English skills are proficient enough to communicate properly in a big and diverse company. We should offer and also expect and check from new hires to improve their language skills, if necessary. Language should never be a limiting factor.
Coming from IT and especially web development, I have to deal with accessibility day in and day out. For me, it is easy to understand that digital tools and devices are about inclusion. In my opinion, it is the same with language.

Let's take this a step further. A good colleague of mine introduced me to an amazing article on some second world war CIA practices.

## How to effectively sabotage your organizations productivity

The CIA created the "Simple Sabotage Field Manual" in 1944 on how everyday people could help the allies weaken their country by reducing production in factories, offices, and transportation lines. There is a wonderful article from the business insider which highlights that. Despite written in 1944 these instructions are timeless. I am sharing with you the selected list of instructions from the business insider article, filtered for communication . See if any of those listed below remind you of our organization, your colleagues, or even yourself.

**Organizations and Conferences**

- Insist on doing everything through "channels." Never permit short-cuts to be taken in order to expedite decisions.
- Make "speeches." Talk as frequently as possible and at great length. Illustrate your "points" by long anecdotes and accounts of personal experiences.
- When possible, refer all matters to committees, for "further study and consideration." Attempt to make the committee as large as possible — never less than five.
- Bring up irrelevant issues as frequently as possible.
- Haggle over precise wordings of communications, minutes, resolutions.
- Refer back to matters decided upon at the last meeting and attempt to re-open the question of the advisability of that decision.

**Managers**

- Hold conferences when there is more critical work to be done.
- Multiply the procedures and clearances involved in issuing instructions, pay checks, and so on. See that three people have to approve everything where one would do.

**Employees**

- Work slowly.
- Contrive as many interruptions to your work as you can.
- Do your work poorly and blame it on bad tools, machinery, or equipment. Complain that these things are preventing you from doing your job right.
- Never pass on your skill and experience to a new or less skillful worker.

I highly encourrage you to read the full [ business insider article](https://www.businessinsider.com/oss-manual-sabotage-productivity-2015-11) for some more bitter sweet laughs.

## Foster your communication

Although being funny to read, the sad truth is that some of these instructions are common practice in our organization. I advise you to take this list into your notes, bookmark the article, read through it frequently and ask yourself: Do my communication behaviors fall into the same categories?
If yes, no worries! Everybody has to start from somewhere. Remember the ADM process:

- **Identify your situation** and ask yourself: Am I sabotaging my company? It's important to be honest here! (Remember: Accurately detecting it enables you to make correct decisions and raise the probability of success)
- **Evaluate your options**, there are plenty! Seek feedback from people you trust and ask them for honest feedback on your ways of communication, do an [Udemy course](https://mercedes-benz.udemy.com/course/communication-fundamentals-how-to-communicate-better/). Heck, maybe even join a [debating club](http://www.debattierclub-stuttgart.de/)!
- **Choose** from your generated options while accessing the risks and viability.
- **Act** according to your plan.
- **Evaluate if your action was successful** and prepare for further decisions.

This is not easy - but it can be done. You can do it!

Now to bring this article to an end let's look at the last dimension of communication.

## Are you talking to me?

I often find myself in situations where I talk **about** colleagues and superiors rather than talking **with** them. Talking about colleagues is easy, but with most things in life, the outcome of easy is not great. It takes courage to work on yourself and even more to reach out for help. There is no effortless solution, be honest and ask yourself if you really want to change something about how you communicate and how you are perceived while communicating. This article is at most only a catalyst that will hopefully ignite your own journey.

## Recap

We have learned how two, at first sight, completely different professions share many fundamental communication skills. We have had a look at the aeronautical decision-making process, what intercultural communication is, that processes are only as good as the material we put into them to be processed, how to effectively sabotage your company and what you can do to foster and improve your communication.

We touched on many topics today and I hope this article touched you personally in at least one of them. If you now think about what you have read in the last couple of minutes I feel already successful in my educational mission and if you remember only one thing then something along the lines of this:

'Don't worry the worst mistake you can make, is to not communicate at all.'

## Further readings

As promised here you have a small collection to further educate yourself about the topics in this article.

[Full blown ADM](https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/phak/media/04_phak_ch2.pdf)

[Aviation English](https://en.wikipedia.org/wiki/Aviation_English)

[Understanding Intercultural Communication](http://kell.indstate.edu/public-comm-intro/chapter/2-3-understanding-intercultural-communication/#:~:text=Power%20distance%20also%20refers%20to,than%20distributed%20throughout%20the%20population.)

[Gert Hofstede - Intercultural Communication](https://uniwork.buxdu.uz/resurs/12547_1_254C840264D12E1ED12D280C545FD07FDF196E34.pdf)

[Business insider - How to sabotage your organizations productivity](https://www.businessinsider.com/oss-manual-sabotage-productivity-2015-11)

[Workplace Communication](https://justworks.com/blog/easy-ways-improve-communication-workplace)
