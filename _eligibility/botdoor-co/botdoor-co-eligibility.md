---
api_specs:
- filename: botdoor-co-openapi-generated.yml
  format: yaml
  label: Botdoor API
  slug: botdoor-co-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botdoor-co/openapi/_ae-authored/botdoor-co-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Botdoor for an organisation, you agree for that organisation.
    type: business
  minimum_age:
    text: You must be at least 16, and old enough to agree to these terms where you live.
    value: '16'
  restricted_uses:
  - summary: Network rules and automation
    text: break the rules of any network you post to, including its rules on automation and AI-generated content
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Sign-ups are by invitation, and features may change.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Botdoor
provenance_date: '2026-11-09'
provider_name: Botdoor
provider_slug: botdoor-co
slug: botdoor-co-eligibility
source_date: '2026-11-09'
source_filename: botdoor-co-eligibility.yml
source_heading: Eligibility
source_page: https://botdoor.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Botdoor\naid: botdoor-co\nurl: https://botdoor.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use Botdoor for an organisation, you agree for that organisation.\nrestricted_uses:\n- summary: Network rules and automation\n  text: break the rules of any network you post to, including its rules on automation and AI-generated content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Sign-ups are by invitation, and features may change.\nminimum_age:\n  value: '16'\n  text: You must be at least 16,\
  \ and old enough to agree to these terms where you live.\n"
source_yaml_url: https://artifacts.apis.io/botdoor-co/eligibility/botdoor-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Botdoor's own page on 2026-11-09.
synthetic: false
tags:
- Social Media
- Automation
- AI Bots
- Scheduling
- Marketing
---
