---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are for use by persons located in the United States only.
  entity_types:
  - text: To use the Website or any other Services, you must (i) be at least 18 years old (or be accompanied by a parent or legal guardian)
    type: individual
  - text: you agree to be bound by the terms and conditions of this Agreement on behalf of yourself, your minor child, or the entity or organization that you represent.
    type: business
  minimum_age:
    text: be at least 18 years old (or be accompanied by a parent or legal guardian)
    value: '18'
  restricted_uses:
  - summary: Competitors of the Company
    text: not be a competitor of or using the Services for purposes that are competitive with the Company
  - summary: Collecting others' personal information
    text: (e) collects or tracks the personal information of others
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If, in our judgment, your purchase constitutes a high-risk transaction, we will require you to provide us with a copy of your valid government-issued photo identification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NutriSense
provenance_date: '2026-11-10'
provider_name: NutriSense
provider_slug: nutrisense
slug: nutrisense-eligibility
source_date: '2026-11-10'
source_filename: nutrisense-eligibility.yml
source_heading: Eligibility
source_page: https://www.nutrisense.io/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NutriSense\naid: nutrisense\nurl: https://www.nutrisense.io/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are for use by persons located in the United States only.\nentity_types:\n- type: individual\n  text: To use the Website or any other Services, you must (i) be at least 18 years old (or be accompanied by a\n    parent or legal guardian)\n- type: business\n  text: you agree to be bound by the terms and conditions of this Agreement on behalf of yourself, your minor child,\n    or the entity or organization that you represent.\n\
  restricted_uses:\n- summary: Competitors of the Company\n  text: not be a competitor of or using the Services for purposes that are competitive with the Company\n- summary: Collecting others' personal information\n  text: (e) collects or tracks the personal information of others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If, in our judgment, your purchase constitutes a high-risk transaction, we will require you to provide us\n    with a copy of your valid government-issued photo identification\nminimum_age:\n  value: '18'\n  text: be at least 18 years old (or be accompanied by a parent or legal guardian)\n"
source_yaml_url: https://artifacts.apis.io/nutrisense/eligibility/nutrisense-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from NutriSense's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Wellness
- Continuous Glucose Monitoring
- Nutrition
- Metabolic Health
- Digital Health
- Coaching
---
