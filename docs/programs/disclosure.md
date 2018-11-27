---
title: "Disclosure"
path: "/programs/disclosure.html"
id: "programs/disclosure"
---

Disclosure enables you to be transparent about the security vulnerabilities found for your program. HackerOne's disclosure process balances transparency with control over what information is shared with the public.  

Programs can choose from 3 disclosure settings:

Option | Details
------ | -------
Disclosure by Default | The hacker or your security team can request disclosure for any closed report in your program. If the admin of your program agrees to disclosure, the contents of the report will be made public within 30 days.<br> <br>*This is the default setting for all verified programs*.
Disclosure requiring Mutual Agreement | The hacker can request disclosure for any closed report in your program. If your program security team agrees to disclosure, the contents of the report will be made public. If the security team doesn't take any action, the contents of the report will remain private. <br>*You must request to opt-in to this option.*
Disclosure Disabled | Disclosure isn't allowed for any report.

### Requesting Disclosure
Both hackers and program members can request for disclosure. To request for disclosure:
1. Go to the report you want to disclose.
2. Make sure the report is closed.
3. Select **Request disclosure** in the action picker at the bottom of the report.

![Request Disclosure](./images/disclosure-1.png)

4. Select whether you want to disclose the **Full** report or a **Limited** version.

Option | Details
------ | -------
Full | Upon disclosure, the full contents of the report are visible including the:<li>Vulnerability information</li><li>Summary</li><li>Timeline (this includes comments and attachments)</li><br>*Note: Internal comments are kept hidden.*  
Limited | Only the summary and timeline of the activity are visible. All comments and attachments are hidden. Limited disclosure allows for greater control over sensitive or extraneous information.

5. *(Optional)* Enter a comment to describe your reasons for disclosure.

6. Click **Post**.    

After disclosure has been requested, the admin of the of the program can choose to publicly disclose the report. They can select **Disclose** to disclose the report, and they can also change the disclosure options to Full or Limited.

![Disclose](./images/disclosure-2.png)

>Made a mistake? To remove a pending disclosure request, reopen and re-close the report.

### Disclosure for Private Programs (beta)
If you’re running a private program, you can enable hackers to disclose a report within your private program. Upon disclosure, contents of the report will only be visible to participants in your private program. This enables hackers to share their vulnerability findings with other hackers in the program, and can also increase awareness for other hackers as they can better see what vulnerabilities have already been found for your program.  

>Disclosure for private programs is currently in the beta phase. To opt-in to the feature contact your program manager.

To enable disclosure for private programs:
1. Go to **Settings > Program > Customization > Disclosure**.

![disclosure settings](./images/disclosure-5.png)

2. Select **Yes** to enable hackers to disclose reports in your private program.

Hackers and other members in your program can request for disclosure following the same steps above in the Requesting Disclosure section above.

When choosing to disclose the Full or Limited report, the options will only be specific to disclosing within your private program:

Option | Details
------ | -------
Full | Upon disclosure, the full contents of the report will be visible to participants in your private program.
Limited | Only the summary and timeline of activity will be visible to participants in your private program.

![disclose for private program](./images/disclosure-3.png)

This diagram illustrates HackerOne's disclosure process:

![disclosure flowchart](./images/disclosure-4.png)

For more information, please read the full [HackerOne Disclosure Guidelines](https://hackerone.com/disclosure-guidelines). If disclosure was accidentally initiated or you have concerns about this process, please [submit a support request](https://support.hackerone.com/hc/en-us/requests/new).