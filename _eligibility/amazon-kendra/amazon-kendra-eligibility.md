---
api_specs:
- filename: amazon-kendra-data-sources-api-openapi.yml
  format: yaml
  label: Amazon Kendra Data Sources API
  slug: amazon-kendra-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-data-sources-api-openapi.yml
- filename: amazon-kendra-documents-api-openapi.yml
  format: yaml
  label: Amazon Kendra Documents API
  slug: amazon-kendra-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-documents-api-openapi.yml
- filename: amazon-kendra-experience-api-openapi.yml
  format: yaml
  label: Amazon Kendra Experience API
  slug: amazon-kendra-experience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-experience-api-openapi.yml
- filename: amazon-kendra-indexes-api-openapi.yml
  format: yaml
  label: Amazon Kendra Indexes API
  slug: amazon-kendra-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-indexes-api-openapi.yml
- filename: amazon-kendra-queries-api-openapi.yml
  format: yaml
  label: Amazon Kendra Queries API
  slug: amazon-kendra-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-queries-api-openapi.yml
- filename: amazon-kendra-query-suggestions-api-openapi.yml
  format: yaml
  label: Amazon Kendra Query Suggestions API
  slug: amazon-kendra-query-suggestions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-query-suggestions-api-openapi.yml
- filename: amazon-kendra-thesaurus-api-openapi.yml
  format: yaml
  label: Amazon Kendra Thesaurus API
  slug: amazon-kendra-thesaurus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-thesaurus-api-openapi.yml
- filename: amazon-kendra-faqs-api-openapi.yml
  format: yaml
  label: Amazon Kendra FA Qs API
  slug: amazon-kendra-faqs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-faqs-api-openapi.yml
- filename: amazon-kendra-access-control-configuration-api-openapi.yml
  format: yaml
  label: Amazon Kendra Kendra Access Control Configuration API
  slug: amazon-kendra-access-control-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-access-control-configuration-api-openapi.yml
- filename: amazon-kendra-data-source-sync-job-api-openapi.yml
  format: yaml
  label: Amazon Kendra Kendra Data Source Sync Job API
  slug: amazon-kendra-data-source-sync-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-data-source-sync-job-api-openapi.yml
- filename: amazon-kendra-featured-results-set-api-openapi.yml
  format: yaml
  label: Amazon Kendra Kendra Featured Results Set API
  slug: amazon-kendra-featured-results-set-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-featured-results-set-api-openapi.yml
- filename: amazon-kendra-operations-api-openapi.yml
  format: yaml
  label: Amazon Kendra Kendra Operations API
  slug: amazon-kendra-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-operations-api-openapi.yml
- filename: amazon-kendra-principal-mapping-api-openapi.yml
  format: yaml
  label: Amazon Kendra Kendra Principal Mapping API
  slug: amazon-kendra-principal-mapping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-principal-mapping-api-openapi.yml
- filename: amazon-kendra-query-suggestions-block-list-api-openapi.yml
  format: yaml
  label: Amazon Kendra Kendra Query Suggestions Block List API
  slug: amazon-kendra-query-suggestions-block-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-query-suggestions-block-list-api-openapi.yml
- filename: amazon-kendra-rescore-execution-plan-api-openapi.yml
  format: yaml
  label: Amazon Kendra Kendra Rescore Execution Plan API
  slug: amazon-kendra-rescore-execution-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-kendra/openapi/amazon-kendra-rescore-execution-plan-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spend limits not for critical systems
    text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of any hazardous environments or critical systems, any regulated content (such as protected health information), government data, or any content of government entities.
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
name: Amazon Kendra
provenance_date: '2026-11-09'
provider_name: Amazon Kendra
provider_slug: amazon-kendra
slug: amazon-kendra-eligibility
source_date: '2026-11-09'
source_filename: amazon-kendra-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon Kendra\naid: amazon-kendra\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spend limits not for critical systems\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems, any regulated content (such as protected health information),\n    government data, or any content of government entities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-kendra/eligibility/amazon-kendra-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Amazon Kendra's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Amazon Web Services
- Enterprise Search
- Knowledge Management
- Machine Learning
- Natural-Language
- Search
---
