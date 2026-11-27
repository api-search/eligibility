---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the company or entity You represent or by which you are employed
    type: business
  minimum_age:
    text: In order to use the Blume Platform, You must be at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions and parties
    text: it is not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Subscriber must be authorized by Blume Global in advance to access the Blume Platform and Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blume Global
provenance_date: '2026-11-09'
provider_name: Blume Global
provider_slug: blume-global
slug: blume-global-eligibility
source_date: '2026-11-09'
source_filename: blume-global-eligibility.yml
source_heading: Eligibility
source_page: https://www.blumeglobal.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blume Global\naid: blume-global\nurl: https://www.blumeglobal.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the company or entity You represent or by which you are employed\nrestricted_uses:\n- summary: Sanctioned jurisdictions and parties\n  text: it is not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a terrorist-supporting country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Subscriber must be authorized\
  \ by Blume Global in advance to access the Blume Platform and Services\nminimum_age:\n  value: '18'\n  text: In order to use the Blume Platform, You must be at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/blume-global/eligibility/blume-global-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Blume Global's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Supply Chain
- Logistics
- Software-as-a-Service
- Visibility
---
