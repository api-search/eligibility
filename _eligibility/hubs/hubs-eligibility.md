---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Site, apps, products, and services are designed for businesses and their representatives.
    type: business
  - text: The Information offered by Protolabs Network on the Site is only available to individuals who are 18 years or older and who can form legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THESE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: No export-controlled data
    text: Protolabs Network does not accept Export Controlled Data.
  - summary: No weapons content
    text: Does not contain any weapons.
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
name: hubs
provenance_date: '2026-11-09'
provider_name: hubs
provider_slug: hubs
slug: hubs-eligibility
source_date: '2026-11-09'
source_filename: hubs-eligibility.yml
source_heading: Eligibility
source_page: https://www.hubs.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hubs\naid: hubs\nurl: https://www.hubs.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our Site, apps, products, and services are designed for businesses and their representatives.\n- type: individual\n  text: The Information offered by Protolabs Network on the Site is only available to individuals who are 18 years\n    or older and who can form legally binding contracts under applicable law.\nrestricted_uses:\n- summary: No export-controlled data\n  text: Protolabs Network does not accept Export Controlled Data.\n\
  - summary: No weapons content\n  text: Does not contain any weapons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THESE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/hubs/eligibility/hubs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from hubs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Manufacturing
- On-Demand Manufacturing
- Digital Manufacturing
- 3D Printing
- CNC Machining
- Injection Molding
- Sheet Metal Fabrication
- Hardware
---
