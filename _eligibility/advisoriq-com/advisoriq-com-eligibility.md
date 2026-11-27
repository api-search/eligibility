---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An account is for one person.
    type: individual
  - text: meant for professional use by financial advisors and the firms they work with.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No spam or misleading information
    text: or use it to send spam or misleading information.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Give accurate details, including your CRD number if you enter one.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AdvisorIQ
provenance_date: '2026-11-09'
provider_name: AdvisorIQ
provider_slug: advisoriq-com
slug: advisoriq-com-eligibility
source_date: '2026-11-09'
source_filename: advisoriq-com-eligibility.yml
source_heading: Eligibility
source_page: https://advisoriq.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdvisorIQ\naid: advisoriq-com\nurl: https://advisoriq.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An account is for one person.\n- type: business\n  text: meant for professional use by financial advisors and the firms they work with.\nrestricted_uses:\n- summary: No spam or misleading information\n  text: or use it to send spam or misleading information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Give accurate details, including your CRD number if you enter one.\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/advisoriq-com/eligibility/advisoriq-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from AdvisorIQ's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Financial Services
- Continuing Education
- CE Tracker
- Webinars
---
