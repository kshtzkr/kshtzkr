# Kshitiz Sinha

**Forward Deployed Engineer — I sit with the business, find where the work actually breaks, and ship the software that fixes it.**

India · Open to remote · Forward Deployed Engineer / Solutions Engineer / Senior Ruby on Rails Engineer

Most of my work starts as a business problem, not a ticket: a sales team losing leads in WhatsApp threads,
operators rebuilding the same itinerary by hand every week, payroll worked out in a spreadsheet on the last
day of the month. I go find where the time and money are leaking, build the thing that closes the gap, put it
in front of the people doing the job, and stay on it until it holds up in production.

Currently the engineer behind [Earthly Group](https://github.com/earthlygroup)'s travel platform — a
customer-facing booking site and an internal CMS that operators run their day on. I own it end to end:
discovery with the people using it, application code, integrations, infrastructure, deploys, and on-call.
The parts that generalise beyond one company I extract and publish as open-source Rails engines.

- **Four published Rails engines on RubyGems, ~40,000 downloads** — problems I hit in the field, solved once, reusable by anyone
- **Domain integrations that carry real money and real messages** — payments, WhatsApp, Instagram, supplier booking APIs
- **Full ownership** — requirements through Terraform, CI/CD, migrations and production support
- Rails 8 · Hotwire · PostgreSQL · Azure · Terraform · Docker

---

## Problems I've solved in the field

**Operators were losing leads in personal WhatsApp threads.** Built a WhatsApp layer into the CMS — inbound
messages, session recovery, delivery retries, rate-limited bulk sends, message content encrypted at rest.
Extracted it as [`whatsapp_notifier`](https://github.com/kshtzkr/whatsapp_notifier); now used by other Rails
teams with a single install generator.

**Payroll and attendance ran on spreadsheets and trust.** Built geolocated attendance, leave, Indian statutory
payroll (PF, ESI, PT, TDS) with generated salary slips, appraisals and kudos. Shipped as
[`hr_lite`](https://github.com/kshtzkr/hr_lite), a mountable engine any Rails app can adopt instead of buying
a per-seat HRMS.

**Inbound demand was stuck in an inbox no one owned.** Wired Instagram DMs, comments and publishing into the
app over HMAC-verified Meta webhooks with OAuth token handling —
[`instagram_connect`](https://github.com/kshtzkr/instagram_connect).

**Sales couldn't find a contact fast enough to matter.** Contact management with Elasticsearch-backed search
and capped two-way Google Contacts sync — [`rails-contact`](https://github.com/kshtzkr/rails-contact).

**Quoting a trip took a day of copy-paste.** Built an itinerary builder, supplier rate search against
third-party travel APIs, flexible package pricing with rate grids and departures, quotations, invoicing and
generated PDF documents — the workflow the whole company now sells through.

**Access and accountability were informal.** Introduced role-based access control with deny-by-default
authorization, row-level ownership rules, and an audit trail on every staff mutation — so the business can
answer who changed what, and when.

---

## Open source

| Project | What it does | Version | Downloads |
| --- | --- | --- | --- |
| [instagram_connect](https://github.com/kshtzkr/instagram_connect) | Instagram DMs, comments and publishing for Rails over HMAC-verified Meta Graph webhooks, with OAuth token management | 0.3.18 | 14k+ |
| [hr_lite](https://github.com/kshtzkr/hr_lite) | Mountable HRMS engine: geolocated attendance, leave, holiday calendar, Indian payroll (PF/ESI/PT/TDS) with salary-slip PDFs, kudos, appraisals | 0.5.2 | 10k+ |
| [whatsapp_notifier](https://github.com/kshtzkr/whatsapp_notifier) | WhatsApp messaging for Rails in one generator: QR auth, multi-user sessions, mailer-style notifications, rate-limited bulk delivery with retries | 0.9.2 | 9k+ |
| [rails-contact](https://github.com/kshtzkr/rails-contact) | Contact CRUD with Elasticsearch-backed search and optional capped two-way Google Contacts sync | 0.1.17 | 7k+ |

Each ships as a mountable engine with its own migrations, generators, RSpec suite and MIT license — install
with one generator, no vendor lock-in.

---

## How I work

**Start with the person doing the job.** I watch the manual workaround before I design the replacement. The
feature that wins is usually smaller than the one that was asked for.

**Ship it into their hands early.** Software that hasn't been used by the operator it was built for is a
guess. I deploy, watch it get used, and fix what the first day exposes.

**Own the whole path.** Discovery, schema, code, third-party integration, infrastructure, deploy, monitoring,
and the support message at 9pm. Handoffs are where problems go to die.

**Automate the runbook away.** Migrations and backfills go into deploy hooks, not into a document someone has
to remember. Manual production steps are a bug.

**Keep it boring and small.** The least code that covers the real case, readable by whoever picks it up next.

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
- Organisation: [@earthlygroup](https://github.com/earthlygroup)
- Location: India (open to remote and to travelling to customer sites)
