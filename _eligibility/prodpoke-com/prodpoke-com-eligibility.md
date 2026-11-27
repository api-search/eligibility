---
claim_count: 2
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
  - summary: No unauthorized testing or DoS
    text: You must not use ProdPoke to test websites without authorization, perform denial-of-service attacks, or attempt to exploit vulnerabilities discovered through testing.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to ProdPoke requires registration with a valid email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: prodpoke-com
provenance_date: '2026-11-10'
provider_name: prodpoke-com
provider_slug: prodpoke-com
slug: prodpoke-com-eligibility
source_date: '2026-11-10'
source_filename: prodpoke-com-eligibility.yml
source_heading: Eligibility
source_page: https://prodpoke.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: prodpoke-com\naid: prodpoke-com\nurl: https://prodpoke.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No unauthorized testing or DoS\n  text: You must not use ProdPoke to test websites without authorization, perform denial-of-service attacks, or\n    attempt to exploit vulnerabilities discovered through testing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to ProdPoke requires registration with a valid email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prodpoke-com/eligibility/prodpoke-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from prodpoke-com's own page on 2026-11-10.
synthetic: false
tags:
- Testing
- Automation
- QA
- Developer Tools
- Web
---
