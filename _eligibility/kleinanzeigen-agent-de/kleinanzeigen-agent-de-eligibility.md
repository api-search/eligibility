---
api_specs:
- filename: kleinanzeigen-agent-de-ads-api-openapi.yml
  format: yaml
  label: kleinanzeigen-agent-de Ads API
  slug: kleinanzeigen-agent-de-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kleinanzeigen-agent-de/openapi/kleinanzeigen-agent-de-ads-api-openapi.yml
- filename: kleinanzeigen-agent-de-categories-api-openapi.yml
  format: yaml
  label: kleinanzeigen-agent-de Categories API
  slug: kleinanzeigen-agent-de-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kleinanzeigen-agent-de/openapi/kleinanzeigen-agent-de-categories-api-openapi.yml
- filename: kleinanzeigen-agent-de-history-api-openapi.yml
  format: yaml
  label: kleinanzeigen-agent-de History API
  slug: kleinanzeigen-agent-de-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kleinanzeigen-agent-de/openapi/kleinanzeigen-agent-de-history-api-openapi.yml
- filename: kleinanzeigen-agent-de-locations-api-openapi.yml
  format: yaml
  label: kleinanzeigen-agent-de Locations API
  slug: kleinanzeigen-agent-de-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kleinanzeigen-agent-de/openapi/kleinanzeigen-agent-de-locations-api-openapi.yml
- filename: kleinanzeigen-agent-de-search-api-openapi.yml
  format: yaml
  label: kleinanzeigen-agent-de Search API
  slug: kleinanzeigen-agent-de-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kleinanzeigen-agent-de/openapi/kleinanzeigen-agent-de-search-api-openapi.yml
- filename: kleinanzeigen-agent-de-sellers-api-openapi.yml
  format: yaml
  label: kleinanzeigen-agent-de Sellers API
  slug: kleinanzeigen-agent-de-sellers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kleinanzeigen-agent-de/openapi/kleinanzeigen-agent-de-sellers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Verbrauchern (§ 13 BGB) steht bei im Fernabsatz geschlossenen Verträgen über kostenpflichtige Tarife oder Credit-Pakete ein 14-tägiges Widerrufsrecht zu.
    type: individual
  - text: Für Unternehmer (§ 14 BGB) besteht kein Widerrufsrecht.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes or infringing rights
    text: der Einsatz des Dienstes für rechtswidrige Zwecke oder zur Verletzung von Rechten Dritter (insb. Urheber-, Marken-, Persönlichkeits- und Datenschutzrechte)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Die Anmeldung erfolgt passwortlos über einen 6-stelligen Anmeldecode, der an die vom Nutzer angegebene E-Mail-Adresse versendet wird.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: kleinanzeigen-agent-de
provenance_date: '2026-11-09'
provider_name: kleinanzeigen-agent-de
provider_slug: kleinanzeigen-agent-de
slug: kleinanzeigen-agent-de-eligibility
source_date: '2026-11-09'
source_filename: kleinanzeigen-agent-de-eligibility.yml
source_heading: Eligibility
source_page: https://kleinanzeigen-agent.de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: kleinanzeigen-agent-de\naid: kleinanzeigen-agent-de\nurl: https://kleinanzeigen-agent.de/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Verbrauchern (§ 13 BGB) steht bei im Fernabsatz geschlossenen Verträgen über kostenpflichtige Tarife oder\n    Credit-Pakete ein 14-tägiges Widerrufsrecht zu.\n- type: business\n  text: Für Unternehmer (§ 14 BGB) besteht kein Widerrufsrecht.\nrestricted_uses:\n- summary: Unlawful purposes or infringing rights\n  text: der Einsatz des Dienstes für rechtswidrige Zwecke oder zur Verletzung von Rechten\
  \ Dritter (insb. Urheber-,\n    Marken-, Persönlichkeits- und Datenschutzrechte)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Die Anmeldung erfolgt passwortlos über einen 6-stelligen Anmeldecode, der an die vom Nutzer angegebene E-Mail-Adresse\n    versendet wird.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kleinanzeigen-agent-de/eligibility/kleinanzeigen-agent-de-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from kleinanzeigen-agent-de's own page on 2026-11-09.
synthetic: false
tags:
- Search
- Monitoring
- Market Analysis
- Germany
- Kleinanzeigen
---
