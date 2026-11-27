---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 16 years of age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the Services
    value: '16'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: If your use of the Services is prohibited by applicable laws, then you aren’t authorized to use the Services.
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
name: Red Balloon Security
provenance_date: '2026-11-10'
provider_name: Red Balloon Security
provider_slug: red-balloon-security
slug: red-balloon-security-eligibility
source_date: '2026-11-10'
source_filename: red-balloon-security-eligibility.yml
source_heading: Eligibility
source_page: https://ofrak.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Red Balloon Security\naid: red-balloon-security\nurl: https://ofrak.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: If your use of the Services is prohibited by applicable laws, then you aren’t authorized to use the Services.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 16 years\n    of age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the\n    Services\n"
source_yaml_url: https://artifacts.apis.io/red-balloon-security/eligibility/red-balloon-security-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Red Balloon Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Firmware
- Embedded Systems
- Binary Analysis
- Reverse Engineering
- Critical Infrastructure
- Open Source
---
