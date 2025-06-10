# Startup Ideas

## **Productivity/Email Web App**

In this project, the user can manage Email, Calendar and Tasks through one interface (sidebar similar to notion) but the way the user interacts with is different. It will be clean interface.

### **Email**

In this section, the user can connect his own Gmail account with the app then he can scroll, archive, delete and search for his email. Now the Strong part, AI interaction. Instead of selecting all commercial emails from certain provider (ACME) they could type into search bar "/ai archive first 10 commercial emails from ACME" and the AI agent will take over and do what it was asked to do (probably show a toast for either status of the task or the result)

The second feature is voice assistance:

- **Voice Interactions**: Instead of typing the user could tell the AI what to do and It would do it just like the action from search bar, this time using voice only.
- **AI Assistance Email Drafting**: Not only can you interact with your inbox but also write emails, The AI can adopt your style of writing and draft emails to your colleagues, by default draft the email, read it for you and ask for confirmation either with the UI or voice.

### **Calendar**

The strong point from this App is you bring up your calendar (Google, Notion, ...etc) and interact with it either from UI or using voice.

For example: A user can use voice feature and ask like following: "Can you check calendar about any meetings on Thursday morning and book meeting with Alice for 30-mins"

In this case, the AI will use the following flow:

> check the calendar for any meetings on Thursday morning -> draft email for Alice -> confirm the email to be sent -> add it to calendar.

Calendar events can be adding while reading emails, the user won't need to jump between tasks, they'll be prompted for confirmation to add the event to calendar while also making sure user doesn't have conflicting timing.

### **Tasks**

This is the Trello/To-do list of our workspace, It will be made from the ground up to work with other tasks and todo list apps. With this the user can have their tasks managed by voice or UI. You can have your tasks organized for you, and even optimized (not sure yet about how would optimization be but this is a later feature) probably this tasks will have Eisenhower matrix organization.

It will be the last piece to the puzzle of our workflow app, with this user can manage their emails, calendars and tasks using one single interface powered by voice.

### What should MVP have?

Some of The features mentioned above are either vague, too complex to build or just fine. The MVP aims to get some of user base and start iterating over the design so I can have more users to interview and understand better how to make the features more complementary with each other and with Real users (not just me)

For MVP I will focus on the Email features, mainly:

- Gmail as the main email service (Sign In, Read Emails)
- Interact with emails (Drafting, Archive, Delete...etc)
- AI Assisted interaction (Drafting, Archive, Delete...etc)
- AI Summarization of recent unread emails
