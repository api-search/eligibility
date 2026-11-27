---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We are currently only able to serve users in certain States ("States Where We Operate").
  entity_types:
  - text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    type: individual
  - text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful user content
    text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content (i) that violates any third-party right
  - summary: Harvesting other users' data
    text: use the Site to harvest, collect, gather or assemble information or data regarding other users, including e-mail addresses, without their consent
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
name: Script Health
provenance_date: '2026-11-10'
provider_name: Script Health
provider_slug: script-health
slug: script-health-eligibility
source_date: '2026-11-10'
source_filename: script-health-eligibility.yml
source_heading: Eligibility
source_page: https://scripted.co/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Script Health\naid: script-health\nurl: https://scripted.co/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We are currently only able to serve users in certain States (\"States Where We Operate\").\nentity_types:\n- type: individual\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\n- type: business\n  text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary: Unlawful or harmful user content\n  text: You agree\
  \ not to use the Site to collect, upload, transmit, display, or distribute any User Content (i)\n    that violates any third-party right\n- summary: Harvesting other users' data\n  text: use the Site to harvest, collect, gather or assemble information or data regarding other users, including\n    e-mail addresses, without their consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/script-health/eligibility/script-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Script Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- Telehealth
- Prescriptions
- Clinical Services
- Health
- Medical Billing
---
