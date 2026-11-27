---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access from countries or territories where such access is illegal is prohibited.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted government rights
    text: Avatier provides software and content downloaded from this website to U.S. Government users with “RESTRICTED RIGHTS.”
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
name: Avatier
provenance_date: '2026-11-09'
provider_name: Avatier
provider_slug: avatier
slug: avatier-eligibility
source_date: '2026-11-09'
source_filename: avatier-eligibility.yml
source_heading: Eligibility
source_page: https://www.avatier.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avatier\naid: avatier\nurl: https://www.avatier.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access from countries or territories where such access is illegal is prohibited.\nentity_types: []\nrestricted_uses:\n- summary: Restricted government rights\n  text: Avatier provides software and content downloaded from this website to U.S. Government users with “RESTRICTED\n    RIGHTS.”\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/avatier/eligibility/avatier-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Avatier's own page on 2026-11-09.
synthetic: false
tags:
- Identity
- Identity and Access Management
- Artificial Intelligence
- Cloud
- Enterprise
---
