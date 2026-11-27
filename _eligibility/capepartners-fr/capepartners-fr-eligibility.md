---
api_specs:
- filename: capepartners-fr-activity-api-openapi.yml
  format: yaml
  label: Cape Partners Activity API
  slug: capepartners-fr-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-activity-api-openapi.yml
- filename: capepartners-fr-confidentiality-api-openapi.yml
  format: yaml
  label: Cape Partners Confidentiality API
  slug: capepartners-fr-confidentiality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-confidentiality-api-openapi.yml
- filename: capepartners-fr-dataquality-api-openapi.yml
  format: yaml
  label: Cape Partners Data Quality API
  slug: capepartners-fr-dataquality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-dataquality-api-openapi.yml
- filename: capepartners-fr-dealflow-api-openapi.yml
  format: yaml
  label: Cape Partners Deal Flow API
  slug: capepartners-fr-dealflow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-dealflow-api-openapi.yml
- filename: capepartners-fr-discovery-api-openapi.yml
  format: yaml
  label: Cape Partners Discovery API
  slug: capepartners-fr-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-discovery-api-openapi.yml
- filename: capepartners-fr-exchange-api-openapi.yml
  format: yaml
  label: Cape Partners Exchange API
  slug: capepartners-fr-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-exchange-api-openapi.yml
- filename: capepartners-fr-identity-api-openapi.yml
  format: yaml
  label: Cape Partners Identity API
  slug: capepartners-fr-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-identity-api-openapi.yml
- filename: capepartners-fr-infomemos-api-openapi.yml
  format: yaml
  label: Cape Partners Info Memos API
  slug: capepartners-fr-infomemos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-infomemos-api-openapi.yml
- filename: capepartners-fr-interest-api-openapi.yml
  format: yaml
  label: Cape Partners Interest API
  slug: capepartners-fr-interest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-interest-api-openapi.yml
- filename: capepartners-fr-mandate-api-openapi.yml
  format: yaml
  label: Cape Partners Mandate API
  slug: capepartners-fr-mandate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-mandate-api-openapi.yml
- filename: capepartners-fr-matching-api-openapi.yml
  format: yaml
  label: Cape Partners Matching API
  slug: capepartners-fr-matching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-matching-api-openapi.yml
- filename: capepartners-fr-pairings-api-openapi.yml
  format: yaml
  label: Cape Partners Pairings API
  slug: capepartners-fr-pairings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-pairings-api-openapi.yml
- filename: capepartners-fr-registration-api-openapi.yml
  format: yaml
  label: Cape Partners Registration API
  slug: capepartners-fr-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-registration-api-openapi.yml
- filename: capepartners-fr-search-api-openapi.yml
  format: yaml
  label: Cape Partners Search API
  slug: capepartners-fr-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-search-api-openapi.yml
- filename: capepartners-fr-valuation-api-openapi.yml
  format: yaml
  label: Cape Partners Valuation API
  slug: capepartners-fr-valuation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capepartners-fr/openapi/capepartners-fr-valuation-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: French and European lower-middle-market businesses are the deal focus; no explicit country eligibility list.
  entity_types:
  - text: Accounts are corporate-gated. You warrant that you are a genuine business entity or its authorised representative.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Anti-circumvention of Platform fee
    text: you shall NOT engage in any direct or indirect negotiation, exchange of confidential materials, or execution of any Transaction with that Counterparty outside the Platform
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Cape Partners reserves the right to require LinkedIn matching, domain-email verification, KYC/KYB checks, or registry (SIREN/SIRET) confirmation before activating or continuing access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cape Partners
provenance_date: '2026-11-09'
provider_name: Cape Partners
provider_slug: capepartners-fr
slug: capepartners-fr-eligibility
source_date: '2026-11-09'
source_filename: capepartners-fr-eligibility.yml
source_heading: Eligibility
source_page: https://www.capepartners.fr/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cape Partners\naid: capepartners-fr\nurl: https://www.capepartners.fr/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: French and European lower-middle-market businesses are the deal focus; no explicit country eligibility list.\nentity_types:\n- type: business\n  text: Accounts are corporate-gated. You warrant that you are a genuine business entity or its authorised representative.\nrestricted_uses:\n- summary: Anti-circumvention of Platform fee\n  text: you shall NOT engage in any direct or indirect negotiation, exchange of confidential materials, or execution\n    of any Transaction\
  \ with that Counterparty outside the Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Cape Partners reserves the right to require LinkedIn matching, domain-email verification, KYC/KYB checks,\n    or registry (SIREN/SIRET) confirmation before activating or continuing access.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/capepartners-fr/eligibility/capepartners-fr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Cape Partners's own page on 2026-11-09.
synthetic: false
tags:
- Mergers and Acquisitions
- Deal Flow
- Valuation
- Investment
- Financial Services
- Agents
- A2A
- France
- Technology
- Software-as-a-Service
---
