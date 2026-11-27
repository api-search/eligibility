---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are at least the age of majority in your state or province of residence
    type: individual
  - text: If you are a wholesaler or retailer interested in purchasing items in bulk, please visit https://davidprotein.com/pages/wholesale
    type: business
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: null
  restricted_uses:
  - summary: Personal or household use only
    text: You represent and warrant that your purchases are for your own personal or household use and not for commercial resale or export.
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
name: David Protein
provenance_date: '2026-11-09'
provider_name: David Protein
provider_slug: david-protein
slug: david-protein-eligibility
source_date: '2026-11-09'
source_filename: david-protein-eligibility.yml
source_heading: Eligibility
source_page: https://davidprotein.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: David Protein\naid: david-protein\nurl: https://davidprotein.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are at least the age of majority in your state or province of residence\n- type: business\n  text: If you are a wholesaler or retailer interested in purchasing items in bulk, please visit https://davidprotein.com/pages/wholesale\nrestricted_uses:\n- summary: Personal or household use only\n  text: You represent and warrant that your purchases are for your own personal or household\
  \ use and not for commercial\n    resale or export.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/david-protein/eligibility/david-protein-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from David Protein's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- MCP
- Universal Commerce Protocol
- Commerce
- E-Commerce
- Shopping
- Catalog
- Checkout
- Nutrition
- Food and Beverage
- Consumer Packaged Goods
- Shopify
---
