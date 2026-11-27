---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Sites is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: Persons under the age of 18 are not permitted to use or register for the Sites.
    type: individual
  - text: whether personally or on behalf of an entity (“you”)
    type: business
  minimum_age:
    text: The Sites are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Sites.
    value: '18'
  restricted_uses:
  - summary: Industry-specific regulated data
    text: The Sites are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Sites.
  - summary: Resellers and dealers
    text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers, or distributors.
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
name: Mejuri
provenance_date: '2026-11-10'
provider_name: Mejuri
provider_slug: mejuri
slug: mejuri-eligibility
source_date: '2026-11-10'
source_filename: mejuri-eligibility.yml
source_heading: Eligibility
source_page: https://mejuri.com/company/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mejuri\naid: mejuri\nurl: https://mejuri.com/company/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Sites is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: individual\n  text: Persons under the age of 18 are not permitted to use or register for the Sites.\n- type: business\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: Industry-specific regulated data\n\
  \  text: The Sites are not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Sites.\n- summary: Resellers and dealers\n  text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n    resellers, or distributors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Sites are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Sites.\n"
source_yaml_url: https://artifacts.apis.io/mejuri/eligibility/mejuri-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Mejuri's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Jewelry
- Fashion
- Retail
- E-Commerce
- Direct to Consumer
- Consumer Brand
---
