toc=true

+++

# 1. Logistics - Before the Workshop

✔️Decide the **_date and time_** of the event as per the convenience of speakers and audience. Conducting **_events during exams_** or some other important event might **_not be a good idea_** in general. Checking **_academic calendar_** and other events in KGP is suggested.

✔️Publicize the event at least **_2 or 3_** days before the workshop. Publicizing earlier will fade away the event info from memory and publicizing late will be difficult for the audience to plan for.

✔️Share the Post via Facebook, Twitter and Linkedin via KOSS Account.

✔️Speakers should be **_decided atleast a week_** before the workshop, giving them enough time to prepare.

✔️It is important to have _atleast two_ backup speakers for each speaker.(One for the speaker, one for the backup speaker)

✔️Speakers of the event should have enough practical experience with the topic. The experience is necessary so that speaker can convey the content in the simplest way and clear doubts.

✔️It is highly recommended that the Slides for the event are made from scratch by the speaker.  Preparing from scratch will add creativity and newness to the content. New and simpler ways to present a topic might come out.  Also...

​      🗸Feel free to look up at previous slides at [kossiitkgp/slides](https://github.com/kossiitkgp/slides) repo for inspiration.

​     🗸Make sure that something important that has been covered in the past doesn't gets removed.

​      🗸Feel free to remove or edit stuff if you ever feel some part of the content is unnecessary and irrelevant, after discussing with team mates. 

✔️Make sure to take feedback on the slides(content) from other members of KOSS regarding the slides. It is suggested to have the discussion over a meet to discuss things like potential queries from audience, thinking of ways to simplify content.

✔️Refer [kossiitkgp/mistakes](https://github.com/kossiitkgp/mistakes) repository to get an idea of what sought of things can go wrong.

✔️It is a good idea to record the event(offline/online) for the sake of posterity.

✔️Make a Github repo for the workshop with name as event name and year which contains - installation instructions, slides, references, recording and others. (For example refer - [1](https://github.com/kossiitkgp/git-and-github-workshop-2020), [2](https://github.com/kossiitkgp/REST-APIs-in-Flask-Workshop-2021), [3](https://github.com/kossiitkgp/Linux-Shell-Vim-Workshop-2021))

## 1.1 Internal

- Keep in touch regularly with other team mates on updates regarding the event. Regular communication on #events channel is suggested.
- Meet regularly to discuss stuff. It is advisable to send mail invites even for a smaller meet, to avoid procrastination.

- **Making the workshop interactive**: It is always a good thing to keep the workshop interactive. If the workshop is conducted offline, we can have members of KOSS help people personally with hands on during the workshop and clear doubts more personally. But during an online workshop, this is not possible. So for sake of interaction, the speakers can encourage the audience to share the screen to show the work, for kind of validation and it also helps the rest of the audience. Asking the audience to share their screen in case of difficulties should also be encouraged. However note that,**do not force the audience to share their screen for sake of interaction. It has be voluntary and audience should not feel uncomfortable through such actions.**

# 2. Technicalities - Workshop content

## 2.1 How to decide the Topic for the workshop

- Make sure that the topic adds value to the community. The topic doesn't have to be trendy or in vogue.
- Atleast a couple of members at KOSS should have enough practical experience to speak about the topic

## 2.2 How to decide the content of the workshop

Make sure that the content adds a practical value to the audience. It might be tempting to add bit of cool jargon or theoretically detailed stuff to impress. But it is not suggested. For every slide, ask - Is this something that adds practical value. Will knowing or not knowing a particular thing affect the practical understanding of the topic. For example, consider explaining the idea of Merkel Tree in git, it might not be necessary to include the explanation of Merkel tree. As someone getting started with git, it is more important to practically understand staging area, branching, commits, sending a PR, pushing and pulling. When we get into details like Merkel Tree, audience might loose track of the event and loose interest. However, for the curious audience, it is a good idea to include such things at the end of the workshop, and provide further resources to explore more. 

During the core period of the workshop, make sure that they get a **practical hands on experience**(which is what they have come for, otherwise they could have learnt it on YouTube too!)

Make sure to give enough time to cover the queries and concerns of the audience during the workshop.(without queries and interaction, the workshop would not differ from a YouTube Tutorial)

## 2.3 How to organize or approach content:

- **2.3.1 Introduction:** It is a good idea to tell the audience the following things: 

  - What they should take away from the workshop. For example, if it is git workshop, convey that by the end of the workshop they will be comfortable to track their project using git and know how to send a Pull Request properly to a open source repository on Github.

  - Give the audience about how the flow of workshop would be. For example...

    - While hands on, asking them to do them along with the speaker
    - There will be small doubt sessions periodically **or** may be if the speaker is comfortable, he/she may ask the audience to interrupt in middle and ask the query. It is a good idea to take breaks after each [microcentury](https://susam.in/blog/microcentury/)
    - It is a good idea to warn the audience if there is a long strech of theoretical discussion for the next few minutes.

  - **2.3.2 Introducing a new topic**: If you are introducing any new topic, it is suggested to try either of the two methods - 

    - **First principles approach**: Introducing the topic from the ground up. Don't just bring up a word and say, **_"we are going to learn about this X topic now"_**. Bring the situation to explain why something of this sought is necessary. For example, in git consider the topic "branching". Introducing a problem in the beginning, where git branching is a super-useful solution, this will help the audience grasp the idea better.

    - **Using Analogy**: It is always a useful thing to give a analogy with something which people already know. For  example, in git consider the idea of staging area. The staging area is [generally difficult to grasp](https://github.com/kossiitkgp/mistakes/blob/master/git-workshop.md#git-workshop-2018) for someone new to git. To explain this, one can use "shopping in a mall"  analogy. 

      - Selecting items from the rack <-> Making changes in the files

      - Adding items in the shopping cart <-> Adding files in the staging area using `git add `

      - Billing at the counter <-> Commiting the changes

        The above analogy was inspired from a [stack exchange answer by Spoike](https://softwareengineering.stackexchange.com/questions/119782/what-does-stage-mean-in-git), Later modified by @Shankusu993 . Good analogies can be found by searching for intuitive explanations for the topic on web and also by brainstorming with the team. The above analogy was a result of both!

        **Caution**: **Make sure to be aware of the consequences of the analogy used. Sometimes analogies can be misguiding. In that case, it is suggested to chose a different analogy. Alternatively, you can also warn the audience that the crafted analogy does not hold for further ideas. The analogy is only helpful for this concept.**

    # 3.  Logistics - After workshop

    ✔️Upload the slides and reference in the Github repo made for the workshop

    ✔️Once audience has learnt the basics from our workshop. We should encourage the curious to explore more advanced and interesting topics on their own. Hence for such people, update further reading material or links to explore more regarding the topic.

    ✔️Share the updated repo's link along with a thanks for the audience. It is a good idea if the post explains the contents of the repo. A Facebook post after the workshop serves the purpose (For example, refer - [1](https://i.imgur.com/IoZsw6r.png),[2](https://i.imgur.com/fHflDQ2.png)).

    ✔️For sake of posterity, update the [kossiitkgp/slides](kossiitkgp/slides) repo

    ✔️Update the [kossiitkgp/mistakes](https://github.com/kossiitkgp/mistakes) repository 
