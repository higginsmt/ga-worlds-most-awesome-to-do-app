ga-worlds-most-awesome-to-do-app
================================

￼THE WORLD’S MOST AWESOME TO-DO APP
!
STORY:
￼The boss isn’t happy with the speed at which tasks are getting accomplished. Team members are unclear about priorities and who’s responsible for what. Hoping to bring some order and organization to the process, the boss has asked us to create a simple task management application that allows us to create to-do lists for projects, invite users to join the list, assign tasks to users, and send assigned users reminders about overdue tasks.
!The boss is out of the office a lot, but luckily she has an iPhone surgically attached to her at all times, so we need to make sure the app is can be used gracefully on mobile devices. We also need to incorporate an activity feed so she can quickly skim progress and changes within a project.
!
GOALS:
• Make task management and organization as easy as possible • Get users to invite other team members
• Allow users to assign tasks and send reminders
!
REQUIREMENTS:
!
To-do lists
!Data:
• Listtitle
!• List members (see Users)
Interactions:
• Addnewlist • Viewlist
• Renamelist • Deletelist
• Inviteusertolist(viausernameoremail)
￼To-do items !Data:
!• Itemtitle
Interactions:
• Addnewitem
• Viewitem
• Renameitem
• Markitemascomplete • Deleteitem
!• Assign user to !Users
!Data:
• Username
!• Profile picture
Interactions:
• Invitetonewusertojoin(viaemail)
• Inviteusertolist(viausernameoremail) !• Assign user to task
!• User marked item as complete !
!Activity
!Data
• Useraddedlist
• Useraddeditem • Userdeletedlist • Userdeleteditem
￼RESOURCES:
Our trusty creative director has been kind enough to put together a simple color and font palette for us to use to ensure the app is beautiful and stays consistent with the company brand. We can use this when styling the app.
!Color Palette !General
!• Application Background: #dff2f2
To-Do Items
• To-DoItemsBackground:#fff • To-DoItemsHeading:#099
• To-DoItemHover:#eee
• To-DoItemText:#555
!• To-DoItemText-Completed:#ccc
Lists
• ListsBackground:#252525 • ListsHeading:#aaa
• ListHover:#555
!• ListTitleText:#fff
Users
• UserListBackground:#252525 • UserListHeading:#aaa
• UserListItemHover:#555
!• UserListItemText:#fff Font Palette
!Font
‘Helvetica Neue’, Helvetiva, Arial, sans-serif - weight: 200
!Size
Headings: 30px Large Buttons: 30px To-Do Items: 20px Users: 20px
Small Buttons: 14px
￼INSTRUCTIONS:
Use the provided goals, requirements and resources, along with the wireframe sketches created in our planning session, to create a simple HTML/CSS prototype of the application. Work will be split up based on number of participants. Within your assigned area, feel free to exercise your creative brain and implement any improvements that you may think of along the way.
!A bootstrapped project template is available in the GitHub repo. Those who are comfortable with GitHub may clone the repo and push changes directly, otherwise you may download a zipped copy and email me your finished version at bferioli@gmail.com.
