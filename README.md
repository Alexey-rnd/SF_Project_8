# Skill Factory Project 8 (HW-3)

- Run a container with nginx forwarding port 80 to port 9889 on the host system. When hosting nginx in a container over HTTP, nginx should serve the modified index.html file
- Checking the response code of the running container when making an HTTP request (the code should be 200)
- Comparing the md5 sum of the modified file with the md5 sum of the file given to nginx for an HTTP request (the sums must match)
- Trigger for starting CI: making changes to the generated index.html file. In case of an error (in the two previous paragraphs), an alert should be sent to a convenient communication channel - Telegram/Slack/email
- After CI execution, the created container is deleted