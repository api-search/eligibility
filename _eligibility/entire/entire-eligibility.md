---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: (or the company or other legal entity on behalf of which you are accessing or using our services, as applicable)
    type: business
  minimum_age:
    text: You must be 16 or over to use our services.
    value: '16'
  restricted_uses:
  - summary: Embargoed countries and listed parties
    text: you are not located in a country that is subject to the United States government embargo, or that has been designated by the United States government as a "terrorist supporting" country, and (ii) you are not listed on any United States government list of prohibited or restricted parties.
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
name: Entire
provenance_date: '2026-11-09'
provider_name: Entire
provider_slug: entire
slug: entire-eligibility
source_date: '2026-11-09'
source_filename: entire-eligibility.yml
source_heading: Eligibility
source_page: https://entire.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Entire\naid: entire\nurl: https://entire.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: (or the company or other legal entity on behalf of which you are accessing or using our services, as applicable)\nrestricted_uses:\n- summary: Embargoed countries and listed parties\n  text: you are not located in a country that is subject to the United States government embargo, or that has been\n    designated by the United States government as a \"terrorist supporting\" country, and (ii) you are not listed\n    on any United States government\
  \ list of prohibited or restricted parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be 16 or over to use our services.\n"
source_yaml_url: https://artifacts.apis.io/entire/eligibility/entire-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Entire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Developer Platform
- Version Control
- Git Hosting
- AI Agents
- Agent Infrastructure
- CLI
---
