---
api_specs:
- filename: przypominamy-com-czarna-lista-api-openapi.yml
  format: yaml
  label: przypominamy-com Czarna lista API
  slug: przypominamy-com-czarna-lista-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-czarna-lista-api-openapi.yml
- filename: przypominamy-com-kontakty-i-grupy-api-openapi.yml
  format: yaml
  label: przypominamy-com Kontakty i grupy API
  slug: przypominamy-com-kontakty-i-grupy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-kontakty-i-grupy-api-openapi.yml
- filename: przypominamy-com-konto-api-openapi.yml
  format: yaml
  label: przypominamy-com Konto API
  slug: przypominamy-com-konto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-konto-api-openapi.yml
- filename: przypominamy-com-linki-api-openapi.yml
  format: yaml
  label: przypominamy-com Linki API
  slug: przypominamy-com-linki-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-linki-api-openapi.yml
- filename: przypominamy-com-numery-api-openapi.yml
  format: yaml
  label: przypominamy-com Numery API
  slug: przypominamy-com-numery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-numery-api-openapi.yml
- filename: przypominamy-com-odpowiedzi-2-way-api-openapi.yml
  format: yaml
  label: przypominamy-com Odpowiedzi (2-way) API
  slug: przypominamy-com-odpowiedzi-2-way-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-odpowiedzi-2-way-api-openapi.yml
- filename: przypominamy-com-status-api-openapi.yml
  format: yaml
  label: przypominamy-com Status API
  slug: przypominamy-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-status-api-openapi.yml
- filename: przypominamy-com-szablony-api-openapi.yml
  format: yaml
  label: przypominamy-com Szablony API
  slug: przypominamy-com-szablony-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-szablony-api-openapi.yml
- filename: przypominamy-com-wiadomo-ci-api-openapi.yml
  format: yaml
  label: przypominamy-com Wiadomości API
  slug: przypominamy-com-wiadomo-ci-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-wiadomo-ci-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: osoba fizyczna prowadząca działalność gospodarczą, osoba prawna lub jednostka organizacyjna, która korzysta z Platformy
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Usługodawca zastrzega sobie prawo do weryfikacji danych Klienta przed aktywacją konta.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: przypominamy-com
provenance_date: '2026-11-10'
provider_name: przypominamy-com
provider_slug: przypominamy-com
slug: przypominamy-com-eligibility
source_date: '2026-11-10'
source_filename: przypominamy-com-eligibility.yml
source_heading: Eligibility
source_page: https://przypominamy.com/regulamin
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: przypominamy-com\naid: przypominamy-com\nurl: https://przypominamy.com/regulamin\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: osoba fizyczna prowadząca działalność gospodarczą, osoba prawna lub jednostka organizacyjna, która korzysta\n    z Platformy\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Usługodawca zastrzega sobie prawo do weryfikacji danych Klienta przed aktywacją konta.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/przypominamy-com/eligibility/przypominamy-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from przypominamy-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SMS
- Communications
- Poland
- Messaging
---
