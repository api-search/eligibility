---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Care Providers will only be permitted to render medical care to you if you are located in a state and jurisdiction in the United States of America in which such Care Providers are licensed to practice medicine.
  entity_types:
  - text: IF YOU ARE AN ENTITY, ORGANIZATION, OR COMPANY, THE INDIVIDUAL ACCEPTING THESE TERMS ON YOUR BEHALF REPRESENTS AND WARRANTS THAT THEY HAVE AUTHORITY TO BIND YOU
    type: business
  minimum_age:
    text: If you are under 18 years of age (or the age of legal majority where you live), you may use the Service only if you are at least 12 years old and under the supervision of a parent or legal guardian
    value: '18'
  restricted_uses:
  - summary: No emergency use
    text: The Service should not be used during a medical emergency. If you have a medical emergency, call 911 or proceed to your nearest Emergency Room immediately.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: When you register for an account, you will be required to provide us with information about yourself, so that we can verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Accolade
provenance_date: '2026-11-09'
provider_name: Accolade
provider_slug: accolade
slug: accolade-eligibility
source_date: '2026-11-09'
source_filename: accolade-eligibility.yml
source_heading: Eligibility
source_page: https://www.accolade.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Accolade\naid: accolade\nurl: https://www.accolade.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Care Providers will only be permitted to render medical care to you if you are located in a state and\n    jurisdiction in the United States of America in which such Care Providers are licensed to practice medicine.\nentity_types:\n- type: business\n  text: IF YOU ARE AN ENTITY, ORGANIZATION, OR COMPANY, THE INDIVIDUAL ACCEPTING THESE TERMS ON YOUR BEHALF REPRESENTS\n    AND WARRANTS THAT THEY HAVE AUTHORITY TO BIND YOU\nrestricted_uses:\n\
  - summary: No emergency use\n  text: The Service should not be used during a medical emergency. If you have a medical emergency, call 911 or\n    proceed to your nearest Emergency Room immediately.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: When you register for an account, you will be required to provide us with information about yourself, so\n    that we can verify your identity.\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age (or the age of legal majority where you live), you may use the Service\n    only if you are at least 12 years old and under the supervision of a parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/accolade/eligibility/accolade-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Accolade's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Benefits
- Care Navigation
- Virtual Care
- Employee Benefits
- Telehealth
- Digital Health
- Mental Health
---
