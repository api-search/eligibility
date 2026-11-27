---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: You are not a minor in the jurisdiction in which you reside, or if a minor, you have received parental permission to use the Services
    type: individual
  minimum_age:
    text: You are not under the age of 13
    value: '13'
  restricted_uses:
  - summary: Automated access restricted
    text: You will not access the Services through automated or non-human means, except through our official agent (MCP) interface or other automated access we expressly authorize
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
name: Brandize
provenance_date: '2026-11-09'
provider_name: Brandize
provider_slug: brandize-me
slug: brandize-me-eligibility
source_date: '2026-11-09'
source_filename: brandize-me-eligibility.yml
source_heading: Eligibility
source_page: https://brandize.me/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brandize\naid: brandize-me\nurl: https://brandize.me/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: individual\n  text: You are not a minor in the jurisdiction in which you reside, or if a minor, you have received parental permission\n    to use the Services\nrestricted_uses:\n- summary: Automated access restricted\n  text:\
  \ You will not access the Services through automated or non-human means, except through our official agent\n    (MCP) interface or other automated access we expressly authorize\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You are not under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/brandize-me/eligibility/brandize-me-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Brandize's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Logo
- Design
- Branding
- Software-as-a-Service
- Company
---
