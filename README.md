# Place-Verify

### AI-Powered Placement Information App

PlaceVerify is an Android app that helps students manage placement opportunities and understand placement notices using AI.

## Problem

Placement information is often scattered across WhatsApp groups, PDFs, and messages. Students may miss important details such as eligibility, deadlines, and job roles.

## Features

- 🔐 Student Login/Register
- 📢 Placement Updates
- 🔎 Search Placement Opportunities
- 📄 Upload Placement Notice
- 🤖 AI extracts:
  - Company
  - Job Role
  - Eligibility
  - Package
  - Deadline
- 📝 AI-generated summary of placement notices
- 🔖 Save important opportunities
- 🔔 Deadline notifications

## AI Feature

The app uses AI to analyze placement notices and automatically extract important information and generate a short summary.

### Example

**Input:** Placement PDF/Image

**AI Output:**
- Company: ABC Technologies
- Role: Software Engineer
- Eligibility: 7+ CGPA
- Package: 8 LPA
- Deadline: 15 Oct

## Tech Stack

- Kotlin
- Jetpack Compose
- Spring Boot
- MySQL
- REST API
- LLM API / AI Service

## Basic Architecture

Android App → Spring Boot Backend → MySQL  
                             ↓  
                           AI API

## Team

**2 Members**

- Rinku: Android + UI
- Arpit: Backend + AI

Both members contribute to testing and deployment.

## Goal

Build and publish a simple, useful placement assistant for college students.
