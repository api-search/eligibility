---
api_specs:
- filename: dataforseo-aioptimization-api-openapi.yml
  format: yaml
  label: DataForSEO AiOptimization API
  slug: dataforseo-aioptimization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-aioptimization-api-openapi.yml
- filename: dataforseo-appendix-api-openapi.yml
  format: yaml
  label: DataForSEO Appendix API
  slug: dataforseo-appendix-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-appendix-api-openapi.yml
- filename: dataforseo-backlinks-api-openapi.yml
  format: yaml
  label: DataForSEO Backlinks API
  slug: dataforseo-backlinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-backlinks-api-openapi.yml
- filename: dataforseo-businessdata-api-openapi.yml
  format: yaml
  label: DataForSEO BusinessData API
  slug: dataforseo-businessdata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-businessdata-api-openapi.yml
- filename: dataforseo-dataforseolabs-api-openapi.yml
  format: yaml
  label: DataForSEO DataforseoLabs API
  slug: dataforseo-dataforseolabs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-dataforseolabs-api-openapi.yml
- filename: dataforseo-domainanalytics-api-openapi.yml
  format: yaml
  label: DataForSEO DomainAnalytics API
  slug: dataforseo-domainanalytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-domainanalytics-api-openapi.yml
- filename: dataforseo-keywordsdata-api-openapi.yml
  format: yaml
  label: DataForSEO KeywordsData API
  slug: dataforseo-keywordsdata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-keywordsdata-api-openapi.yml
- filename: dataforseo-merchant-api-openapi.yml
  format: yaml
  label: DataForSEO Merchant API
  slug: dataforseo-merchant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-merchant-api-openapi.yml
- filename: dataforseo-onpage-api-openapi.yml
  format: yaml
  label: DataForSEO OnPage API
  slug: dataforseo-onpage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-onpage-api-openapi.yml
- filename: dataforseo-serp-api-openapi.yml
  format: yaml
  label: DataForSEO Serp API
  slug: dataforseo-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-serp-api-openapi.yml
- filename: dataforseo-app-data-api-openapi.yml
  format: yaml
  label: DataForSEO App Data API
  slug: dataforseo-app-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-app-data-api-openapi.yml
- filename: dataforseo-content-analysis-api-openapi.yml
  format: yaml
  label: DataForSEO Content Analysis API
  slug: dataforseo-content-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforseo/openapi/dataforseo-content-analysis-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - RU
    - BY
    - CU
    - IR
    - SY
    - MM
    - KP
    served: []
    text: 'The access and use of DataForSEO, and the services we offer, are not allowed if you are located, incorporated or otherwise established in, or a resident of, any of the jurisdictions below: Russian Federation Republic of Belarus Cuba Iran Syrian Arab Republic Myanmar Democratic People’s Republic of Korea Crimea Region and Ukrainian territories temporarily occupied by Russian Federation'
  entity_types:
  - text: If You are entering into these Terms on behalf of a company or another legal entity, You represent that You have the authority to bind such entity and its affiliates to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted jurisdictions
    text: The access and use of DataForSEO, and the services we offer, are not allowed if you are located, incorporated or otherwise established in, or a resident of, any of the jurisdictions below
  - summary: No competing with search engines using SERP data
    text: shall not be used to compete with or adversely affect the business interests of the search engine providers from which such data originates.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- RU
- BY
- CU
- IR
- SY
- MM
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DataForSEO
provenance_date: '2026-11-09'
provider_name: DataForSEO
provider_slug: dataforseo
slug: dataforseo-eligibility
source_date: '2026-11-09'
source_filename: dataforseo-eligibility.yml
source_heading: Eligibility
source_page: https://dataforseo.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DataForSEO\naid: dataforseo\nurl: https://dataforseo.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - RU\n  - BY\n  - CU\n  - IR\n  - SY\n  - MM\n  - KP\n  text: 'The access and use of DataForSEO, and the services we offer, are not allowed if you are located, incorporated\n    or otherwise established in, or a resident of, any of the jurisdictions below: Russian Federation Republic of\n    Belarus Cuba Iran Syrian Arab Republic Myanmar Democratic People’s Republic of Korea Crimea Region and Ukrainian\n    territories temporarily occupied by Russian Federation'\nentity_types:\n\
  - type: business\n  text: If You are entering into these Terms on behalf of a company or another legal entity, You represent that\n    You have the authority to bind such entity and its affiliates to these Terms\nrestricted_uses:\n- summary: Restricted jurisdictions\n  text: The access and use of DataForSEO, and the services we offer, are not allowed if you are located, incorporated\n    or otherwise established in, or a resident of, any of the jurisdictions below\n- summary: No competing with search engines using SERP data\n  text: shall not be used to compete with or adversely affect the business interests of the search engine providers\n    from which such data originates.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dataforseo/eligibility/dataforseo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from DataForSEO's own page on 2026-11-09.
synthetic: false
tags:
- SEO
- SERP
- Keywords
- Backlinks
- Domain Analytics
- On-Page SEO
- Competitor Research
- Search Engines
- Content Analysis
- E-Commerce
- App Store
- Business Data
- AI Optimization
- Social Media
---
