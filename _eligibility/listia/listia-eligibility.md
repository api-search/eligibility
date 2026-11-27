---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Service may be used only by persons 18 years of age or older.
    type: individual
  minimum_age:
    text: This Service may be used only by persons 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Fictitious or third-party account registration
    text: Registration of Accounts in a name other than the registrant's, fictitious or real is expressly prohibited.
  - summary: Listing items without intent to give away
    text: The posting or listing of items without the intention of giving them away is expressly prohibited and may constitute wire or mail fraud in violation of U.S. and state law.
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
name: Listia
provenance_date: '2026-11-09'
provider_name: Listia
provider_slug: listia
slug: listia-eligibility
source_date: '2026-11-09'
source_filename: listia-eligibility.yml
source_heading: Eligibility
source_page: https://www.listia.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Listia\naid: listia\nurl: https://www.listia.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Service may be used only by persons 18 years of age or older.\nrestricted_uses:\n- summary: Fictitious or third-party account registration\n  text: Registration of Accounts in a name other than the registrant's, fictitious or real is expressly prohibited.\n- summary: Listing items without intent to give away\n  text: The posting or listing of items without the intention of giving them away is expressly prohibited and may\n  \
  \  constitute wire or mail fraud in violation of U.S. and state law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Service may be used only by persons 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/listia/eligibility/listia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Listia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- E-Commerce
- Peer-to-Peer
- Auctions
- Reuse
- Secondhand
- Virtual Currency
- Consumer
- Mobile App
---
