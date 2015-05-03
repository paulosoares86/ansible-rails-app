# My Rails Stack

It installs:

- create user deploy
- nginx (with passenger)
- Rails (version configurable)
- Mysql

Change the app name, host and deploy directory in <code>vars/defaults.yml</code>.

To run:

    $ ansible-playbook ruby-webapp.yml
