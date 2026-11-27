---
api_specs:
- filename: metamask-token-api-openapi.yml
  format: yaml
  label: MetaMask Token API
  slug: metamask-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metamask/openapi/metamask-token-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not located in any country subject to a comprehensive sanctions program implemented by the United States.
  entity_types:
  - text: If you are entering into this Agreement for an entity, such as the company you work for, you represent to us that you have legal authority to bind that entity.
    type: business
  - text: As a blockchain native company, we may interact with and provide certain Offerings to DAOs.
    type: other
  minimum_age:
    text: If you are under the age of majority in your jurisdiction of residence, you may use the Site or Offerings only with the consent of or under the supervision of your parent or legal guardian.
    value: age of majority
  restricted_uses:
  - summary: Sanctioned users
    text: You may not use any Offering if you are the subject of U.S. sanctions or of sanctions consistent with U.S. law imposed by the governments of the country where you are using the Offering.
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
name: MetaMask
provenance_date: '2026-11-10'
provider_name: MetaMask
provider_slug: metamask
slug: metamask-eligibility
source_date: '2026-11-10'
source_filename: metamask-eligibility.yml
source_heading: Eligibility
source_page: https://metamask.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MetaMask\naid: metamask\nurl: https://metamask.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: not located in any country subject to a comprehensive sanctions program implemented by the United States.\nentity_types:\n- type: business\n  text: If you are entering into this Agreement for an entity, such as the company you work for, you represent to\n    us that you have legal authority to bind that entity.\n- type: other\n  text: As a blockchain native company, we may interact with and provide certain Offerings to DAOs.\nrestricted_uses:\n- summary:\
  \ Sanctioned users\n  text: You may not use any Offering if you are the subject of U.S. sanctions or of sanctions consistent with U.S.\n    law imposed by the governments of the country where you are using the Offering.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: If you are under the age of majority in your jurisdiction of residence, you may use the Site or Offerings\n    only with the consent of or under the supervision of your parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/metamask/eligibility/metamask-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from MetaMask's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Wallets
- Web3
- Developer Tools
---
