# 📡 Campaign Atlas

**Campaign Atlas** is an LLM-powered, multichannel campaign orchestration engine that delivers personalized messages across email, SMS, push notifications, in-app prompts, and web banners—customized in real-time based on user behavior.

Built for growth teams and engineers, it intelligently generates, routes, and observes marketing content through scalable infrastructure. Whether you're nudging free users to convert or re-engaging dormant ones, Campaign Atlas maps the optimal messaging journey at scale.

---

## ✨ Key Features

- 🤖 **LLM-Generated Messaging**  
  Generate personalized campaign content using GPT-4 based on user's profile, history, tone, and intent.

- 🧭 **Cross-Channel Routing**  
  Dynamically select the best communication channel (email, push, SMS, etc.) based on user behavior and engagement context.

- ⚙️ **Infrastructure-Ready**  
  Built with Docker + AWS for real-world deployment, with Redis caching and observability hooks.

- 📊 **Customizable Rules Engine**  
  Define when, where, and how messages should be triggered and customized.

- 🔍 **Observability & Tracing**  
  Includes structured logging and OpenTelemetry tracing for prompt flow monitoring.

---

## 🧱 Tech Stack

- **Backend**: Python (FastAPI)
- **LLM**: OpenAI GPT-4 API (pluggable with Claude, Gemini, etc.)
- **Routing & Caching**: Custom rules engine + Redis
- **Deployment**: Docker, AWS (EC2 or ECS), optional CI/CD
- **Monitoring**: OpenTelemetry + Logging system (e.g., CloudWatch, Jaeger)

---

> _“Navigating user journeys with AI precision.”_


## 🙇‍♀️ Project Structure
<img width="1066" alt="Screenshot 2025-06-23 at 22 25 27" src="https://github.com/user-attachments/assets/059e4521-d508-4dca-9419-0052e43f07df" />








