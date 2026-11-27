---
api_specs:
- filename: amazap-com-basics-api-openapi.yml
  format: yaml
  label: Amazap Basics API
  slug: amazap-com-basics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazap-com/openapi/amazap-com-basics-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are located in, or ordinarily resident in, a country or region subject to comprehensive U.S. sanctions
  entity_types:
  - text: You must be at least 18 and able to form a binding contract.
    type: individual
  - text: If you're accepting for a company, you confirm you have authority to bind it, and "you" means that company.
    type: business
  minimum_age:
    text: You must be at least 18 and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Sanctioned or restricted parties
    text: if you (or anyone who owns or controls you) are on a U.S. sanctions or restricted-party list, such as OFAC's Specially Designated Nationals (SDN) list.
  - summary: Prohibited content and conduct
    text: create, share, or seek child sexual abuse material; distribute malware or attack, probe, or disrupt Amazap, Sellers, or anyone else
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
name: Amazap
provenance_date: '2026-11-09'
provider_name: Amazap
provider_slug: amazap-com
slug: amazap-com-eligibility
source_date: '2026-11-09'
source_filename: amazap-com-eligibility.yml
source_heading: Eligibility
source_page: https://amazap.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazap\naid: amazap-com\nurl: https://amazap.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are located in, or ordinarily resident in, a country or region subject\n    to comprehensive U.S. sanctions\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to form a binding contract.\n- type: business\n  text: If you're accepting for a company, you confirm you have authority to bind it, and \"you\" means that company.\nrestricted_uses:\n- summary: Sanctioned or restricted parties\n  text: if you (or anyone who owns\
  \ or controls you) are on a U.S. sanctions or restricted-party list, such as OFAC's\n    Specially Designated Nationals (SDN) list.\n- summary: Prohibited content and conduct\n  text: create, share, or seek child sexual abuse material; distribute malware or attack, probe, or disrupt Amazap,\n    Sellers, or anyone else\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/amazap-com/eligibility/amazap-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Amazap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Micropayments
- Lightning
- Marketplace
---
