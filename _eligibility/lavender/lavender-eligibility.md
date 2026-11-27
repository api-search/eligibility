---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Services.
    type: individual
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
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
name: Lavender
provenance_date: '2026-11-09'
provider_name: Lavender
provider_slug: lavender
slug: lavender-eligibility
source_date: '2026-11-09'
source_filename: lavender-eligibility.yml
source_heading: Eligibility
source_page: https://lavender.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lavender\naid: lavender\nurl: https://lavender.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are not intended for distribution to or use by any person or entity in any jurisdiction or\n    country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Services.\nrestricted_uses:\n- summary: Industry-specific regulated data\n  text: The Services\
  \ are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/lavender/eligibility/lavender-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Lavender's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sales
- Email
- Artificial Intelligence
- Sales Enablement
- Sales Engagement
- CRM
- Browser Extension
- Productivity
---
