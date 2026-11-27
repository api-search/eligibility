---
api_specs:
- filename: requestly-openapi-generated.yml
  format: yaml
  label: Requestly API
  slug: requestly-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/requestly/openapi/_ae-authored/requestly-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The term “ User ” includes any individual that uses the Services
    type: individual
  - text: If You are agreeing to these Terms not as an individual but on behalf of Your company, government, or other entity
    type: business
  minimum_age:
    text: The Services are not intended for and should not be used by anyone under the age of 13
    value: '13'
  restricted_uses:
  - summary: Export control and sanctions
    text: You may not use the Services in violation of any laws including export control or sanctions laws of the United States or any other applicable jurisdiction.
  - summary: Sanctioned persons
    text: You may not use the Services if You are or are working on behalf of a Specially Designated National (SDN) or a person subject to similar blocking or denied party prohibitions administered by a U.S. government agency.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Services can be used in automation testing, CI pipelines or any other sorts of automation only after our approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Requestly
provenance_date: '2026-11-10'
provider_name: Requestly
provider_slug: requestly
slug: requestly-eligibility
source_date: '2026-11-10'
source_filename: requestly-eligibility.yml
source_heading: Eligibility
source_page: https://requestly.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Requestly\naid: requestly\nurl: https://requestly.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The term “ User ” includes any individual that uses the Services\n- type: business\n  text: If You are agreeing to these Terms not as an individual but on behalf of Your company, government, or other\n    entity\nrestricted_uses:\n- summary: Export control and sanctions\n  text: You may not use the Services in violation of any laws including export control or sanctions laws of the\n    United States or any other applicable jurisdiction.\n\
  - summary: Sanctioned persons\n  text: You may not use the Services if You are or are working on behalf of a Specially Designated National (SDN)\n    or a person subject to similar blocking or denied party prohibitions administered by a U.S. government agency.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Services can be used in automation testing, CI pipelines or any other sorts of automation only after\n    our approval.\nminimum_age:\n  value: '13'\n  text: The Services are not intended for and should not be used by anyone under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/requestly/eligibility/requestly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Requestly's own page on 2026-11-10.
synthetic: false
tags:
- Platform
- Testing
- Development
- Collaboration
- Security
---
