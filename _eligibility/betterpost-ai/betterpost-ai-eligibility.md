---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided ... is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: you, whether personally or on behalf of an entity
    type: individual
  - text: BetterPost is a content monitoring and creation platform that helps content creators, marketers, and businesses
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Regulated data uses
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BetterPost
provenance_date: '2026-11-09'
provider_name: BetterPost
provider_slug: betterpost-ai
slug: betterpost-ai-eligibility
source_date: '2026-11-09'
source_filename: betterpost-ai-eligibility.yml
source_heading: Eligibility
source_page: https://betterpost.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BetterPost\naid: betterpost-ai\nurl: https://betterpost.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided ... is not intended for distribution to or use by any person or entity in any jurisdiction\n    or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: you, whether personally or on behalf of an entity\n- type: business\n  text: BetterPost is a content monitoring and creation platform that helps content creators, marketers, and businesses\nrestricted_uses:\n- summary: Regulated\
  \ data uses\n  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/betterpost-ai/eligibility/betterpost-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BetterPost's own page on 2026-11-09.
synthetic: false
tags:
- Content Generation
- AI Writing
- Newsletters
- Energy News
---
