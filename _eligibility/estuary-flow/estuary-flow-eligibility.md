---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website is based in the United States. We make no claims concerning whether the Content may be downloaded, viewed, or be appropriate for use outside of the United States.
  entity_types:
  - text: The Website is available only to individuals aged 13 years or older.
    type: individual
  - text: If you accept or agree to this Agreement on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to the Agreement
    type: business
  minimum_age:
    text: The Website is available only to individuals aged 13 years or older.
    value: '13'
  restricted_uses:
  - summary: No market research for competitors
    text: You will not access or use the Website to collect any market research for a competing business;
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
name: Estuary Flow
provenance_date: '2026-11-09'
provider_name: Estuary Flow
provider_slug: estuary-flow
slug: estuary-flow-eligibility
source_date: '2026-11-09'
source_filename: estuary-flow-eligibility.yml
source_heading: Eligibility
source_page: https://estuary.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Estuary Flow\naid: estuary-flow\nurl: https://estuary.dev/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website is based in the United States. We make no claims concerning whether the Content may be downloaded,\n    viewed, or be appropriate for use outside of the United States.\nentity_types:\n- type: individual\n  text: The Website is available only to individuals aged 13 years or older.\n- type: business\n  text: If you accept or agree to this Agreement on behalf of a company or other legal entity, you represent and\n    warrant that you have the authority to bind\
  \ that company or other legal entity to the Agreement\nrestricted_uses:\n- summary: No market research for competitors\n  text: You will not access or use the Website to collect any market research for a competing business;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Website is available only to individuals aged 13 years or older.\n"
source_yaml_url: https://artifacts.apis.io/estuary-flow/eligibility/estuary-flow-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Estuary Flow's own page on 2026-11-09.
synthetic: false
tags:
- Data
- Streaming
- Change Data Capture
- ETL
- ELT
- Real-Time
- Data Pipeline
- Connectors
- Lakehouse
---
