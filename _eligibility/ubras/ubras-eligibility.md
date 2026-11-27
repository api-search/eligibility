---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Void where prohibited
    text: Any offer for any product or service made on this site is void where prohibited.
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
name: Ubras
provenance_date: '2026-11-10'
provider_name: Ubras
provider_slug: ubras
slug: ubras-eligibility
source_date: '2026-11-10'
source_filename: ubras-eligibility.yml
source_heading: Eligibility
source_page: https://ubras.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ubras\naid: ubras\nurl: https://ubras.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Void where prohibited\n  text: Any offer for any product or service made on this site is void where prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent\
  \ that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/ubras/eligibility/ubras-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ubras's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Retail
- E-Commerce
- Apparel
- Intimate Apparel
- Direct to Consumer
- Agentic Commerce
---
