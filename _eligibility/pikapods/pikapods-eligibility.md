---
api_specs:
- filename: pikapods-openapi-generated.yml
  format: yaml
  label: PikaPods API
  slug: pikapods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pikapods/openapi/_ae-authored/pikapods-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using PikaPods on behalf of an organization, you agree to these Terms on behalf of that organization.
    type: business
  - text: Business users in the EU with valid VAT numbers must provide these details during account setup to qualify for VAT exemptions.
    type: individual
  minimum_age:
    text: You must be at least 13 years old (in the United States, per COPPA) or 16 years old (in the European Union, per GDPR) to create an account
    value: 13 or 16
  restricted_uses:
  - summary: Unlawful, harmful or disruptive activity
    text: Using the Service for any unlawful, harmful, or disruptive activities. This includes spamming, phishing, or port scanning.
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
name: PikaPods
provenance_date: '2026-11-10'
provider_name: PikaPods
provider_slug: pikapods
slug: pikapods-eligibility
source_date: '2026-11-10'
source_filename: pikapods-eligibility.yml
source_heading: Eligibility
source_page: https://www.pikapods.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PikaPods\naid: pikapods\nurl: https://www.pikapods.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using PikaPods on behalf of an organization, you agree to these Terms on behalf of that organization.\n- type: individual\n  text: Business users in the EU with valid VAT numbers must provide these details during account setup to qualify\n    for VAT exemptions.\nrestricted_uses:\n- summary: Unlawful, harmful or disruptive activity\n  text: Using the Service for any unlawful, harmful, or disruptive activities. This includes\
  \ spamming, phishing,\n    or port scanning.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 13 or 16\n  text: You must be at least 13 years old (in the United States, per COPPA) or 16 years old (in the European Union,\n    per GDPR) to create an account\n"
source_yaml_url: https://artifacts.apis.io/pikapods/eligibility/pikapods-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from PikaPods's own page on 2026-11-10.
synthetic: false
tags:
- Company
- IoT
- Pet Tech
- Smart Devices
- API Platform
---
