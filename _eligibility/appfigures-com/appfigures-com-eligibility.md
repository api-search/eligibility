---
api_specs:
- filename: appfigures-com-openapi-generated.yml
  format: yaml
  label: Appfigures API
  slug: appfigures-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appfigures-com/openapi/_ae-authored/appfigures-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Users must comply with laws of their state and country of residence; no countries are named. Export clause: "it may be not be exported to or used by embargoed countries or individuals."'
  minimum_age:
    text: You are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Automated scripts
    text: (d) use automated scripts to collect information or otherwise interact with the Service or the Site;
  - summary: Export restrictions
    text: The Software is controlled by U.S. Export Regulations, and it may be not be exported to or used by embargoed countries or individuals.
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
name: Appfigures
provenance_date: '2026-11-09'
provider_name: Appfigures
provider_slug: appfigures-com
slug: appfigures-com-eligibility
source_date: '2026-11-09'
source_filename: appfigures-com-eligibility.yml
source_heading: Eligibility
source_page: https://appfigures.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appfigures\naid: appfigures-com\nurl: https://appfigures.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Users must comply with laws of their state and country of residence; no countries are named. Export clause:\n    \"it may be not be exported to or used by embargoed countries or individuals.\"'\nentity_types: []\nrestricted_uses:\n- summary: Automated scripts\n  text: (d) use automated scripts to collect information or otherwise interact with the Service or the Site;\n- summary: Export restrictions\n  text: The Software is controlled by U.S. Export Regulations, and\
  \ it may be not be exported to or used by embargoed\n    countries or individuals.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/appfigures-com/eligibility/appfigures-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Appfigures's own page on 2026-11-09.
synthetic: false
tags:
- Mobile
- Analytics
- ASO
- Advertising
- Market Data
- Company
---
