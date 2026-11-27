---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Services are not available to users located outside the United States.
  entity_types:
  - text: you represent and warrant that you are 18 years old or older.
    type: individual
  minimum_age:
    text: you represent and warrant that you are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Jurisdictions where content is illegal
    text: Accessing the Platform from jurisdictions where content is illegal, or where we do not offer the Platform, is prohibited.
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
name: CopilotIQ
provenance_date: '2026-11-09'
provider_name: CopilotIQ
provider_slug: copilotiq
slug: copilotiq-eligibility
source_date: '2026-11-09'
source_filename: copilotiq-eligibility.yml
source_heading: Eligibility
source_page: https://copilotiq.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CopilotIQ\naid: copilotiq\nurl: https://copilotiq.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: you represent and warrant that you are 18 years old or older.\nrestricted_uses:\n- summary: Jurisdictions where content is illegal\n  text: Accessing the Platform from jurisdictions where content is illegal, or where we do not offer the Platform,\n    is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/copilotiq/eligibility/copilotiq-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CopilotIQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Remote Patient Monitoring
- Telehealth
- Chronic Disease Management
- Digital Health
- Medicare
---
