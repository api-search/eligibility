---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: You are a legal resident of European Economic Area or the United Kingdom . You must legally reside in a country in European Economic Area or the United Kingdom .
  entity_types:
  - text: You are at least 18 years old. You must be 18 years or older to use Cino Services and by opening a Cino Account you declare that you are 18 years or older.
    type: individual
  minimum_age:
    text: You must be 18 years or older to use Cino Services
    value: '18'
  restricted_uses:
  - summary: Prohibited businesses and activities
    text: Betting, including lottery tickets, sports-related gambling, casino gaming chips, off-track betting, and wagers at races.
  - summary: Money transmission and cash-type activity
    text: Use Cino Services to handle, process, or transmit funds on behalf of any third party.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To help the government fight the funding of terrorism and money laundering activities, MLTFPA requires obtaining, verifying, and recording information that identifies each person who requests to use Cino Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cino
provenance_date: '2026-11-09'
provider_name: Cino
provider_slug: getcino
slug: getcino-eligibility
source_date: '2026-11-09'
source_filename: getcino-eligibility.yml
source_heading: Eligibility
source_page: https://www.getcino.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cino\naid: getcino\nurl: https://www.getcino.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: You are a legal resident of European Economic Area or the United Kingdom . You must legally reside in a\n    country in European Economic Area or the United Kingdom .\nentity_types:\n- type: individual\n  text: You are at least 18 years old. You must be 18 years or older to use Cino Services and by opening a Cino\n    Account you declare that you are 18 years or older.\nrestricted_uses:\n- summary: Prohibited businesses and activities\n  text: Betting, including\
  \ lottery tickets, sports-related gambling, casino gaming chips, off-track betting, and\n    wagers at races.\n- summary: Money transmission and cash-type activity\n  text: Use Cino Services to handle, process, or transmit funds on behalf of any third party.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To help the government fight the funding of terrorism and money laundering activities, MLTFPA requires obtaining,\n    verifying, and recording information that identifies each person who requests to use Cino Services.\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to use Cino Services\n"
source_yaml_url: https://artifacts.apis.io/getcino/eligibility/getcino-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Cino's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Bill Splitting
- Virtual Cards
- Personal Finance
- Consumer Finance
- Europe
---
