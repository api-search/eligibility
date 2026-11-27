---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter a binding agreement, or use Cladwell under the direct involvement of a parent or legal guardian who accepts these Terms for you.
    type: individual
  - text: If you use the Services for a company or another organization, you represent that you have authority to accept these Terms for it.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter a binding agreement, or use Cladwell under the direct involvement of a parent or legal guardian who accepts these Terms for you. No one under 13 may use the Services.
    value: '18'
  restricted_uses:
  - summary: No medical or professional advice
    text: Cladwell does not provide medical, health, mental-health, legal, financial, employment, safety, identity, or body-assessment advice.
  - summary: Not facial recognition
    text: Color and photo analysis is not facial recognition or identity verification.
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
name: Cladwell
provenance_date: '2026-11-09'
provider_name: Cladwell
provider_slug: cladwell
slug: cladwell-eligibility
source_date: '2026-11-09'
source_filename: cladwell-eligibility.yml
source_heading: Eligibility
source_page: https://cladwell.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cladwell\naid: cladwell\nurl: https://cladwell.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter a binding agreement, or use Cladwell under the direct\n    involvement of a parent or legal guardian who accepts these Terms for you.\n- type: business\n  text: If you use the Services for a company or another organization, you represent that you have authority to\n    accept these Terms for it.\nrestricted_uses:\n- summary: No medical or professional advice\n  text:\
  \ Cladwell does not provide medical, health, mental-health, legal, financial, employment, safety, identity,\n    or body-assessment advice.\n- summary: Not facial recognition\n  text: Color and photo analysis is not facial recognition or identity verification.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter a binding agreement, or use Cladwell under the direct\n    involvement of a parent or legal guardian who accepts these Terms for you. No one under 13 may use the Services.\n"
source_yaml_url: https://artifacts.apis.io/cladwell/eligibility/cladwell-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cladwell's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fashion
- Wardrobe
- Sustainability
- Retail
- Consumer App
- AI Styling
---
