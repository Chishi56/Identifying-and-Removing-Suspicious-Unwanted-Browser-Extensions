# Identifying-and-Removing-Suspicious-Unwanted-Browser-Extensions
## Objective
The objective of this task was to mitigate potentially harmful or unnecessary browser extensions and to learn more about specific extensions as well as research malicious extensions.

## Tools Used
- **Web Browser:** Microsoft Edge
- **Extensions:** Built-in/Add-on

---



## Steps Taken

### 1. Accessing Extensions Manager
Opened Microsoft Edge’s extension manager (`edge://extensions/`) to review installed extensions.

### 2. Reviewing Installed Extensions
Evaluated the following extensions for permissions, user reviews, and potential risks:

- **AdBlock**
- **McAfee® WebAdvisor**
- **Google Docs Offline**

### 3. Analyzing Permissions & Risks
Created a comparison table to document:

- **Permissions** (e.g., access to browsing history, data modification).
- **User Reviews** (noted lack of reviews for pre-installed extensions).
- **Safety Status** (identified tracking risks for AdBlock and McAfee).

### 4. Researching Malicious Extension Risks
Investigated how malicious extensions could:

- **Track user behavior** (AdBlock’s domain tracking).
- **Exfiltrate data** (McAfee’s browsing history access).
- **Harvest credentials** (no evidence found in installed extensions).
- Referenced real-world incidents (e.g., Cyberhaven supply-chain attack).

### 5. Decision on Removal
No extensions were removed because:

- **AdBlock:** Despite tracking concerns, its utility outweighed risks (opted for continued use with caution).
- **McAfee WebAdvisor:** Pre-installed tool with no active threats detected.
- **Google Docs Offline:** No risks identified.

### 6. Browser Restart & Performance Check
Restarted **Microsoft Edge** after review.

- **No performance changes** observed (minimal extensions installed).

---

## Installed Extensions Details

| Extensions | Description | Permissions | Reviews | Safety Status |
|----------|----------|----------|----------|----------|
| AdBlock    | Block pop-ups and intrusive ads across YouTube, Facebook, Twitch, and other websites   | - Read and change all your data on all websites <br> - Display notifications   | Some Users claimed it does not work however the issue was with the broswer which was edge version 130 and not the extension itself    | Keeps track of the domain name of sites you visit which could reveal a users interests, habits, and behavior if misused or security breach occurs. However, the company claims it is entirely anonymous and does not linked to a specific user/device if opt-in for the resource.    |
|  McAfee® WebAdvisor    | Designed to help users browse the web safely by protecting against malware, phishing attempts, and malicious downloads   | - Read your browsing history <br> - Block content on any page <br>  - Manage your downloads <br> - Communicate with cooperating native applications <br>   | No Official reviews found as it comes pre-installed on a PC   | Some potential risks e.g.Can reveal sensitive personal data and browsing behavior if misused i.e Read your Browsing History (permission).   |
| Google Docs Offline    | Edit, create, and view your documents, spreadsheets, and presentations — all without internet access   | No Special Permission Needed   | No Official reviews found since it comes pre-installed on a PC    | No such threat detected   |

&nbsp;

## Malicious Extensions Risks
- **User Tracking and Profiling** – Extensions with tracking capabilities can monitor an employee’s browsing habits, search history, and online activities. This data can be used for targeted phishing attacks or to build detailed profiles of individuals within the organization.
- **Corporate Espionage** – Extensions with keylogging capabilities can record every keystroke made by an employee. They can capture sensitive information, including emails, chat messages, and documents. This data can be used for industrial espionage, giving competitors access to trade secrets and strategic plans.
- **Data Theft** – Malicious extensions can access and exfiltrate sensitive information such as login credentials, financial information, and personal data. In an organization, this can lead to the exposure of confidential business information, intellectual property, and client data.
- **Credential Harvesting** – Some malicious extensions are designed to capture usernames and passwords as they are entered on websites. This can lead to unauthorized access to corporate systems, email accounts, and other critical resources. 
- Some Malicious Extension Incidents: [Cyberhaven Incident](https://www.darktrace.com/blog/cyberhaven-supply-chain-attack-exploiting-browser-extensions), [Nano Adblocker and Nano Defender](https://www.zdnet.com/article/google-removes-two-chrome-ad-blockers-caught-collecting-user-data/)

&nbsp;

## Ways to Mitigate the Risks of Malicious Browser Extensions
- **Browser Security Solutions** – Deploying robust browser security solutions can help detect and block malicious activities associated with browser extensions. These solutions can provide real-time risk scoring, monitoring, and alerting, helping to mitigate threats before they cause significant damage.
- **Regular Audits** – Regular audits of installed browser extensions across the organization can help identify and remove any that are unauthorized or potentially malicious. IT departments should stay informed about the latest threats and update their policies accordingly.
- **Employee Education** – Educating employees about the risks associated with browser extensions and providing guidelines on safe practices can help reduce the likelihood of malicious extensions being installed. This includes advising against installing extensions from untrusted sources and encouraging prompt reporting of any suspicious behavior.

---

## End Result
- **Awareness:** Learned to critically evaluate extension permissions and balance utility vs. privacy risks.  
- **Action:** Maintained current extensions but noted potential vulnerabilities for future monitoring.  
- **Documentation:** Detailed findings in this README for transparency.  

---


