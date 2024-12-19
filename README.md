# 2.1-masterserver
Fork of the SRB2 Master Server for use with 2.1.

Based upon the post 2.2 Master Server. The template SQL database before 2.2 was fucked up in some way, and some variables when servers were being added to the database was erroring out because some variables were not being defined correctly.

This was fixed upstream some time after 2.2, but some of the server code was changed as well (pretty much all code related to version checks though).

That code has been reverted, letting 2.1. clients connect to this Master Server.
