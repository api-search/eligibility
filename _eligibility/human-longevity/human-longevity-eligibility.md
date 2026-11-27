---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: All Clients over the age of 18 that have received healthcare at HLI are eligible to use the Client Portal.
    type: individual
  minimum_age:
    text: the Portal is not available for use by persons under 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: the Portal is not meant to be used in the case of an emergency.
  - summary: Only own health care
    text: all communication through the Portal will be in regard to your own health care needs and treatment.
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
name: Human Longevity
provenance_date: '2026-11-09'
provider_name: Human Longevity
provider_slug: human-longevity
slug: human-longevity-eligibility
source_date: '2026-11-09'
source_filename: human-longevity-eligibility.yml
source_heading: Eligibility
source_page: https://www.humanlongevity.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Human Longevity\naid: human-longevity\nurl: https://www.humanlongevity.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: All Clients over the age of 18 that have received healthcare at HLI are eligible to use the Client Portal.\nrestricted_uses:\n- summary: Not for emergencies\n  text: the Portal is not meant to be used in the case of an emergency.\n- summary: Only own health care\n  text: all communication through the Portal will be in regard to your own health care needs and treatment.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the Portal is not available for use by persons under 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/human-longevity/eligibility/human-longevity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Human Longevity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Genomics
- Precision Medicine
- Diagnostics
- Artificial Intelligence
- Longevity
- Life Sciences
- Medical Imaging
---
