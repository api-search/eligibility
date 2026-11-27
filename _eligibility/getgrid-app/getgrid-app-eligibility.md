---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be a U.S. citizen or legal U.S. resident;
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No professional or commercial services
    text: you will not use any part of the Services on behalf of a third party or to perform professional or commercial services.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may also ask to see your driver’s license or other identifying documents.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Grid
provenance_date: '2026-11-09'
provider_name: Grid
provider_slug: getgrid-app
slug: getgrid-app-eligibility
source_date: '2026-11-09'
source_filename: getgrid-app-eligibility.yml
source_heading: Eligibility
source_page: https://getgrid.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grid\naid: getgrid-app\nurl: https://getgrid.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be a U.S. citizen or legal U.S. resident;\nentity_types: []\nrestricted_uses:\n- summary: No professional or commercial services\n  text: you will not use any part of the Services on behalf of a third party or to perform professional or commercial\n    services.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may also ask to see your driver’s license or other identifying documents.\nminimum_age:\n  value: '18'\n  text:\
  \ You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/getgrid-app/eligibility/getgrid-app-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Grid's own page on 2026-11-09.
synthetic: false
tags:
- Cash Advance
- PayBoost
---
