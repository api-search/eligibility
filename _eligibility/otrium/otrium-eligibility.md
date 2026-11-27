---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: In order to be able to use Otrium's services or purchase products on the Website, you must be 18 years or older.
    value: '18'
  restricted_uses:
  - summary: Private use only
    text: The products sold by Otrium are provided for private use only.
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
name: Otrium
provenance_date: '2026-11-10'
provider_name: Otrium
provider_slug: otrium
slug: otrium-eligibility
source_date: '2026-11-10'
source_filename: otrium-eligibility.yml
source_heading: Eligibility
source_page: https://www.otrium.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Otrium\naid: otrium\nurl: https://www.otrium.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Private use only\n  text: The products sold by Otrium are provided for private use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to be able to use Otrium's services or purchase products on the Website, you must be 18 years or\n    older.\n"
source_yaml_url: https://artifacts.apis.io/otrium/eligibility/otrium-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Otrium's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Fashion
- Retail
- Apparel
- Marketplace
- Netherlands
---
