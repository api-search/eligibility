---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Medical Groups have a network of United States based Providers who provide telehealth and clinical services.
  entity_types:
  - text: Individual users may create accounts to access the Platform and receive medical Services directly from the Medical Groups.
    type: individual
  - text: Organizations, companies, and/or businesses, including clinical practices and healthcare providers (“ Clinical Organizations “), may create accounts and license our Platform
    type: business
  minimum_age:
    text: You certify that you are 18 years old or older and have the legal capacity to enter into this binding agreement.
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: DO NOT USE THESE SERVICES FOR EMERGENCY MEDICAL OR MENTAL HEALTH NEEDS.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You certify that you are 18 years old or older and have the legal capacity to enter into this binding agreement.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Frontera
provenance_date: '2026-11-09'
provider_name: Frontera
provider_slug: frontera
slug: frontera-eligibility
source_date: '2026-11-09'
source_filename: frontera-eligibility.yml
source_heading: Eligibility
source_page: https://fronterahealth.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Frontera\naid: frontera\nurl: https://fronterahealth.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Medical Groups have a network of United States based Providers who provide telehealth and clinical services.\nentity_types:\n- type: individual\n  text: Individual users may create accounts to access the Platform and receive medical Services directly from the\n    Medical Groups.\n- type: business\n  text: Organizations, companies, and/or businesses, including clinical practices and healthcare providers (“ Clinical\n    Organizations “), may create\
  \ accounts and license our Platform\nrestricted_uses:\n- summary: Not for emergencies\n  text: DO NOT USE THESE SERVICES FOR EMERGENCY MEDICAL OR MENTAL HEALTH NEEDS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You certify that you are 18 years old or older and have the legal capacity to enter into this binding agreement.\nminimum_age:\n  value: '18'\n  text: You certify that you are 18 years old or older and have the legal capacity to enter into this binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/frontera/eligibility/frontera-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Frontera's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Behavioral Health
- Artificial Intelligence
- Clinical Documentation
- ABA Therapy
- Autism Care
- HIPAA
---
