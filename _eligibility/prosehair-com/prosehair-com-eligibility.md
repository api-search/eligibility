---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: You must be at least eighteen (18) years of age to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Adult-only products
    text: All personalized haircare and skincare Products offered by Prose are intended exclusively for purchase and use by individuals who are eighteen (18) years of age or older.
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
name: Prose
provenance_date: '2026-11-10'
provider_name: Prose
provider_slug: prosehair-com
slug: prosehair-com-eligibility
source_date: '2026-11-10'
source_filename: prosehair-com-eligibility.yml
source_heading: Eligibility
source_page: https://prose.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prose\naid: prosehair-com\nurl: https://prose.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Adult-only products\n \
  \ text: All personalized haircare and skincare Products offered by Prose are intended exclusively for purchase and\n    use by individuals who are eighteen (18) years of age or older.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/prosehair-com/eligibility/prosehair-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Prose's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hair Care
- Skincare
- Personalization
- Subscription
---
