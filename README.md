# GetO365UserLicenses
This simple scripts compiles a list of all users from the O365 tenant, discovers licenses assigned to the users and exports the results in a report.

File description:
Get-UsersWithLicenses.ps1 - Script
ProductNames.csv - File containing all current Microsoft licenses and readable descriptions
UserLicenseReport.csv - Report file
README.md - this file

Report sample:


![image](https://user-images.githubusercontent.com/67024372/141153562-fa3d676a-c9f3-4850-927e-27f3d7abed77.png)




Product name input file sample (file included content from https://docs.microsoft.com/en-us/azure/active-directory/enterprise-users/licensing-service-plan-reference as of Nov 10, 2021):

NOTE: If the "reseller-account:" portion of the license is not included in your org (e.g if you don't have MSP handling licenses for example), then simply Find/Remove all instances of the "reseller-account:" sting from the file.
![image](https://user-images.githubusercontent.com/67024372/141153912-81d90076-5647-4b38-a097-3e213d12daed.png)

