# Nexx Trading Journal

## One-Liner

Nexx is an AI-powered trading assistant that helps traders prepare for the session, validate setups before execution, log trades with full context, and improve through analytics and behavioral coaching.

---

# Elevator Pitch

Trading success depends as much on process as it does on market calls.

Nexx is a full-stack trading platform that provides active traders with a single workspace for their entire workflow:

* Pre-market preparation
* Setup validation
* Trade execution tracking
* Performance analytics
* Behavioral coaching

Before the market opens, traders receive market context through a live Market Brief and Economic Calendar. Before execution, a Setup Validator scores opportunities using personal trade history and macro risk factors. After execution, traders can review detailed analytics, journal entries, screenshots, and AI-powered coaching insights.

Built with Next.js and Supabase, Nexxx is delivered as a Progressive Web App with a premium dark interface optimized for both desktop and mobile review sessions.

---

# Who It's For

### Day Traders & Swing Traders

Traders who want repeatable pre-trade routines and more disciplined execution.

### Process-Oriented Traders

Individuals who already journal but lack structured feedback loops and actionable insights.

### Crypto & Multi-Asset Traders

Traders who need R-multiple tracking, screenshot journaling, psychology notes, and session reviews.

### Spreadsheet Users

Traders looking to move beyond spreadsheets into a purpose-built trading workflow platform.

---

# Product Pillars

## 1. Prepare (Pre-Market)

The Dashboard provides traders with immediate context before the session begins.

Features include:

* Market Brief
* AI Insight
* Weekly performance snapshot
* Discipline score
* Economic Calendar integration

The dedicated Market Brief module expands on live market conditions, macro drivers, and USD economic events.

---

## 2. Validate (Pre-Trade)

The Setup Validator acts as the platform's decision engine.

Each setup is evaluated using:

* Rules-based validation logic
* Historical trade performance
* Economic calendar context
* Execution signals (Proceed, Caution, Avoid)
* Optional AI-generated explanations

The goal is to transform subjective decision-making into a structured pre-trade process.

---

## 3. Execute (During the Session)

The Trades module supports complete trade documentation.

Tracked data includes:

* Instrument
* Direction
* Entry & Exit
* R-Multiple
* USD P&L
* Psychology tags
* Mistake tags
* Journal notes
* Chart screenshots

The Trading Journal complements trade logging with timeline-based reflections, moods, and session notes.

Trade Analysis introduces chart replay functionality using Lightweight Charts and visual trade overlays.

---

## 4. Improve (Post-Session)

The review workflow is centered around performance improvement.

Features include:

* Analytics Dashboard
* Equity Curve Tracking
* Performance Calendar
* AI Coach
* Discipline Tracking
* Goal Management
* Mistake Analysis

The AI Coach identifies recurring behavioral patterns and helps traders improve consistency over time.

---

# Technical Overview

## Frontend

* Next.js 16 (App Router)
* React 19
* Tailwind CSS
* Unified Design System
* Progressive Web App (PWA)
* TradingView Integration
* 70+ React Components

### Key Features

* Client/server component architecture
* Mobile-first responsive design
* Installable PWA experience
* TradingView widgets and market watch integration

---

## Backend & Data

* Supabase Authentication
* PostgreSQL Database
* Supabase Storage
* Row Level Security (RLS)
* Versioned SQL Migrations

### Security

* User-scoped access control
* Hardened storage policies
* Protected API routes
* Session-aware middleware

---

# Integrations

| Service                 | Purpose                                      |
| ----------------------- | -------------------------------------------- |
| Financial Modeling Prep | Economic calendar, market data, index quotes |
| OpenAI                  | Setup explanations and AI insights           |
| Resend                  | Transactional email delivery                 |
| Binance / Yahoo Finance | Candle data for chart replay                 |
| TradingView             | Embedded charts and market watch             |

---

# Domain Logic

Business logic is isolated from UI components through dedicated engines:

* setupValidatorEngine
* executionSignalEngine
* marketBriefEngine
* economicCalendar
* personalPerformanceEngine
* analyticsInsights
* disciplineInsights
* tradeCalculations

This architecture keeps trading logic maintainable, testable, and reusable.

---

# Authentication & Access

Authentication is powered by Supabase with SSR session handling.

Features include:

* Email & Password Authentication
* Protected Routes
* Password Recovery
* 7-Day Pro Trial
* Tier-Based Access Control

Subscription tiers:

* Free
* Pro

---

# Deployment

### Hosting

* Vercel
* Edge Middleware
* Serverless API Routes

### Infrastructure

* Docker Multi-Stage Build
* Non-Root Production Container
* Environment-Based Configuration

All API keys remain server-side and are never exposed to the client.

---

# Project Maturity

| Area                      | Status             |
| ------------------------- | ------------------ |
| Core Trading Workflow     | Production-Grade   |
| Setup Validator           | Production-Grade   |
| Market Brief              | Production-Grade   |
| Analytics & AI Coach      | Production-Grade   |
| Authentication & Security | Production-Grade   |
| Payments                  | In Progress        |
| Legal & Compliance        | Partially Complete |

---

# Why This Project Is Interesting

### Full Product Ownership

Landing page, authentication, application shell, API layer, and database architecture designed and implemented as a single product.

### Real Trading Domain Complexity

Includes:

* Financial calculations
* Economic calendar integration
* AI quota management
* Chart replay functionality
* Behavioral analytics

### Modern React Architecture

* App Router
* Context Providers
* Lazy Loading
* Mobile-First UX

### Security-First Approach

* Row Level Security
* Protected Routes
* Server-Only Secrets
* Migration-Based Hardening

### Production-Oriented UX

* Progressive Web App
* Cohesive Design System
* Trader-Centric Workflow
* Mobile Optimization

---

# Repository Visibility

This repository is private.

Public documentation exists solely for portfolio and GitHub profile presentation purposes.

Source code, credentials, infrastructure configuration, and deployment secrets are not publicly available.

---

# Nexx Trading Journal

**Trade with structure. Validate before you execute. Improve after every session.**
