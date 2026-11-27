---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: Neither the Site nor Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Industry-specific regulated data
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
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
name: Metaview
provenance_date: '2026-11-10'
provider_name: Metaview
provider_slug: metaview
slug: metaview-eligibility
source_date: '2026-11-10'
source_filename: metaview-eligibility.yml
source_heading: Eligibility
source_page: https://www.metaview.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Metaview\naid: metaview\nurl: https://www.metaview.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Industry-specific regulated data\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Neither the Site nor Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/metaview/eligibility/metaview-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Metaview's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Recruiting
- Hiring
- Talent Acquisition
- AI Agents
- Interview Notes
- Human Resources
---
