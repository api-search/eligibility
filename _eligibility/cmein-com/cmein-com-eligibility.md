---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.
    value: '18'
  restricted_uses:
  - summary: Prohibited uses list
    text: 'You may not use the Service to: - Upload photos of, or generate images of, any real person without their consent.'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: CMeIn may require you to take a live selfie so we can confirm you are the person shown in your uploaded reference photos before generating images.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CMeIn
provenance_date: '2026-11-09'
provider_name: CMeIn
provider_slug: cmein-com
slug: cmein-com-eligibility
source_date: '2026-11-09'
source_filename: cmein-com-eligibility.yml
source_heading: Eligibility
source_page: https://cmein.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CMeIn\naid: cmein-com\nurl: https://cmein.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.\nrestricted_uses:\n- summary: Prohibited uses list\n  text: 'You may not use the Service to: - Upload photos of, or generate images of, any real person without their\n    consent.'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: CMeIn may require you to take a live selfie so we can confirm you are the\
  \ person shown in your uploaded\n    reference photos before generating images.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cmein-com/eligibility/cmein-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from CMeIn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Image Generation
- Photos
- Dating
- Headshots
- Consumer Apps
- MCP
---
