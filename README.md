# BashHTMSender

Description"

The tool can send messages based on HTML template and sender list of mails. You can reconfigure it based on your needs, the idea is to be used for phishing campaign. You can hardcode the useraname in the links in the tamplate, in order to have visability of the clicked links from the users. As you probably will use Apache\Nginx webserver and this will help you to see which user has clicked the link based on the http access logs. 

Requirments:

1. Linux Machine
2. Installed sendmail service
3. Configured ssmtp 

Usage:

1. Reconfigure email.html file
2. Add your recipients in the emails.txt file
3. Start the bash script
