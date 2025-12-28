# Local Sync

Goals:

- enable updating the database without access to the database
- reconcile conflicts between different clients updating the database

Solution

1. clients store the data hes updating on his computer
2. when connectivity is restored, do some git-like business logic to determine how data gets updated into the DB
