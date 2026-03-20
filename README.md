## Incident Report: Software Deployment Failure

**Scenario:** User raised a software request that was marked "Completed," but the application was missing from the local machine.

| Field | Details |
| :--- | :--- |
| **Incident ID** | INC-2026-0422 |
| **User Status** | Irate / Urgent Deadline |
| **Issue** | Software marked as "Complete" in ServiceNow but not visible on Client UI. |
| **Root Cause** | Configuration Manager (MECM) "Policy Desk" sync failure. Client device missed the initial deployment window due to sleep mode. |
| **Resolution** | Manually triggered a Machine Policy Retrieval & Evaluation Cycle via the Control Panel to force the download. |

---

### Support Dialogue (Summary)

**Analyst (Natalee):** "Hello! This is Natalee at the Service Desk. How can I help?"  
**User:** "My Adobe request says 'Completed,' but it isn't on my PC. I have a deadline in 30 minutes!"  
**Analyst (Natalee):** "I understand the stress of a deadline. Let’s prioritize this. What is your Employee ID?"  
**User:** "It’s ID-9982. Please fix it!"  
**Analyst (Natalee):** "The server shows a successful push, but your laptop hasn't 'checked in.' What is your Asset Number?"  
**User:** "It’s CAP-LT-554. Can we hurry?"  
**Analyst (Natalee):** "I’m manually forcing the sync now. One moment while I trigger the update."  
**Analyst (Natalee):** "The push is sent. Please check your 'Software Centre' for the installation status."  
**User:** "I see it now. It says 'Downloading (0%).' Why didn't it work before?"  
**Analyst (Natalee):** "It likely missed the signal due to Sleep Mode or weak Wi-Fi. I’ve cleared that queue for you."  
**Analyst (Natalee):** "Great. Your reference is INC-2026-0422. I’ll stay on the line until it reaches 'Installing.'"  
**User:** "It’s at 90% and installing. I’m good to go. Thanks."  
**Analyst (Natalee):** "You're welcome! Good luck with your report and have a great day."

### Images of incident Report:

<img width="1408" height="768" alt="image" src="https://github.com/user-attachments/assets/2db8c1db-d31e-4159-886d-ed98ffbfa5df" />
<img width="1408" height="768" alt="image" src="https://github.com/user-attachments/assets/4a8e4008-1b79-4757-9395-35391e563933" />
<img width="1408" height="768" alt="image" src="https://github.com/user-attachments/assets/4bac8b30-8029-4d28-97f9-af2e6c9d7049" />



