wakemakin-tasks
===============

A general container for tasks so we don't need to get bugzilla or any of that shit setup.

We should use this repo for tasks when they don't fit in a project repo.

Guidelines
----------
When creating github milestones and issues for progress tracking, please use the following guidelines:

- Milestones should give an overview of what needs to be achieved by the specified completion date.
  
  For example:
  
    Create a basic web client.

- Issues (tasks) should be created as a user driven feature and list the acceptance criteria to define task completion.  Once created, make sure issue is assigned to the milestone so that progress can be tracked correctly. 

  For example:

    As a user, I want to be able to create a user account so that I can log in.

    Acceptance Criteria:
    
    - A user can access a sign-up page that displays a form containing first name, last name, email, password and a submit button.
    - Once the user fills out the form and submits valid data, an account is created.
    - The form should validate information and alert users of errors.
