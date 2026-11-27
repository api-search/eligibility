---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: This website is operated by Sano Genetics Limited, a company registered in England and Wales
  entity_types:
  - text: We act as an intermediary between Researchers who need data for an Activity, and individuals like you who supply the data for that Activity.
    type: individual
  minimum_age:
    text: You may only take part in an Activity if you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Domestic and private use only
    text: We only supply the testing kit for domestic and private use.
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
name: Sano
provenance_date: '2026-11-10'
provider_name: Sano
provider_slug: sano
slug: sano-eligibility
source_date: '2026-11-10'
source_filename: sano-eligibility.yml
source_heading: Eligibility
source_page: https://sanogenetics.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sano\naid: sano\nurl: https://sanogenetics.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: This website is operated by Sano Genetics Limited, a company registered in England and Wales\nentity_types:\n- type: individual\n  text: We act as an intermediary between Researchers who need data for an Activity, and individuals like you who\n    supply the data for that Activity.\nrestricted_uses:\n- summary: Domestic and private use only\n  text: We only supply the testing kit for domestic and private use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You may only take part in an Activity if you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/sano/eligibility/sano-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sano's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Precision Medicine
- Genetics
- Clinical Trials
- Healthcare
- Genomics
- Patient Recruitment
---
