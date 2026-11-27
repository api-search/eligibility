---
api_specs:
- filename: tradera-auth-api-openapi.yml
  format: yaml
  label: Tradera Auth API
  slug: tradera-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradera/openapi/tradera-auth-api-openapi.yml
- filename: tradera-buyer-api-openapi.yml
  format: yaml
  label: Tradera Buyer API
  slug: tradera-buyer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradera/openapi/tradera-buyer-api-openapi.yml
- filename: tradera-categories-api-openapi.yml
  format: yaml
  label: Tradera Categories API
  slug: tradera-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradera/openapi/tradera-categories-api-openapi.yml
- filename: tradera-items-api-openapi.yml
  format: yaml
  label: Tradera Items API
  slug: tradera-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradera/openapi/tradera-items-api-openapi.yml
- filename: tradera-listings-api-openapi.yml
  format: yaml
  label: Tradera Listings API
  slug: tradera-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradera/openapi/tradera-listings-api-openapi.yml
- filename: tradera-orders-api-openapi.yml
  format: yaml
  label: Tradera Orders API
  slug: tradera-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradera/openapi/tradera-orders-api-openapi.yml
- filename: tradera-program-api-openapi.yml
  format: yaml
  label: Tradera Program API
  slug: tradera-program-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradera/openapi/tradera-program-api-openapi.yml
- filename: tradera-reference-data-api-openapi.yml
  format: yaml
  label: Tradera Reference Data API
  slug: tradera-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradera/openapi/tradera-reference-data-api-openapi.yml
- filename: tradera-search-api-openapi.yml
  format: yaml
  label: Tradera Search API
  slug: tradera-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradera/openapi/tradera-search-api-openapi.yml
- filename: tradera-tradera-api-services-core-api-openapi.yml
  format: yaml
  label: Tradera Tradera.Api.Services.Core API
  slug: tradera-tradera-api-services-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradera/openapi/tradera-tradera-api-services-core-api-openapi.yml
- filename: tradera-users-api-openapi.yml
  format: yaml
  label: Tradera Users API
  slug: tradera-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradera/openapi/tradera-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: För att registrera ett konto behöver du vara minst 16 år.
    type: individual
  - text: Om du registrerar dig som företagsanvändare intygar du att du har behörighet att företräda och binda företaget till detta Användaravtal.
    type: business
  minimum_age:
    text: För att registrera ett konto behöver du vara minst 16 år.
    value: '16'
  restricted_uses:
  - summary: Facebook Marketplace integration limited to private persons
    text: Marketplaceintegrationen är endast tillgänglig för privatpersoner. Företagsanvändare kan inte använda Marketplaceintegrationen.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Tradera har rätt att avsluta eller begränsa ett användarkonto om kontot inte kan verifieras eller har varit inaktivt under en sammanhängande period om tolv (12) månader.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tradera
provenance_date: '2026-11-10'
provider_name: Tradera
provider_slug: tradera
slug: tradera-eligibility
source_date: '2026-11-10'
source_filename: tradera-eligibility.yml
source_heading: Eligibility
source_page: https://www.tradera.com/support/se/terms/terms-and-conditions/anvaendaravtal-2026-04-15/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tradera\naid: tradera\nurl: https://www.tradera.com/support/se/terms/terms-and-conditions/anvaendaravtal-2026-04-15/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: För att registrera ett konto behöver du vara minst 16 år.\n- type: business\n  text: Om du registrerar dig som företagsanvändare intygar du att du har behörighet att företräda och binda företaget\n    till detta Användaravtal.\nrestricted_uses:\n- summary: Facebook Marketplace integration limited to private persons\n  text: Marketplaceintegrationen är endast tillgänglig\
  \ för privatpersoner. Företagsanvändare kan inte använda Marketplaceintegrationen.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Tradera har rätt att avsluta eller begränsa ett användarkonto om kontot inte kan verifieras eller har varit\n    inaktivt under en sammanhängande period om tolv (12) månader.\nminimum_age:\n  value: '16'\n  text: För att registrera ett konto behöver du vara minst 16 år.\n"
source_yaml_url: https://artifacts.apis.io/tradera/eligibility/tradera-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Tradera's own page on 2026-11-10.
synthetic: false
tags:
- Marketplace
- E-Commerce
- Secondhand
- Auctions
- Sweden
---
