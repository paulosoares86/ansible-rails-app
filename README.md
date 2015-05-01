# My Rails Stack

It installs:

- nginx (with passenger)
- Ruby (version configurable)
- Mysql
- Redis (for Sidekiq)

Change the app name, host and deploy directory in <code>vars/defaults.yml</code>.

To run:

    $ ansible-playbook ruby-webapp.yml
