---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years of age to use this Website.
    value: '18'
  restricted_uses:
  - summary: sanctioned or embargoed territories and persons
    text: the Goods will not be supplied directly or indirectly to any person or entity or into any territory which is embargoed, prohibited, debarred or otherwise the subject of sanctions from the United Kingdom, the European Union, the United States of America or the territory where the Customer is located.
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
name: CloudNC
provenance_date: '2026-11-09'
provider_name: CloudNC
provider_slug: cloudnc
slug: cloudnc-eligibility
source_date: '2026-11-09'
source_filename: cloudnc-eligibility.yml
source_heading: Eligibility
source_page: https://www.cloudnc.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CloudNC\naid: cloudnc\nurl: https://www.cloudnc.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: sanctioned or embargoed territories and persons\n  text: the Goods will not be supplied directly or indirectly to any person or entity or into any territory which\n    is embargoed, prohibited, debarred or otherwise the subject of sanctions from the United Kingdom, the European\n    Union, the United States of America or the territory where the Customer is located.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use this Website.\n"
source_yaml_url: https://artifacts.apis.io/cloudnc/eligibility/cloudnc-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from CloudNC's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Manufacturing
- CAM
- Automation
---
