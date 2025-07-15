# 🤖 AI Meeting Scheduler Automation

This project is an AI-powered Google Meeting Scheduler that automates the end-to-end process of reading emails, understanding the request, checking calendar availability, and scheduling meetings — all without manual effort.

---

## 🧠 How It Works

The automation is built using a no-code/low-code workflow platform (like n8n) and integrates several tools:

### 🔄 Workflow Overview:
1. **Gmail Trigger**  
   - Listens for incoming meeting request emails.

2. **Perplexity AI**  
   - Parses the email content to extract intent (who, when, what the meeting is about).

3. **Code Blocks**  
   - Handles custom logic to format and route data (e.g., availability check, formatting calendar events).

4. **Google Calendar (Availability)**  
   - Checks open time slots using the user's calendar.

5. **Conditional Logic**  
   - Branches the flow depending on whether a slot is available.

6. **Google Calendar (Create Event)**  
   - Creates a new meeting with appropriate details.

7. **Perplexity AI (Response Generator)**  
   - Generates a natural-language confirmation message.

8. **Gmail (Reply)**  
   - Sends a confirmation email back to the requester.

---

## 📦 Tools & APIs Used

| Tool / API        | Purpose                            |
|------------------|------------------------------------|
| Gmail API         | Read & send emails                 |
| Google Calendar API | Check & create calendar events    |
| Perplexity AI      | Understand natural language in emails |
| Custom Code Blocks | Logic for routing and formatting  |
| n8n / Zapier       | Visual workflow automation         |

---

## 🛠 Setup & Configuration

> This project assumes you're using n8n (or similar). Here's how to get started:

1. Connect Gmail and Google Calendar nodes using your Google account.
2. Set up Perplexity AI or other LLM service as a webhook or API key.
3. Copy and paste the workflow into your n8n instance.
4. Activate the Gmail trigger to start listening for emails.
5. Test the end-to-end flow with a sample meeting request.

---

## 📸 Screenshot of Workflow

![Workflow Diagram]([./workflow.png](https://github.com/ChaithuCE/AI-Meeting-Scheduler/blob/main/Workflow.png))



---

## ✅ Features

- Fully automated meeting scheduler
- Smart AI-based intent extraction
- Calendar-aware scheduling
- Human-like email replies
- Easy to customize and extend

---

## 🙋‍♂️ Author

**Chaitanya Nuthakki**  
Python | SQL | Power BI | Automation Enthusiast  
📧 marteen837@gmail.com

---

## 📄 License

This project is open-source. Feel free to use or modify under the MIT License.

