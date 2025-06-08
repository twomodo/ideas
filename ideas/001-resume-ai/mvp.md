# Minimum Viable Product (MVP)

> 🚀 Define the leanest version of the product that can be launched to test value and gather feedback.

## Core Assumptions

1. Users are willing to let AI help write their resume and cover letter.
2. A faster, personalized tool can outperform static templates in user satisfaction.
3. Integration with job descriptions improves relevance and conversion.

---

## MVP Goal

Let users generate a tailored resume and cover letter in under 10 minutes with minimal input, using a job description and simple background form.

---

## Key Features in MVP

| Feature                            | Description                                                                 |
|------------------------------------|-----------------------------------------------------------------------------|
| Quick Resume Builder UI            | Simple web form: name, title, experience, education, skills                 |
| Job Description Input              | Text input or copy-paste of job post to align resume and cover letter       |
| AI-Generated Resume Sections       | Bullet points for experience, summary, skills using AI                      |
| Cover Letter Generator             | One-click personalized cover letter based on resume and job post            |
| PDF Export                         | Clean ATS-compatible layout, downloadable without signup                    |

---

## Optional Stretch Features

| Feature                      | Reason to Consider Early                                       |
|------------------------------|----------------------------------------------------------------|
| AI Tone Selector             | Choose tone: professional, friendly, startup, academic        |
| Resume Score & Feedback      | ATS score estimate, keyword match, and improvement suggestions|
| Chrome Extension Alpha       | Grab job descriptions directly from LinkedIn/Indeed           |

---

## MVP Success Criteria

| Metric                         | Target           |
|--------------------------------|------------------|
| Resume completion rate         | 65%+             |
| Avg. time to completion        | Under 10 minutes |
| Cover letter generation usage  | 50%+             |
| User satisfaction (CSAT)       | 4.2/5+           |
| Waitlist/Signup conversion     | 8–10%+           |

---

## Constraints & Stack

- **Frontend**: React or Next.js (Vercel deploy)
- **Backend**: Serverless API (e.g. Vercel, Supabase, Firebase)
- **AI**: OpenAI API or open-source LLM via hosted inference
- **Storage**: LocalStorage (MVP), optional Supabase DB
- **Authentication**: Anonymous or email-free in MVP

---

## Why This MVP Works

✅ Fast time-to-value  
✅ No friction or signup block  
✅ Useful output even without user perfection  
✅ Collects feedback and usage data for prioritizing next steps

---

## Terminology

- **MVP (Minimum Viable Product)**: The simplest version of a product that can provide value to users.
- **CSAT (Customer Satisfaction)**: A metric measuring user satisfaction with a product or service.
- **Conversion Rate**: The percentage of users who take a desired action (e.g., completing resume creation).
- **Serverless**: A cloud computing model where the provider manages infrastructure.
- **Authentication**: The process of verifying a user's identity.
- **React**: A JavaScript library for building user interfaces.
- **Next.js**: A React framework for production-grade applications.
- **UI (User Interface)**: The visual elements through which users interact with software.
- **Stack**: The combination of technologies used to create a software solution.