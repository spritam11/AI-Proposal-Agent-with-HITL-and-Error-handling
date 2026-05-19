<h1 align="center">🚀 AI Proposal Agent with Human Approval & Error Handling</h1>

<p align="center">
AI-powered automation workflow for proposal generation, approval-based email delivery, and intelligent error monitoring.
</p>

---

# 📌 Problem

Businesses and agencies waste significant time manually:

- Creating proposal presentations
- Sending emails to leads
- Managing approval workflows
- Monitoring workflow failures
- Tracking automation errors

Manual proposal generation slows down lead response time and increases operational overhead.

---

# 💡 Solution

This AI-powered automation system automatically:

✅ Generates proposal content using AI  
✅ Creates presentation files dynamically  
✅ Stores generated assets in Google Drive  
✅ Updates Google Slides presentations  
✅ Sends approval request emails before client delivery  
✅ Waits for human approval/decline decision  
✅ Sends finalized proposal email to client  
✅ Detects workflow errors automatically  
✅ Alerts AI Automation Engineer instantly with node-level error details

---

# ⚙️ Tech Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow Automation |
| Groq Chat Model | AI Proposal Generation |
| Google Drive API | File Storage |
| Google Slides API | Dynamic PPT Generation |
| Gmail API | Email Delivery & Approval Workflow |
| Telegram Bot API | Error Alert System |

---

# 🧠 Key Features

## 🤖 AI Proposal Generation
Automatically generates proposal content using AI models.

---

## 📊 Dynamic PPT Generation
Creates and updates Google Slides presentations automatically.

---

## 👨‍💻 Human-in-the-Loop Approval System

Before sending the final email to the client:

- Approval request is sent
- Generated PPT is attached
- Human can:
  - ✅ Approve
  - ❌ Decline

Only after approval, the workflow sends the proposal to the client.

---

## 🚨 Intelligent Error Handling System

If any workflow node fails:

- AI Automation Engineer gets notified instantly
- Telegram alert is triggered
- Error details include:
  - Failed node name
  - Type of error
  - Workflow failure information

This improves reliability and debugging speed.

---

# 🔄 Workflow Architecture

```text
Lead Form Submission
        ↓
AI Proposal Generation
        ↓
JavaScript Processing
        ↓
Google Drive File Handling
        ↓
Google Slides PPT Generation
        ↓
Approval Request Email
        ↓
Human Approval / Decline
        ↓
Send Final Email to Client
```

---

# 🖼️ Workflow Screenshots

## Full Workflow

![Workflow](https://github.com/spritam11/AI-Proposal-Agent-with-HITL-and-Error-handling/blob/a6274e38380cfeb972a163a6b11334cd1abf07e8/IMG-20260517-WA0012.jpg)

---

## Human Approval System

![Approval](https://github.com/spritam11/AI-Proposal-Agent-with-HITL-and-Error-handling/blob/f732de49c745220ad7c13e70b61b45b859474bae/IMG-20260517-WA0011.jpg)

---

## Error Handling Workflow

![Error Handling](https://github.com/spritam11/AI-Proposal-Agent-with-HITL-and-Error-handling/blob/8e86aa7963f22b7ac3eb0c1bd60271c4da50552c/IMG-20260517-WA0013.jpg)

---

## Telegram Alert System

![Telegram Alerts](https://github.com/spritam11/AI-Proposal-Agent-with-HITL-and-Error-handling/blob/e65cb39345667eccf69fafad67dee998cb123e33/IMG-20260517-WA0010.jpg)

---

# 📬 Human Approval Flow

```text
Generated Proposal
        ↓
Approval Email Sent
        ↓
Human Reviews Proposal
        ↓
Approve / Decline Decision
        ↓
Final Client Delivery
```

---

# 🚨 Error Monitoring Flow

```text
Node Failure
        ↓
Capture Error Information
        ↓
Trigger Telegram Alert
        ↓
Send Error Details to Engineer
```

---

# 📈 Real-World Use Cases

- Agency Proposal Automation
- Client Onboarding Systems
- Sales Workflow Automation
- AI-Based Business Operations
- Lead Response Automation

---

# 🔥 Highlights

✅ Human-in-the-loop architecture  
✅ AI-generated proposals  
✅ Automated PPT creation  
✅ Node-level error monitoring  
✅ Approval-based email delivery  
✅ Production-oriented workflow design 

# 🎥 Full Workflow Demo / click on view raw

[Watch Full Workflow Demo](https://github.com/user-attachments/assets/7d8f47c2-a438-4335-899d-98b1af89ef77)

# 🎥 Error handling demo / click on view raw

[Watch Error handling Demo](https://github.com/spritam11/AI-Proposal-Agent-with-HITL-and-Error-handling/blob/da04cb22c17243ffbee68a570bd439a8edd353c4/lv_0_20260519214744.mp4)


# 🎯 Focus

Designed for scalable business automation workflows with reliability, approval control, and operational monitoring.
