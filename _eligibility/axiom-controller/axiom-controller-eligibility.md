---
api_specs:
- filename: axiom-controller-datasets-api-openapi.yml
  format: yaml
  label: Axiom Controller Datasets API
  slug: axiom-controller-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiom-controller/openapi/axiom-controller-datasets-api-openapi.yml
- filename: axiom-controller-edge-api-openapi.yml
  format: yaml
  label: Axiom Controller Edge API
  slug: axiom-controller-edge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiom-controller/openapi/axiom-controller-edge-api-openapi.yml
- filename: axiom-controller-ingest-api-openapi.yml
  format: yaml
  label: Axiom Controller Ingest API
  slug: axiom-controller-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiom-controller/openapi/axiom-controller-ingest-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ORGANIZATION OR ENTITY, REFERENCES TO “CUSTOMER” AND “YOU” IN THIS AGREEMENT, REFER TO THAT ORGANIZATION OR ENTITY.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with laws
    text: Customer will use the Service only in accordance with all applicable laws, including, but not limited to, rules and regulations related to data and personally identifiable information.
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
name: Axiom Controller
provenance_date: '2026-11-09'
provider_name: Axiom Controller
provider_slug: axiom-controller
slug: axiom-controller-eligibility
source_date: '2026-11-09'
source_filename: axiom-controller-eligibility.yml
source_heading: Eligibility
source_page: https://axiom.co/docs/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Axiom Controller\naid: axiom-controller\nurl: https://axiom.co/docs/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ORGANIZATION OR ENTITY, REFERENCES TO “CUSTOMER”\n    AND “YOU” IN THIS AGREEMENT, REFER TO THAT ORGANIZATION OR ENTITY.\nrestricted_uses:\n- summary: Compliance with laws\n  text: Customer will use the Service only in accordance with all applicable laws, including, but not limited to,\n    rules and regulations related to data and personally\
  \ identifiable information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/axiom-controller/eligibility/axiom-controller-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Axiom Controller's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Cloud-Native
- Logging
- Monitoring
- Observability
- Telemetry
---
