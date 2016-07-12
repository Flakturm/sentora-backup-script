# Sentora backup script
A little script that backups sentora site files and database.

### Installation
In this example, I put the script in server ***daily*** cron job.

Upload or create the script in ```/etc/cron.daily```.

You can also:
* Create a custom cron job to run the script. ```sudo crontab –e```

Replace the following variables.
```
<user>
<site_folder>
<excluded_folder> (optional)
```

Enter the following variables.
```
ROTATE=
USER=
PASS=
DB=
```

### Save
That's it all done!  Easy and simple! :+1:
