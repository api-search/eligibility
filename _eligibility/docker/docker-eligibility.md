---
api_specs:
- filename: docker-config-api-openapi.yml
  format: yaml
  label: Docker Config API
  slug: docker-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-config-api-openapi.yml
- filename: docker-container-api-openapi.yml
  format: yaml
  label: Docker Container API
  slug: docker-container-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-container-api-openapi.yml
- filename: docker-distribution-api-openapi.yml
  format: yaml
  label: Docker Distribution API
  slug: docker-distribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-distribution-api-openapi.yml
- filename: docker-exec-api-openapi.yml
  format: yaml
  label: Docker Exec API
  slug: docker-exec-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-exec-api-openapi.yml
- filename: docker-image-api-openapi.yml
  format: yaml
  label: Docker Image API
  slug: docker-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-image-api-openapi.yml
- filename: docker-network-api-openapi.yml
  format: yaml
  label: Docker Network API
  slug: docker-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-network-api-openapi.yml
- filename: docker-node-api-openapi.yml
  format: yaml
  label: Docker Node API
  slug: docker-node-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-node-api-openapi.yml
- filename: docker-plugin-api-openapi.yml
  format: yaml
  label: Docker Plugin API
  slug: docker-plugin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-plugin-api-openapi.yml
- filename: docker-secret-api-openapi.yml
  format: yaml
  label: Docker Secret API
  slug: docker-secret-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-secret-api-openapi.yml
- filename: docker-service-api-openapi.yml
  format: yaml
  label: Docker Service API
  slug: docker-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-service-api-openapi.yml
- filename: docker-session-api-openapi.yml
  format: yaml
  label: Docker Session API
  slug: docker-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-session-api-openapi.yml
- filename: docker-swarm-api-openapi.yml
  format: yaml
  label: Docker Swarm API
  slug: docker-swarm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-swarm-api-openapi.yml
- filename: docker-system-api-openapi.yml
  format: yaml
  label: Docker System API
  slug: docker-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-system-api-openapi.yml
- filename: docker-task-api-openapi.yml
  format: yaml
  label: Docker Task API
  slug: docker-task-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-task-api-openapi.yml
- filename: docker-volume-api-openapi.yml
  format: yaml
  label: Docker Volume API
  slug: docker-volume-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docker/openapi/docker-volume-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years of age to access or use the Services.
    type: individual
  - text: If you are using the Services on behalf of an entity, you represent that you have authority to bind that entity
    type: business
  minimum_age:
    text: You must be at least 13 years of age to access or use the Services.
    value: '13'
  restricted_uses:
  - summary: High-risk activities
    text: THE WEBSITE, SERVICES, DOCKER HUB, DOCKER IMAGES, AI FEATURES, AND OUTPUT ARE NOT DESIGNED OR CERTIFIED FOR USE IN HIGH-RISK ACTIVITIES
  - summary: Denied parties
    text: You may not use the Services if you are listed on any U.S. Government Denied Party, Denied Person, or Specially Designated Nationals list
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
name: Docker
provenance_date: '2026-11-09'
provider_name: Docker
provider_slug: docker
slug: docker-eligibility
source_date: '2026-11-09'
source_filename: docker-eligibility.yml
source_heading: Eligibility
source_page: https://www.docker.com/legal/docker-terms-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Docker\naid: docker\nurl: https://www.docker.com/legal/docker-terms-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to access or use the Services.\n- type: business\n  text: If you are using the Services on behalf of an entity, you represent that you have authority to bind that\n    entity\nrestricted_uses:\n- summary: High-risk activities\n  text: THE WEBSITE, SERVICES, DOCKER HUB, DOCKER IMAGES, AI FEATURES, AND OUTPUT ARE NOT DESIGNED OR CERTIFIED\n    FOR USE IN HIGH-RISK ACTIVITIES\n-\
  \ summary: Denied parties\n  text: You may not use the Services if you are listed on any U.S. Government Denied Party, Denied Person, or Specially\n    Designated Nationals list\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to access or use the Services.\n"
source_yaml_url: https://artifacts.apis.io/docker/eligibility/docker-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Docker's own page on 2026-11-09.
synthetic: false
tags:
- Cloud
- Containers
- Developer Tools
- DevOps
- Infrastructure
- Microservices
- Docker
---
