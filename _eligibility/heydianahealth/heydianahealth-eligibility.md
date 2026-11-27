---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You live in the United States.
  entity_types:
  - text: You are at least 18 years old, or if You are less than 18 years old, Your parent or guardian has provided consent for You to use the Site.
    type: individual
  minimum_age:
    text: You are at least 18 years old, or if You are less than 18 years old, Your parent or guardian has provided consent for You to use the Site.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: The Site may be used only for lawful purposes.
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
name: Diana Health
provenance_date: '2026-11-09'
provider_name: Diana Health
provider_slug: heydianahealth
slug: heydianahealth-eligibility
source_date: '2026-11-09'
source_filename: heydianahealth-eligibility.yml
source_heading: Eligibility
source_page: https://heydianahealth.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diana Health\naid: heydianahealth\nurl: https://heydianahealth.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You live in the United States.\nentity_types:\n- type: individual\n  text: You are at least 18 years old, or if You are less than 18 years old, Your parent or guardian has provided\n    consent for You to use the Site.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: The Site may be used only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n \
  \ text: You are at least 18 years old, or if You are less than 18 years old, Your parent or guardian has provided\n    consent for You to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/heydianahealth/eligibility/heydianahealth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Diana Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Women's Health
- Digital Health
- Maternity
- Telehealth
- Health Services
- Norwest Venture Partners
---
