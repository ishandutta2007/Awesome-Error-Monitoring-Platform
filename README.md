# Awesome-Error-Monitoring-Platform

## Top Error Monitoring Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Exception Tracking, Crash Reporting, Issue Grouping, Release Health, Session Replay & Developer-First Debugging*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Error Monitoring** (also called exception tracking or crash reporting). These tools automatically capture unhandled errors and exceptions, group them into actionable issues, provide stack traces and context, and help teams detect, triage, and fix problems across web, mobile, and backend applications.



**Examples** include Sentry, Rollbar, Bugsnag, Raygun, Honeybadger, Airbrake, LogRocket, Embrace, Instabug, Crashlytics, TrackJS, and GlitchTip (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project. Sentry itself offers a powerful self-hosted edition, and lightweight Sentry-compatible alternatives plus broader OpenTelemetry-based platforms make full data ownership practical for many teams.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Sentry](https://sentry.io/)**  

  Leading developer-first error tracking and performance monitoring platform with broad SDK support, issue grouping, release health, session replay, and tracing.



- **[Rollbar](https://rollbar.com/)**  

  Error monitoring focused on fast triage, intelligent grouping, and tight integration with deployment pipelines for teams that ship frequently.



- **[Bugsnag (SmartBear Insight Hub)](https://www.bugsnag.com/)**  

  Crash and error monitoring with particular strength in mobile (iOS, Android, React Native) and release stability scoring.



- **[Raygun](https://raygun.com/)**  

  Error tracking, crash reporting, and real user monitoring platform supporting web, mobile, and backend applications.



- **[Honeybadger](https://www.honeybadger.io/)**  

  Developer-friendly error tracking that also bundles uptime monitoring and cron checks, popular with smaller SaaS teams.



- **[Airbrake](https://airbrake.io/)**  

  Classic exception tracking service with strong language support and long-standing presence in the error monitoring space.



- **[LogRocket](https://logrocket.com/)**  

  Session replay and front-end monitoring platform that combines error tracking with visual reproduction of user sessions.



- **[Embrace](https://embrace.io/)**  

  Mobile-focused observability and crash reporting platform with high-fidelity session data and OpenTelemetry-based SDKs.



- **[Instabug](https://www.instabug.com/)**  

  Mobile crash reporting, bug reporting, and in-app feedback platform used by many iOS and Android teams.



- **[Firebase Crashlytics](https://firebase.google.com/products/crashlytics)**  

  Google’s widely adopted free and paid crash reporting solution tightly integrated with the Firebase ecosystem.



- **[TrackJS](https://trackjs.com/)**  

  JavaScript-focused error monitoring with strong emphasis on front-end reliability and actionable insights.



- **[GlitchTip (Cloud)](https://glitchtip.com/)**  

  Hosted version of the open-source GlitchTip platform — a lightweight, Sentry-compatible error tracker.



## Open-Source GitHub Projects

- **[Sentry (Self-Hosted)](https://github.com/getsentry/sentry)**  

  The open-source core of Sentry — a full-featured error tracking, performance monitoring, and session-replay platform that can be self-hosted.



- **[GlitchTip](https://gitlab.com/glitchtip/glitchtip)**  

  Lightweight, open-source, Sentry SDK-compatible error tracking system that is much easier to operate than full self-hosted Sentry.



- **[Highlight.io](https://github.com/highlight/highlight)**  

  Open-source observability platform combining error monitoring, session replay, logging, and tracing.



- **[SigNoz](https://github.com/SigNoz/signoz)**  

  Open-source, OpenTelemetry-native observability platform that includes error tracking alongside metrics, traces, and logs.



- **[Bugsink](https://github.com/)**  

  Minimalist, single-container, Sentry-compatible open-source error tracker designed for very low operational overhead.



- **[Errbit](https://github.com/errbit/errbit)**  

  Open-source error catcher that is API-compatible with Airbrake, popular in Ruby/Rails environments.



- **[OpenTelemetry + Collector pipelines](https://github.com/open-telemetry)**  

  Standards-based instrumentation and collection that can feed errors into any compatible backend (SigNoz, Jaeger, custom stores, etc.).



- **[Self-hosted session replay & RUM tools](https://github.com/)**  

  Open-source projects that capture front-end errors together with user session recordings.



- **[Custom exception aggregators and notifiers](https://github.com/)**  

  Lightweight libraries and services for capturing, grouping, and alerting on exceptions in specific languages or frameworks.



- **[Mobile crash reporters (open SDKs)](https://github.com/)**  

  Open-source Android/iOS crash and ANR reporting components that can send data to self-hosted backends.



### Additional Strong Open-Source Options

- Prometheus + Grafana alert rules combined with application logs for simpler error visibility.

- ELK/EFK or Loki stacks used as lightweight error aggregation layers.

- Language-specific open tools (e.g., for Python, Node, Go) that provide structured exception reporting.

- Status-page and uptime tools that complement pure error tracking.

- AI-assisted grouping and summarization experiments built on top of open error stores.



**Frameworks for building custom systems**: Instrument applications with official **Sentry SDKs** (or OpenTelemetry), point them at a self-hosted **Sentry**, **GlitchTip**, or **Bugsink** instance, and optionally layer **Highlight.io** or **SigNoz** for session replay and broader observability. This gives full ownership of error data while retaining modern issue workflows, source maps, and release tracking. Use standard SDKs wherever possible so switching backends remains simple.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Error monitoring often captures sensitive application data, stack traces, and sometimes user context. Self-hosted solutions provide excellent privacy and cost control but require proper security, scaling, backup, and maintenance.

- Always review data retention, PII handling, and compliance requirements (GDPR, etc.) before deploying any error tracking system in production.



---

**Made for developers, SREs, and engineering teams that want reliable, transparent error visibility.**

Let's make exception monitoring more open, affordable, and under your control.
