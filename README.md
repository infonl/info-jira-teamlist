# jira-teamlist

Show a list of team members next to title of first column of Active Sprint board (the scrumboard)
Looks like this:  Ni Ri Ad Ge Is Ja (Ke) Lb Mar Hr (PO)
- Can be used during standup so everybody knows the order (especially nice when doing a videocall)
- Content of list can differ per day of the week (Mon-Sun). Especially nice with part-timers tht don't pop up on their free day.

Show a list of tips next to title of 4th column of Active Sprint board (the scrumboard)
Looks like this:  "Done?"
- Can be used during standup so everybody knows if there is a recurring special topic, like Done? means "Discuss if we get the full sprint Done?", "Arch align" means for us: "Tomorrow there is an architecture alignment. Do we have any topics?"
- Content of list can differ per day of the sprint (1-14). 


![Screenshot](https://raw.githubusercontent.com/infonl/jira-teamlist/main/Screenshot%20Team%20list.png "Screenshot")

Tip: Put the abbreviation of the name of someone who is optional (like an PO = Product Owner) between round brackets.

Uses the 'User JavaScript and CSS' extension for Chrome https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld?hl=en

Install
=====================
1. install 'User JavaScript and CSS' extension for Chromehttps://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld?hl=en
2. navigate your browser to your JIRA
3. Click 'User JavaScript and CSS' icon in Chrome (Blue/red dotted lines-icon)
4. Click Add new
5. Add the content of js.js to the JS pane
6. Under Options enable Javascript &  Libraries jQuery 3
8. If your JIRA url if different that this format: `jira.*/RapidBoard.jspa` (where * is a wildcard for any character): Edit the url under the Sites-tab -> should become your JIRA url, like `jira.yourdomain.com/jira/secure/RapidBoard.jspa`
9. Hit Save


