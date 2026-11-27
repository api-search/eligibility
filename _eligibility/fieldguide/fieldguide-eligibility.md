---
api_specs:
- filename: fieldguide-comments-api-openapi.yml
  format: yaml
  label: Fieldguide Comments API
  slug: fieldguide-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-comments-api-openapi.yml
- filename: fieldguide-companies-api-openapi.yml
  format: yaml
  label: Fieldguide Companies API
  slug: fieldguide-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-companies-api-openapi.yml
- filename: fieldguide-controls-api-openapi.yml
  format: yaml
  label: Fieldguide Controls API
  slug: fieldguide-controls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-controls-api-openapi.yml
- filename: fieldguide-engagements-api-openapi.yml
  format: yaml
  label: Fieldguide Engagements API
  slug: fieldguide-engagements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-engagements-api-openapi.yml
- filename: fieldguide-files-api-openapi.yml
  format: yaml
  label: Fieldguide Files API
  slug: fieldguide-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-files-api-openapi.yml
- filename: fieldguide-insights-api-openapi.yml
  format: yaml
  label: Fieldguide Insights API
  slug: fieldguide-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-insights-api-openapi.yml
- filename: fieldguide-jobs-api-openapi.yml
  format: yaml
  label: Fieldguide Jobs API
  slug: fieldguide-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-jobs-api-openapi.yml
- filename: fieldguide-milestones-api-openapi.yml
  format: yaml
  label: Fieldguide Milestones API
  slug: fieldguide-milestones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-milestones-api-openapi.yml
- filename: fieldguide-requests-api-openapi.yml
  format: yaml
  label: Fieldguide Requests API
  slug: fieldguide-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-requests-api-openapi.yml
- filename: fieldguide-sheet-columns-api-openapi.yml
  format: yaml
  label: Fieldguide Sheet Columns API
  slug: fieldguide-sheet-columns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-sheet-columns-api-openapi.yml
- filename: fieldguide-sheet-rows-api-openapi.yml
  format: yaml
  label: Fieldguide Sheet Rows API
  slug: fieldguide-sheet-rows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-sheet-rows-api-openapi.yml
- filename: fieldguide-sheets-api-openapi.yml
  format: yaml
  label: Fieldguide Sheets API
  slug: fieldguide-sheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-sheets-api-openapi.yml
- filename: fieldguide-users-api-openapi.yml
  format: yaml
  label: Fieldguide Users API
  slug: fieldguide-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-users-api-openapi.yml
- filename: fieldguide-webhooks-api-openapi.yml
  format: yaml
  label: Fieldguide Webhooks API
  slug: fieldguide-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-webhooks-api-openapi.yml
- filename: fieldguide-scopes-api-openapi.yml
  format: yaml
  label: Fieldguide Scopes API
  slug: fieldguide-scopes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-scopes-api-openapi.yml
- filename: fieldguide-token-api-openapi.yml
  format: yaml
  label: Fieldguide Token API
  slug: fieldguide-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fieldguide/openapi/fieldguide-token-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity (“you”)
    type: business
  minimum_age:
    text: The Services is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Competing or revenue-generating use
    text: Use the Services as part of any effort to compete with us or otherwise use the Services and/or the Content for any revenue-generating endeavor or commercial enterprise.
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
name: Fieldguide
provenance_date: '2026-11-09'
provider_name: Fieldguide
provider_slug: fieldguide
slug: fieldguide-eligibility
source_date: '2026-11-09'
source_filename: fieldguide-eligibility.yml
source_heading: Eligibility
source_page: https://www.fieldguide.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fieldguide\naid: fieldguide\nurl: https://www.fieldguide.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Services is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: Competing or revenue-generating use\n  text: Use the Services as part of any effort to compete with us or otherwise use the Services\
  \ and/or the Content\n    for any revenue-generating endeavor or commercial enterprise.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/fieldguide/eligibility/fieldguide-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Fieldguide's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Audit
- Advisory
- Accounting
- Compliance
- Risk Management
- Engagement Management
- Artificial Intelligence
- Agents
- Webhook
---
