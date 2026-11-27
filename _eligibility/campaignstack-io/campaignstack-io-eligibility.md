---
api_specs:
- filename: campaignstack-io-openapi-generated.yml
  format: yaml
  label: CampaignStack API
  slug: campaignstack-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campaignstack-io/openapi/_ae-authored/campaignstack-io-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: It is sold to businesses.
    type: business
  minimum_age:
    text: It is not for consumers and not for anyone under 18.
    value: '18'
  restricted_uses:
  - summary: Consumer use prohibited
    text: It is not for consumers and not for anyone under 18.
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
name: CampaignStack
provenance_date: '2026-11-09'
provider_name: CampaignStack
provider_slug: campaignstack-io
slug: campaignstack-io-eligibility
source_date: '2026-11-09'
source_filename: campaignstack-io-eligibility.yml
source_heading: Eligibility
source_page: https://campaignstack.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CampaignStack\naid: campaignstack-io\nurl: https://campaignstack.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: It is sold to businesses.\nrestricted_uses:\n- summary: Consumer use prohibited\n  text: It is not for consumers and not for anyone under 18.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: It is not for consumers and not for anyone under 18.\n"
source_yaml_url: https://artifacts.apis.io/campaignstack-io/eligibility/campaignstack-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CampaignStack's own page on 2026-11-09.
synthetic: false
tags:
- Outbound Outreach
- LinkedIn sourcing
- B2B SaaS
---
