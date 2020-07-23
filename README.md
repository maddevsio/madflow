# What is Mad Flow?
Mad Flow is an internal project for company's process automation.

## Project purposes
* Systematize and streamline internal company's processes;
* Transfer management processes to Jira and automate them using extensions (add-ons) and Jira functionality;

## Project advantages
Mad Flow helps PMs, HRs and other employees of the Mad Devs admin staff to have up-to-date information on the tasks assigned to them and to close tasks on time. This project will help to solve problems in the early stages and guide PMs to solve these problems.

## Project Settings

<details>
  <summary>1. Setting up a Workflow</summary>
  
  ### Setting up a Workflow
  Workflow regulates the movement of tasks in projects.

Workflow can be changed according to the ongoing project’s processes.

To get access to the Workflow's settings, you need to log in as a Jira Administrator and click on Project Settings (in the project’s window in which you're going to change the Workflow).

![Снимок экрана 2020-05-29 в 18 51 26](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-14%20at%2015.34.08.png)

Next step: click on Workflows

![Снимок экрана 2020-05-31 в 21 57 25](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-14%20at%2015.39.20.png)

You’ll see a window with the current workflow of our project. There are 4 available actions:

* Add a new workflow (add one of the classic workflows from Jira’s schemes or add another one from the marketplace).

* Change Workflow’s scheme (If you have more than one preset Workflow schemes in your base).

* View the current workflow as a text or diagram.

* Edit current workflow.

![Снимок экрана 2020-05-31 в 21 57 45](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-14%20at%2015.41.49.png)

Let’s move on to the editing. Press on the pencil icon. Jira will send you to the Workflow’s edit page.

On this page we can see the following:

* Workflow’s activation buttons (Publish changes; delete changes; View original).

* Workflow’s name editing field.

*  A button that can show how many projects are operating using the scheme.

* Switch the scheme’s form (diagram; text).

* Workflow’s export button.

* A field for directly configuring workflow elements.

![Снимок экрана 2020-05-31 в 21 58 00](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-14%20at%2016.04.40.png)

To change Workflow under the needs of a specific project, we recommend you to familiarize with Jira Atlassian’s oﬃcial documentations:

Working with workflows - https://confluence.atlassian.com/adminjiracloud/working-with-workflows-776636540.html

Advanced workflow configuration - https://confluence.atlassian.com/adminjiracloud/advanced-workflow-configuration776636620.html
</details>

<details>
  <summary>2. Setting up automatic tasks using Issue Templates for Jira</summary>
  
  ### Setting up automatic tasks using Issue Templates for Jira
  
  Add-on link: https://marketplace.atlassian.com/apps/1211044/issue-templates-for-jira?hosting=cloud&tab=overview
  Official documentation link: https://deviniti.com/support/addon/cloud/issue-templates/latest/getting-started/
  
  We have a need to periodically create tasks with similar content to any project. To avoid manually creating tasks, again and again, we use special add-ons for Jira. Issue Template enables us to create tasks from a template in a few clicks.
  So, to install add-on we need to go to Atlassian Marketplace, Jira Settings > Apps > Find new apps.

![Снимок экрана 2020-05-29 в 22 19 21](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-17%20at%2014.51.55.png)

![Снимок экрана 2020-05-29 в 22 19 21](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-17%20at%2014.52.33.png)

![Снимок экрана 2020-05-29 в 22 19 48](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-17%20at%2014.52.59.png)

Click on extension. You’ll see a pop up window, where you need to click on View app details.

![Снимок экрана 2020-05-29 в 22 20 08](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-17%20at%2015.10.18.png)

Then go to the expansion page in the Atlassian Marketplace. Here, click on Try it free or Buy it now. Note: Since the extension is paid, check its functionality first. You can use a 30-day free trial.

![Снимок экрана 2020-05-29 в 22 22 44](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-17%20at%2015.34.04.png)

Choose Cloud Jira from the list.

![Снимок экрана 2020-05-29 в 22 23 15](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-17%20at%2015.34.40.png)

Hooray! Add-on is installed.

![Снимок экрана 2020-05-29 в 22 23 56](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-17%20at%2015.34.56.png)

Let’s set up the add-on.
First of all we need to create a separate project where only templates will be placed. Let’s name it “Templates”.

![Снимок экрана 2020-05-29 в 22 26 52](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2014.10.50.png)

Then return to the add-on page and click on “Create Template (Basic)” button.

![Снимок экрана 2020-05-29 в 22 27 28](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2014.20.13.png)

Choose created by us project “Templates” as Template Repository.

![Снимок экрана 2020-05-29 в 22 27 47](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2014.22.33.png)

Then the program creates a body of an issue template in the “Templates” project.

Here we need to write the task which we want to automate by creating from templates. Write a title or description, choose task type and fill in all necessary parameters.

![Снимок экрана 2020-05-29 в 22 29 13](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2014.22.53.png)

Click on Create and our first template is done! 

Now we need to set extra settings in our project “Templates” right before using it.
Go to “Templates” Project Settings, click on Issue Templates.

![Снимок экрана 2020-05-29 в 22 33 03](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2014.27.06.png)

![Снимок экрана 2020-05-29 в 22 33 31](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2014.45.44.png)

There are three types of add-on settings: Manage Templates, Variables, Scopes.
In Manage Templates you can see every created issue-templates.

![Снимок экрана 2020-05-29 в 22 34 22](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2014.46.40.png)

In order to enable the display of the desired template, click on the pencil in the column Actions.

![Снимок экрана 2020-05-29 в 22 34 47](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2015.05.47.png)

Activate all switches: Make template selectable and Copy Subtasks (if it’s necessary copy subtasks).
In “Availability” settings choose projects where this template must be displayed.

![Снимок экрана 2020-05-29 в 22 35 15](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2015.08.51.png)

Click on Configure.

In “Scope” settings (list of the number of fields inherited when creating a task from a template) we need to add necessary fields “DEFAULT_SCOPE”s.

![Снимок экрана 2020-05-29 в 22 36 01](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2015.09.05.png)

Click on Configure.

In “Scope” settings (list of the number of fields inherited when creating a task from a template) we need to add necessary fields “DEFAULT_SCOPE”s.

![Снимок экрана 2020-05-29 в 22 37 57](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2015.27.03.png)

Congratulations we have just ended setting up all parameters and now we can begin to use our Issue Templates!
Go to a project in which we want to create a task from a template and in the side menu click on Create from Template tab. 

![Снимок экрана 2020-05-29 в 22 43 57](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2015.35.06.png)

№3 On the page that appears, enter in the fields:
* Project 
* Issue type 
* Template (Сhoose from the list of available templates for a project)

![Снимок экрана 2020-05-29 в 22 44 19](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2015.38.25.png)

Click on Next and go to “the body” of the template task.

![Снимок экрана 2020-05-29 в 22 44 47](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2015.41.15.png)

Click on “Create” and we get to the window of auto-generation of tasks and subtasks from the template.

![Снимок экрана 2020-05-29 в 22 45 06](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2015.41.27.png)

After that, we get to the project’s active board and see the task that was created from the template!

![Снимок экрана 2020-05-29 в 22 45 24](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-02-21%20at%2015.46.58.png)

Additionally: If you want to edit a template, you need to use changes in the body task of project “Templates” then when creating a task from the template, the tasks will be created and modified.
</details>

<details>
  <summary>3. Setting up periodic tasks (Jira Automation)</summary>
  
  ### Setting up periodic tasks (Jira Automation)
  
  Jira Automation can be used in many ways and can automate nearly everything in Jira. In this document, we described the process of creating periodic tasks and assigning them to a specific person.

Install the add-on in Jira. Go to the project in which we need to create periodic tasks. Go to the Project Settings > Project Automation.

![Снимок экрана 2020-05-29 в 22 50 43](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-03%20at%2018.35.01.png)

![Снимок экрана 2020-05-29 в 22 50 43](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-03%20at%2018.36.19.png)

![Снимок экрана 2020-05-29 в 22 51 17](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-03%20at%2018.47.12.png)

Choose Scheduled from the list, Scheduled - schedule a periodic task

![Снимок экрана 2020-05-29 в 22 51 32](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-03%20at%2018.50.25.png)

Choose – Cron expression and set the time frame. Cron setup documentation. 
On screenshot we set up the cron as follows – 0 0 5 25 * ? – (5 a.m., on the 25th of every month, any day of the week).
Further select “simply run the conditions and actions without providing issues” and click on the Save button.

![Снимок экрана 2020-05-29 в 22 51 51](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-03%20at%2018.52.27.png)

We need to choose the next component, which will perform according to the schedule configured above. Choose New action.

![Снимок экрана 2020-05-29 в 22 52 25](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-03%20at%2018.55.51.png)

Our next condition will be creation of the task – Create issue.

![Снимок экрана 2020-05-29 в 22 52 45](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-03%20at%2018.57.00.png)

In creation fields we enter the following data:
* Project
* Issue type
* Summary

Other fields like Assignee, Components, Due date etc., we add from the list “Choose fields to set…”
Fill in all the necessary fields and click on Save.

![Снимок экрана 2020-05-29 в 22 57 54](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-03%20at%2018.58.16.png)

Our automated task is created! All we need to do now is to indicate it’s name in Name your automation field and click on Turn it on.

![Снимок экрана 2020-05-29 в 22 58 45](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-03%20at%2019.03.22.png)

Further we return to the automation list and see the created Rule with New tag.

![Снимок экрана 2020-05-29 в 22 59 00](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-03%20at%2019.05.37.png)

We've just successfully created the simplest type of automation in Jira - a periodic task.

### Additionally

When creating a monthly task, you can set a value? by which the name of the month will be automatically set in the Summary task.
It is necessary to add ‘ ‘ ‘{{now.format(“MMMM”)}} ‘ ‘ ‘ in the task’s title:

![Снимок экрана 2020-05-29 в 22 59 19](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-06%20at%2014.57.17.png)

The created task will look the following way.

![Снимок экрана 2020-05-29 в 22 59 37](https://github.com/maddevsio/madflow/blob/master/pics/Screen%20Shot%202020-03-06%20at%2015.01.52.png)
</details>

<details>
  <summary>4. Integrating Issue Checklists to the tasks created from Issue Templates</summary>
  
  ### Integrating Issue Checklists to the tasks created from Issue Templates
  
  Plugin Issue Templates for Jira doesn’t allow to add checklists from Jira Checklists plugin. The problem was solved with the help of Jira Automation rules. 

Setup Instructions:
* Install extension – Issue Checklists Free 
* We should already have installed and configured – Issue Templates for Jira
* We should have created task-template with ready checklists in the project Templates (Issue Templates plugin)

![Снимок экрана 2020-05-29 в 23 08 39](https://user-images.githubusercontent.com/66111593/83286350-8f3c9280-a201-11ea-8a6f-ebbd5a1179e7.png)

In our next step, we need to go to the project in which we are going to use the task with checklists created from a template. Go to Project Automation in project settings.

![Снимок экрана 2020-05-29 в 23 08 02](https://user-images.githubusercontent.com/66111593/83286353-906dbf80-a201-11ea-9cd6-652f7b6ee560.png)

Now we need to configure the Automation Rule – a condition according to which, when creating a new task in a project,  by a certain label a checklist will be added to it. Set Automation Rule as follows:

![Снимок экрана 2020-05-29 в 23 07 22](https://user-images.githubusercontent.com/66111593/83286355-91065600-a201-11ea-9a56-cd4d3b3020a8.png)

Trigger - Issue created

Condition - JQL definition is equal to the project’s title + task label project = PM and labels = project_start and labels = preparation)

Action - Edit issue for value Checklist Content YAML

In the Checklist Content YAML field, insert the created checklist from the parent task with the checklist.

![Снимок экрана 2020-05-29 в 23 07 04](https://user-images.githubusercontent.com/66111593/83286357-919eec80-a201-11ea-8153-e15004867d2c.png)

Next, save and turn on Automation Rule

![Снимок экрана 2020-05-29 в 23 06 49](https://user-images.githubusercontent.com/66111593/83286358-919eec80-a201-11ea-9c13-8393e10b20b0.png)

Now when creating a task from the issue template Create from Template we will have a task created in a selected project + checklists attached to it.
</details>

<br/> 

[![Read article on Medium](https://user-images.githubusercontent.com/51479167/84348173-1f051800-abd6-11ea-8f4b-dd375da8fbb3.png)](https://blog.maddevs.io/how-to-automate-jira-mad-devs-experience-50c7836eec65?source=false---------0)
