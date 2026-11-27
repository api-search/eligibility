---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity or person accessing the Service (“Customer” or “you”)
    type: individual
  - text: the entity or person accessing the Service (“Customer” or “you”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No deepfakes or digital replicas
    text: Models must not enable, power, or otherwise be used to generate digital replicas of people or characters appearing in the Licensed Dataset
  - summary: No re-identification
    text: Models must not be used to re-identify persons in the Licensed Dataset
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
name: Protege
provenance_date: '2026-11-10'
provider_name: Protege
provider_slug: protege
slug: protege-eligibility
source_date: '2026-11-10'
source_filename: protege-eligibility.yml
source_heading: Eligibility
source_page: https://withprotege.ai/media-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Protege\naid: protege\nurl: https://withprotege.ai/media-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the entity or person accessing the Service (“Customer” or “you”)\n- type: business\n  text: the entity or person accessing the Service (“Customer” or “you”)\nrestricted_uses:\n- summary: No deepfakes or digital replicas\n  text: Models must not enable, power, or otherwise be used to generate digital replicas of people or characters\n    appearing in the Licensed Dataset\n- summary: No re-identification\n  text:\
  \ Models must not be used to re-identify persons in the Licensed Dataset\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/protege/eligibility/protege-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Protege's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Data
- Training Data
- Datasets
- Data Marketplace
- Healthcare
---
