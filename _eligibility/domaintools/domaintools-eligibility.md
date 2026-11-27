---
api_specs:
- filename: domaintools-flex-search-api-openapi.yml
  format: yaml
  label: DomainTools Flex search API
  slug: domaintools-flex-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-flex-search-api-openapi.yml
- filename: domaintools-information-api-openapi.yml
  format: yaml
  label: DomainTools Information API
  slug: domaintools-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-information-api-openapi.yml
- filename: domaintools-iris-detect-api-openapi.yml
  format: yaml
  label: DomainTools Iris Detect API
  slug: domaintools-iris-detect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-iris-detect-api-openapi.yml
- filename: domaintools-iris-enrich-api-openapi.yml
  format: yaml
  label: DomainTools Iris Enrich API
  slug: domaintools-iris-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-iris-enrich-api-openapi.yml
- filename: domaintools-iris-investigate-api-openapi.yml
  format: yaml
  label: DomainTools Iris Investigate API
  slug: domaintools-iris-investigate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-iris-investigate-api-openapi.yml
- filename: domaintools-lookups-api-openapi.yml
  format: yaml
  label: DomainTools Lookups API
  slug: domaintools-lookups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-lookups-api-openapi.yml
- filename: domaintools-monitors-api-openapi.yml
  format: yaml
  label: DomainTools Monitors API
  slug: domaintools-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-monitors-api-openapi.yml
- filename: domaintools-ping-api-openapi.yml
  format: yaml
  label: DomainTools Ping API
  slug: domaintools-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-ping-api-openapi.yml
- filename: domaintools-rate-limit-api-openapi.yml
  format: yaml
  label: DomainTools Rate Limit API
  slug: domaintools-rate-limit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-rate-limit-api-openapi.yml
- filename: domaintools-rdata-lookups-api-openapi.yml
  format: yaml
  label: DomainTools rdata Lookups API
  slug: domaintools-rdata-lookups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-rdata-lookups-api-openapi.yml
- filename: domaintools-rrset-lookups-api-openapi.yml
  format: yaml
  label: DomainTools rrset Lookups API
  slug: domaintools-rrset-lookups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-rrset-lookups-api-openapi.yml
- filename: domaintools-siebatchd-api-openapi.yml
  format: yaml
  label: DomainTools Siebatchd API
  slug: domaintools-siebatchd-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domaintools/openapi/domaintools-siebatchd-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not be barred from accessing or using the Service under United States law or the laws applicable where you reside or from where you access or use the Service.
  minimum_age:
    text: In order to use the Service, you must be at least 18 years old and have legal capacity to enter binding contracts.
    value: '18'
  restricted_uses:
  - summary: Limited to own domain/brand and internal purposes
    text: solely for your own personal or internal purposes relating to your own domain acquisition or brand protection, not for the benefit of any of your customers, constituents or other third parties
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to open an account, you must provide DomainTools with certain information (“Registration Data”) requested on the registration form
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DomainTools
provenance_date: '2026-11-09'
provider_name: DomainTools
provider_slug: domaintools
slug: domaintools-eligibility
source_date: '2026-11-09'
source_filename: domaintools-eligibility.yml
source_heading: Eligibility
source_page: https://www.domaintools.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DomainTools\naid: domaintools\nurl: https://www.domaintools.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not be barred from accessing or using the Service under United States law or the laws applicable\n    where you reside or from where you access or use the Service.\nentity_types: []\nrestricted_uses:\n- summary: Limited to own domain/brand and internal purposes\n  text: solely for your own personal or internal purposes relating to your own domain acquisition or brand protection,\n    not for the benefit of any of your customers, constituents\
  \ or other third parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to open an account, you must provide DomainTools with certain information (“Registration Data”)\n    requested on the registration form\nminimum_age:\n  value: '18'\n  text: In order to use the Service, you must be at least 18 years old and have legal capacity to enter binding\n    contracts.\n"
source_yaml_url: https://artifacts.apis.io/domaintools/eligibility/domaintools-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from DomainTools's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Threat Intelligence
- Domain Intelligence
- DNS
- WHOIS
- Passive DNS
- Cybersecurity
- Domain Monitoring
- Risk Scoring
- Security
---
