# ☁️ Power Automate Cloud Workflows

This folder showcases various **Power Automate Cloud** workflows I created and implemented in previous roles. These automations streamlined communications, improved feedback tracking, supported team operations, and enhanced overall workflow efficiency.

---

## 📋 Workflows Created

### 🎂 DC Birthday Leadership Teams Notification
- **Tools Used:** Power Automate Cloud, SharePoint, Excel, Teams
- Sends leadership daily updates on team member birthdays happening within a three-day window.

### 🎊 DC Work Anniversary Leadership Teams Notification
- **Tools Used:** Power Automate Cloud, SharePoint, Excel, Teams
- Notifies leadership of team members' upcoming work anniversaries within three days.

### 📢 DCS Rotation Support Channel Notification – Standard Extracts
- **Tools Used:** Power Automate Cloud, SharePoint, Excel, Teams
- Similar to the EM Support workflow, notifying standard rotation support.

### 📢 DCS Rotation Support Channel Notification – Custom Extracts
- **Tools Used:** Power Automate Cloud, SharePoint, Excel, Teams
- Tailored notifications for custom extract teams using the same solution approach.

### 📢 DC History Rotation Support Channel Notification
- **Tools Used:** Power Automate Cloud, SharePoint, Excel, Teams
- Posts weekly updates about historical support rotations with team tagging.

### 🔄 DC Scheduling Reschedule Rotation Team Notification
- **Tools Used:** Power Automate Cloud, SharePoint, Excel, Teams
- Sends a weekly Teams notification tagging the team members on reschedule rotation, based on a SharePoint Excel sheet.

### 📢 EM Support Channel Notification
- **Tools Used:** Power Automate Cloud, SharePoint, Excel, Teams
- Weekly posts to a Teams channel tagging support members and the channel itself, notifying them of current rotations.

### 🛠 DC TL Rotation Support Leadership Team Notification
- **Tools Used:** Power Automate Cloud, SharePoint, Excel, Teams
- Pulls the weekly rotation team leads from an Excel sheet stored in SharePoint and posts a tagged notification in a Teams group chat.

### 📝 DC Extract Scheduling Feedback
- **Tools Used:** Power Automate Cloud, SharePoint, Forms, Lists
- Transfers new Microsoft Form submissions to a SharePoint list for leadership review.

### 📩 DC Extract Scheduling Feedback In Review Email
- **Tools Used:** Power Automate Cloud, SharePoint, Lists, Outlook
- Sends an Outlook email to feedback submitter when the feedback status changes to "In Review" and a Reviewer is assigned.

### 📋 DC Suggestion Workflow
- **Tools Used:** Power Automate Cloud, SharePoint, Forms, Lists
- Transfers new Microsoft Form submissions to a SharePoint list for leadership review.

### 📩 DC Suggestion Box In Review Email
- **Tools Used:** Power Automate Cloud, SharePoint, Lists, Outlook
- Sends an Outlook email to the suggestion submitter when the suggestion status changes to "In Review" and a Reviewer is assigned.

### 📋 DC Partners Page Suggestion Workflow
- **Tools Used:** Power Automate Cloud, SharePoint, Forms, Lists
- Transfers new Microsoft Form submissions to a SharePoint list for leadership review.

### ✉️ DC Availability Report to Scheduling SharePoint Library
- **Tools Used:** Power Automate Cloud, SharePoint, Excel, Outlook
- Automatically uploads weekly availability reports from email attachments to a SharePoint library for easy team access.

---

## ⚙️ Technical Challenges and Solutions

**Challenge:** Date formatting for accurate weekly comparisons.  
**Solution:** Ensured Excel sheet dates followed a strict format (`01/01/2025`).

**Challenge:** Tagging both individual members and Teams Channels simultaneously.  
**Solution:**
- Sent a Microsoft Graph HTTP Request via Power Automate.
- Used "List of Teams Channels" action to retrieve necessary Channel IDs.
- Built the HTTP request with proper JSON formatting for seamless tagging.

This solution was critical across multiple workflows, including:
- **DCS Rotation Support Channel Notification - Standard Extracts**
- **DCS Rotation Support Channel Notification - Custom Extracts**
- **DC History Rotation Support Channel Notification**

---


## 🧩 Workflows I Assisted On

### 📝 Team DCS Extract Review to Individual Lists
- Helped set up SharePoint list architecture within the leadership SharePoint site and tested automation that moved extract reviews from leadership list to individual team lists for visibility.

---
