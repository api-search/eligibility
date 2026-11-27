---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform is not available to anyone under the age of 13 (or under 16 in certain jurisdictions).
    type: individual
  minimum_age:
    text: The Platform is not available to anyone under the age of 13 (or under 16 in certain jurisdictions).
    value: '13'
  restricted_uses:
  - summary: Spam, solicitation, unauthorized commercial use
    text: Not use the Platform for spam, solicitation, or unauthorized commercial purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Access to the Platform as a member requires acceptance through our admissions process. Submitting an application does not guarantee membership.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Praxis
provenance_date: '2026-11-10'
provider_name: Praxis
provider_slug: praxis
slug: praxis-eligibility
source_date: '2026-11-10'
source_filename: praxis-eligibility.yml
source_heading: Eligibility
source_page: https://www.praxisnation.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Praxis\naid: praxis\nurl: https://www.praxisnation.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Platform is not available to anyone under the age of 13 (or under 16 in certain jurisdictions).\nrestricted_uses:\n- summary: Spam, solicitation, unauthorized commercial use\n  text: Not use the Platform for spam, solicitation, or unauthorized commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Access to the Platform as a member requires acceptance through\
  \ our admissions process. Submitting an application\n    does not guarantee membership.\nminimum_age:\n  value: '13'\n  text: The Platform is not available to anyone under the age of 13 (or under 16 in certain jurisdictions).\n"
source_yaml_url: https://artifacts.apis.io/praxis/eligibility/praxis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Praxis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Smart Cities
- Community
- Membership
- Urban Development
- Network State
---
