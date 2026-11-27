---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer represents and warrants that it is entering into this Agreement and procuring the Service solely in connection with its trade, business, or professional activity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use outside business activity
    text: If you are a consumer or would use the Service outside the scope of your business or professional activity, you must not register an account through the standard signup flow.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer has failed to provide information requested under Section 4 of the Usage Terms (KYC and Onboarding Verification) within a reasonable time
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Viktor
provenance_date: '2026-11-10'
provider_name: Viktor
provider_slug: viktor
slug: viktor-eligibility
source_date: '2026-11-10'
source_filename: viktor-eligibility.yml
source_heading: Eligibility
source_page: https://app.viktor.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Viktor\naid: viktor\nurl: https://app.viktor.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer represents and warrants that it is entering into this Agreement and procuring the Service solely\n    in connection with its trade, business, or professional activity.\nrestricted_uses:\n- summary: Use outside business activity\n  text: If you are a consumer or would use the Service outside the scope of your business or professional activity,\n    you must not register an account through the standard signup flow.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer has failed to provide information requested under Section 4 of the Usage Terms (KYC and Onboarding\n    Verification) within a reasonable time\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/viktor/eligibility/viktor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Viktor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Artificial Intelligence
- AI Agents
- Automation
- Slack
- Microsoft Teams
- Productivity
- Workflows
---
