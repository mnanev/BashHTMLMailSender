📧 BashHTMLMailSender

📝 Description

The script is used to send messages based on an HTML template and a list of recipient emails. It can be reconfigured based on your needs and is primarily designed for phishing campaigns. The script hardcodes the usernames into the links within the template, allowing you to track which users have clicked on the links.

By using a web server like Apache or Nginx, you can monitor which users clicked the links by reviewing the HTTP access logs. Without this modification, you would only see the accessed link and the IP address.

⚙️ Requirements

🐧 Linux Machine
✉️ Installed sendmail service
🔧 Configured ssmtp

🚀 Usage

📝 Reconfigure email.html and the bash script according to your needs.
📋 Add your recipients in the emails.txt file.
▶️ Run the bash script.
