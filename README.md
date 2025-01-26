# Linux-assignments
# My Azure Virtual Machine Setup Report

---

# Login Process
1. VM Info:
   - OS: Ubuntu 24.04.1 LTS
   - Public IP: `52.138.158.56`
   - **Username:** `lingkon`

2. How I Logged In:
   - I used PuTTY to log in to the VM.
   - Entered:
     - Host Name (IP):`52.138.158.56`
     - Port: `22`
     - Connection Type: SSH
   - After entering my username and password, I successfully logged in and saw the welcome message:
     ```
     Welcome to Ubuntu 24.04.1 LTS
     ```

---

# System Update & Checks
1. Updating the System:
   - I ran this command to update and upgrade the system:
     ```bash
     sudo apt update && sudo apt upgrade -y
     ```
   - The system confirmed there were no pending updates.

2. Checking Disk Space & Memory:
   - Disk Space:
     ```bash
     df -h
     ```
     Result:
     ```
     Filesystem      Size  Used Avail Use% Mounted on
     /dev/root        28G  1.5G   26G   6% /
     ```
   - Memory Usage:
     ```bash
     free -h
     ```
     Result:
     ```
                   total        used        free      shared  buff/cache   available
     Mem:           976M         77M        802M        1.0M         97M        782M
     ```

3. Checking Internet Connection:
   - Ran this to check if the VM is connected to the internet:
     ```bash
     ping google.com -c 4
     ```
   - Output showed that everything is fine with the connection.

---

# Final Notes
- The login and setup worked perfectly.
- The system is running smoothly with all updates applied.
- I also made the SSH setup more secure by disabling root login.

#Screenshots
- Screenshots of the login process, system update confirmation, and system checks have been saved as evidence of successful execution.
-  ![Screenshot 2025-01-26 235826](https://github.com/user-attachments/assets/83525cc9-2d92-44a2-a64a-eb04f6d6bb88)


---
