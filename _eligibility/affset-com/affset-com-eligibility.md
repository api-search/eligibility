---
api_specs:
- filename: affset-com-openapi-generated.yml
  format: yaml
  label: Affset API
  slug: affset-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affset-com/openapi/_ae-authored/affset-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you have the authority to bind that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal advertising
    text: Advertise anything illegal in a jurisdiction you're targeting, including counterfeit goods, unlicensed pharmaceuticals, or content exploiting minors;
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
name: Affset
provenance_date: '2026-11-09'
provider_name: Affset
provider_slug: affset-com
slug: affset-com-eligibility
source_date: '2026-11-09'
source_filename: affset-com-eligibility.yml
source_heading: Eligibility
source_page: https://affset.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Affset\naid: affset-com\nurl: https://affset.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you\n    have the authority to bind that entity.\nrestricted_uses:\n- summary: Illegal advertising\n  text: Advertise anything illegal in a jurisdiction you're targeting, including counterfeit goods, unlicensed pharmaceuticals,\n    or content exploiting minors;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/affset-com/eligibility/affset-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Affset's own page on 2026-11-09.
synthetic: false
tags:
- Affiliate Tracking
- Media Buying
- CPA Networks
- Postback
- White Label
- Pricing
---
