Powershell to enable Azure multi-factor authentication for bulk user
====================================================================

            

[Powershell to enable Azure multi-factor authentication for bulk user](http://vedtechno.com/how-to-enable-multi-factor-authentication-for-azure-user-step-by-step/)


[Attached is the script to enable MFA for bulk user useing powershell. you can specify the users or you can use different method to pass the user principle names to script](http://vedtechno.com/how-to-enable-multi-factor-authentication-for-azure-user-step-by-step/)


[How to use - http://vedtechno.com/how-to-enable-multi-factor-authentication-for-azure-user-step-by-step/](http://vedtechno.com/how-to-enable-multi-factor-authentication-for-azure-user-step-by-step/)


 


 .PARAMETER  


 All - set MFA for all user in azure ad       


Synchronized - set MFA for Synchronized users (Synchronized from on premises)       


specific - set MFA for specific users. if you select this option then you will get prompt to enter username.       


Synchronized - set MFA for Synchronized users. if you select this option then you will get prompt to enter txt file full path



   .EXAMPLE 1 PS C:\> Set-MFA -specific -NewState Enabled 



 .EXAMPLE 2 PS C:\> Set-MFA -Synchronized -NewState Disabled 
.EXAMPLE 3 PS C:\> Set-MFA -All -NewState Disabled 
.EXAMPLE 3 PS C:\> Set-MFA -txt -NewState Enforced 


**Why multi-factor authentication?** –  Compromising multiple authentication factors presents a significant challenge for attackers. Even if an attacker manages to learn the user’s password, it is useless without also having
 possession of the trusted device. Should the user lose the device, the person who finds it won’t be able to use it unless he or she also knows the user’s password.

 

 

» Azure » **[How to enable multi-factor authentication for Azure user – Step by step](http://vedtechno.com/how-to-enable-multi-factor-authentication-for-azure-user-step-by-step/)**

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
