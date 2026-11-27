---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THIS SITE IS ONLY TO BE ACCESSED BY INDIVIDUALS EIGHTEEN (18) YEARS OR OLDER.
    type: individual
  minimum_age:
    text: THIS SITE IS ONLY TO BE ACCESSED BY INDIVIDUALS EIGHTEEN (18) YEARS OR OLDER.
    value: '18'
  restricted_uses:
  - summary: No medical advice
    text: This Site does not, and is not intended to, provide medical advice
  - summary: Research use only
    text: Information on this Site are not approved for any use outside of research, development, or in some cases, clinical trials.
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
name: Trace Neuroscience
provenance_date: '2026-11-10'
provider_name: Trace Neuroscience
provider_slug: trace-neuroscience
slug: trace-neuroscience-eligibility
source_date: '2026-11-10'
source_filename: trace-neuroscience-eligibility.yml
source_heading: Eligibility
source_page: https://www.traceneuro.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trace Neuroscience\naid: trace-neuroscience\nurl: https://www.traceneuro.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: THIS SITE IS ONLY TO BE ACCESSED BY INDIVIDUALS EIGHTEEN (18) YEARS OR OLDER.\nrestricted_uses:\n- summary: No medical advice\n  text: This Site does not, and is not intended to, provide medical advice\n- summary: Research use only\n  text: Information on this Site are not approved for any use outside of research, development, or in some cases,\n    clinical trials.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: THIS SITE IS ONLY TO BE ACCESSED BY INDIVIDUALS EIGHTEEN (18) YEARS OR OLDER.\n"
source_yaml_url: https://artifacts.apis.io/trace-neuroscience/eligibility/trace-neuroscience-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Trace Neuroscience's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Biotechnology
- Neuroscience
- ALS
- Therapeutics
- Clinical Trials
---
