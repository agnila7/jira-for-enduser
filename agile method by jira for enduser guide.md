Esp thanks to: Dan LeFebvre for his 'Understanding Jira for users, managers and admins' course

Agile: methodology/framework of rules. all soft. dev follows to get stuff done for adaptive planning, evolutionary development, early delivery, and continuous improvement. encourages rapid and flexible responses to changes.

agile board: different lanes (in Jira called columns) including to-do list, in progress, done. simple steps to get things done.

two primary ways to organize projects: scrum, kanban. scrum has sprints and kanban not.

sprint: predetermined of time where team determines to get the work done. sprint workflow: ideally we work on one element and progress it until done before touching the next element.

3 ques of sprint: 1. what went well? what didn't go well? what could be better?

kanban: ongoing process.new things added to board as we are working.

standup meeting: accomplished work yesterday and what going to do that day, any roadblocks.

project: containers for issues. different projects hold different issues. for ex: web dev projects with different issues and prod with different issues. what types of issues live inside? do not need to create more & more project. just create more issues in the particular project.

issues (kinda like post-it notes): containers for fields. fields hold data. data: work description, summary, due date, assignee

user story: So, this is the formula for a user story.

As a insert <type of user>, ex: web dev

I want <some sort of goal>.ex: add users to jira

So that's <some sort of reason>.ex:so coworkers can access to jira

epic: not every stories have to live in the epic. Core functionality of a big project. stories to complete the epic is the prod teams, dev teams and qa teams projects.

You can't change the team-managed project to a company-managed project. So be careful, you will need to create a new one.

jira workflow: is going from one status to another. ex: issues go from to-do to in progress.

create custom filters: In 'project settings', go to 'board', and select 'custom filters' from the board dropdown. Now click on 'Create Custom Filter'. give a name and add 'filter query' as 'issuetype = name'

adding card cover images: on 'project settings', go to 'issue type', select 'car cover image', click tickbox here. then when you attach an image to the task, it will show it as cover when you hit refresh button.

access, automation, notification, features, toolchain.

features: even using kanban , we can customize to scrum by adding sprint into the kanban.

Creating new issue type: go to 'project settings'. Select 'Issue type' and click on 'task'. now add in 'add issue type', it will show some suggested options. use for ex: 'Bugs' and click on 'Add'.

Adding customized fields: from the right-side menu, see 'previously created fields,' click on 'due date'. drag it in the context fields of your designated issue.

board lives in the project.

Jira admin needs to set up the company-managed project. Hence, we can not practice hands on.

Spcrum dashboard: Your issues should be in the active sprint to show up on the board.

Issues: Creating an issue is similar, you can choose the issue type if you have permission. This task will be assigned with an issue type + number (Key). You can also create subtasks to break down. Attach and link issue attach (you need to finish the previous issue to work on it)

Sprint board: In issues, there is activity. Comments, History, and work log

in the work log, how much time one assignee has done can be logged. it will be easier to count with the originate time estimation for the issue in the active sprint

Searching in jira: Go to 'your work'. you can see your all activities. Or you can also search in the 'search box'. They will be in the numerical sequence. It only search through the text of the issue name not the summary. If you can go to 'filter' from the top or go to 'issues' down from search box, then you can have more search options.

Searching best practice for searching in 1000 of jira issues is jira query language: Click on 'Switch to JQL' and type:

<Issue type = "what u want to search" AND status =DONE ORDER BY lastViewed DESC>

<Issue type = "what u want to search" AND status!=DONE ORDER BY lastViewed DESC>

<Issue type = "what u want to search" and project = "" order by created DESC>

ps: dont use <> in the search option it is for highlighted purpose only.

save this search by clicking 'save as' in top and give it a name. You can view these saved query from 'Filters' on top.
