---
api_specs:
- filename: cenogram-pl-demographics-api-openapi.yml
  format: yaml
  label: Cenogram Demographics API
  slug: cenogram-pl-demographics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-demographics-api-openapi.yml
- filename: cenogram-pl-infrastructure-api-openapi.yml
  format: yaml
  label: Cenogram Infrastructure API
  slug: cenogram-pl-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-infrastructure-api-openapi.yml
- filename: cenogram-pl-locations-api-openapi.yml
  format: yaml
  label: Cenogram Locations API
  slug: cenogram-pl-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-locations-api-openapi.yml
- filename: cenogram-pl-parcels-api-openapi.yml
  format: yaml
  label: Cenogram Parcels API
  slug: cenogram-pl-parcels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-parcels-api-openapi.yml
- filename: cenogram-pl-spatial-api-openapi.yml
  format: yaml
  label: Cenogram Spatial API
  slug: cenogram-pl-spatial-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-spatial-api-openapi.yml
- filename: cenogram-pl-statistics-api-openapi.yml
  format: yaml
  label: Cenogram Statistics API
  slug: cenogram-pl-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-statistics-api-openapi.yml
- filename: cenogram-pl-transactions-api-openapi.yml
  format: yaml
  label: Cenogram Transactions API
  slug: cenogram-pl-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-transactions-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Użytkownik - osoba fizyczna, prawna lub jednostka organizacyjna korzystająca z Serwisu
    type: individual
  - text: Użytkownik - osoba fizyczna, prawna lub jednostka organizacyjna korzystająca z Serwisu
    type: business
  - text: Użytkownik - osoba fizyczna, prawna lub jednostka organizacyjna korzystająca z Serwisu
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful content
    text: Użytkownik zobowiązuje się do niedostarczania treści o charakterze bezprawnym.
  - summary: Identifying individuals from data
    text: Użytkownik nie ustala tożsamości osób fizycznych na podstawie tych danych ani nie łączy oferty z cennika z transakcją RCN dotyczącą konkretnego lokalu.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Aktywacja Konta następuje po kliknięciu w link weryfikacyjny.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cenogram
provenance_date: '2026-11-09'
provider_name: Cenogram
provider_slug: cenogram-pl
slug: cenogram-pl-eligibility
source_date: '2026-11-09'
source_filename: cenogram-pl-eligibility.yml
source_heading: Eligibility
source_page: https://cenogram.pl/regulamin
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cenogram\naid: cenogram-pl\nurl: https://cenogram.pl/regulamin\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Użytkownik - osoba fizyczna, prawna lub jednostka organizacyjna korzystająca z Serwisu\n- type: business\n  text: Użytkownik - osoba fizyczna, prawna lub jednostka organizacyjna korzystająca z Serwisu\n- type: other\n  text: Użytkownik - osoba fizyczna, prawna lub jednostka organizacyjna korzystająca z Serwisu\nrestricted_uses:\n- summary: Unlawful content\n  text: Użytkownik zobowiązuje się do niedostarczania treści o charakterze\
  \ bezprawnym.\n- summary: Identifying individuals from data\n  text: Użytkownik nie ustala tożsamości osób fizycznych na podstawie tych danych ani nie łączy oferty z cennika\n    z transakcją RCN dotyczącą konkretnego lokalu.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Aktywacja Konta następuje po kliknięciu w link weryfikacyjny.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cenogram-pl/eligibility/cenogram-pl-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Cenogram's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Data
- Analytics
- Poland
---
