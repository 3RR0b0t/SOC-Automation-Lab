# SOC-Automation-Lab

## Objectives
Setting up a SOC (Security Operations Center) automation lab with TheHive, Wazuh, Shuffle, OSINT (Open Source Intelligence), and email integration for receiving email notifications on alerts can be a robust way to enhance your security monitoring capabilities. Here's a breakdown of the objectives and steps to achieve them:

Objective:
Automate the process of receiving alerts from Wazuh, enrich them with OSINT data using TheHive, and send email notifications using Shuffle.

Steps:
## 1. Setup Environment:

  Install and configure Wazuh for intrusion detection and monitoring.
  
  Deploy TheHive for case management and incident response.
  
  Set up Shuffle for workflow automation.
  
  Configure email server or use an SMTP service for sending email notifications.


![Screenshot 2024-05-08 201724](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/eca6478f-9a6f-4177-afa3-1095d52d908d)


![Screenshot 2024-05-08 202011](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/5bd8d015-1f29-4768-8603-6b0a5d01c96e)

## 2. Integrate Wazuh with TheHive:
  
  Configure Wazuh to send alerts to TheHive.
  
  Use Webhooks or native integration depending on the capabilities of Wazuh and TheHive versions.
  
  Ensure proper mapping of Wazuh alerts to TheHive cases.

![Screenshot 2024-05-10 131046](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/79e62be2-d2bb-448c-9278-53d0c8d55b10)

![Screenshot 2024-05-10 010115](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/5ddbe9e4-a97b-4dab-8fec-3e8f9f85f343)


![Screenshot 2024-05-10 133123](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/20e512b9-2002-4230-80ed-40a6018b5fd5)

  
![Screenshot 2024-05-10 180918](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/2d27e020-5407-4620-bade-32245e60f8e3)


![Screenshot 2024-05-10 181812](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/a195faea-5d7c-4613-a9ac-dadb1e8127a4)


![Screenshot 2024-05-10 182245](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/790680fe-e336-4259-801a-e4a1188608c5)


![Screenshot 2024-05-10 182626](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/09347016-c240-4401-a016-0346d5008e3f)


![Screenshot 2024-05-10 222647](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/7918acab-075d-4574-9045-fe3bd4be3fa7)


## 3. Enrich Alerts with OSINT:

  Integrate OSINT tools or APIs with TheHive.
  
  Customize TheHive to automatically enrich incoming alerts with relevant OSINT data.
  
  Ensure privacy and compliance considerations are addressed when fetching external data.


![Screenshot 2024-05-10 182245](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/fd947dd0-f271-4a17-8ea5-bcea2cf7b9b2)

![Screenshot 2024-05-13 165732](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/5f31347b-3f37-460c-91d1-6689a1c48d09)


![Screenshot 2024-05-13 174146](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/a79f7dc5-114a-47e3-b5c3-b78467b3af64)


![Screenshot 2024-05-13 174335](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/47da20cd-c128-4cdb-9891-25f52b724301)


## 4. Automate Workflow with Shuffle:

  Design workflows within Shuffle to automate incident response processes.
  
  Define actions based on the severity and type of alerts received.
  
  Implement decision trees and logic for automated response actions.

![Screenshot 2024-05-12 234751](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/37031baf-3d8e-4ed2-8d6f-449c5413246a)

![Screenshot 2024-05-13 000109](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/21d71ccd-4f5d-477f-a706-e73fc402e431)

![Screenshot 2024-05-13 000404](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/8d3f0776-f276-4e94-ab24-7a9fe659ae6b)

![Screenshot 2024-05-13 004711](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/05f13177-43d7-401b-ba68-c8eaa6298389)


## 5. Configure Email Notifications:

  Utilize Shuffle's email integration capabilities.
  
  Set up email templates for different types of alerts and incidents.
  
  Configure triggers to send email notifications based on predefined conditions.

![Screenshot 2024-05-13 174604](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/4bba2d73-ee5a-426f-9257-ee13b397d610)
 

## 6. Test and Refine:

  Conduct testing to ensure the end-to-end automation flow works as expected.
  
  Test various scenarios, including different types of alerts and OSINT enrichment.
  
  Refine configurations based on feedback and real-world use cases.

![Screenshot 2024-05-10 232323](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/f921cdc7-065b-407d-af73-476e61a64dad)

![Screenshot 2024-05-12 150915](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/a0938263-ed5e-4a55-8ea0-43e87d6d98f5)


![Screenshot 2024-05-12 175259](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/f4c80a8d-17c2-4070-a741-c77a0db180ed)


![Screenshot 2024-05-12 175312](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/22c6ca8b-67d5-4d1c-afa3-0fa9fb6094a0)


## 7. Monitor and Maintain:

  Monitor the SOC automation lab for any issues or failures in alert processing.
  
  Perform regular maintenance tasks, such as updating software versions and security patches.
  
  Continuously optimize the workflow and automation processes based on performance metrics and feedback.

![Screenshot 2024-05-12 184333](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/5d9058a4-6d6f-479c-9af7-aabe28e36507)

  
![Screenshot 2024-05-13 173700](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/101d5a0c-bba5-4e31-a4c9-4e9e22c91b4e)


![Screenshot 2024-05-13 174146](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/4544ba45-afb2-4580-9982-e63849288fc0)


![Screenshot 2024-05-13 005202](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/7a40ca46-518c-4c9c-9702-c0da2588ec66)


![Screenshot 2024-05-13 031647](https://github.com/3RR0b0t/SOC-Automation-Lab/assets/168855597/80fa5e35-527a-4345-a9a1-b072e9502745)


By following these steps, you can establish a comprehensive SOC automation lab that leverages the capabilities of TheHive, Wazuh, Shuffle, OSINT, and email integration to enhance your security monitoring and incident response capabilities while reducing manual effort.
