# dynamic-motd
A dynamic MOTD built in tclsh.

*Why tcl? Because I couldn't get tput colors to work through pam.*

Currently up and running on my Debian "jessie" server and should™ work on all similar dists.

### Prequesities
The scripts expect you to have these commands/apps installed and available:
- tclsh
- tclx (tcl package)
- lsb_release
- uname
- echo
- sed
- date
- grep
- cat
- awk
- tr
- uptime
- top (it's possible it needs a specific layout here as well, will check)
- ps
- sensors
- perl
- df
- w
- lastlog
- last
- aptitude
- apt-get
- needrestart

I also suggest you enable apt-get to update it's list with cron.hourly (or cron.daily). Otherwise you can uncomment the script in '50-check-updates' for a cheeky workaround. :)
