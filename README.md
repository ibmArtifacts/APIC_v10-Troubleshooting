# APIC_v10-Troubleshooting
These are some basic troubleshooting items for API Connect v10.

## Logging into the CLI terminal  
To log into the subsystem command prompt, the RSA key created from the install configuration is required.
Here is one method of logging in via Putty.  
1.	Enter the host/ip of the target system:  
![image](https://user-images.githubusercontent.com/66093865/207202856-481b2fbe-46ef-4e13-a60e-9bc05f54a72b.png)

2.	Navigate to the Connection > SSH > Auth section and select the private key to be used to login.  
![image](https://user-images.githubusercontent.com/66093865/207202896-30caf20d-b027-443a-9a77-02190546ec35.png)

3.	Once logged in, the user will be apicadm for all subsystems. The password will be what the rsa key was set to when initially creating it.  

## Checking APIC health-check  
Issue the following command 
```   
apic health-check
```  
