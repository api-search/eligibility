---
api_specs:
- filename: amika-api-keys-api-openapi.yml
  format: yaml
  label: Amika API keys API
  slug: amika-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-api-keys-api-openapi.yml
- filename: amika-docker-registries-api-openapi.yml
  format: yaml
  label: Amika Docker registries API
  slug: amika-docker-registries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-docker-registries-api-openapi.yml
- filename: amika-downloads-api-openapi.yml
  format: yaml
  label: Amika Downloads API
  slug: amika-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-downloads-api-openapi.yml
- filename: amika-git-user-settings-api-openapi.yml
  format: yaml
  label: Amika Git user settings API
  slug: amika-git-user-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-git-user-settings-api-openapi.yml
- filename: amika-integrations-api-openapi.yml
  format: yaml
  label: Amika Integrations API
  slug: amika-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-integrations-api-openapi.yml
- filename: amika-repositories-api-openapi.yml
  format: yaml
  label: Amika Repositories API
  slug: amika-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-repositories-api-openapi.yml
- filename: amika-sandboxes-api-openapi.yml
  format: yaml
  label: Amika Sandboxes API
  slug: amika-sandboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-sandboxes-api-openapi.yml
- filename: amika-sandboxsnapshots-api-openapi.yml
  format: yaml
  label: Amika SandboxSnapshots API
  slug: amika-sandboxsnapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-sandboxsnapshots-api-openapi.yml
- filename: amika-secrets-api-openapi.yml
  format: yaml
  label: Amika Secrets API
  slug: amika-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-secrets-api-openapi.yml
- filename: amika-services-api-openapi.yml
  format: yaml
  label: Amika Services API
  slug: amika-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-services-api-openapi.yml
- filename: amika-slack-api-openapi.yml
  format: yaml
  label: Amika Slack API
  slug: amika-slack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-slack-api-openapi.yml
- filename: amika-uploads-api-openapi.yml
  format: yaml
  label: Amika Uploads API
  slug: amika-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-uploads-api-openapi.yml
- filename: amika-agentsessions-api-openapi.yml
  format: yaml
  label: Amika Agent Sessions API
  slug: amika-agentsessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-agentsessions-api-openapi.yml
- filename: amika-hosts-api-openapi.yml
  format: yaml
  label: Amika Hosts API
  slug: amika-hosts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-hosts-api-openapi.yml
- filename: amika-linear-api-openapi.yml
  format: yaml
  label: Amika Linear API
  slug: amika-linear-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-linear-api-openapi.yml
- filename: amika-meta-api-openapi.yml
  format: yaml
  label: Amika Meta API
  slug: amika-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-meta-api-openapi.yml
- filename: amika-sandboxbindings-api-openapi.yml
  format: yaml
  label: Amika Sandbox Bindings API
  slug: amika-sandboxbindings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-sandboxbindings-api-openapi.yml
- filename: amika-sandboxservices-api-openapi.yml
  format: yaml
  label: Amika Sandbox Services API
  slug: amika-sandboxservices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amika/openapi/amika-sandboxservices-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Agreement is between Fixpoint, Inc. and the company or person accessing or using the Product.
    type: individual
  - text: If the person accepting this Agreement is doing so on behalf of a company, all use of the word "Customer" in the Agreement will mean that company.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Amika
provenance_date: '2026-11-09'
provider_name: Amika
provider_slug: amika
slug: amika-eligibility
source_date: '2026-11-09'
source_filename: amika-eligibility.yml
source_heading: Eligibility
source_page: https://www.amika.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amika\naid: amika\nurl: https://www.amika.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Agreement is between Fixpoint, Inc. and the company or person accessing or using the Product.\n- type: business\n  text: If the person accepting this Agreement is doing so on behalf of a company, all use of the word \"Customer\"\n    in the Agreement will mean that company.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amika/eligibility/amika-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Amika's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Coding Agents
- Developer Tools
- Sandbox
- Infrastructure
- CI/CD
- Automation
- SoftwareFactory
---
