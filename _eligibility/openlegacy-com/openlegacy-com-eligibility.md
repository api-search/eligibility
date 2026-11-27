---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal jurisdictions
    text: make use of the Website in any jurisdiction where same are illegal
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
name: OpenLegacy
provenance_date: '2026-11-10'
provider_name: OpenLegacy
provider_slug: openlegacy-com
slug: openlegacy-com-eligibility
source_date: '2026-11-10'
source_filename: openlegacy-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.openlegacy.com/p/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenLegacy\naid: openlegacy-com\nurl: https://www.openlegacy.com/p/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal jurisdictions\n  text: make use of the Website in any jurisdiction where same are illegal\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openlegacy-com/eligibility/openlegacy-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from OpenLegacy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legacy Modernization
- API Generation
- Low-Code
- Cloud Integration
---
