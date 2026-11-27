---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age to create an Account and use the Services.
    value: '18'
  restricted_uses:
  - summary: Market manipulation and fraud
    text: Use the Services to engage in any form of market manipulation, insider trading, fraud, or other activity that violates applicable securities laws or financial regulations
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
name: Askria
provenance_date: '2026-11-09'
provider_name: Askria
provider_slug: askria
slug: askria-eligibility
source_date: '2026-11-09'
source_filename: askria-eligibility.yml
source_heading: Eligibility
source_page: https://askria.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Askria\naid: askria\nurl: https://askria.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you\n    have the authority to bind such entity to these Terms\nrestricted_uses:\n- summary: Market manipulation and fraud\n  text: Use the Services to engage in any form of market manipulation, insider trading, fraud, or other activity\n    that violates applicable securities laws or financial regulations\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to create an Account and use the Services.\n"
source_yaml_url: https://artifacts.apis.io/askria/eligibility/askria-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Askria's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Venture Capital
- Private Capital
- Due Diligence
- Deal Management
- Artificial Intelligence
- Investment
- Fintech
---
