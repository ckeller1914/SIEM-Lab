# SIEM-Lab

## Objective

### The goal of this project was to create a Security Information and Event Management (SIEM) home lab to simulate a real-world security environment. The lab involved setting up a honeypot to attract potential attackers, logging the events, and visualizing the attack data on a world map using Azure Sentinel.

## Skills Learned

### Network Security | Log management | SIEM Configuration and management | Threat Detection

## Steps

### 1) Create Azure Subscription

 ![Screenshot (116)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/4df086b0-889c-464a-8b38-4a419320136c)
  

### 2) Create Virtual Machine

![VM](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/160f38a4-f7bc-4f9c-829d-d752024af04d)


### 3) Allow All Traffic in Security Group

![SecurityGroup](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/a5a7b1c8-6b26-4efa-9781-5e0013b1611c)


### 4) Create Log Analytics Workspace

![CreateLogAnalytic](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/b7fea80e-e983-4771-98d7-262503b38240)


### 5) Enable VM Log Collection in Security Center

![logSecurityCenter](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/fbc8457e-d813-4f0f-8155-d8feaa415214)


### 6) Connect Log Analytics to VM


![LogVMFR](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/5c2d9d55-9cf9-44e7-b8d4-e5501b7cb616)



### 7) Set Up Azure Sentinel

![Sentinel](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/ac303aab-e39c-42e7-be30-409be15e2866)


### 8) Log into VM with Remote Desktop 

![remote](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/2b1c9212-2e80-4f6a-b258-64c2ced76f52)


### 9) Observe Event Viewer Logs in VM

![EventViewer](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/4e119a16-9416-4585-ab41-cbdb7198f13a)


![Event Veiwer 2](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/42f49708-e7da-457e-914b-694840e235fd)


 ### 10) Turn of Windows Firewall on VM

 ![firewall](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/81b0581f-7e36-47e0-a619-6d697f1e2b51)

 
![Screenshot (104)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/e6d61fe9-4057-4f4b-a61d-1cec352dd477)

 
### 11) Download PowerShell Script

![PowerScript](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/8498d122-ee71-49be-bb92-58aee5631683)


### 12) Get Geolocation.io API Key

![Screenshot (101)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/795c38ba-59f3-4a83-973e-8036f8d2ef05)


### 13) Run Script to Get Geo Data from attackers

![Run Script](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/f4e7caa5-c233-42ed-ba84-3bf8f2008dfb)



### 14) Create Custom Log in Log Analytics Workspace

    
 ![CustomLog](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/809d77d3-bc69-4983-9d17-f6fc5ef8f761)
 

### 15) Create Custom Fields/Extract Fields from Raw Custom Log Data

  ![Screenshot (122)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/c8a53a9c-67c0-4cb3-90db-c298cecf9d74)

 
### 16) Testing Extracts

![Screenshot (123)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/efac444c-0164-4174-87e4-f664fc3167b3)

### 17) Set Up Map in Sentinel with Latitude and Longitude (or country)

![Screenshot (126)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/740c1952-207c-4e87-8d5c-2fed75d0ad62)


### 18)  Monitor Honeypot Activity Over Time

   ### -Hour 1

![Screenshot (128)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/d472d704-afb2-4305-a574-e2c7aed6fc86)

   ### -Hour 3

  ![Screenshot (129)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/b953b11a-3dfa-405a-85a1-2fe54bf52359)

   ### -Hour 7

![Screenshot (130)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/ae6caf3e-793f-4531-9733-769578ceea77)

   ### -Hour 15

   ![Screenshot (135)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/0d5fed4d-eaab-4e7e-a924-9adee2f4e4f9)

## Outcomes:

 ### -Successfully set up and configured a SIEM environment using Azure services.

 ### -Collected and analyzed log data from a honeypot, demonstrating threat detection capabilities.

 ### -Visualized attack data on a world map, showcasing the ability to track and monitor security incidents in real-time.

## Summary

### This project demonstrates a comprehensive understanding of setting up and managing a SIEM environment, highlighting key skills in cybersecurity and practical experience with industry-standard tools and technologies.
