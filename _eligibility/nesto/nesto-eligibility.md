---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are over the age of 18.
    type: individual
  minimum_age:
    text: You represent and warrant that you are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Abusive or unlawful content or use
    text: use the Site or its content in any manner that is exploitive, obscene, harmful, threatening, abusive, harassing, hateful, defamatory
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
name: Nesto
provenance_date: '2026-11-10'
provider_name: Nesto
provider_slug: nesto
slug: nesto-eligibility
source_date: '2026-11-10'
source_filename: nesto-eligibility.yml
source_heading: Eligibility
source_page: https://www.nesto.ca/terms-of-services/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nesto\naid: nesto\nurl: https://www.nesto.ca/terms-of-services/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are over the age of 18.\nrestricted_uses:\n- summary: Abusive or unlawful content or use\n  text: use the Site or its content in any manner that is exploitive, obscene, harmful, threatening, abusive, harassing,\n    hateful, defamatory\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you\
  \ are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/nesto/eligibility/nesto-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Nesto's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Canada
- Mortgage
- Lending
- PropTech
- Financial Services
- Underwriting
- Loan Servicing
---
