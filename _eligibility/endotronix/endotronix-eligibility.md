---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a patient user, your participation in using the Service is for your sole, personal use.
    type: individual
  - text: If you are a clinical user, your participation in using the Service is for the sole purpose of fulfilling your job duties and is further governed by the terms of the subscription agreement, service agreement, or other agreement between the Company and your employer.
    type: business
  minimum_age:
    text: By using the Service, you represent and warrant that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: The Service is intended for your personal, noncommercial use in accordance with these Terms.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will provide us with proof of identity as we may reasonably request from time to time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Endotronix
provenance_date: '2026-11-09'
provider_name: Endotronix
provider_slug: endotronix
slug: endotronix-eligibility
source_date: '2026-11-09'
source_filename: endotronix-eligibility.yml
source_heading: Eligibility
source_page: https://endotronix.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Endotronix\naid: endotronix\nurl: https://endotronix.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a patient user, your participation in using the Service is for your sole, personal use.\n- type: business\n  text: If you are a clinical user, your participation in using the Service is for the sole purpose of fulfilling\n    your job duties and is further governed by the terms of the subscription agreement, service agreement, or other\n    agreement between the Company and your employer.\nrestricted_uses:\n\
  - summary: No commercial use\n  text: The Service is intended for your personal, noncommercial use in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You will provide us with proof of identity as we may reasonably request from time to time.\nminimum_age:\n  value: '18'\n  text: By using the Service, you represent and warrant that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/endotronix/eligibility/endotronix-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Endotronix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Medical Devices
- Digital Health
- Remote Patient Monitoring
- Cardiology
- Heart Failure
- Healthcare
- Connected Devices
---
