# Next Journey: Application Pipeline Tracker

**Version:** 1.0.0  
**Description:** A full-stack, serverless application tracker designed to help job seekers manage their pipeline with a drag-and-drop Kanban interface and powerful analytics based on an immutable event log.

---

## ✨ Features

* **Drag & Drop Pipeline:** Quickly manage your applications by dragging them between tracking stages defined in the system.
* **Progress Visualization:** See where you are in your job search with a clear, visual board for every company you've contacted.
* **Flow & Success Metrics:** Automatically track how many applications succeed (or drop off) at each stage using a simple, graphical chart.
* **Reliable Data:** The system ensures your status updates are reliable and automatically backed up, so your data is always correct and secure.

---

## 🛠️ Technology Stack

| Tier | Component | Focus |
| :--- | :--- | :--- |
| Frontend | React, TypeScript, Tailwind CSS | Kanban UI and rapid, consistent styling. |
| Backend | Node.js (Lambda Runtime), Cognito | Decoupled, event-driven microservice pattern with secure user authentication. |
| Data Persistence | DynamoDB | High-availability NoSQL used for persistence and logging. |
| Deployment | Terraform, API Gateway, S3/CloudFront | Automated, version-controlled provisioning and API routing. |

---

## 📜 License

Next Journey is licensed under the [Apache License 2.0](LICENSE).
