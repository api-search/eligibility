---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access the Services from outside the United States, you understand that your information may be transferred to and processed in jurisdictions where privacy laws may differ
  entity_types:
  - text: The Services are intended for individuals who are at least 18 years old.
    type: individual
  - text: If you are acting on behalf of an employer or organization, you represent that you are authorized to accept these Terms
    type: business
  minimum_age:
    text: The Services are intended for individuals who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Non-emergency use only
    text: The Services are intended for non-emergency use only.
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
name: Microhealth
provenance_date: '2026-11-10'
provider_name: Microhealth
provider_slug: microhealth
slug: microhealth-eligibility
source_date: '2026-11-10'
source_filename: microhealth-eligibility.yml
source_heading: Eligibility
source_page: https://microhealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Microhealth\naid: microhealth\nurl: https://microhealth.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access the Services from outside the United States, you understand that your information may be transferred\n    to and processed in jurisdictions where privacy laws may differ\nentity_types:\n- type: individual\n  text: The Services are intended for individuals who are at least 18 years old.\n- type: business\n  text: If you are acting on behalf of an employer or organization, you represent that you are authorized to accept\n    these Terms\nrestricted_uses:\n\
  - summary: Non-emergency use only\n  text: The Services are intended for non-emergency use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for individuals who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/microhealth/eligibility/microhealth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Microhealth's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Health
- Healthcare
- Digital Therapeutics
- Hemophilia
- Bleeding Disorders
- Sickle Cell Disease
- Patient Engagement
- Real-World Evidence
- Software as a Medical Device
---
