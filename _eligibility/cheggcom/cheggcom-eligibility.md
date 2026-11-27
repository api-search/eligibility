---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Chegg operates the majority of its Services in the United States.
  entity_types:
  - text: The Services are available to individuals age 13 and over.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use contrary to local law
    text: The Services are not intended for distribution or use in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  - summary: Personal use only
    text: You may only use the Services for your own personal use.
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
name: Chegg.com
provenance_date: '2026-11-09'
provider_name: Chegg.com
provider_slug: cheggcom
slug: cheggcom-eligibility
source_date: '2026-11-09'
source_filename: cheggcom-eligibility.yml
source_heading: Eligibility
source_page: https://www.chegg.com/en-US/termsofuse/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chegg.com\naid: cheggcom\nurl: https://www.chegg.com/en-US/termsofuse/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Chegg operates the majority of its Services in the United States.\nentity_types:\n- type: individual\n  text: The Services are available to individuals age 13 and over.\nrestricted_uses:\n- summary: Use contrary to local law\n  text: The Services are not intended for distribution or use in any jurisdiction or country where such distribution\n    or use would be contrary to law or regulation\n- summary: Personal use only\n  text: You may only use\
  \ the Services for your own personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cheggcom/eligibility/cheggcom-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Chegg.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Learning
- Students
- Homework Help
- Tutoring
- Textbooks
---
