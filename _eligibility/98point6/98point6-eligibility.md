---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Site is intended for use only by individuals within the United States.
  entity_types:
  - text: You must be at least 18 years of age (or the age of legal majority where you live) in order to use the Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age (or the age of legal majority where you live) in order to use the Site.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 98point6 may request proof of age at any point, and if 98point6 believes that a Minor is using the Site without adult supervision, it may block the Minor from using the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 98point6 Technologies
provenance_date: '2026-11-09'
provider_name: 98point6 Technologies
provider_slug: 98point6
slug: 98point6-eligibility
source_date: '2026-11-09'
source_filename: 98point6-eligibility.yml
source_heading: Eligibility
source_page: https://www.98point6.com/legal-and-privacy/#licenseagreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 98point6 Technologies\naid: 98point6\nurl: https://www.98point6.com/legal-and-privacy/#licenseagreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Site is intended for use only by individuals within the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age (or the age of legal majority where you live) in order to use the Site.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 98point6 may request proof of age at any point, and if 98point6 believes that a Minor is\
  \ using the Site\n    without adult supervision, it may block the Minor from using the Site.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of legal majority where you live) in order to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/98point6/eligibility/98point6-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from 98point6 Technologies's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Virtual Care
- Digital Health
- Electronic Health Records
- Clinical Decision Support
- Artificial Intelligence
- Software
---
