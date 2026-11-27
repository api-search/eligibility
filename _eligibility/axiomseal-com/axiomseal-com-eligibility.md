---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Highly sensitive data
    text: do not store highly sensitive data yet.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: on application in the dashboard (company, website, location, use case); we decide freely.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AxiomSeal
provenance_date: '2026-11-09'
provider_name: AxiomSeal
provider_slug: axiomseal-com
slug: axiomseal-com-eligibility
source_date: '2026-11-09'
source_filename: axiomseal-com-eligibility.yml
source_heading: Eligibility
source_page: https://axiomseal.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AxiomSeal\naid: axiomseal-com\nurl: https://axiomseal.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Highly sensitive data\n  text: do not store highly sensitive data yet.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: on application in the dashboard (company, website, location, use case); we decide freely.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/axiomseal-com/eligibility/axiomseal-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from AxiomSeal's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Data Integrity
- Swiss
- GDPR
---
