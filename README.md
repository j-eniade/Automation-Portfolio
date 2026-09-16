
# Automation-Portfolio
I am currently completing the no-code/automation track where I build practical, working automations using tools such as Make, Google Forms, Google identifying repetitive, time-consuming processes and replacing them with reliable, low-maintenance systems. I'm seeking an internship where I can apply and grow these skills within a real business environment.

## Build 1
Client Payment-Confirmation & Alert System
1. What I built
A payment-confirmation system that catches new client submissions (name, email, and cohort paid for) and alerts the team by email, while also logging each one as a Trello card.
2. The problem it solves
When new clients confirm payment through a form, the response can sit unseen in a spreadsheet for hours or days. This delays getting them properly enrolled into the right cohort and makes it easy to lose track of who has actually paid, making the client wonder if you're a scam, or just lose enthusiasm.
3. How it works, step by step
A new client fills in the form with their name, email, and the cohort they've paid for. Their answers land as a new row in a Google Sheet. The automation notices the new row and checks that it's a real submission, not a blank test entry. If it's real, it sends the team an email with the client's name, email, and cohort, and creates a Trello card with the same details so it can be tracked and actioned.
4. The tools I used
Make, Google Forms, Google Sheets, Gmail, Trello.
5. The result
Every new client's payment confirmation now reaches the team by email and appears as a Trello card within about a minute of being submitted, with no one checking the form by hand.
All of the above actions are carried out within a minute after triggered by Lead’s Instagram comment.  

## Build 2
Instagram Comment-to-DM Lead Alert System
1. What I built
An Instagram lead-alert system that sends an automatic DM to anyone who comments a keyword on a post, and emails the vendor immediately so no potential client is missed.
2. The problem it solves
Vendors often miss interested customers because Instagram comments and DMs aren't checked constantly. By the time someone notices a comment, the potential client may have already moved on or lost interest.
3. How it works, step by step
A person comments a specific keyword on the Instagram post. InstantDM detects the comment and automatically sends that person a DM for payment. At the same time, InstantDM sends the comment details to Make through a webhook. Make picks this up and immediately emails the vendor to let them know a new client has shown interest and paid.
Make, InstantDM, Instagram, Gmail.
5. What I had to solve
Setting up worked smoothly this time, since I applied what I'd learned from my first build — mainly making sure the webhook was properly connected between InstantDM and Make before testing.
The result
The vendor now receives an email alert within about a minute of a real comment, without needing to check Instagram manually.
All of the above actions are carried out within a minute after triggered by Lead’s Instagram comment.  

## Build 3
Monthly Client Check-In Emailer
1. What I built
A monthly check-in system that automatically emails every client on a list, addressing them by name personally without anyone needing to send messages or edit by hand.
2. The problem it solves
Businesses often forget to regularly check in with clients because it's easy to overlook when there's no reminder. Over time, this can make clients feel forgotten and less likely to stay engaged.
3. How it works, step by step
Once a month, on a set day and time, the automation runs on its own. It pulls the full list of clients from a Google Sheet. It goes through the list one client at a time. For each one, it sends a personalized check-in email using their name, and also sends a confirmation email to notify that the message went out.
4. The tools I used
Make, Google Sheets, Gmail.
5. What I had to solve
This build went smoothly overall, building on what I'd learned from my earlier automations.
The result	
Every client on the list now receives a personalized check-in email automatically each month, with a confirmation sent as well, and no manual sending required.
All of the above actions are carried out within a minute after triggered by Lead’s Instagram comment.  
