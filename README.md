# Digital Legacy AI Chatbot

**Preserving Memories. Connecting Generations.**

Digital Legacy AI is a personalized artificial intelligence chatbot designed to preserve an individual's memories, personal values, experiences, and communication style. The project explores how AI can provide emotional continuity for authorized loved ones while maintaining privacy, consent, and ethical boundaries.
It also introduces a digital estate organization feature that helps individuals prepare important document information, financial records, trusted contacts, and practical instructions for their families.

## 🌐 Live Website - https://digitallegacyai.vercel.app/

## 📌 Project Overview

Digital Legacy AI adapts a pre-trained Large Language Model (LLM) using an individual's writings, personal memories, values, and optional voice samples.
The system aims to create a personalized digital representation that authorized loved ones can interact with after the individual's passing. It is designed to preserve meaningful memories and communication patterns while clearly communicating that the chatbot is an AI representation, not the actual person.
Beyond memory preservation, the project explores a digital estate support feature that allows users to organize information about:

- Wills and legal documents.
- Insurance policies and providers.
- Property records and important assets.
- Financial paperwork and known liabilities.
- Recurring bills and outstanding obligations.
- Lawyers, accountants, and trusted contacts.
- Personal instructions and family guidance.

Authorized family members or representatives can use the platform to locate shared information, review prepared instructions, and organize practical follow-up checklists.

## ✨ Key Features

### 1. Personalized AI Chatbot
- AI conversations based on personal memories and values.
- Personalized responses using a pre-trained LLM.
- Context-aware memory retrieval.
- Communication-style personalization.

### 2. Life & Memory Timeline
- Organizes personal memories chronologically.
- Categorizes memories by life phase and topic.
- Supports memory tagging and importance scoring.

### 3. Intelligent Memory Retrieval
- Uses Retrieval-Augmented Generation (RAG).
- Identifies relevant memories based on user input.
- Ranks memories using keyword matching, emotional tags, and importance scores.
- Retrieves relevant information to provide contextual responses.

### 4. Digital Estate Organization
- Organizes information about important legal and financial records.
- Stores document locations and trusted professional contacts.
- Provides practical checklists for authorized family members.
- Separates access to personal memories from sensitive estate information.

### 5. Consent & Access Management
- Configurable access permissions.
- Role-based access control.
- Conditional activation and expiry rules.
- Access revocation and privacy controls.

### 6. Safety & Ethical Protection
- Session duration limits.
- AI identity and reality-check reminders.
- Fail-safe responses when memory confidence is low.
- Adaptive response control.
- Professional mental health support pathways.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React | Frontend user interface |
| Node.js | Backend runtime |
| Express.js | REST API development |
| Prisma ORM | Database management |
| PostgreSQL | Relational database |
| JWT | Authentication and authorization |
| Large Language Models | Personalized AI conversations |
| RAG | Contextual memory retrieval |

## 🏗️ System Architecture

The proposed system consists of four main layers:

1. **Frontend Layer — React:** Provides the user interface, dashboards, memory timeline, chatbot, and management features.
2. **Backend Layer — Node.js & Express:** Handles API requests, authentication, user management, and application logic.
3. **AI Layer — LLM & RAG:** Processes user messages, retrieves relevant memories, and generates personalized responses.
4. **Consent & Security Layer:** Manages access permissions, activation conditions, expiry, and revocation.

## 🔐 Privacy, Safety & Ethical Considerations

Digital Legacy AI is designed around responsible AI principles:

- Personal information should only be processed with appropriate consent.
- Access to sensitive records should be restricted to authorized individuals.
- The chatbot must clearly identify itself as an AI representation.
- Users should be able to configure access permissions and expiry conditions.
- Sensitive legal and financial records require appropriate security controls.
- The system does not replace lawyers, financial advisers, executors, or mental health professionals.

## 📄 License

This project is developed for educational and academic purposes. All rights and usage permissions should be confirmed by the project authors before redistribution.
