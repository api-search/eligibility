---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Site, you confirm that you are at least 18 years old and possess the legal capacity and authority to enter into this agreement.
    type: individual
  - text: If you are accessing the Site on behalf of an organization — including as an automated agent acting for an operator — you represent that you have the authority to bind that organization or operator to these Terms
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old
    value: '18'
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
name: ACHIVX
provenance_date: '2026-11-09'
provider_name: ACHIVX
provider_slug: achivx-com
slug: achivx-com-eligibility
source_date: '2026-11-09'
source_filename: achivx-com-eligibility.yml
source_heading: Eligibility
source_page: https://achivx.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ACHIVX\naid: achivx-com\nurl: https://achivx.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Site, you confirm that you are at least 18 years old and possess the legal capacity and authority\n    to enter into this agreement.\n- type: business\n  text: If you are accessing the Site on behalf of an organization — including as an automated agent acting for\n    an operator — you represent that you have the authority to bind that organization or operator to these Terms\nrestricted_uses: []\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/achivx-com/eligibility/achivx-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from ACHIVX's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Blockchain
- Stablecoins
- Payments
- Open Source
- Community
---
