This playbook is an example of how handlers can be used to gain idempotence in ansible.

This is the following scenario :

When the is playbook is executed the webserver restarts every time even if there was no change in files
which indeed consumes a lot of time and resources. 
So to save time and resources we can use **handlers** in ansible.
They are executed when there is a change in the particular task which can save a lot of resources.
