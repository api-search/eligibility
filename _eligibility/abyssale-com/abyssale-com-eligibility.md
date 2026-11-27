---
api_specs:
- filename: abyssale-com-auth-api-openapi.yml
  format: yaml
  label: Abyssale Auth API
  slug: abyssale-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-auth-api-openapi.yml
- filename: abyssale-com-credits-api-openapi.yml
  format: yaml
  label: Abyssale Credits API
  slug: abyssale-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-credits-api-openapi.yml
- filename: abyssale-com-design-duplication-requests-api-openapi.yml
  format: yaml
  label: Abyssale Design Duplication Requests API
  slug: abyssale-com-design-duplication-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-design-duplication-requests-api-openapi.yml
- filename: abyssale-com-designs-api-openapi.yml
  format: yaml
  label: Abyssale Designs API
  slug: abyssale-com-designs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-designs-api-openapi.yml
- filename: abyssale-com-examples-api-openapi.yml
  format: yaml
  label: Abyssale Examples API
  slug: abyssale-com-examples-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-examples-api-openapi.yml
- filename: abyssale-com-export-abyssale-api-openapi.yml
  format: yaml
  label: Abyssale Export Abyssale API
  slug: abyssale-com-export-abyssale-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-export-abyssale-api-openapi.yml
- filename: abyssale-com-fonts-api-openapi.yml
  format: yaml
  label: Abyssale Fonts API
  slug: abyssale-com-fonts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-fonts-api-openapi.yml
- filename: abyssale-com-images-api-openapi.yml
  format: yaml
  label: Abyssale Images API
  slug: abyssale-com-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-images-api-openapi.yml
- filename: abyssale-com-projects-api-openapi.yml
  format: yaml
  label: Abyssale Projects API
  slug: abyssale-com-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-projects-api-openapi.yml
- filename: abyssale-com-workspace-template-categories-api-openapi.yml
  format: yaml
  label: Abyssale Workspace Template Categories API
  slug: abyssale-com-workspace-template-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-workspace-template-categories-api-openapi.yml
- filename: abyssale-com-workspace-templates-api-openapi.yml
  format: yaml
  label: Abyssale Workspace Templates API
  slug: abyssale-com-workspace-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-workspace-templates-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual Client who will also be a User
    type: individual
  - text: a legal entity Client, who subscribes to the Platform for one or more Users according to the chosen Subscription plan.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal or infringing content
    text: The Client undertakes to only load and process via the Platform strictly legal Client Content.
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
name: Abyssale
provenance_date: '2026-11-09'
provider_name: Abyssale
provider_slug: abyssale-com
slug: abyssale-com-eligibility
source_date: '2026-11-09'
source_filename: abyssale-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.abyssale.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Abyssale\naid: abyssale-com\nurl: https://www.abyssale.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual Client who will also be a User\n- type: business\n  text: a legal entity Client, who subscribes to the Platform for one or more Users according to the chosen Subscription\n    plan.\nrestricted_uses:\n- summary: No illegal or infringing content\n  text: The Client undertakes to only load and process via the Platform strictly legal Client Content.\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/abyssale-com/eligibility/abyssale-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Abyssale's own page on 2026-11-09.
synthetic: false
tags:
- Creative Automation
- Marketing
- Agencies
- Visual-Production
- Software-as-a-Service
---
