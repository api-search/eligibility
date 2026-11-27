---
api_specs:
- filename: power-query-items-api-openapi.yml
  format: yaml
  label: Power Query Items API
  slug: power-query-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/power-query/openapi/power-query-items-api-openapi.yml
- filename: power-query-background-jobs-api-openapi.yml
  format: yaml
  label: Power Query Background Jobs API
  slug: power-query-background-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/power-query/openapi/power-query-background-jobs-api-openapi.yml
- filename: power-query-query-execution-api-openapi.yml
  format: yaml
  label: Power Query Query Execution API
  slug: power-query-query-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/power-query/openapi/power-query-query-execution-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By creating a Microsoft account or using the Services, you accept and agree to be bound by these Terms and represent that you have either reached the age of majority where you live or your parent or legal guardian agrees to be bound by these Terms on your behalf.
    type: individual
  - text: If you create a Microsoft account on behalf of an entity, such as your business or employer, you represent that you have the legal authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: represent that you have either reached the age of majority where you live or your parent or legal guardian agrees to be bound by these Terms on your behalf
    value: null
  restricted_uses:
  - summary: XBOX services personal use only
    text: are only for your personal and noncommercial use
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
name: Power Query
provenance_date: '2026-11-10'
provider_name: Power Query
provider_slug: power-query
slug: power-query-eligibility
source_date: '2026-11-10'
source_filename: power-query-eligibility.yml
source_heading: Eligibility
source_page: https://www.microsoft.com/en-us/servicesagreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Power Query\naid: power-query\nurl: https://www.microsoft.com/en-us/servicesagreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By creating a Microsoft account or using the Services, you accept and agree to be bound by these Terms and\n    represent that you have either reached the age of majority where you live or your parent or legal guardian agrees\n    to be bound by these Terms on your behalf.\n- type: business\n  text: If you create a Microsoft account on behalf of an entity, such as your business or\
  \ employer, you represent\n    that you have the legal authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: XBOX services personal use only\n  text: are only for your personal and noncommercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: represent that you have either reached the age of majority where you live or your parent or legal guardian\n    agrees to be bound by these Terms on your behalf\n"
source_yaml_url: https://artifacts.apis.io/power-query/eligibility/power-query-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Power Query's own page on 2026-11-10.
synthetic: false
tags:
- Business Intelligence
- Data Integration
- Data Transformation
- ETL
- Microsoft
- Microsoft Fabric
- Power BI
- Dataflows
- M Language
- Data Connectors
- Self-Service ETL
---
