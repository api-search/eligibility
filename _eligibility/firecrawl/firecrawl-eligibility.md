---
api_specs:
- filename: firecrawl-account-api-openapi.yml
  format: yaml
  label: Firecrawl Account API
  slug: firecrawl-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-account-api-openapi.yml
- filename: firecrawl-agent-api-openapi.yml
  format: yaml
  label: Firecrawl Agent API
  slug: firecrawl-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-agent-api-openapi.yml
- filename: firecrawl-billing-api-openapi.yml
  format: yaml
  label: Firecrawl Billing API
  slug: firecrawl-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-billing-api-openapi.yml
- filename: firecrawl-browser-api-openapi.yml
  format: yaml
  label: Firecrawl Browser API
  slug: firecrawl-browser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-browser-api-openapi.yml
- filename: firecrawl-crawling-api-openapi.yml
  format: yaml
  label: Firecrawl Crawling API
  slug: firecrawl-crawling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-crawling-api-openapi.yml
- filename: firecrawl-extraction-api-openapi.yml
  format: yaml
  label: Firecrawl Extraction API
  slug: firecrawl-extraction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-extraction-api-openapi.yml
- filename: firecrawl-mapping-api-openapi.yml
  format: yaml
  label: Firecrawl Mapping API
  slug: firecrawl-mapping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-mapping-api-openapi.yml
- filename: firecrawl-miscellaneous-api-openapi.yml
  format: yaml
  label: Firecrawl Miscellaneous API
  slug: firecrawl-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-miscellaneous-api-openapi.yml
- filename: firecrawl-scraping-api-openapi.yml
  format: yaml
  label: Firecrawl Scraping API
  slug: firecrawl-scraping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-scraping-api-openapi.yml
- filename: firecrawl-search-api-openapi.yml
  format: yaml
  label: Firecrawl Search API
  slug: firecrawl-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-search-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'you represent and warrant you: (i) have the authority and capacity to enter this Agreement; (ii) are at least 18 years old, or 13 years or older and have the express permission of your parent or guardian'
    type: individual
  minimum_age:
    text: are at least 18 years old, or 13 years or older and have the express permission of your parent or guardian to use the Services
    value: '13'
  restricted_uses:
  - summary: Debt collection
    text: Employing the Services in association with debt collection;
  - summary: Hard background checks
    text: Employing the Services for hard background check purposes;
  - summary: Fair Credit Reporting Act purposes
    text: Using or reselling Services in connection with any purpose covered by the Fair Credit Reporting Act.
  - summary: Law enforcement evidence
    text: Any evidentiary purpose related to law enforcement or criminal prosecution;
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
name: Firecrawl
provenance_date: '2026-11-09'
provider_name: Firecrawl
provider_slug: firecrawl
slug: firecrawl-eligibility
source_date: '2026-11-09'
source_filename: firecrawl-eligibility.yml
source_heading: Eligibility
source_page: https://www.firecrawl.dev/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Firecrawl\naid: firecrawl\nurl: https://www.firecrawl.dev/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'you represent and warrant you: (i) have the authority and capacity to enter this Agreement; (ii) are at\n    least 18 years old, or 13 years or older and have the express permission of your parent or guardian'\nrestricted_uses:\n- summary: Debt collection\n  text: Employing the Services in association with debt collection;\n- summary: Hard background checks\n  text: Employing the Services for hard background check\
  \ purposes;\n- summary: Fair Credit Reporting Act purposes\n  text: Using or reselling Services in connection with any purpose covered by the Fair Credit Reporting Act.\n- summary: Law enforcement evidence\n  text: Any evidentiary purpose related to law enforcement or criminal prosecution;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: are at least 18 years old, or 13 years or older and have the express permission of your parent or guardian\n    to use the Services\n"
source_yaml_url: https://artifacts.apis.io/firecrawl/eligibility/firecrawl-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Firecrawl's own page on 2026-11-09.
synthetic: false
tags:
- Crawling
- Data Extraction
- Web Scraping
- URLs
- Artificial Intelligence
- Markdown
---
