---
api_specs:
- filename: immutable-activities-api-openapi.yml
  format: yaml
  label: Immutable Activities API
  slug: immutable-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-activities-api-openapi.yml
- filename: immutable-chains-api-openapi.yml
  format: yaml
  label: Immutable Chains API
  slug: immutable-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-chains-api-openapi.yml
- filename: immutable-collections-api-openapi.yml
  format: yaml
  label: Immutable Collections API
  slug: immutable-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-collections-api-openapi.yml
- filename: immutable-crafting-api-openapi.yml
  format: yaml
  label: Immutable Crafting API
  slug: immutable-crafting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-crafting-api-openapi.yml
- filename: immutable-data-api-openapi.yml
  format: yaml
  label: Immutable Data API
  slug: immutable-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-data-api-openapi.yml
- filename: immutable-ingest-api-openapi.yml
  format: yaml
  label: Immutable Ingest API
  slug: immutable-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-ingest-api-openapi.yml
- filename: immutable-metadata-api-openapi.yml
  format: yaml
  label: Immutable Metadata API
  slug: immutable-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-metadata-api-openapi.yml
- filename: immutable-metadata-search-api-openapi.yml
  format: yaml
  label: Immutable Metadata Search API
  slug: immutable-metadata-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-metadata-search-api-openapi.yml
- filename: immutable-nft-owners-api-openapi.yml
  format: yaml
  label: Immutable nft owners API
  slug: immutable-nft-owners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-nft-owners-api-openapi.yml
- filename: immutable-orders-api-openapi.yml
  format: yaml
  label: Immutable Orders API
  slug: immutable-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-orders-api-openapi.yml
- filename: immutable-passport-api-openapi.yml
  format: yaml
  label: Immutable Passport API
  slug: immutable-passport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-passport-api-openapi.yml
- filename: immutable-passport-profile-api-openapi.yml
  format: yaml
  label: Immutable passport profile API
  slug: immutable-passport-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-passport-profile-api-openapi.yml
- filename: immutable-pricing-api-openapi.yml
  format: yaml
  label: Immutable Pricing API
  slug: immutable-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-pricing-api-openapi.yml
- filename: immutable-tokens-api-openapi.yml
  format: yaml
  label: Immutable Tokens API
  slug: immutable-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-tokens-api-openapi.yml
- filename: immutable-tracking-consent-api-openapi.yml
  format: yaml
  label: Immutable Tracking Consent API
  slug: immutable-tracking-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-tracking-consent-api-openapi.yml
- filename: immutable-nfts-api-openapi.yml
  format: yaml
  label: Immutable Nfts API
  slug: immutable-nfts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immutable/openapi/immutable-nfts-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not a person or entity who is a citizen of, resident, incorporated, has a registered office or is located in any comprehensively sanctioned country
  entity_types:
  - text: If you are using the Services on behalf of another person (including a company), you warrant that you are authorized to bind that person to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned countries and persons
    text: you are not accessing the Services from a comprehensively sanctioned country;
  - summary: VPN use prohibited
    text: you are not using a virtual private network or other means to obfuscate your location or access to the Services;
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
name: Immutable
provenance_date: '2026-11-09'
provider_name: Immutable
provider_slug: immutable
slug: immutable-eligibility
source_date: '2026-11-09'
source_filename: immutable-eligibility.yml
source_heading: Eligibility
source_page: https://www.immutable.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Immutable\naid: immutable\nurl: https://www.immutable.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not a person or entity who is a citizen of, resident, incorporated,\n    has a registered office or is located in any comprehensively sanctioned country\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of another person (including a company), you warrant that you are\n    authorized to bind that person to these Terms\nrestricted_uses:\n- summary: Sanctioned countries\
  \ and persons\n  text: you are not accessing the Services from a comprehensively sanctioned country;\n- summary: VPN use prohibited\n  text: you are not using a virtual private network or other means to obfuscate your location or access to the Services;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/immutable/eligibility/immutable-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Immutable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Blockchain
- NFT
- Web3
- Wallets
- Marketplace
- Analytics
- Attribution
- Customer Data Platform
- Authentication
- Developer Platform
- A2A
---
