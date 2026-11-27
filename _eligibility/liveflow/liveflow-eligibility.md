---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Business User Any User that does not qualify as a Consumer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or rights-infringing use
    text: violate laws, regulations and/or these Terms; infringe any third-party rights
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
name: LiveFlow
provenance_date: '2026-11-09'
provider_name: LiveFlow
provider_slug: liveflow
slug: liveflow-eligibility
source_date: '2026-11-09'
source_filename: liveflow-eligibility.yml
source_heading: Eligibility
source_page: https://liveflow.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LiveFlow\naid: liveflow\nurl: https://liveflow.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Business User Any User that does not qualify as a Consumer.\nrestricted_uses:\n- summary: Unlawful or rights-infringing use\n  text: violate laws, regulations and/or these Terms; infringe any third-party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/liveflow/eligibility/liveflow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from LiveFlow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Financial Reporting
- FP&A
- Fintech
- Consolidation
- Forecasting
- Accounting Automation
- Spreadsheets
---
