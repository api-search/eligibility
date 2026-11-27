---
api_specs:
- filename: ostium-labs-prices-asyncapi.yml
  format: yaml
  label: Ostium Builder API
  slug: ostium-builder-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/ostium-labs/asyncapi/ostium-labs-prices-asyncapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - US
    - GB
    - PH
    served: []
    text: USE OF THE APP OR BOT FOR TRADING IS NOT PERMITTED BY PERSONS OR ENTITIES WHO RESIDE IN, ARE LOCATED IN, ARE INCORPORATED IN, HAVE A REGISTERED OFFICE IN, OR HAVE THEIR PRINCIPAL PLACE OF BUSINESS IN CERTAIN JURISDICTIONS, INCLUDING THE UNITED STATES OF AMERICA, THE UNITED KINGDOM, THE EUROPEAN UNION, THE PHILIPPINES, OR ANY OTHER RESTRICTED TERRITORY
  entity_types:
  - text: If you are entering into or accepting these Terms on behalf of a legal entity, you represent and warrant that you have the right, authority and capacity to bind such entity and its affiliates to these Terms.
    type: business
  minimum_age:
    text: The Services and Tools are intended only for users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties
    text: the subject of economic or trade sanctions administered or enforced by any governmental authority or otherwise designated on any list of prohibited or restricted parties
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
- GB
- PH
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ostium Labs
provenance_date: '2026-11-10'
provider_name: Ostium Labs
provider_slug: ostium-labs
slug: ostium-labs-eligibility
source_date: '2026-11-10'
source_filename: ostium-labs-eligibility.yml
source_heading: Eligibility
source_page: https://docs.ostium.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ostium Labs\naid: ostium-labs\nurl: https://docs.ostium.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - GB\n  - PH\n  text: USE OF THE APP OR BOT FOR TRADING IS NOT PERMITTED BY PERSONS OR ENTITIES WHO RESIDE IN, ARE LOCATED IN,\n    ARE INCORPORATED IN, HAVE A REGISTERED OFFICE IN, OR HAVE THEIR PRINCIPAL PLACE OF BUSINESS IN CERTAIN JURISDICTIONS,\n    INCLUDING THE UNITED STATES OF AMERICA, THE UNITED KINGDOM, THE EUROPEAN UNION, THE PHILIPPINES, OR ANY OTHER\n    RESTRICTED TERRITORY\nentity_types:\n- type: business\n  text: If you are entering into or\
  \ accepting these Terms on behalf of a legal entity, you represent and warrant\n    that you have the right, authority and capacity to bind such entity and its affiliates to these Terms.\nrestricted_uses:\n- summary: Sanctioned parties\n  text: the subject of economic or trade sanctions administered or enforced by any governmental authority or otherwise\n    designated on any list of prohibited or restricted parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services and Tools are intended only for users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/ostium-labs/eligibility/ostium-labs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ostium Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Perpetual Futures
- Decentralized Finance
- DeFi
- Trading
- Real World Assets
- Derivatives
- Arbitrum
- Blockchain
- Web3
- Market Data
- SDK
- Real-Time
---
