# CSV2AD
This automates Active Directory user creation. It prompts for domain, top-level domain, and organizational unit, ensuring connectivity and OU existence. The user details, sourced from a CSV file, generate accounts with default passwords. The script creates accounts efficiently, providing success messages, while tracking added and skipped users. 

To use:
1. Copy over the script and the csv file in the same folder
2. Load powershell, and launch the script
3. type the start of your domain i.e google
4. type your tld(do not include a .) i.e com
5. Let the script work its magic.
## Features:

- **Dynamic Configuration:** Prompt for domain, top-level domain, and organizational unit.
- **Connectivity Check:** Verify connectivity with the primary domain controller.
- **OU Validation:** Check if the specified organizational unit exists.
- **CSV Import:** Import user details from a CSV file for bulk processing.
- **User Creation:** Efficiently create user accounts with default passwords. (Default is Password123, users are prompted to set a password upon loggin in)
- **Success Tracking:** Display success messages for each user created.
- **User Count:** Track the number of users added and skipped during execution.
- **Execution Time:** Calculate and display the duration of the script execution.
