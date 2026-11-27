---
api_specs:
- filename: elastic-observability-server-info-api-openapi.yml
  format: yaml
  label: Elastic Observability Server Info API
  slug: elastic-observability-server-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-observability/openapi/elastic-observability-server-info-api-openapi.yml
- filename: elastic-observability-agent-config-api-openapi.yml
  format: yaml
  label: Elastic Observability agent config API
  slug: elastic-observability-agent-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-observability/openapi/elastic-observability-agent-config-api-openapi.yml
- filename: elastic-observability-event-intake-api-openapi.yml
  format: yaml
  label: Elastic Observability event intake API
  slug: elastic-observability-event-intake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-observability/openapi/elastic-observability-event-intake-api-openapi.yml
- filename: elastic-observability-opentelemetry-intake-api-openapi.yml
  format: yaml
  label: Elastic Observability opentelemetry intake API
  slug: elastic-observability-opentelemetry-intake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-observability/openapi/elastic-observability-opentelemetry-intake-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    - BY
    served: []
    text: 'No Elastic products or service may be sold, exported or re-exported, to an individual or entity located in an embargoed country... Such prohibition includes the following countries: Cuba, Iran, North Korea, Syria, Russia, Belarus, and the Crimea, Luhansk, and Donetsk regions of Ukraine.'
  entity_types:
  - text: If you are accessing or using the Site on behalf of a corporation, organization or other entity, you represent and warrant that you have the legal authority to agree to these terms on behalf of such organization
    type: business
  - text: This website and all associated content, software, discussion forums, products, and services are intended for professional use only. No consumer use of this website or its content is intended or directed.
    type: individual
  minimum_age:
    text: By using the Site, you represent and warrant that you are 18 years of age or older. If you are under the age of 13 years old, you may not use the Site.
    value: '18'
  restricted_uses:
  - summary: Export-restricted use
    text: you are not located in, under the control of, or a national or resident of, any country to which the United States has embargoed goods.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Elastic Observability
provenance_date: '2026-11-09'
provider_name: Elastic Observability
provider_slug: elastic-observability
slug: elastic-observability-eligibility
source_date: '2026-11-09'
source_filename: elastic-observability-eligibility.yml
source_heading: Eligibility
source_page: https://www.elastic.co/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elastic Observability\naid: elastic-observability\nurl: https://www.elastic.co/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  - BY\n  text: 'No Elastic products or service may be sold, exported or re-exported, to an individual or entity located\n    in an embargoed country... Such prohibition includes the following countries: Cuba, Iran, North Korea, Syria,\n    Russia, Belarus, and the Crimea, Luhansk, and Donetsk regions of Ukraine.'\nentity_types:\n- type: business\n  text: If you are accessing or using the Site on behalf of a\
  \ corporation, organization or other entity, you represent\n    and warrant that you have the legal authority to agree to these terms on behalf of such organization\n- type: individual\n  text: This website and all associated content, software, discussion forums, products, and services are intended\n    for professional use only. No consumer use of this website or its content is intended or directed.\nrestricted_uses:\n- summary: Export-restricted use\n  text: you are not located in, under the control of, or a national or resident of, any country to which the United\n    States has embargoed goods.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Site, you represent and warrant that you are 18 years of age or older. If you are under the\n    age of 13 years old, you may not use the Site.\n"
source_yaml_url: https://artifacts.apis.io/elastic-observability/eligibility/elastic-observability-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Elastic Observability's own page on 2026-11-09.
synthetic: false
tags:
- AIOps
- Observability
- APM
- Logging
- Metrics
- Tracing
- OpenTelemetry
- Monitoring
- Telemetry
---
