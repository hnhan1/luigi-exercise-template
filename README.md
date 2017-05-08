# Exercise Template for "Build a data pipeline with Luigi"

This is a jumping-off point for the exercise portion of the PyCon 2017 tutorial session on building a data pipeline with Luigi.

This template demonstrates how to:
- Download files from Amazon S3
- Execute a shell script in a Luigi task
- Write data from a CSV file to a database table

If you have Postgres installed, you can run this example script by doing the following:
1. Install the packages in the requirements.txt file
2. Rename the 'luigi.cfg.tmp' file to 'luigi.cfg' and fill in the missing credentials 
3. From a shell terminal, run `python example.py WriteUserUpdatesToSQL --id=1`
