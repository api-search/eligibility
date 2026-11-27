---
api_specs:
- filename: filen-health-api-openapi.yml
  format: yaml
  label: Filen Health API
  slug: filen-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-health-api-openapi.yml
- filename: filen-items-api-openapi.yml
  format: yaml
  label: Filen Items API
  slug: filen-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-items-api-openapi.yml
- filename: filen-shared-api-openapi.yml
  format: yaml
  label: Filen Shared API
  slug: filen-shared-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-shared-api-openapi.yml
- filename: filen-user-api-openapi.yml
  format: yaml
  label: Filen User API
  slug: filen-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-user-api-openapi.yml
- filename: filen-auth-api-openapi.yml
  format: yaml
  label: Filen Auth API
  slug: filen-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-auth-api-openapi.yml
- filename: filen-chat-api-openapi.yml
  format: yaml
  label: Filen Chat API
  slug: filen-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-chat-api-openapi.yml
- filename: filen-contacts-api-openapi.yml
  format: yaml
  label: Filen Contacts API
  slug: filen-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-contacts-api-openapi.yml
- filename: filen-dir-api-openapi.yml
  format: yaml
  label: Filen Dir API
  slug: filen-dir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-dir-api-openapi.yml
- filename: filen-directories-api-openapi.yml
  format: yaml
  label: Filen Directories API
  slug: filen-directories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-directories-api-openapi.yml
- filename: filen-file-api-openapi.yml
  format: yaml
  label: Filen File API
  slug: filen-file-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-file-api-openapi.yml
- filename: filen-file-transfers-api-openapi.yml
  format: yaml
  label: Filen File Transfers API
  slug: filen-file-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-file-transfers-api-openapi.yml
- filename: filen-internal-api-openapi.yml
  format: yaml
  label: Filen (internal) API
  slug: filen-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-internal-api-openapi.yml
- filename: filen-item-api-openapi.yml
  format: yaml
  label: Filen Item API
  slug: filen-item-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-item-api-openapi.yml
- filename: filen-misc-api-openapi.yml
  format: yaml
  label: Filen Misc API
  slug: filen-misc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-misc-api-openapi.yml
- filename: filen-mobile-api-openapi.yml
  format: yaml
  label: Filen Mobile API
  slug: filen-mobile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-mobile-api-openapi.yml
- filename: filen-notes-api-openapi.yml
  format: yaml
  label: Filen Notes API
  slug: filen-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-notes-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Site.
    type: individual
  - text: Anyone, including business entities, not in compliance may be removed from the service without prior notice.
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Site.
    value: '18'
  restricted_uses:
  - summary: Regulated data
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: GLBA
    text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Filen
provenance_date: '2026-11-09'
provider_name: Filen
provider_slug: filen
slug: filen-eligibility
source_date: '2026-11-09'
source_filename: filen-eligibility.yml
source_heading: Eligibility
source_page: https://filen.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Filen\naid: filen\nurl: https://filen.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Site.\n- type: business\n  text: Anyone, including business entities, not in compliance may be removed\
  \ from the service without prior notice.\nrestricted_uses:\n- summary: Regulated data\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: GLBA\n  text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Site.\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Site.\n"
source_yaml_url: https://artifacts.apis.io/filen/eligibility/filen-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Filen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Storage
- Encryption
- Zero Knowledge
- File Sync
---
