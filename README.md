# Kshitiz Sinha

**I build open-source Rails engines: WhatsApp, Instagram, HR and payroll, contacts. Four gems on RubyGems, 80,000+ downloads.**

India · Open to remote · Forward Deployed Engineer / Solutions Engineer / Senior Ruby on Rails Engineer

Each gem started as a problem I had to solve in a production app: leads lost in personal WhatsApp threads,
payroll worked out in a spreadsheet on the last day of the month, an Instagram inbox nobody owned. I solved it
once, pulled it out of the app, and published it so the next Rails team can install it instead of rebuilding it.

- **Four mountable Rails engines, MIT licensed**, each with its own migrations, generators and RSpec suite
- **Integrations that carry real messages and real money**: Meta Graph API, WhatsApp, Google Contacts, Indian statutory payroll
- Rails 8 · Hotwire · PostgreSQL · Azure · Terraform · Docker

---

## Open source

| Project | What it does | Version | Downloads |
| --- | --- | --- | --- |
| [hr_lite](https://github.com/kshtzkr/hr_lite) | HRMS engine: geolocated attendance, leave, holiday calendar, Indian payroll (PF/ESI/PT/TDS) with salary-slip PDFs, kudos, appraisals | ![version](https://img.shields.io/gem/v/hr_lite) | ![downloads](https://img.shields.io/gem/dt/hr_lite) |
| [instagram_connect](https://github.com/kshtzkr/instagram_connect) | Instagram DMs, comments and publishing over HMAC-verified Meta Graph webhooks, with OAuth token management | ![version](https://img.shields.io/gem/v/instagram_connect) | ![downloads](https://img.shields.io/gem/dt/instagram_connect) |
| [rails-contact](https://github.com/kshtzkr/rails-contact) | Contact CRUD with Elasticsearch-backed search and optional capped two-way Google Contacts sync | ![version](https://img.shields.io/gem/v/rails-contact) | ![downloads](https://img.shields.io/gem/dt/rails-contact) |
| [whatsapp_notifier](https://github.com/kshtzkr/whatsapp_notifier) | WhatsApp messaging in one generator: QR auth, multi-user sessions, mailer-style notifications, rate-limited bulk delivery with retries | ![version](https://img.shields.io/gem/v/whatsapp_notifier) | ![downloads](https://img.shields.io/gem/dt/whatsapp_notifier) |

Install any of them with one generator. No vendor lock-in.

---

## Why each one exists

### [hr_lite](https://github.com/kshtzkr/hr_lite)

Payroll and attendance ran on spreadsheets and trust. `hr_lite` is a mountable engine with geolocated
attendance, leave, a holiday calendar, Indian statutory payroll (PF, ESI, PT, TDS) with generated salary
slips, appraisals and kudos. A Rails app can adopt it instead of buying a per-seat HRMS.

### [instagram_connect](https://github.com/kshtzkr/instagram_connect)

Inbound demand was stuck in an inbox no one owned. `instagram_connect` brings Instagram DMs, comments and
publishing into a Rails app over HMAC-verified Meta webhooks, and handles the OAuth tokens.

### [whatsapp_notifier](https://github.com/kshtzkr/whatsapp_notifier)

A sales team was losing leads in personal WhatsApp threads. `whatsapp_notifier` adds inbound messages, session
recovery, delivery retries and rate-limited bulk sends, with message content encrypted at rest. One install
generator sets it up.

### [rails-contact](https://github.com/kshtzkr/rails-contact)

Sales couldn't find a contact fast enough to matter. `rails-contact` is contact management with
Elasticsearch-backed search and capped two-way Google Contacts sync.

---

## How I build them

**Start with the person doing the job.** I watch the manual workaround before I design the replacement. The
feature that wins is usually smaller than the one that was asked for.

**Extract after it works, not before.** Every engine ran in production inside a real app first. What gets
published is the part that survived real use.

**One generator to install.** Migrations, routes and config come from the install generator, so nobody has to
follow a setup document.

**Keep it boring and small.** The least code that covers the real case, readable by whoever picks it up next.

Issues and pull requests are welcome on any of the four repos.

---

## Technical skills

**Languages:** Ruby, JavaScript, TypeScript, SQL, HTML, CSS

**Frameworks:** Ruby on Rails 8, Hotwire (Turbo, Stimulus), RSpec, Sidekiq / Solid Queue, Tailwind CSS,
Node.js, React Native

**Data:** PostgreSQL, Redis, Elasticsearch, Active Record, schema design, query optimisation

**Cloud and DevOps:** Microsoft Azure (Container Apps, Container Registry, VMs, Log Analytics), Terraform /
OpenTofu, Docker, GitHub Actions, Woodpecker CI, Google Cloud Platform, Linux

**Integration engineering:** REST API design, webhooks, OAuth 2.0, HMAC request verification, Meta Graph API
(Instagram, WhatsApp), Cashfree Payments, Google Contacts, OpenAI and Azure OpenAI, MaxMind GeoIP

**Engineering practice:** requirements discovery with non-technical users, RBAC and audit logging,
test-driven development, code review, zero-downtime migrations, incident response, Agile delivery

---

## Contact

- Email: kshtzkr@gmail.com
- Location: India (open to remote)
