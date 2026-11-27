---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation or which would subject us to any registration requirement within such jurisdiction or country.
  entity_types:
  - text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Site.
    type: individual
  - text: Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: you will not use the Site for any illegal or unauthorized purpose
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
name: Arden
provenance_date: '2026-11-09'
provider_name: Arden
provider_slug: arden
slug: arden-eligibility
source_date: '2026-11-09'
source_filename: arden-eligibility.yml
source_heading: Eligibility
source_page: https://ardentech.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arden\naid: arden\nurl: https://ardentech.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation or which\n    would subject us to any registration requirement within such jurisdiction or country.\nentity_types:\n- type: individual\n  text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to\
  \ use or register for the Site.\n- type: business\n  text: Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf of\n    an entity\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: you will not use the Site for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/arden/eligibility/arden-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Arden's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Internal Audit
- SOX Compliance
- Audit Automation
- GRC
- Artificial Intelligence
- AI Agents
- Financial Reporting
- Y Combinator
---
