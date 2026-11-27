---
api_specs:
- filename: davisvillelabs-com-agent-api-openapi.yml
  format: yaml
  label: davisvillelabs-com Agent API
  slug: davisvillelabs-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/davisvillelabs-com/openapi/davisvillelabs-com-agent-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use a service for a company, school, family, organization, or other entity, you represent that you have authority to bind that entity.
    type: business
  minimum_age:
    text: Our services are not intended for children under 13 unless Davisville Labs expressly provides a compliant parent-consent flow for that service.
    value: '13'
  restricted_uses:
  - summary: Compass age and grade limits
    text: Compass is limited to students in grades 9 through 12 who are age 13 or older.
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
name: davisvillelabs-com
provenance_date: '2026-11-09'
provider_name: davisvillelabs-com
provider_slug: davisvillelabs-com
slug: davisvillelabs-com-eligibility
source_date: '2026-11-09'
source_filename: davisvillelabs-com-eligibility.yml
source_heading: Eligibility
source_page: https://davisvillelabs.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: davisvillelabs-com\naid: davisvillelabs-com\nurl: https://davisvillelabs.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use a service for a company, school, family, organization, or other entity, you represent that you\n    have authority to bind that entity.\nrestricted_uses:\n- summary: Compass age and grade limits\n  text: Compass is limited to students in grades 9 through 12 who are age 13 or older.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n\
  \  text: Our services are not intended for children under 13 unless Davisville Labs expressly provides a compliant\n    parent-consent flow for that service.\n"
source_yaml_url: https://artifacts.apis.io/davisvillelabs-com/eligibility/davisvillelabs-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from davisvillelabs-com's own page on 2026-11-09.
synthetic: false
tags:
- Software
- Artificial Intelligence
- Education
- Bitcoin
- Analytics
---
