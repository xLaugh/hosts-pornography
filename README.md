# Block List `hosts` File

This `hosts` file blocks specific websites by redirecting them to `0.0.0.0` or `127.0.0.1`.

---

## Installation (Windows)

1. **Download the `hosts` File**  
   - Click **Code** > **Download ZIP**.  
   - Extract the ZIP file to get the `hosts` file.

2. **Backup Your Current `hosts` File**  
   - Go to `C:\Windows\System32\drivers\etc`.  
   - Copy the existing `hosts` file to a safe location.

3. **Replace the `hosts` File**  
   - Paste the downloaded `hosts` file into `C:\Windows\System32\drivers\etc`.  
   - Select **Replace the file in the destination** if prompted.

4. **Flush the DNS Cache**  
   - Open Command Prompt as Administrator.  
   - Run the command:  
     ```bash
     ipconfig /flushdns
     ```

5. **Test the Block**  
   - Open your browser and try visiting one of the blocked websites. It should fail to load.

---
