---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Site is offered and available to users who reside in the United States or any of its territories or possessions.
  entity_types:
  - text: By using this Site, you represent and warrant that you are of legal age to form a binding contract with DELFI
    type: individual
  minimum_age:
    text: you are of legal age to form a binding contract with DELFI
    value: null
  restricted_uses:
  - summary: Unlawful or disruptive use
    text: You may use the Site only for lawful purposes and in accordance with these Terms of Use.
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
name: Delfi Diagnostics
provenance_date: '2026-11-09'
provider_name: Delfi Diagnostics
provider_slug: delfi-diagnostics
slug: delfi-diagnostics-eligibility
source_date: '2026-11-09'
source_filename: delfi-diagnostics-eligibility.yml
source_heading: Eligibility
source_page: https://delfidiagnostics.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Delfi Diagnostics\naid: delfi-diagnostics\nurl: https://delfidiagnostics.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Site is offered and available to users who reside in the United States or any of its territories or\n    possessions.\nentity_types:\n- type: individual\n  text: By using this Site, you represent and warrant that you are of legal age to form a binding contract with\n    DELFI\nrestricted_uses:\n- summary: Unlawful or disruptive use\n  text: You may use the Site only for lawful purposes and in accordance with these Terms of Use.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract with DELFI\n"
source_yaml_url: https://artifacts.apis.io/delfi-diagnostics/eligibility/delfi-diagnostics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Delfi Diagnostics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Diagnostics
- Precision Oncology
- Liquid Biopsy
- Cancer Screening
- Genomics
- Machine Learning
- Healthcare
---
