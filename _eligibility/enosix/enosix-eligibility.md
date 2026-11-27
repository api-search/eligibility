---
api_specs:
- filename: enosix-search-api-openapi.yml
  format: yaml
  label: enosix Search API
  slug: enosix-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enosix/openapi/enosix-search-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Subscriber shall not enable use of the Services in a U.S.-embargoed country or in violation of any U.S. export law or regulation.
  entity_types:
  - text: IF YOU ARE ENTERING INTO OR ACCEPTING THESE TERMS ON BEHALF OF A LEGAL ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE RIGHT, AUTHORITY AND CAPACITY TO BIND SUCH ENTITY
    type: business
  - text: if Subscriber is an agency of, or contractor to, the US Government, it receives only those rights with respect to such software as are granted to all other end users under license
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or objectionable content
    text: For the transmission of material that is defamatory, obscene, indecent, abusive, offensive, harassing, violent, hateful, inflammatory, or otherwise objectionable.
  - summary: Infringement
    text: In any manner that infringe any patent, trademark, trade secret, copyright, or other intellectual property or other rights of any other person.
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
name: enosix
provenance_date: '2026-11-09'
provider_name: enosix
provider_slug: enosix
slug: enosix-eligibility
source_date: '2026-11-09'
source_filename: enosix-eligibility.yml
source_heading: Eligibility
source_page: https://docs.enosix.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: enosix\naid: enosix\nurl: https://docs.enosix.io/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Subscriber shall not enable use of the Services in a U.S.-embargoed country or in violation of any U.S.\n    export law or regulation.\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO OR ACCEPTING THESE TERMS ON BEHALF OF A LEGAL ENTITY, YOU REPRESENT AND WARRANT\n    THAT YOU HAVE THE RIGHT, AUTHORITY AND CAPACITY TO BIND SUCH ENTITY\n- type: government\n  text: if Subscriber is an agency of, or contractor to, the US Government, it receives only those rights with\
  \ respect\n    to such software as are granted to all other end users under license\nrestricted_uses:\n- summary: Unlawful or objectionable content\n  text: For the transmission of material that is defamatory, obscene, indecent, abusive, offensive, harassing, violent,\n    hateful, inflammatory, or otherwise objectionable.\n- summary: Infringement\n  text: In any manner that infringe any patent, trademark, trade secret, copyright, or other intellectual property\n    or other rights of any other person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/enosix/eligibility/enosix-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from enosix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SAP
- Artificial Intelligence
- Integration
- Workflows
---
