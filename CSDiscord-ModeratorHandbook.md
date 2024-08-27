---
title: |
  University of Manitoba \
  Computer Science Discord Server \
  Moderator Handbook \
author:
- CSSA
- WICS
- .devClub
- CrewSEC
titlepage: true
titlepage-background: "./background.pdf"
date: August 2024
header-left: Computer Science Discord Server Moderator Handbook
toc-own-page: true
colorlinks: true
linkcolor: blue
---

# UM CS Club Discord Moderation Handbook

## Introduction

The moderation team exists to ensure the Computer Science Clubs’ Discord server is a safe and welcoming space for everyone. Additionally, they enforce compliance with policies the server is beholden to — specifically, the server’s Terms of Use, the Discord Terms of Service, Discord Community Guidelines, and all relevant University of Manitoba policies. The team is led by the administrators, made up of Computer Science Clubs’ executives, and the moderators, made up of other server members and appointed by the moderators. It’s the moderation team’s responsibility to maintain the server, based on the guidelines herein.

\pagebreak

## Terms & Definitions

**administrator(s):** Executives who have chosen to be moderators and CS Club presidents

**Computer Science Clubs[^1] (the “CS Clubs”):** A group of student clubs at the University of Manitoba consisting of the Computer Science Students Association (CSSA), Women in Computer Science (WICS), .devClub (Dev Club), and the UM Crew for Software Engineering Conferences (CrewSEC).

**Computer Science Clubs’ Discord (the “Server”):** The Discord server owned and operated by the CS Clubs.

**Computer Science Clubs’ Discord Terms of Use (the “TOU”):** The Computer Science Clubs’ [Terms of Use](https://umanitobacssa.ca/docs/discordTOU.pdf) that define the rules and guidelines of the Server.

**club executive(s) / executive(s):** An executive member of one of the Computer Science Clubs, including vice executives and councillors.

**Discord Community Guidelines (the “Community Guidelines”):** The Discord [Community Guidelines](https://discord.com/guidelines).

**Discord Terms of Service (the “TOS”):** The Discord [Terms of Service](https://discord.com/terms).

**faculty / faculty member(s):** A permanent employee of the University of Manitoba. This includes professors, instructors, and department and faculty heads. This does not include temporary or contract employees such as TA’s or sessional instructors.

**HonkBot (the “Bot”):** HonkBot is the Discord Bot for the Server. Used for moderation and administrative purposes.

**moderator(s) / moderation team:** Volunteer student(s) who help moderate the server including administrators.

**server member(s) / member(s):** A member of the Computer Science Clubs’ Discord Server.

**sessional instructor(s):** An instructor employed by the University of Manitoba to teach a course for one session/term.

When we say “we”, we mean the executives of the CS Clubs. When we say “you”, we mean you, the moderator (or future moderator).

\pagebreak

## Applying to be a Moderator

The Server will be made aware when moderator applications are open. Any current student who has been a member of the Server for at least a semester is eligible to apply to become a moderator. Applicants will go through an interview process with administrators and will be subject to a review of their Server history (messages from the past semester and moderative actions from the time they joined the Server) before they are selected. All selected moderators will be expected to take the [Healthy Relationships Workshop](https://umanitoba.ca/sexual-violence/get-informed) or the “UMSU Sexual Violence Prevention Course” (SVPW\_022023) on UMLearn before they can begin their moderator duties.

As mentioned above, moderators are charged with making the server a safe space. The moderation team is committed to principles of equity, diversity, inclusion, and accessibility (EDIA), and every moderator must be prepared to uphold these principles. As moderators are the first point of contact for conflict or concern in the Server, they should also be approachable and welcoming so server members feel comfortable bringing up concerns. Additionally, we require accountability and transparency from all moderators, both to members and administrators.

There is no maximum period of moderation; moderators will be kept on as long as they wish to be, barring any extraneous circumstances (e.g. graduation).

## Who Should We Moderate?

The Server has the privilege of hosting a large and diverse community. The roles we take on are constantly shifting and dynamics change. It is important to be aware of the ways that our differences impact the Server.

We must ensure that executives are not given more leniency than other members of the Server. Executives, councillors, moderators, and others that serve the community are still able to make mistakes. While it is natural to assume that these people have good intentions, their actions can have a larger impact because of their status. Well-established figures in the Server play a similar role. In many ways, they set the standard for behaviour in this setting, and it can feel awkward to call them out. However, they must be held to the same standard as everyone else. Administrators may wish to discuss taking further action with their home club if a representative of their group violates the TOU.

Our community serves people in a variety of stages in their academic career. This means that some members are beholden to different rules. For example, sessional instructors are not permitted to engage in discussions about courses that they are teaching, faculty are not to be allowed to join the server at all, and undergraduate and graduate students must be prevented from sharing course material or violating academic integrity. As a moderator, it is your job to keep track of these differences.

Finally, your power as a moderator only exists in the Server. Taking action in the server to punish behaviour that took place elsewhere is an abuse of power and will not be tolerated. This includes threatening others with moderation action for any reason. If you believe that someone’s behaviour is inappropriate, you may discuss this with other authorities like executives, lounge supervisors, or faculty members.

\pagebreak

## Moderative Actions

The moderation actions that HonkBot has are created to assist the moderation team in keeping the server a safe space.

### Messaging via the Bot

Using the Bot allows the moderators to send a message on our behalf. This should only be used for official moderation actions. All messages are logged and can be reviewed and referenced later.

| Command | Result |
| :---- | :---- |
| `/message [user] [message]` | Messages `[user]` with `[message]` |
| `/modmail [user]` | Sends the message history to/from `[user]` |

### Modnotes

If a note for fellow moderators needs to be left on a user, it is best to leave a modnote. This gets brought up when reviewing the user log.

| Command | Result |
| :---- | :---- |
| `/modnote [user] [note]` | Adds a modnote `[note]` for `[user]` |

### Warnings/Strikes

When people break rules, it’s often that they just need a reminder of their actions, and this is a way to communicate that reminder to them. In the case of a repeated offence, strikes should be issued.

| Command | Result |
| :---- | :---- |
| `/warn [user] [reason] [strike]` | Warns `[user]` for `[reason]`; `[true/false]` for strike |
| `/warn [user] [reason] false` | Warns `[user]` for `[reason]` |
| `/warn [user] [reason] true` | Warns `[user]` and issues a strike for `[reason]` |

### Timeouts/Temporary Bans

Sometimes people need to spend a bit of time away, and cool down from the situation. This takes away their access to engaging in text and voice channels.

| Command | Result |
| :---- | :---- |
| `/timeout [user] [minutes]` | Timeout `[user]` for `[minutes]` (up to 28 days) |
| `/timeout [user] 5` | Timeout `[user]` for 5 minutes |
| `/timeout [user] 60` | Timeout `[user]` for 1 hour |
| `/timeout [user] 1440` | Timeout `[user]` for 1 day |
| `/timeout [user] 10080` | Timeout `[user]` for 1 week |

### Kick

Once a certain amount of strikes/warnings have been issued and users are continually breaking rules, a kick can be issued. It’s good to consult with fellow moderators and administrators before administering a kick.

| Command | Result |
| :---- | :---- |
| `/kick [user] [reason]` | Kicks `[user]` for `[reason]` and notifies them |

### Bans

Bans should only be issued after consulting with administrators. These are used for repeat offenders, or people who are just here to cause trouble.

| Command | Result |
| :---- | :---- |
| `/ban [user] [reason]` | Bans `[user]` for `[reason]` and notifies them |


\pagebreak

### Logs

| Command | Result |
| :---- | :---- |
| `/userinfo [user]` | Fetches the verification info for `[user]` |
| `/userlog [user]` | Fetches the moderation logs of `[user]` |
| `/actionlog [user] [type]` | Fetches the actions taken by `[user]` of `[type]` (warn, kick, ban) |
| `/modmail [user]` | Sends the message history to/from `[user]` |

\pagebreak


## Making Mistakes

Moderation is not easy, and as students, we understand that everyone makes mistakes; it’s how we handle them that determines the reputation of the Server and the reliability of our moderation team.

If you time out, ban or apply a strike to a person incorrectly, apologize to the user, undo the action and remove the action from the record. Correcting a ban/timeout length (e.g. the original length was too harsh for the situation) is similar – apologize and let the user know that the duration has been updated. The action should remain on their record since it has not been completely undone, but may be reissued as appropriate (e.g. a warning with a strike may be reissued without it.)

Executives are responsible for the integrity of the Server and its moderation team. We want moderators to feel comfortable asking for help and advice when making decisions or when fixing a mistake. Similarly, decisions can and should be discussed by fellow administrators and moderators, and actions can be determined collectively.

For any applied moderators actions, please let administrators know if a mistake was made and the actions taken to fix it. We’ll be able to help better if we’re informed sooner rather than later. Repeated mistakes from the same moderator may require a longer conversation about judgment, or other repercussions if we believe the moderator is abusing their privileges.

### Appeals

Server members may request to appeal a strike, ban, or other moderator action using the form at [discord.umanitobacssa.ca/appeal](https://discord.umanitobacssa.ca/appeal).

Appeals for actions such as timeouts or temporary bans are unlikely to result in a reversal. They provide time to reset and reevaluate, and allow some breathing room for other users. Reverting a temporary ban or timeout should really only occur to resolve moderator error. If someone is permanently banned, it is likely because they have gained multiple strikes, repeatedly or severely violated our TOU or the TOS, and will likely remain banned. However, there may be exceptions and members are welcome to appeal the decision regardless.

Appeals will be handled by the Server administrators. We will discuss with the moderator responsible for the action being appealed to determine if the action was appropriate, and communicate the final decision with the appealing member.

\pagebreak

## Keeping Ourselves Honest

One of the most important virtues of being a good moderator is integrity. All moderators have the responsibility of holding themselves as well as other moderators accountable to their actions.

Administrators and moderators are beholden to the right to utilize the Bot’s logging features at any moment to check any moderation actions that have been taken. Moderators aren’t mandated, but are encouraged, to view the logs regularly and be aware of the Server’s recent happenings. Moderators are expected to answer any inquiries by administrators and fellow moderators on past moderation actions they have taken, as well as the content of the modmails they have sent to users. As the built in discord moderation features do not log actions within the Bot we discourage use of them. Any moderator found using Discord’s built in moderation features will be subject to discussion with the administrators and may be subject to possible repercussions.

Beyond their moderation duties, moderators are encouraged to partake in the community they are responsible for. However, moderators are expected to uphold a sense of self-awareness when interacting with the community. As a direct administrative force, the moderator’s behavior implicitly defines what is and is not acceptable in a conversation. If the moderator feels that they are getting caught up in a conversation that is heading down a potentially controversial path or making someone uncomfortable, they are responsible for shutting it down, making warranted moderation actions, and, if necessary, distancing themselves from the channel.

If the moderator feels any doubt they are not able to make the best judgement when contemplating making a moderation action, they are expected to inform fellow moderators and discuss in good faith. If the moderator has doubts about another moderator or an administrator’s chosen action, they are also expected to voice their concerns, be it in the mod channel or in DMs with a trusted administrator; the former is much more encouraged as moderators should feel comfortable stating their opinions. Administrators are responsible for taking any moderator’s concerns into account and will have the final say in whether the moderation action being considered was warranted.

### How to report users in the Server

If a moderator or executive is suspected of violating the TOU, TOS, Community Guidelines, or moderation guidelines, they should be kept accountable. If this behaviour is observed it can be reported to the administrators by filling out the form at discord.umanitobacssa.ca/reporting. It will go directly to them, and they will take action. *Anonymous* reporting will not involve any follow up, *Non-Anonymous* reporting may involve follow up by an administrator. If this is an action that happened in-person, anonymous reporters should understand that we can only take action on what we know, and that there cannot be any follow up to their report.

[^1]:  The list of clubs that fall under this umbrella is not fixed and may be updated at the discretion of the current club executives.
