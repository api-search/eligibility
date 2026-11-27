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
  - summary: One key per customer, no sharing across organizations
    text: An API key is issued to one customer. Don't share a key across unrelated organizations or resell access to your key's quota.
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
name: billcommons-org
provenance_date: '2026-11-09'
provider_name: billcommons-org
provider_slug: billcommons-org
slug: billcommons-org-eligibility
source_date: '2026-11-09'
source_filename: billcommons-org-eligibility.yml
source_heading: Eligibility
source_page: https://billcommons.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: billcommons-org\naid: billcommons-org\nurl: https://billcommons.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: One key per customer, no sharing across organizations\n  text: An API key is issued to one customer. Don't share a key across unrelated organizations or resell access\n    to your key's quota.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/billcommons-org/eligibility/billcommons-org-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from billcommons-org's own page on 2026-11-09.
synthetic: false
tags:
- Legislative
- State bills
- Open Source
- Research Tools
---
