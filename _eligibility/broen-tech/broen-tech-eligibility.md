---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The service is currently provided free of charge for individual use, with usage-based token billing for advanced ASMI features.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to create an account and use the service.
    value: '16'
  restricted_uses:
  - summary: Illegal content
    text: Upload, share, or generate content that is illegal under Norwegian, EU, UK, or US law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must verify your email address before accessing messaging and meeting features.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Broentech
provenance_date: '2026-11-09'
provider_name: Broentech
provider_slug: broen-tech
slug: broen-tech-eligibility
source_date: '2026-11-09'
source_filename: broen-tech-eligibility.yml
source_heading: Eligibility
source_page: https://broen.tech/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Broentech\naid: broen-tech\nurl: https://broen.tech/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The service is currently provided free of charge for individual use, with usage-based token billing for\n    advanced ASMI features.\nrestricted_uses:\n- summary: Illegal content\n  text: Upload, share, or generate content that is illegal under Norwegian, EU, UK, or US law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must verify your email address before accessing messaging and meeting features.\n\
  minimum_age:\n  value: '16'\n  text: You must be at least 16 years old to create an account and use the service.\n"
source_yaml_url: https://artifacts.apis.io/broen-tech/eligibility/broen-tech-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Broentech's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Software
- Consulting
- ESG
- Norway
- Company
---
