# What is Mad Flow?
Mad Flow is an internal project for company's process automation.

## Project purposes
* Systematize and streamline internal company's processes;
* Transfer management processes to Jira and automate them using extensions (add-ons) and Jira functionality;

## Project advantages
Mad Flow helps PMs, HRs and other employees of the Mad Devs admin staff to have up-to-date information on the tasks assigned to them and to close tasks on time. This project will help to solve problems in the early stages and guide PMs to solve these problems.

## Setting up a Workflow

Workflow regulates the movement of tasks in projects.

Workflow can be changed according to the ongoing project’s processes.

To get access to the Workflow's settings, you need to log in as a Jira Administrator and click on Project Settings (in the project’s window in which you're going to change the Workflow).

![Снимок экрана 2020-05-29 в 18 51 26](https://user-images.githubusercontent.com/66111593/83281079-60222300-a1f9-11ea-8573-1ce94f88e17d.png)

# Setting up automatic tasks using Issue Templates for Jira

Add-on link: https://marketplace.atlassian.com/apps/1211044/issue-templates-for-jira?hosting=cloud&tab=overview
Official documentation link: https://deviniti.com/support/addon/cloud/issue-templates/latest/getting-started/

We have a need to periodically create tasks with similar content to any project. To avoid manually creating tasks, again and again, we use special add-ons for Jira. Issue Template enables us to create tasks from a template in a few clicks. 
So, to install add-on we need to go to Atlassian Marketplace, Jira Settings > Apps > Find new apps.

![Снимок экрана 2020-05-29 в 22 19 21](https://user-images.githubusercontent.com/66111593/83281910-a035d580-a1fa-11ea-8036-eeab567740ce.png)

![Снимок экрана 2020-05-29 в 22 19 48](https://user-images.githubusercontent.com/66111593/83281941-af1c8800-a1fa-11ea-8e6e-9fe6e25dcea8.png)

Click on extension. You’ll see a pop up window, where you need to click on View app details.

![Снимок экрана 2020-05-29 в 22 20 08](https://user-images.githubusercontent.com/66111593/83281963-b6dc2c80-a1fa-11ea-88b6-979a536c650b.png)

Then go to the expansion page in the Atlassian Marketplace. Here, click on Try it free or Buy it now. Note: Since the extension is paid, check its functionality first. You can use a 30-day free trial.

![Снимок экрана 2020-05-29 в 22 22 44](https://user-images.githubusercontent.com/66111593/83282286-2b16d000-a1fb-11ea-9607-fdb6bbb7dc46.png)

Choose Cloud Jira from the list.

![Снимок экрана 2020-05-29 в 22 23 15](https://user-images.githubusercontent.com/66111593/83282335-3f5acd00-a1fb-11ea-906e-7844cedebaef.png)

Hooray! Add-on is installed.

![Снимок экрана 2020-05-29 в 22 23 56](https://user-images.githubusercontent.com/66111593/83282389-53063380-a1fb-11ea-8289-96e1e46d7ecc.png)

Let’s set up the add-on.
First of all we need to create a separate project where only templates will be placed. Let’s name it “Templates”.

![Снимок экрана 2020-05-29 в 22 26 52](https://user-images.githubusercontent.com/66111593/83282778-e9d2f000-a1fb-11ea-8069-682f71be7edd.png)

Then return to the add-on page and click on “Create Template (Basic)” button.

![Снимок экрана 2020-05-29 в 22 27 28](https://user-images.githubusercontent.com/66111593/83282801-f48d8500-a1fb-11ea-959a-587f6fe309b4.png)

Choose created by us project “Templates” as Template Repository.

![Снимок экрана 2020-05-29 в 22 27 47](https://user-images.githubusercontent.com/66111593/83282869-0f5ff980-a1fc-11ea-9518-5d6e2e59f7af.png)

Then the program creates a body of an issue template in the “Templates” project.

Here we need to write the task which we want to automate by creating from templates. Write a title or description, choose task type and fill in all necessary parameters.

![Снимок экрана 2020-05-29 в 22 29 13](https://user-images.githubusercontent.com/66111593/83282900-1dae1580-a1fc-11ea-98f1-5fe98cdcf5a9.png)

Click on Create and our first template is done! 

Now we need to set extra settings in our project “Templates” right before using it.
Go to “Templates” Project Settings, click on Issue Templates.

![Снимок экрана 2020-05-29 в 22 33 03](https://user-images.githubusercontent.com/66111593/83283517-281cdf00-a1fd-11ea-868e-a08c519a4764.png)

![Снимок экрана 2020-05-29 в 22 33 31](https://user-images.githubusercontent.com/66111593/83283564-379c2800-a1fd-11ea-880e-95745a264842.png)

There are three types of add-on settings: Manage Templates, Variables, Scopes.
In Manage Templates you can see every created issue-templates.

![Снимок экрана 2020-05-29 в 22 34 22](https://user-images.githubusercontent.com/66111593/83283614-50a4d900-a1fd-11ea-8f8b-4451b9c037b2.png)

In order to enable the display of the desired template, click on the pencil in the column Actions.

![Снимок экрана 2020-05-29 в 22 34 47](https://user-images.githubusercontent.com/66111593/83283654-5ef2f500-a1fd-11ea-8e16-681a62171bf8.png)

Activate all switches: Make template selectable and Copy Subtasks (if it’s necessary copy subtasks).
In “Availability” settings choose projects where this template must be displayed.

![Снимок экрана 2020-05-29 в 22 35 15](https://user-images.githubusercontent.com/66111593/83283669-661a0300-a1fd-11ea-8d3b-8569ee5eb011.png)

Click on Configure.

In “Scope” settings (list of the number of fields inherited when creating a task from a template) we need to add necessary fields “DEFAULT_SCOPE”s.

![Снимок экрана 2020-05-29 в 22 36 01](https://user-images.githubusercontent.com/66111593/83283718-76ca7900-a1fd-11ea-88fc-8f361848ffde.png)

Click on Configure.

In “Scope” settings (list of the number of fields inherited when creating a task from a template) we need to add necessary fields “DEFAULT_SCOPE”s.

![Снимок экрана 2020-05-29 в 22 37 57](https://user-images.githubusercontent.com/66111593/83283751-83e76800-a1fd-11ea-972d-08412d9421aa.png)

Congratulations we have just ended setting up all parameters and now we can begin to use our Issue Templates!
Go to a project in which we want to create a task from a template and in the side menu click on Create from Template tab. 


