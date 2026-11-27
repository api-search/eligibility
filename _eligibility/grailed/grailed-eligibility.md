---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are using the Services from a country embargoed by the US or are on the US Treasury Department's list of "Specially Designated Nationals," you agree that you will not engage in financial transactions or conduct any commercial activities through the Services.
  entity_types:
  - text: If you are entering into these Terms as an individual (i.e., non-business, non-entity) user
    type: individual
  - text: If you are entering into these Terms on behalf of an entity
    type: business
  minimum_age:
    text: You must be at least 16 years of age (or at least 18 years of age if you are located in China) to use the Services.
    value: '16'
  restricted_uses:
  - summary: Under-18 users
    text: If you are under the age of 18 (or the age of legal majority where you live) and are not located in China, you may only use the Services under your parent or legal guardian's supervision and you may not list items for sale through the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Persona's verification requirements include, but are not limited to, the provision of a government-issued ID matching the full legal name used to create your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Grailed
provenance_date: '2026-11-09'
provider_name: Grailed
provider_slug: grailed
slug: grailed-eligibility
source_date: '2026-11-09'
source_filename: grailed-eligibility.yml
source_heading: Eligibility
source_page: https://www.grailed.com/about/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grailed\naid: grailed\nurl: https://www.grailed.com/about/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: If you are using the Services from a country embargoed by the US or are on the US Treasury Department's\n    list of \"Specially Designated Nationals,\" you agree that you will not engage in financial transactions or conduct\n    any commercial activities through the Services.\nentity_types:\n- type: individual\n  text: If you are entering into these Terms as an individual (i.e., non-business, non-entity) user\n- type: business\n  text: If you are entering\
  \ into these Terms on behalf of an entity\nrestricted_uses:\n- summary: Under-18 users\n  text: If you are under the age of 18 (or the age of legal majority where you live) and are not located in China,\n    you may only use the Services under your parent or legal guardian's supervision and you may not list items for\n    sale through the Services.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Persona's verification requirements include, but are not limited to, the provision of a government-issued\n    ID matching the full legal name used to create your account.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age (or at least 18 years of age if you are located in China) to use the\n    Services.\n"
source_yaml_url: https://artifacts.apis.io/grailed/eligibility/grailed-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Grailed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- Fashion
- Marketplace
- E-Commerce
- Resale
- Streetwear
- Luxury
---
