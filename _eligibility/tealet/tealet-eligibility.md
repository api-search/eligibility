---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Tealet's services are available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law.
    type: individual
  - text: If you are registering as a business entity, you personally guarantee that you have the authority to bind the entity to this Agreement.
    type: business
  minimum_age:
    text: Tealet's services are available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law.
    value: '18'
  restricted_uses:
  - summary: Jurisdictions that do not give effect to the Agreement
    text: Use of the Site is not authorized in any jurisdiction that does not give effect to all provisions of the Agreement, including without limitation, this section.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Tealet does not pre-screen users or the content or information provided by users.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tealet
provenance_date: '2026-11-10'
provider_name: Tealet
provider_slug: tealet
slug: tealet-eligibility
source_date: '2026-11-10'
source_filename: tealet-eligibility.yml
source_heading: Eligibility
source_page: https://tealet.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tealet\naid: tealet\nurl: https://tealet.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Tealet's services are available only to, and may only be used by, individuals who are 18 years and older\n    who can form legally binding contracts under applicable law.\n- type: business\n  text: If you are registering as a business entity, you personally guarantee that you have the authority to bind\n    the entity to this Agreement.\nrestricted_uses:\n- summary: Jurisdictions that do not give effect to the Agreement\n  text:\
  \ Use of the Site is not authorized in any jurisdiction that does not give effect to all provisions of the\n    Agreement, including without limitation, this section.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Tealet does not pre-screen users or the content or information provided by users.\nminimum_age:\n  value: '18'\n  text: Tealet's services are available only to, and may only be used by, individuals who are 18 years and older\n    who can form legally binding contracts under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/tealet/eligibility/tealet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Tealet's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tea
- Wholesale
- Marketplace
- E-Commerce
- Food and Beverage
- Agriculture
- Direct Trade
- Specialty Tea
---
