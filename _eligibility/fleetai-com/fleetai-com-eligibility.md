---
api_specs:
- filename: fleetai-com-account-api-openapi.yml
  format: yaml
  label: Fleet Account API
  slug: fleetai-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-account-api-openapi.yml
- filename: fleetai-com-browsers-api-openapi.yml
  format: yaml
  label: Fleet Browsers API
  slug: fleetai-com-browsers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-browsers-api-openapi.yml
- filename: fleetai-com-cost-attribution-api-openapi.yml
  format: yaml
  label: Fleet Cost Attribution API
  slug: fleetai-com-cost-attribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-cost-attribution-api-openapi.yml
- filename: fleetai-com-instances-api-openapi.yml
  format: yaml
  label: Fleet Instances API
  slug: fleetai-com-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-instances-api-openapi.yml
- filename: fleetai-com-jobs-api-openapi.yml
  format: yaml
  label: Fleet Jobs API
  slug: fleetai-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-jobs-api-openapi.yml
- filename: fleetai-com-matg-api-openapi.yml
  format: yaml
  label: Fleet Matg API
  slug: fleetai-com-matg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-matg-api-openapi.yml
- filename: fleetai-com-provenance-audits-api-openapi.yml
  format: yaml
  label: Fleet Provenance Audits API
  slug: fleetai-com-provenance-audits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-provenance-audits-api-openapi.yml
- filename: fleetai-com-seed-gen-api-openapi.yml
  format: yaml
  label: Fleet Seed Gen API
  slug: fleetai-com-seed-gen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-seed-gen-api-openapi.yml
- filename: fleetai-com-seeds-api-openapi.yml
  format: yaml
  label: Fleet Seeds API
  slug: fleetai-com-seeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-seeds-api-openapi.yml
- filename: fleetai-com-sessions-api-openapi.yml
  format: yaml
  label: Fleet Sessions API
  slug: fleetai-com-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-sessions-api-openapi.yml
- filename: fleetai-com-task-groups-api-openapi.yml
  format: yaml
  label: Fleet Task Groups API
  slug: fleetai-com-task-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-task-groups-api-openapi.yml
- filename: fleetai-com-tasks-api-openapi.yml
  format: yaml
  label: Fleet Tasks API
  slug: fleetai-com-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-tasks-api-openapi.yml
- filename: fleetai-com-verifiers-api-openapi.yml
  format: yaml
  label: Fleet Verifiers API
  slug: fleetai-com-verifiers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleetai-com/openapi/fleetai-com-verifiers-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: individual
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated data (HIPAA, FISMA, etc.)
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fleet
provenance_date: '2026-11-09'
provider_name: Fleet
provider_slug: fleetai-com
slug: fleetai-com-eligibility
source_date: '2026-11-09'
source_filename: fleetai-com-eligibility.yml
source_heading: Eligibility
source_page: https://fleetai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fleet\naid: fleetai-com\nurl: https://fleetai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Industry-regulated data (HIPAA, FISMA, etc.)\n  text: The Services\
  \ are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/fleetai-com/eligibility/fleetai-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Fleet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Reinforcement Learning Environments
- Evaluation
- Simulation
- Training Data
---
