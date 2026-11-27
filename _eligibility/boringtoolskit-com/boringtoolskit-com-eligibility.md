---
api_specs:
- filename: boringtoolskit-com-privacy-region-api-openapi.yml
  format: yaml
  label: BoringToolsKit Privacy region API
  slug: boringtoolskit-com-privacy-region-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boringtoolskit-com/openapi/boringtoolskit-com-privacy-region-api-openapi.yml
- filename: boringtoolskit-com-usage-events-api-openapi.yml
  format: yaml
  label: BoringToolsKit Usage events API
  slug: boringtoolskit-com-usage-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boringtoolskit-com/openapi/boringtoolskit-com-usage-events-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the tools freely for personal and business planning
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or abusive activity
    text: Do not use the tools for illegal or abusive activity.
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
name: BoringToolsKit
provenance_date: '2026-11-09'
provider_name: BoringToolsKit
provider_slug: boringtoolskit-com
slug: boringtoolskit-com-eligibility
source_date: '2026-11-09'
source_filename: boringtoolskit-com-eligibility.yml
source_heading: Eligibility
source_page: https://boringtoolskit.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BoringToolsKit\naid: boringtoolskit-com\nurl: https://boringtoolskit.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You may use the tools freely for personal and business planning\nrestricted_uses:\n- summary: Illegal or abusive activity\n  text: Do not use the tools for illegal or abusive activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boringtoolskit-com/eligibility/boringtoolskit-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from BoringToolsKit's own page on 2026-11-09.
synthetic: false
tags:
- Tools
- Finance
- Health
- Education
- Construction
- Free
---
