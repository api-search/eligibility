---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Raritan makes no representation that materials or services at this site are appropriate or available for use outside the United States, and access to them from territories where their contents are illegal is prohibited.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and unlawful-territory restrictions
    text: You may not use or export the materials or services at this site or any copy or adaptation in violation of any applicable laws including without limitation U.S. export laws and regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All information about you must be truthful, and you may not use any aliases or other means to mask your true identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Raritan
provenance_date: '2026-11-10'
provider_name: Raritan
provider_slug: raritan
slug: raritan-eligibility
source_date: '2026-11-10'
source_filename: raritan-eligibility.yml
source_heading: Eligibility
source_page: https://www.raritan.com/about-us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Raritan\naid: raritan\nurl: https://www.raritan.com/about-us/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Raritan makes no representation that materials or services at this site are appropriate or available for\n    use outside the United States, and access to them from territories where their contents are illegal is prohibited.\nentity_types: []\nrestricted_uses:\n- summary: Export and unlawful-territory restrictions\n  text: You may not use or export the materials or services at this site or any copy or adaptation in violation\n    of any applicable laws including\
  \ without limitation U.S. export laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All information about you must be truthful, and you may not use any aliases or other means to mask your\n    true identity.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/raritan/eligibility/raritan-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Raritan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Power Management
- DCIM
- KVM-over-IP
- Data Center
---
