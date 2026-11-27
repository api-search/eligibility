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
  - summary: No eligibility decisions
    text: Do not use similarity results to make employment, housing, credit or other eligibility decisions.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The current service does not provide formal identity verification, background screening or guaranteed search coverage.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Facehunch
provenance_date: '2026-11-09'
provider_name: Facehunch
provider_slug: facehunch-com
slug: facehunch-com-eligibility
source_date: '2026-11-09'
source_filename: facehunch-com-eligibility.yml
source_heading: Eligibility
source_page: https://facehunch.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Facehunch\naid: facehunch-com\nurl: https://facehunch.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No eligibility decisions\n  text: Do not use similarity results to make employment, housing, credit or other eligibility decisions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The current service does not provide formal identity verification, background screening or guaranteed search\n    coverage.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/facehunch-com/eligibility/facehunch-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Facehunch's own page on 2026-11-09.
synthetic: false
tags:
- Face Recognition
- Reverse Image Search
- Privacy
- Security
- Artificial Intelligence
---
