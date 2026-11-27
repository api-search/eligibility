---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the service on behalf of a company, agency, client, or other organization, you represent that you have authority to bind that organization to these terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the service.
    value: '18'
  restricted_uses:
  - summary: Regulated and legal compliance responsibility
    text: You are responsible for legal pages, cookie notices, privacy notices, consent requirements, accessibility, claims, licensing, regulated-industry requirements, and ongoing compliance.
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
name: 1ClickWebsite.ai
provenance_date: '2026-11-09'
provider_name: 1ClickWebsite.ai
provider_slug: 1clickwebsite-ai
slug: 1clickwebsite-ai-eligibility
source_date: '2026-11-09'
source_filename: 1clickwebsite-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.1clickwebsite.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1ClickWebsite.ai\naid: 1clickwebsite-ai\nurl: https://www.1clickwebsite.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the service on behalf of a company, agency, client, or other organization, you represent that\n    you have authority to bind that organization to these terms.\nrestricted_uses:\n- summary: Regulated and legal compliance responsibility\n  text: You are responsible for legal pages, cookie notices, privacy notices, consent requirements, accessibility,\n    claims, licensing, regulated-industry requirements,\
  \ and ongoing compliance.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the service.\n"
source_yaml_url: https://artifacts.apis.io/1clickwebsite-ai/eligibility/1clickwebsite-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from 1ClickWebsite.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SEO
- WordPress
- Agency
- Automation
---
