<p align="center">

  ![image](https://github.com/user-attachments/assets/0266b5ec-3625-46bd-a656-29ce838eebd8)

</p>

<h1>SOC Log Analytics and GeoIP Watchlist Setup Lab</h1>
In this lab, I set up a Log Analytics Workspace (LAW) named "LAW-Cyber-Lab-0x" and configured Azure Sentinel to monitor and aggregate logs for security analysis. A key part of the lab is creating a GeoIP watchlist, which includes 27,000 records uploaded from a local file. The watchlist, named "geoip," is queried within the workspace to ensure proper integration with Sentinel. This lab demonstrates my ability to configure security monitoring tools, manage log aggregation, and use watchlists for network analysis in a SOC environment.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Sentinel
- Log Analytics Workspace

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 - Create a Log Analytics Workspace (our log aggregator) named: LAW-Cyber-Lab-0x
- Step 2 - Setup Microsoft Sentinel and connect it to our Log Analytics Workspace
- Step 3 - Create the geoip watchlist:
- Step 4 - Next, go to Log Analytics Workspace and make sure something comes out when you query _GetWatchlist("geoip")


<h2>Deployment and Configuration Steps</h2>

- Create a Log Analytics Workspace (our log aggregator) named: LAW-Cyber-Lab-0x
![Screenshot 2024-10-06 163119](https://github.com/user-attachments/assets/062b2ad1-6cf0-4bfe-a7eb-3c9dba37e836)

- Setup Sentinel and connect it to our Log Analytics Workspace
![Screenshot 2024-10-06 163817](https://github.com/user-attachments/assets/7edbb621-c18f-4f2d-9fe7-31b1f510b44c)

- Create the geoip watchlist:
![Screenshot 2024-10-06 164854](https://github.com/user-attachments/assets/f957fa05-9789-4be1-a609-96947e5f214f)

- Next, go to Log Analytics Workspace and make sure something comes out when you query _GetWatchlist("geoip")
![image](https://github.com/user-attachments/assets/030fc31d-2623-445c-b349-1d5f5d02b712)






