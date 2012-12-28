INTRODUCTION
This is a collection of three cron jobs that imitate Apple's Time
Machine.  Together, they keep hourly snapshots for the past day, daily
snapshots for the past week, and weekly snapshots beyond that.

DEPENDENCIES
rsync

USAGE
Change the location of the source directory, backup directory, and 
backup device (if any) in the scripts.  Then place snapshot in
/etc/cron.hourly/, daily-snapshot in /etc/cron.daily/, and
weekly-snapshot in /etc/cron.weekly/. 
