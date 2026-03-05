**Contents**

1. [First things first](#first-things-first)
1. [Pre-registration](#pre-registration)
1. [Distribution of Work](#distribution-of-work)
1. [Registration](#registration)
	1. [Project Approval Guidelines](#project-approval-guidelines)
1. [Complaints and Queries](#complaints-and-queries)
1. [Coding Period](#coding-period)
1. [Mid Evals](#mid-evals)
1. [End evals](#end-evals)
1. [Feedback](#feedback)
1. [Certificates](#certificates)
	1. [KWoC Website Archival Guidelines](#kwoc-website-archival-guidelines)
1. [Miscellaneous](#miscellaneous)

## First things first 

- KWoC is a month-long event, generally conducted in December.
- Registrations start at least a week before the coding period (more than a week is preferred).
- Coding period is generally 4 weeks long
- Mid evals are held around 2 weeks after start of the coding period.
- End evals are done after the coding period

## Distribution of Work

KWoC broadly involves the following separate tasks:
0. Finalizing the timeline, getting sponsors for goodies (optional), and general planning.
1. Conducting an introductory seminar, and other publicity.
1. Preparing student and mentor manuals.
1. Hosting and managing the website (backend + frontend + stats script).
1. Handling emails - including previous contributors and mentors, responding to queries, and eval reminders.
1. Handling backend tasks - including approving projects, keeping track of stats, and handling mid and end evals.
1. Managing the Discord server - replying to queries, announcements, and moderation.

### KWoC Captains
All of the above tasks, except for the planning and timeline should be assigned one or more executives as captains. These captains do not necessarily have to restrict themselves to only work on the assigned task, but would take the responsibility of keeping track of progress, delegating work to CTMs, and ensure it happens. CTMs on the other hand, need not be assigned specific tasks but are encouraged to try out different things.

Assigning executives to specific tasks is not meant to break the flat hierarchy but instead to prevent confusion. During KWoC, some executives take up specific jobs anyway and unofficially act as captains. It is better if this is done earlier and more efficiently.

### How to assign captains
- During the planning phase, the executives should divide the tasks among themselves. They may ask the advisors for help.
- Some larger tasks such as managing the website may be assigned multiple captains - e.g., one for the backend and one for the frontend.
- If an executive may be busy due to any reason (internships, interiit, etc.), other captains should be assigned to the same task as backup.
- It is advisable to create a checklist for ALL tasks and the assigned captains during the planning phase.

## Pre-registration

- The following things should be ready (or updated) :-

  - KWoC Website:
    - Registration feature, should be tested internally.
    - Last year's stats.
    - Last year's testimonials.
    - FAQs.
  - Student and Mentor Docs of KWoC. Make sure that the content of the doc is updated with the current rules of KWoC(especially rules like Mid Evals and End Evals criteria). If there are any new important changes, do mention them in the docs. 

- A dedicated slack workspace for KWoC. If the old one has reached the maximum free limit, create a new Slack workspace.

- Printing and circulation of posters to every hall's, main building's and nalanda's notice boards.

- Intro Seminar of KWoC should be conducted, a week before the registrations begin.

- If possible approach a few organisations or companies - well before the website goes live - to sponsor KWoC for providing swags/goodies to the top-contributors (the number of top-contributors might vary based on what we get in the swag). Do NOT term them as `winners` - [KWoC is not a competition](https://github.com/kossiitkgp/mistakes/blob/kwoc-22-mistakes/kwoc20.md#5-reduce-competive-nature-)

## Registration

-  It is recommended to start the registrations in the first week of November. At maximum, the registrations should begin by third week of November. Please do not delay the registrations further.
- Mentor/Project Registrations should begin earlier than Student registrations to ensure they see some projects on the first day. One week earlier is recommended.
- Release a Facebook, Twitter and LinkedIn Post from KOSS account. The post should contain the following things:
  - Briefly about KWoC
  - Mentor and Student Docs' Links
  - Instructions to register
  - A KWoC workspace invite link. (The previous workspace can be reused or a new one can be made)
-  Mail previous year's students and mentors that kwoc is back - along with working registration links.
-  Make sure to take database backups periodically.
-  When projects are being registered, they should not be immediately shown on the Projects Page. The projects should be shown only when they are accepted. During the registration period, the projects should be accepted frequently(atleast on a daily basis). If we are rejecting a project, mail the mentor why we are doing so.  

### Project Approval Guidelines

Below are the minimum required criteria to approve a KWoC project. Further discretion may be required for approving certain projects. Ensure that projects inspire young developers to get involved in Open Source software, and help them master Git/Github. 

> [!NOTE]
> Keep the [Mentor Manual](./mentor-manual.md) updated with these guidelines.

- A project must have more than two easy-to-fix and at least one moderate-level issue
- A project must have at least 5 issues
- A project must have a dedicated public communication channel
- The mentor must have merge access in the project
- A project must have a descriptive README
- A project must have an actual usecase and not just be a tutorial/example/sandbox repo
- A project should have an open source LICENSE
- A project must have at least a minimum amount of development, There should be some sort of roadmap laid out

## Complaints and Queries

It is suggested a group of dedicated people from KOSS handle complaints and queries through out KWoC. The responsibilities can be split shift wise - One group can handle complaints during the day and the other during the night. However, **please make sure that the queries are answered within 24 hours**. KOSS members should be active at the following places to answer queries and complaints

- Facebook, Instagram, Twitter, and Linkedin of KOSS account.

- Mails received at admin@kossiitkgp.org

- Discord Server of KWoC.

- ~KWoC Slack workspace~ (inactive)

- ~A Github Repo for Technical complaints. For example refer [this](https://github.com/kossiitkgp/kwoc-bugs)~ (archived)

> [!TIP]
> Make sure to keep the FAQ page exhaustive and detailed. Update the FAQ page regularly if new frequent queries come up. Along with answering the queries, it is a good idea to share the FAQ Page of KWoC, so that future queries can be addressed without need of contact. 

## Coding Period

- Sometimes due to serious reasons, participants(students or mentors) miss out the registration period. In such cases, collect the details from the participant and add their entry in the database manually.
- Make sure that the site is regularly up and working, especially the stats tables. A group of people should be vigilant in this matter.
- Any important changes or announcements(like informing in case of spam, changing Mid evals dates) are to be made on both website and via email.
- If a project is not approved then mail the mentor immediately for "Why their project is not healthy for KWoC" and "What they can do for it to be approved" (if possible).

## Mid Evals

- It is important to inform about the Mid evals and its criteria via email and KWoC website atleast 3 days before the Mid evaluation. 
- **Mid evals criteria**:
  - **KWoC 20 criteria**: Having atleast one commit before was the criteria for clearing Mid evals. If the mentor has been inactive and the PR remains unmerged. We asked the students to mail 
  - In the previous KWoCs, there was a form, which was to filled by mentors. However, to automate stuff the single commit criteria was implemented. 
  - You are encouraged to make changes in the Mid Eval criteria, but make sure that it is fair and is not too hard to clear. (Remember, KWoC is meant to encourage beginners)
- In case of serious emergencies, do not hesitate cancel mid evaluations. For example, in 2019 when there was a ban of internet in few states, the mid evals were cancelled. 
- In case, if any individual is unable to clear mid evals due to some genuine reasons, it should be considered.
- Mail the students a day or two before the dead-line of mid-evals as a last reminder.
- Announce the results of Mid-Evals via mailing the students (in both cases) & via a pop-up on student's dashboard.

## End evals

- **End evals criteria**:
  - Till KWoC 20, the end evals criteria was asking the students to write a blog that summarizes their work. And the students would be evaluated based on the blog.
  - The above criteria was made to make sure that no mentor would unfairly pass/fail a student as per his/her wish.
  - Feel free to come up with any other criteria for End evals, but make sure that no student should have an unfair advantage.
- If blog criteria is being followed
  - Make sure to inform the students atleast a week time after the coding period ends to write the blog
  - Inform the criteria for end evals via email. Examples of previous blogs should be given.
- If  a student was unable to submit his/her blog before the deadline due to some genuine reasons. Do consider it later, its a month long effort!
- **Evaluation of blogs**:
  - For evaluation, distribute the blogs among members of KOSS for evaluation
  - While evaluating, if a member finds some blog that doesn't seem to clear the end evals, make sure to cross verify the same with other members of KOSS
- It is good to inform the participants by what date, they might expect the results of KWoC after they have submitted their End evals Blog. 

## Feedback

Share an **anonymous** feedback form with following
1. Some objective questions, where they can rate about different aspects of KWoC-website, doubts clarification,coding experience.
2. Subjective questions - What did they like about KWoC, What did they didn't like about KWoC, Anything they would like to tell us.

## Certificates

- Along with the name of the participant, the certificate must contain the following links
  - Verification link: A link of certificate hosted on a Public repository of KOSS - [kossiitkgp/public-files](https://github.com/kossiitkgp/public-files)
  - Stats link: A link containing the Student's or the Project's stats respectively for a student or a Mentor.

- The certificates must be hosted on the public files repo - [kossiitkgp/public-files](https://github.com/kossiitkgp/public-files)
- The certificates in PDF formats should be sent via mail to the participants.

### KWoC Website Archival Guidelines

- Move the website from `kwoc.kossiitkgp.org` to `kwoc{Y}.kossiitkgp.org` (e.g. `kwoc19.kossiitkgp.org` for KWoC19). Thereafter, the stats are hosted on the latter while the former is reused next year.

- archived websites are branches in the frontend repo
- these branches are deployed on [netlify](https://www.netlify.com/) because [vercel](https://vercel.com/) has a limitation on the number of branches.
- `kwocxx.kossiitkgp.org` will be the domain of each archive
- [`kwoc.kossiitkgp.org`](https://kwoc.kossiitkgp.org) will point to the previous KWoC's archive after it ends and before the next KWoC's website is deployed.

> [!NOTE]
> Each year a new website may be made or the previous one may be reused with a new design. Reuse previous components if necessary, but ensure that a new design is implemented every year.

## Miscellaneous

- Take anonymous feedback about the proceedings of KWoC from participants. Preferably after the submission of the end evals blog.
- Update [kossiitkgp/mistakes](https://github.com/kossiitkgp/mistakes) repo atleast for the sake of posterity based on feedback and other things that went wrong.
