---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services presented on the Website may be subject to restrictions in certain countries or with regard to certain persons, in particular, some Services might not be accessible to French Users/Clients and will be identified as such.
  entity_types:
  - text: The Services provided by the Company are strictly intended for professional Clients.
    type: business
  - text: The Services are accessible to any legal entity acting through a natural person who has the legal capacity to enter into a contract in the name and on behalf of such legal entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited persons and jurisdictions
    text: if the User is a Prohibited Person, whether a Sanctioned Person or is established in a Prohibited Jurisdiction, it will not be authorized to use the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The use of the Services is subject to AML/CFT identification requirements.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Keyrock
provenance_date: '2026-11-09'
provider_name: Keyrock
provider_slug: keyrock
slug: keyrock-eligibility
source_date: '2026-11-09'
source_filename: keyrock-eligibility.yml
source_heading: Eligibility
source_page: https://keyrock.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Keyrock\naid: keyrock\nurl: https://keyrock.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services presented on the Website may be subject to restrictions in certain countries or with regard\n    to certain persons, in particular, some Services might not be accessible to French Users/Clients and will be\n    identified as such.\nentity_types:\n- type: business\n  text: The Services provided by the Company are strictly intended for professional Clients.\n- type: business\n  text: The Services are accessible to any legal entity acting through a natural\
  \ person who has the legal capacity\n    to enter into a contract in the name and on behalf of such legal entity.\nrestricted_uses:\n- summary: Prohibited persons and jurisdictions\n  text: if the User is a Prohibited Person, whether a Sanctioned Person or is established in a Prohibited Jurisdiction,\n    it will not be authorized to use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The use of the Services is subject to AML/CFT identification requirements.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/keyrock/eligibility/keyrock-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Keyrock's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Market Making
- Liquidity
- Digital Assets
- Cryptocurrency
- Trading
- OTC
- Options
- Market Data
- Financial Services
---
