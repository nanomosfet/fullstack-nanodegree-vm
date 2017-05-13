Tournament Project
=============

## What is this project?
This project builds a database for a swiss style tournament. 

## How to run the tournament project

1. Install Virtual Box
2. Install Vagrant
3. Clone this repo
4. `cd <repo home>/vagrant`
5. In your terminal run `vagrant up`
6. After virtual machine starts log in to the machine by running `vagrant ssh`
7. Access the tournament files - `cd /vagrant/tournament`
8. run 'psql -f tournament.sql'
9. Run unit tests - `python tournament_test.py`
10. Confirm that all tests passed!
