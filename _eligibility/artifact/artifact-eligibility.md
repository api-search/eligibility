---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This Agreement is void where prohibited by law, and the right to access the Service is revoked in such jurisdictions.
  entity_types:
  - text: The Service is available only to individuals who are at least 18 years old.
    type: individual
  minimum_age:
    text: The Service is available only to individuals who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Export and trade controls
    text: You agree not to import, export, re-export, or transfer, directly or indirectly, any part of the Service or any information provided on or through the Service except in full compliance with all United States, foreign and other applicable laws and regulations.
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
name: Artifact
provenance_date: '2026-11-09'
provider_name: Artifact
provider_slug: artifact
slug: artifact-eligibility
source_date: '2026-11-09'
source_filename: artifact-eligibility.yml
source_heading: Eligibility
source_page: https://www.heyartifact.com/termsofservice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Artifact\naid: artifact\nurl: https://www.heyartifact.com/termsofservice/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This Agreement is void where prohibited by law, and the right to access the Service is revoked in such jurisdictions.\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who are at least 18 years old.\nrestricted_uses:\n- summary: Export and trade controls\n  text: You agree not to import, export, re-export, or transfer, directly or indirectly, any part of the Service\n    or any information provided on or through the Service\
  \ except in full compliance with all United States, foreign\n    and other applicable laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is available only to individuals who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/artifact/eligibility/artifact-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Artifact's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Family Stories
- Audio
- Storytelling
- Interviews
- Memories
- Legacy
---
