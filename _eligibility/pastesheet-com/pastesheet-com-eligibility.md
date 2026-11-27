---
api_specs:
- filename: pastesheet-com-openapi-generated.yml
  format: yaml
  label: pastesheet-com API
  slug: pastesheet-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pastesheet-com/openapi/_ae-authored/pastesheet-com-openapi-generated.yml
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
  - summary: Unlawful or infringing content
    text: Publish or distribute content that is unlawful, infringing, defamatory, or that violates the rights of any third party.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must verify your email address before accessing most features of the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: pastesheet-com
provenance_date: '2026-11-10'
provider_name: pastesheet-com
provider_slug: pastesheet-com
slug: pastesheet-com-eligibility
source_date: '2026-11-10'
source_filename: pastesheet-com-eligibility.yml
source_heading: Eligibility
source_page: https://pastesheet.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pastesheet-com\naid: pastesheet-com\nurl: https://pastesheet.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: Publish or distribute content that is unlawful, infringing, defamatory, or that violates the rights of any\n    third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must verify your email address before accessing most features of the Service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pastesheet-com/eligibility/pastesheet-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from pastesheet-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Google Sheets
- No-Code
- Artificial Intelligence
---
