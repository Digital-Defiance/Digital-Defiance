# Email Migration from Microsoft 365 to DreamHost

1) You should receive an email to your personal email address and your M365 Digital Defiance email containing your new login credentials for DreamHost email.
2) You'll want to [download Mozilla Thunderbird](https://www.thunderbird.net/en-US/download/) and install it
3) In Thunderbird, add an email account
    ![image](https://github.com/Digital-Defiance/Digital-Defiance/assets/3766240/53f221d6-c902-4ad7-a90a-cd9dafaadff2)
    
      * Leave password blank.
      * Click 'Configure Manually'
      * Fill in your account details for Microsoft 365
        ![image](https://github.com/Digital-Defiance/Digital-Defiance/assets/3766240/4d2d61a1-5b51-486d-bb6f-ce1d3c93573e)
        The server for outgoing and incoming is 'outlook.office365.com' and the port for IMAP is 993 and the one for SMTP is 587.
        Note that M365 is using OAuth2 for authentication
      * Click 'Re-Test', then 'Done'
4. In Thunderbird under your newly added M365 account, subscribe to any folders you had in place, especially 'Sent' and optionally 'Junk'

     * Click the account name in the Thunderbiard main email window, then right click and select Subscribe
       ![image](https://github.com/Digital-Defiance/Digital-Defiance/assets/3766240/cca1ddab-2fef-46d1-818a-0dad093f2b20)
     * Click each folder you want to subscribe to and click the subscribe button
       ![image](https://github.com/Digital-Defiance/Digital-Defiance/assets/3766240/fb106dec-0923-4b5e-aa0c-24f82b21c15c)
5. In Thunderbird, add another mail account

   * Click the cog at the bottom left
        ![image](https://github.com/Digital-Defiance/Digital-Defiance/assets/3766240/25c3f14e-abd3-4677-8e82-827b9c174e42)

   * Click 'Account Settings'
        ![image](https://github.com/Digital-Defiance/Digital-Defiance/assets/3766240/878e402f-abcc-4d1c-9338-d1e182f0bfa6)

   * Click 'Account Actions' and then 'Add mail account'
        ![image](https://github.com/Digital-Defiance/Digital-Defiance/assets/3766240/819a3608-9e4a-4f51-b902-0ce08f38c32c)

6) Fill in the DreamHost account details, this time filling in the password you were mailed in Step 1
     ![image](https://github.com/Digital-Defiance/Digital-Defiance/assets/3766240/3a4fa695-8849-46da-b0f4-e3f80ff2c85d)

       * Click 'Configure Manually'

     * Fill in the IMAP and SMTP details
          * ![image](https://github.com/Digital-Defiance/Digital-Defiance/assets/3766240/77c9f1e5-72db-483a-97ea-06a631e78301)
               IMAP host is imap.dreamhost.com and port is 993
               SMTP host is smtp.dreamhost.com and port is 465
               Click 'Re-Test' and 'Done'


7) You should now have two functioning email accounts in Thunderbird.
     * Wait for all the email messages to download/index

8) Select all (Ctrl+A/CMD+A) of the emails in each folder on the M365 account that you want to copy and drag them to the Inbox on the other (Dreamhost) account.

     * This will take some time

     * Repeat for each folder, eg 'Sent'.
