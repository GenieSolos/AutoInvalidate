# AutoInvalidate
This is a batch script to Automatically invalidate your cloudfront with one click!

Follow the below steps in order to securely activate
Step 1: Create a new AWS user with no permissions added, select access key instead of password.  copy down user access key and secret id  
Step 2: Create a new permission that only gives the user from your ip address the ability to invalidate your cloudfront distribution,
Sample template for policcy will be in the file titled "InvalidationBoss"
Step 3: download aws cli to your desktop, type "aws configure" and enter that users access key id, secret id, region, and default file type
Step 4: copy script from "AutoInvalidate.bat" into a text file.  Replace needed parts, save AutoInvalidate.bat
Step 5: For added spice, create a shortcut, right click, properties, shortcut, change icon, replace icon with GenieSolos.ico


in my scripts a <> means you do not have to rewrite the <> when you replace them... IE  a <insert ip> means 10.10.10.10 NOT <10.10.10.10>
