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
  - summary: Unlawful interactive content
    text: Users shall not post or upload any content to Interactive Areas that is unlawful, defamatory, obscene, pornographic, harassing, invasive of privacy, or violates any third-party rights.
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
name: Storyraise
provenance_date: '2026-11-10'
provider_name: Storyraise
provider_slug: storyraise
slug: storyraise-eligibility
source_date: '2026-11-10'
source_filename: storyraise-eligibility.yml
source_heading: Eligibility
source_page: https://storyraise.com/terms-conditions?hsLang=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Storyraise\naid: storyraise\nurl: https://storyraise.com/terms-conditions?hsLang=en\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful interactive content\n  text: Users shall not post or upload any content to Interactive Areas that is unlawful, defamatory, obscene, pornographic,\n    harassing, invasive of privacy, or violates any third-party rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/storyraise/eligibility/storyraise-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Storyraise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Non-Profit
- Fundraising
- Donor Management
- Software-as-a-Service
---
