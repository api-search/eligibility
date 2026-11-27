---
api_specs:
- filename: pluralsight-catalog-api-openapi.yml
  format: yaml
  label: Pluralsight Catalog API
  slug: pluralsight-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-catalog-api-openapi.yml
- filename: pluralsight-coding-metrics-api-openapi.yml
  format: yaml
  label: Pluralsight Coding Metrics API
  slug: pluralsight-coding-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-coding-metrics-api-openapi.yml
- filename: pluralsight-collaboration-metrics-api-openapi.yml
  format: yaml
  label: Pluralsight Collaboration Metrics API
  slug: pluralsight-collaboration-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-collaboration-metrics-api-openapi.yml
- filename: pluralsight-commits-api-openapi.yml
  format: yaml
  label: Pluralsight Commits API
  slug: pluralsight-commits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-commits-api-openapi.yml
- filename: pluralsight-dora-metrics-api-openapi.yml
  format: yaml
  label: Pluralsight DORA Metrics API
  slug: pluralsight-dora-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-dora-metrics-api-openapi.yml
- filename: pluralsight-integrations-api-openapi.yml
  format: yaml
  label: Pluralsight Integrations API
  slug: pluralsight-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-integrations-api-openapi.yml
- filename: pluralsight-licensing-api-openapi.yml
  format: yaml
  label: Pluralsight Licensing API
  slug: pluralsight-licensing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-licensing-api-openapi.yml
- filename: pluralsight-pull-requests-api-openapi.yml
  format: yaml
  label: Pluralsight Pull Requests API
  slug: pluralsight-pull-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-pull-requests-api-openapi.yml
- filename: pluralsight-reports-api-openapi.yml
  format: yaml
  label: Pluralsight Reports API
  slug: pluralsight-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-reports-api-openapi.yml
- filename: pluralsight-repos-api-openapi.yml
  format: yaml
  label: Pluralsight Repos API
  slug: pluralsight-repos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-repos-api-openapi.yml
- filename: pluralsight-tickets-api-openapi.yml
  format: yaml
  label: Pluralsight Tickets API
  slug: pluralsight-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-tickets-api-openapi.yml
- filename: pluralsight-users-api-openapi.yml
  format: yaml
  label: Pluralsight Users API
  slug: pluralsight-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-users-api-openapi.yml
- filename: pluralsight-graph-ql-api-openapi.yml
  format: yaml
  label: Pluralsight Graph QL API
  slug: pluralsight-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pluralsight/openapi/pluralsight-graph-ql-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. We make no representation that the Site is appropriate or available for use outside of the United States.
  entity_types:
  - text: solely for your personal use
    type: individual
  - text: If you are accessing the Site on behalf of an entity, organization, or company, then (a) “you” will refer to that entity, organization, or company
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal use
    text: use the Site for any illegal purpose or in violation of any local, state, national, or international law
  - summary: Automated scraping
    text: use, or permit or facilitate others to use, the Site by automated electronic processes, “robots,” “spiders,” “scrapers,” “webcrawlers,” or other computer programs
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
name: Pluralsight
provenance_date: '2026-11-10'
provider_name: Pluralsight
provider_slug: pluralsight
slug: pluralsight-eligibility
source_date: '2026-11-10'
source_filename: pluralsight-eligibility.yml
source_heading: Eligibility
source_page: https://legal.pluralsight.com/policies
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pluralsight\naid: pluralsight\nurl: https://legal.pluralsight.com/policies\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. We make no representation that the Site\n    is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: solely for your personal use\n- type: business\n  text: If you are accessing the Site on behalf of an entity, organization, or company, then (a) “you” will refer\n    to that entity, organization, or company\nrestricted_uses:\n- summary:\
  \ Illegal use\n  text: use the Site for any illegal purpose or in violation of any local, state, national, or international law\n- summary: Automated scraping\n  text: use, or permit or facilitate others to use, the Site by automated electronic processes, “robots,” “spiders,”\n    “scrapers,” “webcrawlers,” or other computer programs\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pluralsight/eligibility/pluralsight-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Pluralsight's own page on 2026-11-10.
synthetic: false
tags:
- Courses
- Education
- Engineering Metrics
- Learning
- Skills Assessment
- Technology
- Video Training
---
