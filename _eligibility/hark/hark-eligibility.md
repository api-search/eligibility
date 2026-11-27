---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Memory is not available in the European Economic Area, the United Kingdom or Switzerland. You may not provide access to our Services in any U.S. embargoed country or to any person or entity on (1) the U.S. Treasury Department's list of Specially Designated Nationals
  entity_types:
  - text: If you are an individual using the Services for personal, non-commercial purposes, the indemnification obligation in Section 13.a above does not apply to you.
    type: individual
  - text: If you are accessing or using the Services on behalf of a business or other legal entity (rather than as an individual consumer for personal use), you agree to indemnify, defend, and hold harmless Hark
    type: business
  minimum_age:
    text: You must be at least 18 years old or the minimum age required by law to use the Services in your location, whichever is higher.
    value: '18'
  restricted_uses:
  - summary: Financial advice reliance
    text: Rely on the Services (including the Content or the Actions) when buying or selling financial products or services (including securities)
  - summary: Decisions about individuals with legal or material consequences
    text: You must not use any Outputs relating to someone in a manner where it may produce a legal or material consequence for them, including decisions regarding credit, education, employment, housing, insurance, legal, medical, or other significant decisions about them.
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
name: Hark
provenance_date: '2026-11-09'
provider_name: Hark
provider_slug: hark
slug: hark-eligibility
source_date: '2026-11-09'
source_filename: hark-eligibility.yml
source_heading: Eligibility
source_page: https://hark.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hark\naid: hark\nurl: https://hark.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Memory is not available in the European Economic Area, the United Kingdom or Switzerland. You may not provide\n    access to our Services in any U.S. embargoed country or to any person or entity on (1) the U.S. Treasury Department's\n    list of Specially Designated Nationals\nentity_types:\n- type: individual\n  text: If you are an individual using the Services for personal, non-commercial purposes, the indemnification obligation\n    in Section 13.a above does not apply\
  \ to you.\n- type: business\n  text: If you are accessing or using the Services on behalf of a business or other legal entity (rather than as\n    an individual consumer for personal use), you agree to indemnify, defend, and hold harmless Hark\nrestricted_uses:\n- summary: Financial advice reliance\n  text: Rely on the Services (including the Content or the Actions) when buying or selling financial products or\n    services (including securities)\n- summary: Decisions about individuals with legal or material consequences\n  text: You must not use any Outputs relating to someone in a manner where it may produce a legal or material consequence\n    for them, including decisions regarding credit, education, employment, housing, insurance, legal, medical, or\n    other significant decisions about them.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the minimum age required by law to\
  \ use the Services in your location,\n    whichever is higher.\n"
source_yaml_url: https://artifacts.apis.io/hark/eligibility/hark-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Hark's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Foundation Models
- Agents
- Consumer Hardware
- Consumer Electronics
- Devices
- Assistant
- Pre-Product
---
