---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: either in individual capacity as an independent consultant
    type: individual
  - text: as a duly authorised representative of a firm
    type: business
  minimum_age:
    text: a legal entity or an individual 18 years or older who can form legally binding contracts
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing content
    text: any unlawful, hateful, racially or ethnically offensive, threatening, libellous, defamatory, obscene, pornographic, or other material or content that would violate rights of publicity and/or privacy or that would violate any law;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Upon successful completion of the interview process, the Consultant will be admitted into the Company’s services and assigned a consultant level.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Scalable CFO
provenance_date: '2026-11-10'
provider_name: Scalable CFO
provider_slug: scalable-cfo
slug: scalable-cfo-eligibility
source_date: '2026-11-10'
source_filename: scalable-cfo-eligibility.yml
source_heading: Eligibility
source_page: https://www.thescalablecfo.com/terms_conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scalable CFO\naid: scalable-cfo\nurl: https://www.thescalablecfo.com/terms_conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: either in individual capacity as an independent consultant\n- type: business\n  text: as a duly authorised representative of a firm\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: any unlawful, hateful, racially or ethnically offensive, threatening, libellous, defamatory, obscene, pornographic,\n    or other material or content that would violate rights of publicity\
  \ and/or privacy or that would violate any\n    law;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Upon successful completion of the interview process, the Consultant will be admitted into the Company’s\n    services and assigned a consultant level.\nminimum_age:\n  value: '18'\n  text: a legal entity or an individual 18 years or older who can form legally binding contracts\n"
source_yaml_url: https://artifacts.apis.io/scalable-cfo/eligibility/scalable-cfo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Scalable CFO's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Fintech
- CFO
- Cash Flow
- Forecasting
- Accounting
- Small Business
- Marketplace
---
