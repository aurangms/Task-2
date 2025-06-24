# Task-2
Cyber security intership Task 2
Analyze a Phishing Email Sample
- In this task i added one sample Phishing email . Sample phishing email 1

we can look into the  sample 
- Suspicious Sender Email Address:
  - the Display name 'Security_Alerts' looks officail but the underscore is a minor tell
  - The From Address <support@onlineservice.co.uk> the 'onlineservice' sound ok but the '.co.uk' domain might not match the expected domain of a global cloud storage provider (eg:.com).
  - Attacker often use similar lokking but slightly off domain to trick recipients
  - The "Replay-To" Address 'security.verifaction@outlook.com' this is a red flag. Legitimate companies would use their official domain for replies not a generic email service like outlook and we can see "verifaction" has a spelling error
- Generic Greeting:
  - 'Dear Valued Member,'  This is a common tactic. Legitimate services typically address you by your specific name if they have your account details. Scammers use generic greetings because they send mass emails.

- Sense of Urgency and Threatening Language:
  - Urgent Security Alert, Immediately Suspended, immediate verification, Failure to complete this verification within 24 hours will result in permanent account termination and loss of all data. - This is classic phishing. It tries to create panic and pressure you into acting without thinking, bypassing your critical judgment.

- Requests for Sensitive Information (Indirect):
  - The email doesn't directly ask for your password in the email body, but it instructs you to "click on the secure link below to verify your account and restore full access." The goal of this link is to take you to a fake login page where you will be asked for your credentials. Legitimate companies rarely ask you to "verify" account details by clicking a link in an email.

- Suspicious Link (URL Manipulation):
  - Displayed Text: Verify Your Account Now - Looks clean and inviting.

        Actual URL (if you were to hover, DO NOT CLICK IN A REAL SCENARIO): https://www.online-cloud-secure.com/account/login?id=your-account-id-12345

   - Notice the domain: online-cloud-secure.com. While it includes keywords like "online," "cloud," and "secure," it's likely not the actual domain of a real cloud storage provider (e.g., Dropbox.com, GoogleDrive.com). Phishers use domains that sound legitimate but are slightly different.

   - The use of HTTPS (https://) can make it seem legitimate, as many phishing sites now use SSL certificates. So, always check the domain itself, not just the "s".

- Spelling and Grammar Errors:
  - top priorety instead of top priority. While subtle, these errors are common in phishing emails, especially those originating from non-native English speakers or those trying to bypass spam filters.

  - verifaction in the reply-to address.

- Generic Reference ID:
  - Reference ID: #SEC00987654321 - While legitimate emails often have reference IDs, in a phishing attempt, it's often a generic or randomly generated string to add a false sense of authenticity.

- How to handle real suspicious emails (Training takeaway):
  - DON'T click links or open attachments.
  - DON'T reply to the email.
  - Verify Independently: If you're concerned about your account, do not use any links or contact information provided in the suspicious email. Instead, go directly to the official website of the service (by typing the known URL into your browser) or use a phone number you know is legitimate (from their official website or a previous bill).
   - Report It: Most email clients and organizations have a way to report suspicious emails (e.g., a "Report Phishing" button).

    Delete It: Once reported (or if you can't report it), delete the email.
