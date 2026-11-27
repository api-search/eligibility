---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you're using Aymo on behalf of an organization, you confirm you have authority to bind that organization, and "you" means that organization.
    type: other
  minimum_age:
    text: You must be at least 18 years old to use Aymo.
    value: '18'
  restricted_uses:
  - summary: No adult content
    text: Aymo is not for creating or distributing adult or sexually explicit content.
  - summary: No content involving minors
    text: Any content that sexualizes, exploits, or endangers a minor is strictly prohibited.
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
name: Pimjo
provenance_date: '2026-11-09'
provider_name: Pimjo
provider_slug: aymo
slug: aymo-eligibility
source_date: '2026-11-09'
source_filename: aymo-eligibility.yml
source_heading: Eligibility
source_page: https://aymo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pimjo\naid: aymo\nurl: https://aymo.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: If you're using Aymo on behalf of an organization, you confirm you have authority to bind that organization,\n    and \"you\" means that organization.\nrestricted_uses:\n- summary: No adult content\n  text: Aymo is not for creating or distributing adult or sexually explicit content.\n- summary: No content involving minors\n  text: Any content that sexualizes, exploits, or endangers a minor is strictly prohibited.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use Aymo.\n"
source_yaml_url: https://artifacts.apis.io/aymo/eligibility/aymo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pimjo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Platform
- Team Collaboration
- LLM
- Software-as-a-Service
---
