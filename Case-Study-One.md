## Case Study 01: No Internet Connection

### Problem Statement

An employee is having trouble accessing websites on their Windows laptop. They are connected to Wi-Fi but are unable to access the internet in order to complete their task.

### Initial Questions 

1. Are other devices able to connect to the Wi-Fi and access the internet?
2. Is there an error message appearing. on the laptop?
3. Has this happened after restarting the device, updating windows or changing the network?
4. Are they able to access internal resources?


### Possible Causes

Temporary issue with the Wi-Fi or router.
Incorrect IP configuration or DHCP.
DNS issue.
Proxy/Firewall or other network configuration issue.


### Troubleshooting Process

1. Check the Wi-Fi connection.  Check if Wi-Fi is enabled and connected to the right network.

2. Test other devices. Check if other devices can access the internet on the same Wi-Fi network.


3. Inspect the IP configuration. Open up command prompt and type in ipconfig to check the IP address, default gateway and DNS server.


4. Test connectivity to the gateway. Try pinging your gateway. You can do this by typing ping followed by the default gateway address shown in ipconfig. This will help you see if you can communicate with the gateway on your local network. Some networks may not allow you to do this.

5. Test DNS resolution. Run `nslookup example.com`. This will tell you if your DNS server can resolve domain names into IP addresses.
6. 

6. Analyze the results. If your laptop is unable to resolve domain names but can access the gateway then investigate the DNS settings. If your laptop can’t even access the gateway then check your local network connection and IP settings.

7. Apply the appropriate fix. Use the diagnostic results to guide the next step. Avoid changing multiple settings at once, and follow the organization's network policies.


### Resolution

For this example, suppose the investigation identifies an incorrect DNS configuration as the cause of the problem.

After confirming the correct network settings with the authorized network administrator, the technician corrects the DNS configuration. The technician then tests DNS resolution using `nslookup` and verifies internet access by opening several websites.

The employee confirms that the laptop can now access the internet and continue with their task. 

### Preventive Measures

- Ensure that the laptop has correct IP and DNS settings.
- Maintain updates to windows and network drivers in line with company policy.
Document ongoing connection problems and solutions.
- Notify the network administrator if the issue affects multiple devices or if changes are needed to managed network settings.

### Conclusion

This case shows how you can systematically troubleshoot an issue with your internet connectivity. By checking your Wi-Fi connection, IP configuration, gateway connectivity and DNS resolution you can easily determine what is causing the issue and apply the correct solution.


