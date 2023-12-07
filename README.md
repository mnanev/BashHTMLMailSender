# BashHTMLMailSender

# Description:

The script is used to send messages based on HTML template and sender list of mails. You can reconfigure it based on your needs, the idea is to be used for phishing campaign. It hardcoding the useraname\s in the links in the tamplate, in order to have visability of the clicked links from the users. As you probably will use Apache\Nginx webserver and this will help you to see which user has clicked the link based on the http access logs, if this one is not added you probably will see only the accessed link and the IP address.

Requirments:

1. Linux Machine
2. Installed sendmail service
3. Configured ssmtp 

Usage:

1. Reconfigure email.html and bash script based on your needs
2. Add your recipients in the emails.txt file
3. Start the bash script
