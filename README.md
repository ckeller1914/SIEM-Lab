# SIEM-Lab

## Objective

This is a brief overview of a SIEM home lab I created.
In this lab we will create a honeypot, log the events,
and display the results on a world map via Sentinel.

## Skills Learned

Network Security | Log management | SIEM Configuration and management | Threat Detection

## Steps

1) Create Azure Subscription

 ![Screenshot (116)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/4df086b0-889c-464a-8b38-4a419320136c)
  

2) Create Virtual Machine

![VM](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/160f38a4-f7bc-4f9c-829d-d752024af04d)


3) Allow all in Security Group

![SecurityGroup](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/a5a7b1c8-6b26-4efa-9781-5e0013b1611c)


4) Create Log Analytics Workspace

![CreateLogAnalytic](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/b7fea80e-e983-4771-98d7-262503b38240)



5) Enable gathering VM logs in Security Center

![logSecurityCenter](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/fbc8457e-d813-4f0f-8155-d8feaa415214)


6) Connect Log Analytics to VM


![LogVMFR](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/5c2d9d55-9cf9-44e7-b8d4-e5501b7cb616)



7) Setup Azure Sentinel

![Sentinel](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/ac303aab-e39c-42e7-be30-409be15e2866)


8) Log into VM with Remote Desktop 

![remote](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/2b1c9212-2e80-4f6a-b258-64c2ced76f52)


9) Observe Event Viewer Logs in VM

![EventViewer](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/4e119a16-9416-4585-ab41-cbdb7198f13a)


![Event Veiwer 2](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/42f49708-e7da-457e-914b-694840e235fd)




 10) Turn of Windows Firewall on VM

 ![firewall](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/81b0581f-7e36-47e0-a619-6d697f1e2b51)

 
![Screenshot (104)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/e6d61fe9-4057-4f4b-a61d-1cec352dd477)

 
11) Download PowerShell Script

![PowerScript](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/8498d122-ee71-49be-bb92-58aee5631683)


12) Get Geolocation.io API Key

![Screenshot (101)](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/795c38ba-59f3-4a83-973e-8036f8d2ef05)


13) Run Script To get Geo Data from attackers

![Run Script](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/f4e7caa5-c233-42ed-ba84-3bf8f2008dfb)



14) Create custom log in LAW to bring in our custom log

    
 ![CustomLog](https://github.com/ckeller1914/SIEM-Lab/assets/116524804/809d77d3-bc69-4983-9d17-f6fc5ef8f761)
 

15) Create custom fields/extract fields from raw custom log data
 
16) Testing Extracts

17) Setup map in sentinel with Latitude and Longitude (or country)

18) Monitor honeypot activity over time


