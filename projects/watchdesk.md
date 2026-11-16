# WatchDesk

**Personal project · Computer vision, Python backends and native-to-web integration**

Started October 2026.

WatchDesk is my computer-vision project for account-based laptop monitoring. It combines a native Python/OpenCV agent, FastAPI and Django REST services, and a Next.js portal for activation, approved-person enrollment, monitoring settings and warning review.

## Purpose

Connect local laptop monitoring with an owner-controlled account and web portal, so enrollment, monitoring settings and warnings can be managed through a consistent workflow.

## Main components

| Component | Responsibility |
| --- | --- |
| Native Python/OpenCV agent | Camera-health telemetry, idle-resume face comparison, bounded local alarms and durable event queues |
| FastAPI and Django REST services | Account activation, authentication, account isolation, agent credentials, monitoring settings and warning workflows |
| Next.js portal | Activation, approved-person enrollment, monitoring configuration and warning review |

## Engineering highlights

- Verified-email login, account isolation, single-use activation and revocable credentials.
- Consent-based enrollment, encrypted templates and transient enrollment-image processing.
- Camera-health telemetry, recoverable event processing, notification cooldowns and bounded local alerts.
- Optional consent-controlled voice/SMS notifications.
- Windows agent packaging with PyInstaller.
- Backend delivery on AWS Ubuntu with NGINX/HTTPS, with Docker, GitHub Actions and Terraform used in the delivery workflow.

## What this project demonstrates

API and backend design, computer-vision integration, native application packaging, account and credential lifecycle handling, and coordination between an agent, backend services and a web portal.

## Implementation access

The implementation is maintained in a private repository. This public overview describes the project for portfolio discussions.

[Back to my GitHub profile](https://github.com/amisomnath) · [Connect on LinkedIn](https://www.linkedin.com/in/amisomnath/)
