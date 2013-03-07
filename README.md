new-podcast-notifier
====================

This shell script will check for new podcasts in the user designated 
download directory and send an email that contains a list of the new 
podcasts. Keep in mind this will not download the podcasts. You must 
use a pod cast aggregator such as mashpodder or podget.

This script requires a functional Message Transfer Agent (MTA) such 
as EXIM4. 

This script is intended to be executed with a cronjob after the podcatcher 
downloads the content.

Install file to /usr/bin
