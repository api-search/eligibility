---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms, or using the Services, on behalf of a company or other legal entity, you hereby represent and warrant that you have the authority to enter into these Terms on behalf of such entity.
    type: business
  - text: These Terms may apply to you individually, the business or other legal entity user you represent, or both.
    type: individual
  minimum_age:
    text: 'you represent and warrant that you: (i) are at least 18 years of age, or otherwise over the age of majority in the jurisdiction in which you reside'
    value: '18'
  restricted_uses:
  - summary: No AI use that exposes data to outputs or external providers
    text: use of Intrinio Data in any AI or machine learning system that generates outputs containing, reproducing, or enabling the reconstruction of Intrinio Data, where such outputs are visible to, or accessible by, end users, customers, or the public
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
name: Intrinio
provenance_date: '2026-11-09'
provider_name: Intrinio
provider_slug: intrinio
slug: intrinio-eligibility
source_date: '2026-11-09'
source_filename: intrinio-eligibility.yml
source_heading: Eligibility
source_page: https://about.intrinio.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Intrinio\naid: intrinio\nurl: https://about.intrinio.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms, or using the Services, on behalf of a company or other legal entity,\n    you hereby represent and warrant that you have the authority to enter into these Terms on behalf of such entity.\n- type: individual\n  text: These Terms may apply to you individually, the business or other legal entity user you represent, or both.\nrestricted_uses:\n- summary: No AI use that exposes data to outputs\
  \ or external providers\n  text: use of Intrinio Data in any AI or machine learning system that generates outputs containing, reproducing,\n    or enabling the reconstruction of Intrinio Data, where such outputs are visible to, or accessible by, end users,\n    customers, or the public\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'you represent and warrant that you: (i) are at least 18 years of age, or otherwise over the age of majority\n    in the jurisdiction in which you reside'\n"
source_yaml_url: https://artifacts.apis.io/intrinio/eligibility/intrinio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Intrinio's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Financial Data
- Market Data
- Stocks
- Options
- Fundamentals
- ETFs
- Real-Time Data
---
