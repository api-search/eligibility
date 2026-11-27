---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Azura may, at any time and in its sole discretion, restrict, suspend or terminate your access to the Services if it determines that you are located in a Restricted Jurisdiction.
  entity_types:
  - text: You are (i) at least eighteen (18) years old; (ii) of legal age to form a binding contract
    type: individual
  - text: you represent and warrant that you have all right and authority necessary to act on behalf of such entity
    type: business
  minimum_age:
    text: You are (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Restricted Jurisdictions
    text: not a resident of, organized under the laws of, or located in a jurisdiction in which the offer, sale, or use of the Services would violate applicable law
  - summary: OFAC sanctions
    text: Neither you nor any of the foregoing person(s) will use the Services in violation of any applicable export control or sanctions law(s)
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
name: Azura
provenance_date: '2026-11-09'
provider_name: Azura
provider_slug: azura
slug: azura-eligibility
source_date: '2026-11-09'
source_filename: azura-eligibility.yml
source_heading: Eligibility
source_page: https://azura.xyz/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Azura\naid: azura\nurl: https://azura.xyz/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Azura may, at any time and in its sole discretion, restrict, suspend or terminate your access to the Services\n    if it determines that you are located in a Restricted Jurisdiction.\nentity_types:\n- type: individual\n  text: You are (i) at least eighteen (18) years old; (ii) of legal age to form a binding contract\n- type: business\n  text: you represent and warrant that you have all right and authority necessary to act on behalf of such entity\nrestricted_uses:\n- summary:\
  \ Restricted Jurisdictions\n  text: not a resident of, organized under the laws of, or located in a jurisdiction in which the offer, sale, or\n    use of the Services would violate applicable law\n- summary: OFAC sanctions\n  text: Neither you nor any of the foregoing person(s) will use the Services in violation of any applicable export\n    control or sanctions law(s)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/azura/eligibility/azura-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Azura's own page on 2026-11-09.
synthetic: false
tags:
- Company
- DeFi
- Cryptocurrency
- Blockchain
- Trading
- Onchain
- Token Swap
- Cross-Chain
- Fintech
---
