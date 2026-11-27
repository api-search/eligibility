---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that our website or other services are appropriate, legal or available for use in other locations.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: Member may not use the Service in any way that violates applicable state, federal, or international laws, regulations or other government requirements.
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
name: Renew Financial
provenance_date: '2026-11-10'
provider_name: Renew Financial
provider_slug: renew-financial
slug: renew-financial-eligibility
source_date: '2026-11-10'
source_filename: renew-financial-eligibility.yml
source_heading: Eligibility
source_page: https://renewfinancial.com/terms-use-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Renew Financial\naid: renew-financial\nurl: https://renewfinancial.com/terms-use-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that our website or other services are appropriate, legal or available for use\n    in other locations.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: Member may not use the Service in any way that violates applicable state, federal, or international laws,\n    regulations or other government requirements.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/renew-financial/eligibility/renew-financial-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Renew Financial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Lending
- Consumer Finance
- PACE Financing
- Home Improvement
- Clean Energy
- Energy Efficiency
- Solar
- Real Estate
---
