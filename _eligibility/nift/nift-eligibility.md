---
api_specs:
- filename: nift-customers-api-openapi.yml
  format: yaml
  label: NIFT Customers API
  slug: nift-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nift/openapi/nift-customers-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you have the legal authority to bind such client entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No harmful or unlawful Ad Content
    text: the Ad Content, Campaigns, Gifts and Destinations shall not contain material which is harmful, unlawful, defamatory, obscene, fraudulent
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
name: NIFT
provenance_date: '2026-11-10'
provider_name: NIFT
provider_slug: nift
slug: nift-eligibility
source_date: '2026-11-10'
source_filename: nift-eligibility.yml
source_heading: Eligibility
source_page: https://www.gonift.com/business/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NIFT\naid: nift\nurl: https://www.gonift.com/business/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You represent that you have the legal authority to bind such client entity.\nrestricted_uses:\n- summary: No harmful or unlawful Ad Content\n  text: the Ad Content, Campaigns, Gifts and Destinations shall not contain material which is harmful, unlawful,\n    defamatory, obscene, fraudulent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nift/eligibility/nift-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from NIFT's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Gifting
- Customer Acquisition
- Loyalty
- Rewards
- SDK
- Partners
---
