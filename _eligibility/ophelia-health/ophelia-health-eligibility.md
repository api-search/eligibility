---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Platform is limited exclusively to users located in states within the United States where the Platform is available. Services are not available to users located outside the United States.
  entity_types:
  - text: solely for your personal use
    type: individual
  minimum_age:
    text: you must be, and you represent and warrant that you are, 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: for your personal, non-commercial use only
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Ophelia Health, Medical Group, and your Provider may contact you by telephone, SMS text, mail, or e-mail to verify your information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ophelia Health
provenance_date: '2026-11-10'
provider_name: Ophelia Health
provider_slug: ophelia-health
slug: ophelia-health-eligibility
source_date: '2026-11-10'
source_filename: ophelia-health-eligibility.yml
source_heading: Eligibility
source_page: https://ophelia.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ophelia Health\naid: ophelia-health\nurl: https://ophelia.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Platform is limited exclusively to users located in states within the United States\n    where the Platform is available. Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: solely for your personal use\nrestricted_uses:\n- summary: No commercial use\n  text: for your personal, non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: Ophelia Health, Medical Group, and your Provider may contact you by telephone, SMS text, mail, or e-mail\n    to verify your information.\nminimum_age:\n  value: '18'\n  text: you must be, and you represent and warrant that you are, 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/ophelia-health/eligibility/ophelia-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Ophelia Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Opioid Use Disorder
- Addiction Treatment
- Mental Health
- Digital Health
- Medication-Assisted Treatment
---
