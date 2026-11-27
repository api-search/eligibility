---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are at least the age of majority in your state or province of residence
    type: individual
  - text: These Terms of Service apply to all users of the site, including without limitation users who are browsers, vendors, customers, merchants, and/ or contributors of content.
    type: business
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use our products for any illegal or unauthorized purpose
  - summary: Generated content responsibility
    text: We explicitly only offer a human-facing interface and access to infrastructure for machine learning platforms, the user is responsible for the created content within the platform.
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
name: Mokker.ai
provenance_date: '2026-11-10'
provider_name: Mokker.ai
provider_slug: mokkerai
slug: mokkerai-eligibility
source_date: '2026-11-10'
source_filename: mokkerai-eligibility.yml
source_heading: Eligibility
source_page: https://mokker.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mokker.ai\naid: mokkerai\nurl: https://mokker.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are at least the age of majority in your state or province of residence\n- type: business\n  text: These Terms of Service apply to all users of the site, including without limitation users who are browsers,\n    vendors, customers, merchants, and/ or contributors of content.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use our products for any illegal or unauthorized purpose\n\
  - summary: Generated content responsibility\n  text: We explicitly only offer a human-facing interface and access to infrastructure for machine learning platforms,\n    the user is responsible for the created content within the platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/mokkerai/eligibility/mokkerai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Mokker.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Image Processing
- Product Photography
- E-Commerce
- Background Removal
- Computer Vision
- Generative AI
---
