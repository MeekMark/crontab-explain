# crontab-explain
Convert crontab -l output into useful human-readable dates and times of execution

Example crontab entry:

40      */12     *       *       1-5       /home/oracle/bin/rman_archive_logfiles_rcat.sh

When run through crontab_explain.pl the output is

At 40 minutes of every  12 hours; on every day of every month that fall on Mon, Tue, Wed, Thu, Fri invoke the command: /home/oracle/bin/rman_archive_logfiles_rcat.sh
