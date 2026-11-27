---
api_specs:
- filename: thordata-locations-api-openapi.yml
  format: yaml
  label: Thordata Locations API
  slug: thordata-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-locations-api-openapi.yml
- filename: thordata-proxy-extract-api-openapi.yml
  format: yaml
  label: Thordata Proxy IP Extract API
  slug: thordata-proxy-ip-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-proxy-extract-api-openapi.yml
- filename: thordata-account-api-openapi.yml
  format: yaml
  label: Thordata Account API
  slug: thordata-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-account-api-openapi.yml
- filename: thordata-proxy-api-openapi.yml
  format: yaml
  label: Thordata Proxy API
  slug: thordata-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-proxy-api-openapi.yml
- filename: thordata-proxy-users-api-openapi.yml
  format: yaml
  label: Thordata Proxy Users API
  slug: thordata-proxy-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-proxy-users-api-openapi.yml
- filename: thordata-serp-api-api-openapi.yml
  format: yaml
  label: Thordata SERP API
  slug: thordata-serp-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-serp-api-api-openapi.yml
- filename: thordata-tasks-api-openapi.yml
  format: yaml
  label: Thordata Tasks API
  slug: thordata-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-tasks-api-openapi.yml
- filename: thordata-web-scraper-api-api-openapi.yml
  format: yaml
  label: Thordata Web Scraper API
  slug: thordata-web-scraper-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-web-scraper-api-api-openapi.yml
- filename: thordata-whitelist-api-openapi.yml
  format: yaml
  label: Thordata Whitelist API
  slug: thordata-whitelist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-whitelist-api-openapi.yml
- filename: thordata-public-api-api-openapi.yml
  format: yaml
  label: Thordata Public API
  slug: thordata-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-public-api-api-openapi.yml
- filename: thordata-universal-api-api-openapi.yml
  format: yaml
  label: Thordata Universal API
  slug: thordata-universal-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-universal-api-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Accounts can be created for personal and business use by natural persons
    type: individual
  - text: legal entities represented by natural persons
    type: business
  minimum_age:
    text: the Services may only be used by individuals who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Violating applicable laws
    text: Customer shall not use the Services in violation of applicable laws or regulations or any third party rights (including intellectual property rights)
  - summary: Sharing account credentials
    text: The Account is for own use only and cannot be used to use the Services on behalf of other individuals or entities.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Certain Services will be provided after Thordata has successfully completed the Customer's compliance review process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Thordata
provenance_date: '2026-11-10'
provider_name: Thordata
provider_slug: thordata
slug: thordata-eligibility
source_date: '2026-11-10'
source_filename: thordata-eligibility.yml
source_heading: Eligibility
source_page: https://www.thordata.com/service-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thordata\naid: thordata\nurl: https://www.thordata.com/service-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Accounts can be created for personal and business use by natural persons\n- type: business\n  text: legal entities represented by natural persons\nrestricted_uses:\n- summary: Violating applicable laws\n  text: Customer shall not use the Services in violation of applicable laws or regulations or any third party rights\n    (including intellectual property rights)\n- summary: Sharing account credentials\n  text: The\
  \ Account is for own use only and cannot be used to use the Services on behalf of other individuals or\n    entities.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Certain Services will be provided after Thordata has successfully completed the Customer's compliance review\n    process.\nminimum_age:\n  value: '18'\n  text: the Services may only be used by individuals who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/thordata/eligibility/thordata-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Thordata's own page on 2026-11-10.
synthetic: false
tags:
- Proxy Network
- Web Scraping
- Data Extraction
- SERP
- Search data
- Web unblocking
- Residential Proxies
- Mobile Proxies
- ISP Proxies
- Datacenter Proxies
- Scraping Browser
- Data-for-AI
- RAG data pipelines
- Web Data
---
