---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: are at least 18 years of age, and have the legal capacity to enter into these Terms of Use;
    type: individual
  - text: This Site is for use by Travel Agents and Agency Administrators.
    type: business
  minimum_age:
    text: are at least 18 years of age, and have the legal capacity to enter into these Terms of Use;
    value: '18'
  restricted_uses:
  - summary: Commercial use of the Website
    text: Use of the Website for any other purpose, including any commercial use or purpose, is expressly prohibited.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We may refuse your registration request at our sole discretion, for any reason
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Air Canada
provenance_date: '2026-11-09'
provider_name: Air Canada
provider_slug: air-canada
slug: air-canada-eligibility
source_date: '2026-11-09'
source_filename: air-canada-eligibility.yml
source_heading: Eligibility
source_page: https://www.aircanada.com/ca/en/aco/home/legal/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Air Canada\naid: air-canada\nurl: https://www.aircanada.com/ca/en/aco/home/legal/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: are at least 18 years of age, and have the legal capacity to enter into these Terms of Use;\n- type: business\n  text: This Site is for use by Travel Agents and Agency Administrators.\nrestricted_uses:\n- summary: Commercial use of the Website\n  text: Use of the Website for any other purpose, including any commercial use or purpose, is expressly prohibited.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: We may refuse your registration request at our sole discretion, for any reason\nminimum_age:\n  value: '18'\n  text: are at least 18 years of age, and have the legal capacity to enter into these Terms of Use;\n"
source_yaml_url: https://artifacts.apis.io/air-canada/eligibility/air-canada-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Air Canada's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Canada
- Aviation
- Airlines
- NDC
- Distribution
- Booking
- Loyalty
---
