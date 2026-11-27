---
api_specs:
- filename: trueproxies-analytics-api-openapi.yml
  format: yaml
  label: TrueProxies Analytics API
  slug: trueproxies-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trueproxies/openapi/trueproxies-analytics-api-openapi.yml
- filename: trueproxies-catalog-api-openapi.yml
  format: yaml
  label: TrueProxies Catalog API
  slug: trueproxies-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trueproxies/openapi/trueproxies-catalog-api-openapi.yml
- filename: trueproxies-invoices-api-openapi.yml
  format: yaml
  label: TrueProxies Invoices API
  slug: trueproxies-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trueproxies/openapi/trueproxies-invoices-api-openapi.yml
- filename: trueproxies-me-api-openapi.yml
  format: yaml
  label: TrueProxies Me API
  slug: trueproxies-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trueproxies/openapi/trueproxies-me-api-openapi.yml
- filename: trueproxies-services-api-openapi.yml
  format: yaml
  label: TrueProxies Services API
  slug: trueproxies-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trueproxies/openapi/trueproxies-services-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use TrueProxies.
    type: individual
  - text: If you are using the Services on behalf of a company or organization, you represent that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use TrueProxies.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: The Services are intended solely for lawful purposes.
  - source: https://trueproxies.com/acceptable-use/
    summary: Proxy detection tools
    text: Using the Services to build, support, or enrich proxy detection or classification tools
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
name: TrueProxies
provenance_date: '2026-11-10'
provider_name: TrueProxies
provider_slug: trueproxies
slug: trueproxies-eligibility
source_date: '2026-11-10'
source_filename: trueproxies-eligibility.yml
source_heading: Eligibility
source_page: https://trueproxies.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrueProxies\naid: trueproxies\nurl: https://trueproxies.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trueproxies.com/acceptable-use/\n  - https://trueproxies.com/terms/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use TrueProxies.\n- type: business\n  text: If you are using the Services on behalf of a company or organization, you represent that you have authority\n    to bind that entity to these Terms.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: The Services are intended solely for lawful\
  \ purposes.\n- summary: Proxy detection tools\n  text: Using the Services to build, support, or enrich proxy detection or classification tools\n  source: https://trueproxies.com/acceptable-use/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use TrueProxies.\n"
source_yaml_url: https://artifacts.apis.io/trueproxies/eligibility/trueproxies-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from TrueProxies's own page on 2026-11-10.
synthetic: false
tags:
- Proxies
- Residential Proxies
- Datacenter Proxies
- Web Scraping
- Networking
- IPv6
- SOCKS5
- Data Collection
---
