<h1 align="center">Kshitiz Sinha</h1>

<p align="center">
  <strong>Forward Deployed Engineer</strong><br>
  I sit with the business, find where the work actually breaks, and ship the software that fixes it.
</p>

<p align="center">
  <img alt="4 Rails engines published on RubyGems" src="https://img.shields.io/badge/Rails_engines-4_published-CC342D?style=for-the-badge&logo=rubygems&logoColor=white">
  <img alt="80,000+ RubyGems downloads" src="https://img.shields.io/badge/Downloads-80%2C000%2B-CC342D?style=for-the-badge">
  <img alt="Open to remote, based in India" src="https://img.shields.io/badge/India-Open_to_remote-2F363D?style=for-the-badge">
</p>

<p align="center">
  <a href="mailto:kshtzkr@gmail.com">Email</a> ·
  <a href="https://rubygems.org/profiles/kshtzkr">RubyGems</a> ·
  <a href="#open-source">Open source</a> ·
  <a href="#problems-ive-solved-in-the-field">Field work</a>
</p>

<p align="center">Forward Deployed Engineer / Solutions Engineer / Senior Ruby on Rails Engineer</p>

---

Most of my work starts as a business problem, not a ticket: a sales team losing leads in WhatsApp threads,
payroll worked out in a spreadsheet on the last day of the month. I go find where the time and money are leaking, build the thing that closes the gap, put it
in front of the people doing the job, and stay on it until it holds up in production.

I own what I build end to end: discovery with the people using it, application code, integrations,
infrastructure, deploys, and on-call.
The parts that generalise beyond one company I extract and publish as open-source Rails engines.

- **Four published Rails engines on RubyGems, 80,000+ downloads** — problems I hit in the field, solved once, reusable by anyone
- **Domain integrations that carry real money and real messages** — payments, WhatsApp, Instagram
- **Full ownership** — requirements through Terraform, CI/CD, migrations and production support
- Rails 8 · Hotwire · PostgreSQL · Azure · Terraform · Docker

---

## Open source

### [hr_lite](https://github.com/kshtzkr/hr_lite)

![hr_lite gem version](https://img.shields.io/gem/v/hr_lite?style=flat-square&color=CC342D) ![hr_lite total downloads](https://img.shields.io/gem/dt/hr_lite?style=flat-square&label=downloads) ![MIT license](https://img.shields.io/badge/license-MIT-2F363D?style=flat-square)

Mountable HRMS engine: geolocated attendance, leave, holiday calendar, Indian payroll (PF/ESI/PT/TDS) with salary-slip PDFs, kudos, appraisals.

```bash
bundle add hr_lite
bin/rails g hr_lite:install
```

### [instagram_connect](https://github.com/kshtzkr/instagram_connect)

![instagram_connect gem version](https://img.shields.io/gem/v/instagram_connect?style=flat-square&color=CC342D) ![instagram_connect total downloads](https://img.shields.io/gem/dt/instagram_connect?style=flat-square&label=downloads) ![MIT license](https://img.shields.io/badge/license-MIT-2F363D?style=flat-square)

Instagram DMs, comments and publishing for Rails over HMAC-verified Meta Graph webhooks, with OAuth token management.

```bash
bundle add instagram_connect
bin/rails g instagram_connect:install
```

### [rails-contact](https://github.com/kshtzkr/rails-contact)

![rails-contact gem version](https://img.shields.io/gem/v/rails-contact?style=flat-square&color=CC342D) ![rails-contact total downloads](https://img.shields.io/gem/dt/rails-contact?style=flat-square&label=downloads) ![MIT license](https://img.shields.io/badge/license-MIT-2F363D?style=flat-square)

Contact CRUD with Elasticsearch-backed search and optional capped two-way Google Contacts sync.

```bash
bundle add rails-contact
bin/rails g rails:contact:install
```

### [whatsapp_notifier](https://github.com/kshtzkr/whatsapp_notifier)

![whatsapp_notifier gem version](https://img.shields.io/gem/v/whatsapp_notifier?style=flat-square&color=CC342D) ![whatsapp_notifier total downloads](https://img.shields.io/gem/dt/whatsapp_notifier?style=flat-square&label=downloads) ![MIT license](https://img.shields.io/badge/license-MIT-2F363D?style=flat-square)

WhatsApp messaging for Rails in one generator: QR auth, multi-user sessions, mailer-style notifications, rate-limited bulk delivery with retries.

```bash
bundle add whatsapp_notifier
bin/rails g whatsapp_notifier:install
```

Each ships as a mountable engine with its own migrations, generators, RSpec suite and MIT license — install
with one generator, no vendor lock-in.

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

**Access and accountability were informal.** Introduced role-based access control with deny-by-default
authorization, row-level ownership rules, and an audit trail on every staff mutation — so the business can
answer who changed what, and when.

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

![Ruby](https://img.shields.io/badge/Ruby-2F363D?style=flat-square&logo=ruby&logoColor=white) ![Rails 8](https://img.shields.io/badge/Rails_8-2F363D?style=flat-square&logo=rubyonrails&logoColor=white) ![Hotwire](https://img.shields.io/badge/Hotwire-2F363D?style=flat-square&logo=hotwire&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-2F363D?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-2F363D?style=flat-square&logo=redis&logoColor=white) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-2F363D?style=flat-square&logo=elasticsearch&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-2F363D?style=flat-square&logo=typescript&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-2F363D?style=flat-square) ![Terraform](https://img.shields.io/badge/Terraform-2F363D?style=flat-square&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2F363D?style=flat-square&logo=docker&logoColor=white)

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
- RubyGems: [rubygems.org/profiles/kshtzkr](https://rubygems.org/profiles/kshtzkr)
- Location: India (open to remote and to travelling to customer sites)
