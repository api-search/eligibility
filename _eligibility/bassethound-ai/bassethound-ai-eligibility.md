---
api_specs:
- filename: bassethound-ai-openapi-generated.yml
  format: yaml
  label: Bassethound API
  slug: bassethound-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bassethound-ai/openapi/_ae-authored/bassethound-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you agree to these terms on its behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Use the Service to violate any law or any third party's rights.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The MCP endpoint requires you to sign in; the /sniff playground on this site does not.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bassethound
provenance_date: '2026-11-09'
provider_name: Bassethound
provider_slug: bassethound-ai
slug: bassethound-ai-eligibility
source_date: '2026-11-09'
source_filename: bassethound-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bassethound.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bassethound\naid: bassethound-ai\nurl: https://bassethound.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you agree to these terms on its behalf.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: Use the Service to violate any law or any third party's rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The MCP endpoint requires you to sign in; the /sniff playground on this site does not.\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/bassethound-ai/eligibility/bassethound-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Bassethound's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Intelligence
- MCP
- Company Intelligence
---
