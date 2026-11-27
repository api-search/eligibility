---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These partnerships enable us to provide up to 200 million euros in funding for European businesses.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited user conduct
    text: 'In particular, the user is prohibited from: (i) disrupt access to or operation of the Website and the Application'
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Verifications (identification, verification of identity and knowledge of clients ("Know Your Customer")) relating to the fight against money laundering and terrorist financing.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Silvr
provenance_date: '2026-11-10'
provider_name: Silvr
provider_slug: silvr
slug: silvr-eligibility
source_date: '2026-11-10'
source_filename: silvr-eligibility.yml
source_heading: Eligibility
source_page: https://www.silvr.co/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Silvr\naid: silvr\nurl: https://www.silvr.co/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These partnerships enable us to provide up to 200 million euros in funding for European businesses.\nrestricted_uses:\n- summary: Prohibited user conduct\n  text: 'In particular, the user is prohibited from: (i) disrupt access to or operation of the Website and the Application'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Verifications (identification, verification of identity and knowledge of clients (\"\
  Know Your Customer\"))\n    relating to the fight against money laundering and terrorist financing.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/silvr/eligibility/silvr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Silvr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech Insurtech
- Lending
- Revenue-Based Financing
- Embedded Finance
- Working Capital
- Invoice Financing
- SME Finance
- France
- Acquired
---
