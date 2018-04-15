# CodePath Honeypot

Honeypot(s) used: Dionaea with HTTP

Difficulties encountered during activity:

- installation of Google Cloud SDK using archive files: it turns out that using the goggle SDK installer was much simpler
- initial setup of firewall using gcloud command line prompts- needed to hit yes quickly to allow creation or process would run forever
- setup of the initial mhn-admin Virtual Machine, poor setup required reinitialization of ssh keys
- running the script failed first time- deleted the VM and ran process again

Summary of data:
<img src=https://github.com/Granty1231/CodePath9/blob/master/honeypot-1.PNG>

<img src=https://github.com/Granty1231/CodePath9/blob/master/honeypot-2.PNG>

Unresolved questions raised by the data collected:
- What determined the source of attacks geographically? the countries/ IP addresses seemed to come from arbitrary locations

Link session.json: https://github.com/Granty1231/CodePath9/blob/master/session.json
