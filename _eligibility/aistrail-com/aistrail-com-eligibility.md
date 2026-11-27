---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Accounts, API keys, paid plans and credit packs are for business use only. You may use them only for purposes related to your trade, business, craft or profession
    type: business
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons
    text: give access to the Service or the Data to a person who is named on a sanctions list of the UN, the EU, the UK or the U.S., or is owned or controlled by such a person.
  - summary: Unlawful or sanctions-breaching use
    text: use the Service or the Data for any unlawful purpose, including in breach of sanctions or export control rules;
  - summary: Foreign adversary access to US station data
    text: sell, license or otherwise make available Data from receiving stations in the U.S. to a foreign adversary country, or to an entity it controls
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign up with an email address and a password at app.aistrail.com/signup and must confirm your email address before you can create API keys or buy a paid plan.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AIS Trail
provenance_date: '2026-11-09'
provider_name: AIS Trail
provider_slug: aistrail-com
slug: aistrail-com-eligibility
source_date: '2026-11-09'
source_filename: aistrail-com-eligibility.yml
source_heading: Eligibility
source_page: https://aistrail.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIS Trail\naid: aistrail-com\nurl: https://aistrail.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Accounts, API keys, paid plans and credit packs are for business use only. You may use them only for purposes\n    related to your trade, business, craft or profession\nrestricted_uses:\n- summary: Sanctioned persons\n  text: give access to the Service or the Data to a person who is named on a sanctions list of the UN, the EU, the\n    UK or the U.S., or is owned or controlled by such a person.\n- summary: Unlawful or\
  \ sanctions-breaching use\n  text: use the Service or the Data for any unlawful purpose, including in breach of sanctions or export control\n    rules;\n- summary: Foreign adversary access to US station data\n  text: sell, license or otherwise make available Data from receiving stations in the U.S. to a foreign adversary\n    country, or to an entity it controls\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign up with an email address and a password at app.aistrail.com/signup and must confirm your email\n    address before you can create API keys or buy a paid plan.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/aistrail-com/eligibility/aistrail-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AIS Trail's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Maritime
- AIS
- Data
- Real-Time
---
