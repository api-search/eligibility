---
api_specs:
- filename: atlasburn-com-openapi-generated.yml
  format: yaml
  label: atlasburn-com API
  slug: atlasburn-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlasburn-com/openapi/_ae-authored/atlasburn-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years old or have lawful authority to bind an organization
    type: individual
  - text: Have authority to agree to these Terms on behalf of your company
    type: business
  minimum_age:
    text: Be at least 18 years old or have lawful authority to bind an organization
    value: '18'
  restricted_uses:
  - summary: Acceptable use limits
    text: Upload malicious files or content, or anything unlawful, infringing, or offensive
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
name: atlasburn-com
provenance_date: '2026-11-09'
provider_name: atlasburn-com
provider_slug: atlasburn-com
slug: atlasburn-com-eligibility
source_date: '2026-11-09'
source_filename: atlasburn-com-eligibility.yml
source_heading: Eligibility
source_page: https://atlasburn.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: atlasburn-com\naid: atlasburn-com\nurl: https://atlasburn.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years old or have lawful authority to bind an organization\n- type: business\n  text: Have authority to agree to these Terms on behalf of your company\nrestricted_uses:\n- summary: Acceptable use limits\n  text: Upload malicious files or content, or anything unlawful, infringing, or offensive\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: Be at least 18 years old or have lawful authority to bind an organization\n"
source_yaml_url: https://artifacts.apis.io/atlasburn-com/eligibility/atlasburn-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from atlasburn-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Cost Management
- Monitoring
- SDK
---
