---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Alkohol a tabákové výrobky prodáváme pouze osobám starším 18 let.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Při převzetí zboží bude ověřen váš věk.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rohlik
provenance_date: '2026-11-10'
provider_name: Rohlik
provider_slug: rohlik
slug: rohlik-eligibility
source_date: '2026-11-10'
source_filename: rohlik-eligibility.yml
source_heading: Eligibility
source_page: https://www.rohlik.cz/stranka/vseobecne-obchodni-podminky
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rohlik\naid: rohlik\nurl: https://www.rohlik.cz/stranka/vseobecne-obchodni-podminky\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Při převzetí zboží bude ověřen váš věk.\nminimum_age:\n  value: '18'\n  text: Alkohol a tabákové výrobky prodáváme pouze osobám starším 18 let.\n"
source_yaml_url: https://artifacts.apis.io/rohlik/eligibility/rohlik-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Rohlik's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- Grocery
- E-Commerce
- Delivery
- Logistics
- MCP
- OAuth
- Europe
- Authentication
---
