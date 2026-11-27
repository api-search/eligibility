---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for business use by organizations and their authorized representatives.
    type: business
  minimum_age:
    text: You must be at least 18 years of age and have the authority to bind your organization to these Terms.
    value: '18'
  restricted_uses:
  - summary: Unlawful or regulated use
    text: Use the Services for unlawful purposes or in violation of applicable regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to certain features may require a separate enterprise agreement.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: X5 Labs
provenance_date: '2026-11-10'
provider_name: X5 Labs
provider_slug: x5-labs
slug: x5-labs-eligibility
source_date: '2026-11-10'
source_filename: x5-labs-eligibility.yml
source_heading: Eligibility
source_page: https://x5labs.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: X5 Labs\naid: x5-labs\nurl: https://x5labs.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended for business use by organizations and their authorized representatives.\nrestricted_uses:\n- summary: Unlawful or regulated use\n  text: Use the Services for unlawful purposes or in violation of applicable regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to certain features may require a separate enterprise agreement.\nminimum_age:\n  value: '18'\n  text: You must\
  \ be at least 18 years of age and have the authority to bind your organization to these Terms.\n"
source_yaml_url: https://artifacts.apis.io/x5-labs/eligibility/x5-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from X5 Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Governance
- Enterprise
- Automation
---
