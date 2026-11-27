---
api_specs:
- filename: zoho-campaigns-email-api-collection.json
  format: json
  label: Zoho Campaigns Email API
  slug: zoho-campaigns-email-api
  spec_type: Postman
  url: https://artifacts.apis.io/zoho-campaigns/postman/zoho-campaigns-email-api-collection.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content
    text: You must not use Zoho Campaigns to promote, market, sell, conduct, or send any content listed as Prohibited Content
  - summary: Emergency services
    text: Zoho Campaigns is not designed for, and does not provide access to any emergency services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zoho Campaigns
provenance_date: '2026-11-10'
provider_name: Zoho Campaigns
provider_slug: zoho-campaigns
slug: zoho-campaigns-eligibility
source_date: '2026-11-10'
source_filename: zoho-campaigns-eligibility.yml
source_heading: Eligibility
source_page: https://www.zoho.com/campaigns/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zoho Campaigns\naid: zoho-campaigns\nurl: https://www.zoho.com/campaigns/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content\n  text: You must not use Zoho Campaigns to promote, market, sell, conduct, or send any content listed as Prohibited\n    Content\n- summary: Emergency services\n  text: Zoho Campaigns is not designed for, and does not provide access to any emergency services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zoho-campaigns/eligibility/zoho-campaigns-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Zoho Campaigns's own page on 2026-11-10.
synthetic: false
tags:
- Email Marketing
- Campaigns
- Mailing Lists
- Subscribers
- Email Templates
- A/B Testing
- Campaign Analytics
- Marketing Automation
- Transactional Email
- Webhook
---
