# Lets-Go-Splunking

I successfully completed the Vandalay Industries Monitoring Activity assignment, where I was hired as an SOC analyst to enhance the security monitoring using Splunk. 

In the first step, I addressed the impact of a recent DDOS attack on Vandalay's web servers. After uploading the system speed data, I utilized the eval command to create a "ratio" field representing the upload/download speed ratio. The report, generated with Splunk's table command, displayed relevant fields such as date, time, IP address, download and upload speeds, and the calculated ratio. I provided insights into the approximate date and time of the attack and the duration of the system recovery along with a screenshot of the report.

Moving on to the second step, I focused on assessing the vulnerability of sensitive customer data on the servers using Nessus scans. I created a report showcasing the count of critical vulnerabilities on the customer database server and implemented an alert to notify the team if any critical vulnerability reoccurs. Screenshots of the report and the alert creation were included in the submission.

For the final step, I tackled brute force attacks on a Vandalay server's administrator account. By analyzing administrator login logs, I identified the timeframe of the brute force attack, established a baseline for normal activity, and set a threshold for triggering an alert. I designed an alert to check the threshold hourly and email the SOC team at SOC@vandalay.com if triggered, providing a screenshot as evidence of the alert creation. 

The entire assignment showcased my ability to effectively use Splunk for security monitoring and respond to specific threats faced by Vandalay Industries.
