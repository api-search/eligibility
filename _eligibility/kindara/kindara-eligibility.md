---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Website, Wink by Kindara, the App, and the Products and Services are controlled and offered by Kindara from its facilities in the United States of America and are offered to residents of the United States and Canada.
  entity_types:
  - text: You represent and warrant that you are at least the age of majority in the jurisdiction where you are located (which is 18 years of age in most locations in the United States) and fully able, competent and authorized to enter into and be bound by these Terms.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least the age of majority in the jurisdiction where you are located (which is 18 years of age in most locations in the United States)
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: You are authorized to use the Products and Services for personal, non-commercial use only.
  - summary: Export compliance
    text: You agree to comply with all export laws and restrictions and regulations of the United States Department of Commerce
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
name: Kindara
provenance_date: '2026-11-09'
provider_name: Kindara
provider_slug: kindara
slug: kindara-eligibility
source_date: '2026-11-09'
source_filename: kindara-eligibility.yml
source_heading: Eligibility
source_page: https://www.kindara.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kindara\naid: kindara\nurl: https://www.kindara.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Website, Wink by Kindara, the App, and the Products and Services are controlled and offered by Kindara\n    from its facilities in the United States of America and are offered to residents of the United States and Canada.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least the age of majority in the jurisdiction where you are located\n    (which is 18 years of age in most locations in the United\
  \ States) and fully able, competent and authorized to\n    enter into and be bound by these Terms.\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: You are authorized to use the Products and Services for personal, non-commercial use only.\n- summary: Export compliance\n  text: You agree to comply with all export laws and restrictions and regulations of the United States Department\n    of Commerce\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least the age of majority in the jurisdiction where you are located\n    (which is 18 years of age in most locations in the United States)\n"
source_yaml_url: https://artifacts.apis.io/kindara/eligibility/kindara-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Kindara's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fertility
- Femtech
- Reproductive Health
- Women's Health
- Menstrual Cycle Tracking
- Health
- Mobile App
---
