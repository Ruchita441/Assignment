Connect to the EC2 instance using Secure Shell (SSH). You will need the IP address of the instance, as well as a username and password or an SSH key pair to authenticate the connection.First In AWS EC2 server we need to add SSH 22 port in Security Group.


After that for login to the EC2 server we can use WINSCP Software or Session Manager ,EC2 Instance Connect (browser-based SSH connection) but recommended way is use software to login to EC2 server
Launch WinSCP and click on the "New Site" button in the main interface
In the "New Site" dialog box, enter the IP address of the EC2 instance in the "Host name" field.
Select "SCP" as the file protocol and enter the username and password or the path to the SSH key pair file in the appropriate fields.
Click the "Advanced" button to open the advanced settings for the connection.
In the "Advanced Site Settings" dialog box, go to the "SSH" tab and select "2 only" as the SSH protocol version.
Click "OK" to save the advanced settings and close the dialog box.
Click "Login" to connect to the EC2 instance using WinSCP
