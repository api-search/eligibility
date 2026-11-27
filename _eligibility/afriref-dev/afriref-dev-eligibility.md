---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Which countries and series are held, and where we deliberately hold nothing, is listed live at https://afriref.dev/coverage .
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No bulk competing dataset
    text: Do not resell or redistribute bulk extracts of the data as a competing dataset.
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
name: afriref
provenance_date: '2026-11-09'
provider_name: afriref
provider_slug: afriref-dev
slug: afriref-dev-eligibility
source_date: '2026-11-09'
source_filename: afriref-dev-eligibility.yml
source_heading: Eligibility
source_page: https://afriref.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: afriref\naid: afriref-dev\nurl: https://afriref.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Which countries and series are held, and where we deliberately hold nothing, is listed live at https://afriref.dev/coverage\n    .\nentity_types: []\nrestricted_uses:\n- summary: No bulk competing dataset\n  text: Do not resell or redistribute bulk extracts of the data as a competing dataset.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/afriref-dev/eligibility/afriref-dev-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from afriref's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Government
- Africa
- Reference
---
