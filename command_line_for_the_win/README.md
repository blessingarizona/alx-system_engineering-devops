## Uploading Screenshots using SFTP

The screenshots of completed levels are uploaded to the sandbox environment using the SFTP command-line tool. Here's a breakdown of the process:

1. **Connect to Sandbox:**
   - Use the `sftp` command followed by your username and hostname (replace `<username>` and `<hostname>` with your actual credentials):

     ```bash
     sftp <username>@<hostname>
     ```

2. **Navigate to Upload Directory:**
   - Use the `cd` command to change the directory to the desired location within the sandbox (replace `<upload_directory>` with the actual directory name):

     ```bash
     cd <upload_directory>
     ```

3. **Upload Screenshots:**
   - Use the `put` command followed by the filename of each screenshot to upload them from your local machine:

     ```bash
     put 0-first_9_tasks.png
     put 1-next_9_tasks.png
     put 2-next_9_tasks.png
     
     ```

