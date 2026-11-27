---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use this Site or any Protolabs ’ services if You are the subject of U.S. or E.U. sanctions
  entity_types:
  - text: Our Site, apps, products, and services are designed for businesses and their representatives.
    type: business
  - text: The Information offered by Protolabs on the Site is only available to individuals who are 18 years or older
    type: individual
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THESE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Export-controlled data
    text: Protolabs Network does not accept Export Controlled Data.
  - summary: Weapons
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
name: Protolabs
provenance_date: '2026-11-10'
provider_name: Protolabs
provider_slug: protolabs
slug: protolabs-eligibility
source_date: '2026-11-10'
source_filename: protolabs-eligibility.yml
source_heading: Eligibility
source_page: https://www.protolabs.com/legal-notices/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Protolabs\naid: protolabs\nurl: https://www.protolabs.com/legal-notices/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may not use this Site or any Protolabs ’ services if You are the subject of U.S. or E.U. sanctions\nentity_types:\n- type: business\n  text: Our Site, apps, products, and services are designed for businesses and their representatives.\n- type: individual\n  text: The Information offered by Protolabs on the Site is only available to individuals who are 18 years or older\nrestricted_uses:\n- summary: Export-controlled data\n  text: Protolabs\
  \ Network does not accept Export Controlled Data.\n- summary: Weapons\n  text: Does not contain any weapons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THESE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/protolabs/eligibility/protolabs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Protolabs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Manufacturing
- Rapid Prototyping
- Digital Manufacturing
- Engineering
---
