---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: CauseComp is a web-based compensation benchmarking tool for nonprofit organizations.
    type: nonprofit
  - text: You must be at least 18 years old and able to form a binding contract to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Use in violation of law
    text: Use the Service in violation of any applicable law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need to register with a valid email address to use the Service, including the free tier.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CauseComp
provenance_date: '2026-11-09'
provider_name: CauseComp
provider_slug: causecomp-org
slug: causecomp-org-eligibility
source_date: '2026-11-09'
source_filename: causecomp-org-eligibility.yml
source_heading: Eligibility
source_page: https://www.causecomp.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CauseComp\naid: causecomp-org\nurl: https://www.causecomp.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: nonprofit\n  text: CauseComp is a web-based compensation benchmarking tool for nonprofit organizations.\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to use the Service.\nrestricted_uses:\n- summary: Use in violation of law\n  text: Use the Service in violation of any applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need to register with\
  \ a valid email address to use the Service, including the free tier.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/causecomp-org/eligibility/causecomp-org-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from CauseComp's own page on 2026-11-09.
synthetic: false
tags:
- Non-Profit
- Compensation
- Benchmarks
- Data
- Transparency
---
