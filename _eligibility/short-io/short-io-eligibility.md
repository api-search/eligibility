---
api_specs:
- filename: short-io-audit-api-openapi.yml
  format: yaml
  label: Short.io Audit API
  slug: short-io-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-audit-api-openapi.yml
- filename: short-io-domain-dns-api-openapi.yml
  format: yaml
  label: Short.io Domain DNS API
  slug: short-io-domain-dns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-domain-dns-api-openapi.yml
- filename: short-io-domains-api-openapi.yml
  format: yaml
  label: Short.io Domains API
  slug: short-io-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-domains-api-openapi.yml
- filename: short-io-link-bundles-api-openapi.yml
  format: yaml
  label: Short.io Link Bundles API
  slug: short-io-link-bundles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-link-bundles-api-openapi.yml
- filename: short-io-link-duplication-api-openapi.yml
  format: yaml
  label: Short.io Link Duplication API
  slug: short-io-link-duplication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-link-duplication-api-openapi.yml
- filename: short-io-link-management-api-openapi.yml
  format: yaml
  label: Short.io Link Management API
  slug: short-io-link-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-link-management-api-openapi.yml
- filename: short-io-link-queries-api-openapi.yml
  format: yaml
  label: Short.io Link queries API
  slug: short-io-link-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-link-queries-api-openapi.yml
- filename: short-io-link-targeting-api-openapi.yml
  format: yaml
  label: Short.io Link Targeting API
  slug: short-io-link-targeting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-link-targeting-api-openapi.yml
- filename: short-io-organizations-api-openapi.yml
  format: yaml
  label: Short.io Organizations API
  slug: short-io-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-organizations-api-openapi.yml
- filename: short-io-posts-api-openapi.yml
  format: yaml
  label: Short.io Posts API
  slug: short-io-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-posts-api-openapi.yml
- filename: short-io-qr-codes-api-openapi.yml
  format: yaml
  label: Short.io QR Codes API
  slug: short-io-qr-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-qr-codes-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    served: []
    text: You further represent that you are not located in or ordinarily resident in any country or region that is subject to comprehensive sanctions or embargoes (which, as of the effective date of these Terms, include the countries of Cuba, Iran, and North Korea, as well as the Crimea, Donetsk, and Luhansk regions of Ukraine).
  entity_types:
  - text: When you are creating an account on behalf of a legal entity (when you are business owner or using Services on behalf of your employer) you represent and warrant that you have the authority to bind the respective legal entity
    type: business
  minimum_age:
    text: When you are creating an account you represent to us that you are at least 18 years old or have legal majority and capacity where you reside to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties and jurisdictions
    text: You will not use the Services, or permit the Services to be used, in violation of any applicable sanctions or export-control laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Short.io
provenance_date: '2026-11-10'
provider_name: Short.io
provider_slug: short-io
slug: short-io-eligibility
source_date: '2026-11-10'
source_filename: short-io-eligibility.yml
source_heading: Eligibility
source_page: https://short.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Short.io\naid: short-io\nurl: https://short.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  text: You further represent that you are not located in or ordinarily resident in any country or region that is\n    subject to comprehensive sanctions or embargoes (which, as of the effective date of these Terms, include the\n    countries of Cuba, Iran, and North Korea, as well as the Crimea, Donetsk, and Luhansk regions of Ukraine).\nentity_types:\n- type: business\n  text: When you are creating an account on behalf of a legal entity (when you are business owner\
  \ or using Services\n    on behalf of your employer) you represent and warrant that you have the authority to bind the respective legal\n    entity\nrestricted_uses:\n- summary: Sanctioned parties and jurisdictions\n  text: You will not use the Services, or permit the Services to be used, in violation of any applicable sanctions\n    or export-control laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you are creating an account you represent to us that you are at least 18 years old or have legal majority\n    and capacity where you reside to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/short-io/eligibility/short-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Short.io's own page on 2026-11-10.
synthetic: false
tags:
- URL Shortening
- Analytics
- QR Codes
- Enterprise
- Integration
---
