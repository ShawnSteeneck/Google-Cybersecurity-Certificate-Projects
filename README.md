# Google-Cybersecurity-Certificate-Projects
Google Cybersecurity: Using Suricata to trigger alerts on network traffic.
This lab has provided me with experience in using Suricata. 
This lab provided a step by step that taught me how to examine custom rules/signatures as well as create custom rules/signatures. It also taught me how to monitor traffic captured in a packet capture file and examine the fast.log and eve.json output.

I first examined the signature the file that the lab provided.
Using the cat command I displayed the rule in the file.
![image](https://github.com/ShawnSteeneck/Google-Cybersecurity-Certificate-Projects/assets/136599539/386dee13-6fff-405c-b91c-dc788e501b30)

This rule has three components. Which is an action, a header, and rule options. 
An action in this case it was alert. Which will send an alert based on selected network traffic. 
A header which consists of the protocol, source, and destination IP address. Also, the source and destination ports as well as the traffic direction. You can define a certain subnet as a variable to enable conditions to fit your organization’s needs. 
Rule options will let you customize the signature such as printing out an message showing why the alert was triggered. It also has options for network flow, what content to look for in which protocol. It also shows the signature ID and revision version. 
Next, we processed a pcap file with the rules provided in the initial signature file.
![image](https://github.com/ShawnSteeneck/Google-Cybersecurity-Certificate-Projects/assets/136599539/2def23be-9ab3-4e4b-8418-514b3b35fcf2)
These rules trigger multiple alerts.
![image](https://github.com/ShawnSteeneck/Google-Cybersecurity-Certificate-Projects/assets/136599539/83943d29-ba4f-4176-95bc-18c2a5183fb2)
I also learned to use the jq command to extract specific data from the eve.json file
![image](https://github.com/ShawnSteeneck/Google-Cybersecurity-Certificate-Projects/assets/136599539/b68790db-6bf6-4cdf-bfb9-6fbb7e920dd4)

 
