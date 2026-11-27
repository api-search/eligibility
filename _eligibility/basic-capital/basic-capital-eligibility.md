---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for users who are at least 18 years old.
    type: individual
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity ("you")
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Services.
    value: '18'
  restricted_uses:
  - summary: Industry-specific regulated data
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Basic Capital
provenance_date: '2026-11-09'
provider_name: Basic Capital
provider_slug: basic-capital
slug: basic-capital-eligibility
source_date: '2026-11-09'
source_filename: basic-capital-eligibility.yml
source_heading: Eligibility
source_page: https://app.termly.io/policy-viewer/policy.html?policyUUID=56a26f98-d16c-4837-8246-b82903d339a8
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Basic Capital\naid: basic-capital\nurl: https://app.termly.io/policy-viewer/policy.html?policyUUID=56a26f98-d16c-4837-8246-b82903d339a8\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old.\n- type: business\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity (\"you\")\nrestricted_uses:\n- summary: Industry-specific regulated data\n  text: The Services are not tailored to comply with industry-specific\
  \ regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Services.\n"
source_yaml_url: https://artifacts.apis.io/basic-capital/eligibility/basic-capital-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Basic Capital's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Retirement
- 401k
- Investing
- Wealth Management
- Financial Services
---
