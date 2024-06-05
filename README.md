# Google-Cybersecurity-Certificate-Projects
Google Cybersecurity: Using Suricata to trigger alerts on network traffic.
This lab has provided me with experience in using Suricata. 
This lab provided a step by step that taught me how to examine custom rules/signatures as well as create custom rules/signatures. It also taught me how to monitor traffic captured in a packet capture file and examine the fast.log and eve.json output.

I first examined the signature the file that the lab provided.
Using the cat command I displayed the rule in the file.
 
This rule has three components. Which is an action, a header, and rule options. 
An action in this case it was alert. Which will send an alert based on selected network traffic. 
A header which consists of the protocol, source, and destination IP address. Also, the source and destination ports as well as the traffic direction. You can define a certain subnet as a variable to enable conditions to fit your organization’s needs. 
Rule options will let you customize the signature such as printing out an message showing why the alert was triggered. It also has options for network flow, what content to look for in which protocol. It also shows the signature ID and revision version. 
Next, we processed a pcap file with the rules provided in the initial signature file.
 
These rules trigger multiple alerts.
 
I also learned to use the jq command to extract specific data from the eve.json file.
 
