---
api_specs:
- filename: cloudchipr-accounts-api-openapi.yml
  format: yaml
  label: CloudChipr Accounts API
  slug: cloudchipr-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudchipr/openapi/cloudchipr-accounts-api-openapi.yml
- filename: cloudchipr-budgets-api-openapi.yml
  format: yaml
  label: CloudChipr Budgets API
  slug: cloudchipr-budgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudchipr/openapi/cloudchipr-budgets-api-openapi.yml
- filename: cloudchipr-categories-api-openapi.yml
  format: yaml
  label: CloudChipr Categories API
  slug: cloudchipr-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudchipr/openapi/cloudchipr-categories-api-openapi.yml
- filename: cloudchipr-custom-data-api-openapi.yml
  format: yaml
  label: CloudChipr Custom Data API
  slug: cloudchipr-custom-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudchipr/openapi/cloudchipr-custom-data-api-openapi.yml
- filename: cloudchipr-dashboards-api-openapi.yml
  format: yaml
  label: CloudChipr Dashboards API
  slug: cloudchipr-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudchipr/openapi/cloudchipr-dashboards-api-openapi.yml
- filename: cloudchipr-filters-api-openapi.yml
  format: yaml
  label: CloudChipr Filters API
  slug: cloudchipr-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudchipr/openapi/cloudchipr-filters-api-openapi.yml
- filename: cloudchipr-regions-api-openapi.yml
  format: yaml
  label: CloudChipr Regions API
  slug: cloudchipr-regions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudchipr/openapi/cloudchipr-regions-api-openapi.yml
- filename: cloudchipr-resource-explorer-api-openapi.yml
  format: yaml
  label: CloudChipr Resource Explorer API
  slug: cloudchipr-resource-explorer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudchipr/openapi/cloudchipr-resource-explorer-api-openapi.yml
- filename: cloudchipr-resources-api-openapi.yml
  format: yaml
  label: CloudChipr Resources API
  slug: cloudchipr-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudchipr/openapi/cloudchipr-resources-api-openapi.yml
- filename: cloudchipr-savings-opportunities-api-openapi.yml
  format: yaml
  label: CloudChipr Savings Opportunities API
  slug: cloudchipr-savings-opportunities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudchipr/openapi/cloudchipr-savings-opportunities-api-openapi.yml
- filename: cloudchipr-widgets-api-openapi.yml
  format: yaml
  label: CloudChipr Widgets API
  slug: cloudchipr-widgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudchipr/openapi/cloudchipr-widgets-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity (“you”)
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Industry-specific regulated data
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: GLBA
    text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CloudChipr
provenance_date: '2026-11-09'
provider_name: CloudChipr
provider_slug: cloudchipr
slug: cloudchipr-eligibility
source_date: '2026-11-09'
source_filename: cloudchipr-eligibility.yml
source_heading: Eligibility
source_page: https://cloudchipr.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CloudChipr\naid: cloudchipr\nurl: https://cloudchipr.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: Industry-specific regulated data\n  text: The Site is not tailored to comply with industry-specific regulations\
  \ (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: GLBA\n  text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Site.\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/cloudchipr/eligibility/cloudchipr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from CloudChipr's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Microsoft Azure
- Cloud Cost Management
- Cost Optimization
- FinOps
- GCP
- Multi-Cloud
- Resource Cleanup
- Rightsizing
---
