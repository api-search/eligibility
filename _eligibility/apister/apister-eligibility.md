---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided ... is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: The Services are intended for users who are at least 18 years old.
    type: individual
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: Persons under the age of 18 are not permitted to use or register for the Services.
    value: '18'
  restricted_uses:
  - summary: Industry-specific regulated data
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
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
name: Apister
provenance_date: '2026-11-09'
provider_name: Apister
provider_slug: apister
slug: apister-eligibility
source_date: '2026-11-09'
source_filename: apister-eligibility.yml
source_heading: Eligibility
source_page: https://www.apister.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apister\naid: apister\nurl: https://www.apister.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided ... is not intended for distribution to or use by any person or entity in any jurisdiction\n    or country where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old.\n- type: business\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n\
  - summary: Industry-specific regulated data\n  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Persons under the age of 18 are not permitted to use or register for the Services.\n"
source_yaml_url: https://artifacts.apis.io/apister/eligibility/apister-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Apister's own page on 2026-11-09.
synthetic: false
tags:
- Company
- No-Code
- API Builder
- Automation
- Integration
---
