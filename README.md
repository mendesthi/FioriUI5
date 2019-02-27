# FioriUI5
FioriUI5 for SMB Summits 2019 Hackathon

# Pre-reqs
This app requires at least two destinations on SAP Cloud Platform: one core ERP as the back-end and an smb mkt place app running.

Please, follow the steps below to configure the destinations:
1 - Access your SAP Cloud Platform account on https://account.hanatrial.ondemand.com/cockpit/#/home/trialhome;
2 - Select Neo Trial > Connectivity > Destinations
3 - Select "Import Destination"
4 - Use the file https://github.com/mendesthi/FioriUI5/blob/master/destinations/B1CLOUDSAP
5 - In the URL field, replace the <your-sapb1hana-host> by your B1 backend system
6 - Change the user/password fields accordingly
7 - Save the destination
8 - Select "Import Destination" again, this time to create the smb mkt place app's destination
9 - Use the file https://github.com/mendesthi/FioriUI5/blob/master/destinations/smbmkt
10 - Save the destination
  
# Import this SAP Fiori App into your SAP Cloud Platform Webide
1 - Go to your SAP Cloud Plaftform Webide, right-click the workspace folder > Git > Clone Repository
2 - Paste this repo URL: https://github.com/mendesthi/FioriUI5.git
3 - Run your app
