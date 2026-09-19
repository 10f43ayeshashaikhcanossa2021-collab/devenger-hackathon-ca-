# GST Mitra AI – The CA in Your Pocket

> AI-Powered GST Compliance & ITC Recovery Platform for MSMEs

![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=next.js)
![Node.js](https://img.shields.io/badge/Node.js-Express-green?logo=node.js)
![Supabase](https://img.shields.io/badge/Supabase-PostgreSQL-3ECF8E?logo=supabase)
![Gemini AI](https://img.shields.io/badge/Google-Gemini_AI-blue?logo=google)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Overview

GST Mitra AI is an AI-powered GST compliance platform designed to help MSMEs, traders, retailers, and wholesalers simplify tax management. Instead of spending hours manually checking invoices, preparing ledgers, and reconciling GSTR-2B, users can upload their invoices and let AI automate the entire workflow.

The platform extracts invoice data using OCR, generates monthly ledgers, detects GST mismatches, identifies Input Tax Credit (ITC) losses, and provides actionable compliance insights through an intelligent GST assistant.

## The Problem

Millions of small businesses struggle with GST compliance because:

* Invoice verification is manual and time-consuming.
* GSTR-2B reconciliation requires repetitive work.
* Small GSTIN or HSN errors can block Input Tax Credit.
* Professional accounting services are expensive for many MSMEs.
* Compliance mistakes lead to financial losses and penalties.

## Our Solution

GST Mitra AI automates the complete GST workflow using Artificial Intelligence.

### Workflow

Invoice Upload

↓

AI OCR (Gemini Vision)

↓

Data Extraction

↓

Ledger Generation

↓

GSTR-2B Reconciliation

↓

ITC Analysis

↓

AI GST Assistant

↓

Reports & Insights

## Key Features

* AI-powered Invoice OCR (JPG, PNG, PDF)
* Automatic Ledger Generation (Excel & CSV)
* GSTR-2B Reconciliation
* GSTIN & HSN Mismatch Detection
* ITC Loss & Recovery Analysis
* Compliance Score
* Supplier Risk Analysis
* GST-specific AI Assistant
* Multilingual Support
* Downloadable PDF & Excel Reports

## Technology Stack

| Layer          | Technologies                             |
| -------------- | ---------------------------------------- |
| Frontend       | Next.js, Tailwind CSS, TypeScript        |
| Backend        | Node.js, Express.js                      |
| Database       | Supabase PostgreSQL                      |
| Authentication | Supabase Auth                            |
| Storage        | Supabase Storage                         |
| AI             | Google Gemini 2.5 Pro, Gemini Vision OCR |
| Reports        | ExcelJS, jsPDF                           |
| Deployment     | Vercel                                   |

## System Architecture

<AsyncImage query="clean AI system architecture diagram Next.js Node.js Supabase Gemini OCR dashboard" aspectRatio="16:9"/>

## Project Structure

```text
gst-mitra-ai/
├── frontend/
│   ├── app/
│   ├── components/
│   ├── lib/
│   └── public/
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── services/
│   ├── middleware/
│   └── config/
│
├── database/
├── docs/
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/gst-mitra-ai.git
cd gst-mitra-ai
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Environment Variables

Create a `.env` file.

```env
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
GEMINI_API_KEY=your_gemini_api_key
```

## Use Cases

* MSMEs
* Retail Stores
* Wholesalers
* Traders
* Small Businesses
* Accountants

## Why GST Mitra AI?

| Traditional Process   | GST Mitra AI          |
| --------------------- | --------------------- |
| Manual invoice entry  | AI OCR                |
| Separate bookkeeping  | Automatic ledger      |
| Manual reconciliation | Smart matching        |
| No recovery guidance  | ITC recovery insights |
| Multiple tools        | One unified platform  |

## Future Scope

* One-click GST filing
* WhatsApp invoice upload
* Mobile application
* Voice-based GST assistant
* ERP integration
* Predictive compliance alerts
* CA collaboration portal
* Business analytics dashboard

## Expected Impact

* Reduce GST compliance errors
* Save hours of manual work every month
* Recover blocked Input Tax Credit
* Improve financial accuracy
* Make AI-powered tax assistance accessible to MSMEs

## Team: synaptic surge

**GST Mitra AI**

*The CA in Your Pocket*

Built for Hackathons • Built for MSMEs • Built with AI
