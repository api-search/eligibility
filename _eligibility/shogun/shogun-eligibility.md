---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering for a Shogun account or using the Shogun Software on behalf of an entity or other organization, you are agreeing to these Terms for that entity or organization
    type: business
  - text: If Customer (or any of its customers) is an agency, department, or other entity of any government, the use, duplication, reproduction, release, modification, disclosure, or transfer of the Shogun Software
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use or AUP violation
    text: (3) use the Shogun Software in an unlawful manner, in violation of the AUP or otherwise outside the scope expressly permitted hereunder.
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
name: Shogun
provenance_date: '2026-11-10'
provider_name: Shogun
provider_slug: shogun
slug: shogun-eligibility
source_date: '2026-11-10'
source_filename: shogun-eligibility.yml
source_heading: Eligibility
source_page: https://getshogun.com/policy/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shogun\naid: shogun\nurl: https://getshogun.com/policy/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering for a Shogun account or using the Shogun Software on behalf of an entity or other\n    organization, you are agreeing to these Terms for that entity or organization\n- type: government\n  text: If Customer (or any of its customers) is an agency, department, or other entity of any government, the use,\n    duplication, reproduction, release, modification, disclosure, or transfer of the Shogun Software\nrestricted_uses:\n\
  - summary: Unlawful use or AUP violation\n  text: (3) use the Shogun Software in an unlawful manner, in violation of the AUP or otherwise outside the scope\n    expressly permitted hereunder.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shogun/eligibility/shogun-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Shogun's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Page Builder
- Headless Commerce
- Shopify
- BigCommerce
- Conversion Optimization
- No-Code
---
