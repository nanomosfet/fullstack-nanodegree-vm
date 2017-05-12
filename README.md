Tournament Project
=============

## How to run the tournament project

1. Install Virtual Box
2. Install Vagrant
3. Clone this repo
4. `cd <repo home>/vagrant`
5. In your terminal run `vagrant up`
6. After virtual machine starts log in to the machine by running `vagrant ssh`
7. Access the tournament files - `cd /vagrant/tournament`
8. run 'psql'
9. create the tournament database - `create database tournament;`
10. Connect to the database - `\c tournament`
11. Create the tables from the tournament.sql file - `\i tournament.sql`
12. Quit postgress Shell - `\q`
13. Run unit tests - `python tournament_test.py`
14. Confirm that all tests passed!
