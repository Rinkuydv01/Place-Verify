# PlaceVerify

### AI-Powered Placement Information App

PlaceVerify is an Android app that helps students manage placement opportunities and quickly understand placement notices using AI.

## Problem

Placement information is often scattered across WhatsApp groups, PDFs, and messages. Important details like eligibility, job role, package, and deadlines can easily be missed.

PlaceVerify brings this information into one simple app.

## Features

- 🔐 Student Login / Register
- 📢 View placement opportunities
- 🔎 Search placement opportunities
- 📄 Upload placement notices
- 🤖 AI-based placement notice analysis
- 📝 AI-generated summaries
- 🔖 Save placement opportunities
- 🔔 Deadline notifications

## AI Feature

The main AI feature is **Placement Notice Analysis**.

Users can upload a placement notice as an image or document. The AI analyzes it and extracts important information.

### Example

**Input:** Placement Notice

**AI Output:**

- Company: ABC Technologies
- Role: Software Engineer
- Eligibility: 7+ CGPA
- Package: 8 LPA
- Deadline: 15 October

The AI also generates a short summary of the notice.

## Technology Stack

### Android

- Kotlin
- Jetpack Compose
- Material 3
- Kotlin Coroutines

### Firebase

- Firebase Authentication
- Cloud Firestore
- Firebase Storage
- Firebase Cloud Messaging

### AI

- LLM API
- OCR / Document Text Extraction

## Architecture

```text
Android App
     |
     ├── Firebase Authentication
     |
     ├── Cloud Firestore
     |
     ├── Firebase Storage
     |
     └── AI API
            |
            ↓
    Extracted Information
            |
            ↓
        Android App
