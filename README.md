
# Safe Space: Bridges to Connection

## Inspiration

Modern life is increasingly connected digitally, yet millions of people experience profound social isolation and social anxiety. For shy or anxious individuals, stepping into high-stakes social interactions, such as job interviews, networking events, or difficult conversations, can feel overwhelming.

I wanted to build a low-pressure, empathetic bridge: a secure, judgment-free space where users can practice being human, build confidence, and master interpersonal skills at their own pace.

## What It Does

**Safe Space: Bridges to Connection** is an interactive Chrome web application designed to help users gently overcome social anxiety through immersive, guided practice.

- **The Seated Sanctuary:** Users enter a cozy, calming virtual therapist's office or park setting where they can interact naturally through text or voice.
- **Hume AI Empathic Integration:** The application can both hear and see the user in real time, analyzing vocal prosody and facial micro-expressions to gauge stress, hesitation, or relief.
- **Interactive Roleplay & Deduction Panels:** Guided by an AI therapist, users practice realistic social scenarios, such as talking through social anxiety with characters like Maya or Leo. They can use the Deduction Panel to develop emotional intelligence and watch a persistent Session Garden bloom with every unlocked insight.

## How I Built It with Firebase AI Logic

### On-Device Privacy (Gemini Nano 4)

Sensitive reflections, real-time emotion telemetry, and personally identifiable information (PII) filtering run locally on-device inside Chrome through Firebase AI Logic. This creates a secure **Privacy Vault** designed to ensure that personal emotional data and session transcripts never leave the user's browser.

### Cloud Fallback & Adaptation (Firebase AI Logic)

When users complete sessions or require broader multi-character interactions, Firebase AI Logic leverages cloud intelligence to generate adaptive characters, branching dialogue trees, and personalized real-world missions.

### Supporting Firebase Products

I integrated several Firebase products to provide a secure and persistent experience:

- **Firebase Authentication:** Provides secure user authentication and session management.
- **Cloud Firestore:** Persists unlocked insights and Session Garden progress.
- **Firebase App Check:** Strengthens platform security and helps protect backend resources, using debug tokens during development.

## Challenges I Faced

Balancing real-time multimodal telemetry from Hume AI video and audio streams with local on-device LLM inference required careful thread management and asynchronous state handling.

I had to ensure that multiple AI processes could operate smoothly without introducing UI lag or disrupting the user's experience. Maintaining a serene, immersive environment while handling complex real-time processing was one of my biggest technical challenges.

## What I Learned

I learned how to design a hybrid AI application that combines local privacy with dynamic cloud reasoning.

This project demonstrated how on-device intelligence and cloud-based AI can work together to create more personalized, adaptive, and privacy-conscious experiences.

Most importantly, I learned that mental health and social skills tools can be both deeply empathetic and technically advanced, giving people a safe environment to practice, grow, and build meaningful connections at their own pace.
