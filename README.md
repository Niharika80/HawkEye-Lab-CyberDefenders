# HawkEye-Lab-CyberDefenders
This repository contains my notes and analysis from the HawkEye lab on [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/achievements/Niharika/hawkeye/). 
The lab focuses on **network traffic analysis** and **Blue Team operations** using **Wireshark**.

## Tools Used: `Wireshark`

## Scenario:
An accountant at your organization received an email regarding an invoice with a download link. Suspicious network traffic was observed shortly after opening the email. As a SOC analyst, investigate the network trace and analyze exfiltration attempts.

## Questions:

Q1 : How many packets does the capture have?

Answer : `4003`

![Description](images/hawk_eye_packet.png)
___

Q2 : At what time was the first packet captured?

Answer : `2019-04-10 20:37`

___

Q3 : What is the duration of the capture?

Answer : `01:03:41`

___

Q4 : What is the most active computer at the link level?

Answer : `00:08:02:1c:47:ae`

___

Q5 : Manufacturer of the NIC of the most active system at the link level?

Answer : `Hewlett-Packard`

___

Q6 : Where is the headquarter of the company that manufactured the NIC of the most active computer at the link level?

Answer : `Palo Alto`

___

Q7 : The organization works with private addressing and netmask /24. How many computers in the organization are involved in the capture?

Answer : `3`

In Wireshark under Statistics > Endpoints, I observed 4 IP addresses. One of them was 10.4.10.255, which is the broadcast address for the /24 network and not an actual host. Excluding the broadcast address, there are 3 computers involved in the capture.
___

Q8 : What is the name of the most active computer at the network level?

Answer : `BEIJING-5CD1-PC`

___

Q5 : Manufacturer of the NIC of the most active system at the link level?

Answer : `Hewlett-Packard`

___

Q5 : Manufacturer of the NIC of the most active system at the link level?

Answer : `Hewlett-Packard`

___

Q5 : Manufacturer of the NIC of the most active system at the link level?

Answer : `Hewlett-Packard`

___

Q5 : Manufacturer of the NIC of the most active system at the link level?

Answer : `Hewlett-Packard`

___

Q5 : Manufacturer of the NIC of the most active system at the link level?

Answer : `Hewlett-Packard`

___



