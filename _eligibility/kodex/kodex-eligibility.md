---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: registered users who are employed by or acting on behalf of a government agency or office, law enforcement entity
    type: government
  minimum_age:
    text: You must be over the age of 18 to register an account or use the Services.
    value: '18'
  restricted_uses:
  - summary: Use that violates law
    text: You are not eligible to use the Services if doing so would violate any law or regulation
  - summary: False or misleading submissions
    text: (iv) are false, inaccurate, fraudulent or misleading
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: other information about yourself and your employment affiliation necessary to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kodex
provenance_date: '2026-11-09'
provider_name: Kodex
provider_slug: kodex
slug: kodex-eligibility
source_date: '2026-11-09'
source_filename: kodex-eligibility.yml
source_heading: Eligibility
source_page: https://www.kodexglobal.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kodex\naid: kodex\nurl: https://www.kodexglobal.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: registered users who are employed by or acting on behalf of a government agency or office, law enforcement\n    entity\nrestricted_uses:\n- summary: Use that violates law\n  text: You are not eligible to use the Services if doing so would violate any law or regulation\n- summary: False or misleading submissions\n  text: (iv) are false, inaccurate, fraudulent or misleading\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: other information about yourself and your employment affiliation necessary to verify your identity.\nminimum_age:\n  value: '18'\n  text: You must be over the age of 18 to register an account or use the Services.\n"
source_yaml_url: https://artifacts.apis.io/kodex/eligibility/kodex-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Kodex's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Law Enforcement
- Compliance
- Legal
- Identity Verification
- Government
- Security
- Threat Intelligence
- Data Requests
- Trust and Safety
---
