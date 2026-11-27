---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - BH
    - KW
    - OM
    - QA
    - SA
    - AE
    - TN
    - DZ
    - MA
    - EG
    - TR
    text: Our site is only for users in the Middle East (Bahrain, Kuwait, Oman, Qatar, Saudi Arabia, and the United Arab Emirates), Tunisia, Algeria, Morocco, Egypt, and Turkey.
  entity_types:
  - text: Our site is directed to people residing in the Middle East (Bahrain, Kuwait, Oman, Qatar, Saudi Arabia, and the United Arab Emirates), Tunisia, Algeria, Morocco, Egypt, and Turkey.
    type: individual
  - text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms that may apply to our site'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use restricted to Permitted Territory
    text: you hereby warrant and represent to us that you are located in a Permitted Territory.
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
name: Klaim
provenance_date: '2026-11-09'
provider_name: Klaim
provider_slug: klaim
slug: klaim-eligibility
source_date: '2026-11-09'
source_filename: klaim-eligibility.yml
source_heading: Eligibility
source_page: https://klaim.ai/terms/uae
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Klaim\naid: klaim\nurl: https://klaim.ai/terms/uae\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BH\n  - KW\n  - OM\n  - QA\n  - SA\n  - AE\n  - TN\n  - DZ\n  - MA\n  - EG\n  - TR\n  excluded: []\n  text: Our site is only for users in the Middle East (Bahrain, Kuwait, Oman, Qatar, Saudi Arabia, and the United\n    Arab Emirates), Tunisia, Algeria, Morocco, Egypt, and Turkey.\nentity_types:\n- type: individual\n  text: Our site is directed to people residing in the Middle East (Bahrain, Kuwait, Oman, Qatar, Saudi Arabia,\n    and the United Arab Emirates), Tunisia, Algeria, Morocco, Egypt, and Turkey.\n\
  - type: business\n  text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms\n    that may apply to our site'\nrestricted_uses:\n- summary: Use restricted to Permitted Territory\n  text: you hereby warrant and represent to us that you are located in a Permitted Territory.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/klaim/eligibility/klaim-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Klaim's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Healthcare
- Insurance
- Claims
- Invoice Financing
- Working Capital
- Receivables
- Embedded Finance
- Real Estate
- United Arab Emirates
---
