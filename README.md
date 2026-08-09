# Kshitiz Sinha

**Senior Ruby on Rails Engineer — Bengaluru / India · Building and running production SaaS end to end**

I design, build, deploy and operate Rails systems on my own: application code, background jobs,
infrastructure, CI/CD and on-call. Currently building [Earthly Group](https://github.com/earthlygroup)'s
travel platform — a customer-facing booking site plus an internal CMS used daily by operators — and
extracting the reusable parts into open-source Rails engines.

- Published Rails engines and gems on RubyGems, **~40,000 total downloads**
- Rails 8 · Hotwire (Turbo + Stimulus) · Tailwind · PostgreSQL · Solid Queue / Solid Cache
- Azure Container Apps · Terraform (OpenTofu) · Docker · self-hosted Woodpecker CI/CD
- Payments, WhatsApp and Instagram messaging, PDF generation, Elasticsearch, RBAC and audit trails

---

## Open source

| Project | What it does | Version | Downloads |
| --- | --- | --- | --- |
| [hr_lite](https://github.com/kshtzkr/hr_lite) | Mountable HRMS engine for Rails: geolocated attendance, leave, holiday calendar, Indian payroll (PF/ESI/PT/TDS) with salary-slip PDFs, kudos, appraisals | 0.5.2 | 10k+ |
| [instagram_connect](https://github.com/kshtzkr/instagram_connect) | Instagram DMs, comments and publishing for Rails over HMAC-verified Meta Graph webhooks, with OAuth token management | 0.3.18 | 14k+ |
| [whatsapp_notifier](https://github.com/kshtzkr/whatsapp_notifier) | WhatsApp messaging for Rails in one generator: QR auth, multi-user sessions, mailer-style notifications, rate-limited bulk delivery with retries | 0.9.2 | 9k+ |
| [rails-contact](https://github.com/kshtzkr/rails-contact) | Contact CRUD engine with Elasticsearch-backed search and optional capped two-way Google Contacts sync | 0.1.17 | 7k+ |

Each ships as a mountable engine with its own migrations, generators, RSpec suite and MIT license, so a
host app installs it with one generator and no vendor lock-in.

---

## What I work on

**Product engineering.** Multi-tenant CMS with role-based access control, deny-by-default authorization,
and an audit trail on every staff mutation. Itinerary builder, quotations, invoicing, supplier rate search
and booking flows against third-party travel APIs.

**Messaging and integrations.** Production WhatsApp and Instagram pipelines: webhook verification, session
recovery, delivery retries, rate limiting, and encryption of message content at rest.

**Payments and compliance.** Cashfree payment gateway integration, KYC capture, invoice generation, and
PDF documents rendered server-side.

**Infrastructure and operations.** Azure Container Apps deployments driven by Terraform, self-hosted CI/CD,
zero-downtime migrations wired into deploy hooks rather than manual runbooks, log analytics and alerting.

**Performance and correctness.** Pagination and rate limiting as framework-level defaults, N+1 elimination,
database index audits, and a test suite kept green as a release gate.

---

## Technical skills

**Languages:** Ruby, JavaScript, TypeScript, SQL, HTML, CSS

**Frameworks:** Ruby on Rails 8, Hotwire (Turbo, Stimulus), RSpec, Sidekiq / Solid Queue, Tailwind CSS,
React Native (mobile), Node.js

**Data:** PostgreSQL, Redis, Elasticsearch, Active Record, database design and query optimisation

**Cloud and DevOps:** Microsoft Azure (Container Apps, Container Registry, VMs, Log Analytics), Terraform /
OpenTofu, Docker, GitHub Actions, Woodpecker CI, Google Cloud Platform, Linux administration

**Practices:** REST API design, webhook integrations, OAuth 2.0, HMAC request verification, RBAC,
audit logging, test-driven development, code review, Agile delivery

**Integrations:** Meta Graph API (Instagram, WhatsApp), Cashfree Payments, Google Contacts, OpenAI and
Azure OpenAI, MaxMind GeoIP

---

## Contact

- Email: kshtzkr@gmail.com
- Organisation: [@earthlygroup](https://github.com/earthlygroup)
- Location: India (open to remote)
