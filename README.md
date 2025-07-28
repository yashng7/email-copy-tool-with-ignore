# 📧 Email Copy Tool

A simple web-based tool that helps you efficiently copy individual email addresses from a comma-separated list. No more tedious one-by-one email entry!

## 🎯 Why I Built This

I created this tool to solve a specific workflow problem I was facing with **HelpSpot ticketing system**. 

### The Problem
When working with support tickets in HelpSpot, I frequently needed to add multiple people to the CC field of tickets. However, HelpSpot's interface only allows you to add one email address at a time to the CC field. 

My typical workflow was:
1. Get a list of emails from a spreadsheet or document (like: `john@company.com, sarah@business.org, mike@startup.io`)
2. Copy the entire list
3. Go to HelpSpot ticket
4. Manually type or paste each email one by one into the CC field
5. Try to remember which emails I'd already added
6. Repeat this tedious process for every ticket that needed multiple CCs

This was incredibly time-consuming and error-prone, especially when dealing with 5-10+ email addresses per ticket.

### The Solution
Now with this tool, my workflow is:
1. Paste the comma-separated email list into the tool
2. Click "Process Emails" 
3. Go to HelpSpot and click "Copy" next to each email as I add them to the CC field
4. The tool tracks which emails I've copied (green checkmarks) so I never lose my place
5. No more manual typing, no more forgetting which emails I've added!

**What used to take 5-10 minutes of careful copying now takes 30 seconds of clicking buttons.**

## ✨ Features

- **Bulk Processing**: Paste comma-separated emails and process them all at once
- **Individual Copying**: Click to copy each email address individually  
- **Visual Feedback**: Copied emails turn green with checkmarks
- **Email Filtering**: Automatically ignore specific emails (like support addresses)
- **Progress Tracking**: See total, copied, remaining, and ignored counts
- **Duplicate Removal**: Automatically removes duplicate email addresses
- **Email Validation**: Only processes valid email formats
- **Bulk Actions**: Copy all remaining emails at once or reset progress

## 🚀 How to Use

### Step 1: Open the Tool
- Save the \`index.html\` file to your computer
- Double-click to open it in your web browser
- Bookmark the page for quick access

### Step 2: Configure (Optional)
- The "Email to ignore" field defaults to \`support@tangentia.com\`
- Change this to any email you want to automatically filter out
- Leave blank if you don't want to ignore any emails

### Step 3: Process Your Emails
1. **Paste your comma-separated emails** into the main text area
   \`\`\`
   john@company.com, sarah@business.org, mike@startup.io, lisa@agency.net
   \`\`\`
2. **Click "Process Emails"**
3. The tool will:
   - Validate all email addresses
   - Remove duplicates
   - Filter out ignored emails
   - Display each email with its own copy button

### Step 4: Copy Individual Emails
- **Click "Copy"** next to any email to copy it to your clipboard
- **Copied emails turn green** with a checkmark ✓
- **Paste the email** into HelpSpot CC field (or wherever you need it)
- **Track your progress** with the stats counter

### Step 5: Bulk Actions (Optional)
- **"Copy All Remaining"**: Copies all uncopied emails as a comma-separated list
- **"Reset All"**: Marks all emails as uncopied to start over

## 💡 Use Cases

### Primary Use Case: HelpSpot Ticketing
- **Adding multiple CCs to support tickets** (my original problem!)
- **Customer escalation workflows** where multiple stakeholders need to be included
- **Internal ticket routing** to various team members
- **Client communication** where multiple contacts need visibility

### Other Ticketing Systems
- Zendesk, Freshdesk, ServiceNow
- JIRA Service Management
- Any system that requires individual email entry

### General Email Management
- Adding contacts to Gmail, Outlook
- CRM data entry (Salesforce, HubSpot, etc.)
- Email marketing platforms (Mailchimp, Constant Contact)
- Survey invitations and event registrations

### Business Operations
- Client outreach campaigns
- Vendor communications
- Team notifications
- Partnership outreach

## 🎨 Interface Overview

\`\`\`
📧 Email Copy Tool
┌─────────────────────────────────────┐
│ Paste comma-separated emails:      │
│ ┌─────────────────────────────────┐ │
│ │ john@test.com, sarah@test.com   │ │
│ └─────────────────────────────────┘ │
│                                     │
│ Email to ignore:                    │
│ ┌─────────────────────────────────┐ │
│ │ support@tangentia.com           │ │
│ └─────────────────────────────────┘ │
│                                     │
│ [Process Emails]                    │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │ john@test.com        [Copy]     │ │
│ │ ✓ sarah@test.com     [Copied]   │ │
│ └─────────────────────────────────┘ │
│                                     │
│ Total: 2 | Copied: 1 | Remaining: 1│
│ [Copy All Remaining] [Reset All]    │
└─────────────────────────────────────┘
\`\`\`

## ⌨️ Keyboard Shortcuts

- **Ctrl+Enter** (or **Cmd+Enter** on Mac): Process emails
- **Tab**: Navigate between input fields
- **Enter**: Click focused button

## 🔧 Technical Details

- **No Installation Required**: Just open the HTML file in any modern browser
- **No Internet Required**: Works completely offline
- **Browser Compatibility**: Works in Chrome, Firefox, Safari, Edge
- **Privacy Focused**: All processing happens locally, no data sent anywhere
- **Lightweight**: Single HTML file under 10KB

## 📱 Mobile Support

The tool works on mobile browsers, though it's optimized for desktop use where you're more likely to be doing bulk email operations in ticketing systems.

## 🤝 Contributing

This is a simple personal productivity tool built to solve a specific HelpSpot workflow problem. Feel free to modify the code for your own needs:

- Change the default ignore email
- Modify the styling/colors
- Add additional features
- Customize for your specific ticketing system workflow

## 📄 License

Free to use and modify for personal or commercial purposes.

---

**Built with ❤️ to solve the frustrating problem of adding multiple CCs to HelpSpot tickets one email at a time.**
\`\`\`
