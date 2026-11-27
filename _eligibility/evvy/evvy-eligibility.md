---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Evvy does not warrant or guarantee that the Service or the Materials is or will be accessible and/or legally permissible outside of the United States or Canada.
  entity_types:
  - text: In order to use the Service, you must (a) be at least 18 years old;
    type: individual
  minimum_age:
    text: you must (a) be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: These Terms permit you to use the Service for your personal use only, and not for any commercial purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: This includes ID verification and any other required steps needed for our medical team to write and fulfill your prescription.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Evvy
provenance_date: '2026-11-09'
provider_name: Evvy
provider_slug: evvy
slug: evvy-eligibility
source_date: '2026-11-09'
source_filename: evvy-eligibility.yml
source_heading: Eligibility
source_page: https://www.evvy.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evvy\naid: evvy\nurl: https://www.evvy.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Evvy does not warrant or guarantee that the Service or the Materials is or will be accessible and/or legally\n    permissible outside of the United States or Canada.\nentity_types:\n- type: individual\n  text: In order to use the Service, you must (a) be at least 18 years old;\nrestricted_uses:\n- summary: Personal use only\n  text: These Terms permit you to use the Service for your personal use only, and not for any commercial purpose.\nverification:\n \
  \ kyc: true\n  kyb: null\n  approval_required: null\n  text: This includes ID verification and any other required steps needed for our medical team to write and fulfill\n    your prescription.\nminimum_age:\n  value: '18'\n  text: you must (a) be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/evvy/eligibility/evvy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Evvy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Women's Health
- Diagnostics
- Microbiome
- Testing
- Telehealth
- Consumer Health
- E-Commerce
---
