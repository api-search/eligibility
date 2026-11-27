---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access and use this Site outside the United States you are responsible for complying with your local laws and regulations.
  entity_types:
  - text: By accessing or using the Site, and/or using a Service, (i) you agree to these Terms and (ii) you represent that you are at least 18 years old.
    type: individual
  minimum_age:
    text: you represent that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No resale or commercial exploitation
    text: No One Health Company Service may be reproduced, duplicated, copied, sold, resold, or otherwise exploited for any commercial purpose without the express written consent of One Health Company.
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
name: OneHealthCompany
provenance_date: '2026-11-10'
provider_name: OneHealthCompany
provider_slug: onehealthcompany
slug: onehealthcompany-eligibility
source_date: '2026-11-10'
source_filename: onehealthcompany-eligibility.yml
source_heading: Eligibility
source_page: https://fidocure.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OneHealthCompany\naid: onehealthcompany\nurl: https://fidocure.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access and use this Site outside the United States you are responsible for complying with your local\n    laws and regulations.\nentity_types:\n- type: individual\n  text: By accessing or using the Site, and/or using a Service, (i) you agree to these Terms and (ii) you represent\n    that you are at least 18 years old.\nrestricted_uses:\n- summary: No resale or commercial exploitation\n  text: No One Health Company Service may be reproduced,\
  \ duplicated, copied, sold, resold, or otherwise exploited\n    for any commercial purpose without the express written consent of One Health Company.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/onehealthcompany/eligibility/onehealthcompany-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from OneHealthCompany's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Veterinary
- Animal Health
- Healthcare
- Precision Medicine
- Oncology
- Genomics
- Artificial Intelligence
- Real-World Evidence
---
