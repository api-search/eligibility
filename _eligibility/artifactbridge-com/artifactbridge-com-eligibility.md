---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old and able to form a binding contract to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 16 years old and able to form a binding contract to use the Service.
    value: '16'
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
name: ArtifactBridge
provenance_date: '2026-11-09'
provider_name: ArtifactBridge
provider_slug: artifactbridge-com
slug: artifactbridge-com-eligibility
source_date: '2026-11-09'
source_filename: artifactbridge-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.artifactbridge.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ArtifactBridge\naid: artifactbridge-com\nurl: https://www.artifactbridge.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old and able to form a binding contract to use the Service.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old and able to form a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/artifactbridge-com/eligibility/artifactbridge-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from ArtifactBridge's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Collaboration
- Document Management
- Governance
- Agents
---
