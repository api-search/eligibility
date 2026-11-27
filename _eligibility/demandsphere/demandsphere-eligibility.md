---
api_specs:
- filename: demandsphere-keywords-api-openapi.yml
  format: yaml
  label: DemandSphere Keywords API
  slug: demandsphere-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandsphere/openapi/demandsphere-keywords-api-openapi.yml
- filename: demandsphere-pages-api-openapi.yml
  format: yaml
  label: DemandSphere Pages API
  slug: demandsphere-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandsphere/openapi/demandsphere-pages-api-openapi.yml
- filename: demandsphere-searchengines-api-openapi.yml
  format: yaml
  label: DemandSphere SearchEngines API
  slug: demandsphere-searchengines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandsphere/openapi/demandsphere-searchengines-api-openapi.yml
- filename: demandsphere-sites-api-openapi.yml
  format: yaml
  label: DemandSphere Sites API
  slug: demandsphere-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandsphere/openapi/demandsphere-sites-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: The DemandSphere Items may not be downloaded or otherwise provided or made available, either directly or indirectly, (i) in Cuba, Iran, North Korea, Syria, Crimea region of Ukraine, or any other country subject to U.S. trade sanctions
  entity_types:
  - text: If you are entering into this Agreement on behalf of a business or other legal entity, you represent that you have the authority to bind said entity to this Agreement
    type: business
  - text: you are at least 18 years of age and have the capacity and authority to enter into this Agreement
    type: individual
  minimum_age:
    text: you are at least 18 years of age and have the capacity and authority to enter into this Agreement
    value: '18'
  restricted_uses:
  - summary: Sensitive information
    text: You acknowledge that the Services have not been designed to process or manage sensitive information and you agree not to use the Services to collect, manage or process sensitive information.
  - summary: Military end-use in China, Russia, Venezuela
    text: nor will you use the DemandSphere Items for a military end-use or a military end-user in China, Russia or Venezuela.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DemandSphere
provenance_date: '2026-11-09'
provider_name: DemandSphere
provider_slug: demandsphere
slug: demandsphere-eligibility
source_date: '2026-11-09'
source_filename: demandsphere-eligibility.yml
source_heading: Eligibility
source_page: https://www.demandsphere.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DemandSphere\naid: demandsphere\nurl: https://www.demandsphere.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: The DemandSphere Items may not be downloaded or otherwise provided or made available, either directly or\n    indirectly, (i) in Cuba, Iran, North Korea, Syria, Crimea region of Ukraine, or any other country subject to\n    U.S. trade sanctions\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a business or other legal entity, you represent that\n    you have the authority to\
  \ bind said entity to this Agreement\n- type: individual\n  text: you are at least 18 years of age and have the capacity and authority to enter into this Agreement\nrestricted_uses:\n- summary: Sensitive information\n  text: You acknowledge that the Services have not been designed to process or manage sensitive information and\n    you agree not to use the Services to collect, manage or process sensitive information.\n- summary: Military end-use in China, Russia, Venezuela\n  text: nor will you use the DemandSphere Items for a military end-use or a military end-user in China, Russia or\n    Venezuela.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age and have the capacity and authority to enter into this Agreement\n"
source_yaml_url: https://artifacts.apis.io/demandsphere/eligibility/demandsphere-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from DemandSphere's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SEO
- Search Intelligence
- SERP Analytics
- AI Search
- LLM Visibility
- Rank Tracking
- Analytics
- MCP
---
