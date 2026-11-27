---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 years of age or older to use the Website and any services provided through the Website.
    type: individual
  minimum_age:
    text: You must be 18 years of age or older to use the Website and any services provided through the Website.
    value: '18'
  restricted_uses:
  - summary: No emergency use
    text: DO NOT USE OUR WEBSITE TO SEEK MEDICAL SERVICES FOR SOMEONE WHO IS UNCONSCIOUS, NOT BREATHING OR GASPING FOR AIR, HAVING CHEST PAIN, UNCONTROLLABLY BLEEDING, OR ANY OTHER SYMPTOMS THAT REQUIRE IMMEDIATE OR EMERGENT MEDICAL ATTENTION.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: You agree to provide us with whatever proof of identity we may request to verify your identity and/or eligibility for Medical Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DispatchHealth
provenance_date: '2026-11-09'
provider_name: DispatchHealth
provider_slug: dispatchhealth
slug: dispatchhealth-eligibility
source_date: '2026-11-09'
source_filename: dispatchhealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.dispatchhealth.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DispatchHealth\naid: dispatchhealth\nurl: https://www.dispatchhealth.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older to use the Website and any services provided through the Website.\nrestricted_uses:\n- summary: No emergency use\n  text: DO NOT USE OUR WEBSITE TO SEEK MEDICAL SERVICES FOR SOMEONE WHO IS UNCONSCIOUS, NOT BREATHING OR GASPING\n    FOR AIR, HAVING CHEST PAIN, UNCONTROLLABLY BLEEDING, OR ANY OTHER SYMPTOMS THAT REQUIRE IMMEDIATE OR EMERGENT\n    MEDICAL ATTENTION.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: You agree to provide us with whatever proof of identity we may request to verify your identity and/or eligibility\n    for Medical Services.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the Website and any services provided through the Website.\n"
source_yaml_url: https://artifacts.apis.io/dispatchhealth/eligibility/dispatchhealth-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from DispatchHealth's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Systems
- Hospital at Home
- Home Care
- Urgent Care
- Care Delivery
- Medical Services
- Telehealth
- Digital Health
---
