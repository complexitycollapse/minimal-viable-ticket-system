# Minimal Viable Ticket System

This is an example of a Minimal Viable Program, defined as "the smallest program that solves a particular problem". In this case, the problem is ticketing/issue management. With this system you can raise, edit, close, delete and reassign tickets, as well as calculate various statistics (e.g. number of open tickets), yet the core of the program is just 20 lines long.

The idea comes from <https://joearms.github.io/published/2014-06-25-minimal-viable-program.html> which describes an actually used-in-production ticketing system that works on the same principle. To create an instance of the system, just fork this repo. To use it, open a terminal and change directory to your fork, then raise a ticket by running

    ./newticket

The ticket will be created in the tickets folder, and the number of the ticket (which is also its filename) will be returned. A new ticket looks like this:

ticket: 1
responsible: <your_git_name>
status: open
title: ?
----
Describe your problem here

The ticket will already have been committed to the repo. You can edit it further with your favourite text editor and commit the changes. Don't forget to 'git push' to share your changes with the other users.
