---
api_specs:
- filename: chorilo-com-openapi-generated.yml
  format: yaml
  label: Chorilo API
  slug: chorilo-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chorilo-com/openapi/_ae-authored/chorilo-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Chorilo steht Chören, Ensembles, Vereinen, Verbänden und ihren Mitgliedern für die eigene Chor- und Vereinsarbeit zur Verfügung.
    type: nonprofit
  - text: Ist das Ensemble Unternehmer im Sinne des Umsatzsteuergesetzes, unterliegt die Provision grundsätzlich dem allgemeinen Steuersatz.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Chat illegal content
    text: Keine Verbreitung von illegalen Inhalten
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
name: Chorilo
provenance_date: '2026-11-09'
provider_name: Chorilo
provider_slug: chorilo-com
slug: chorilo-com-eligibility
source_date: '2026-11-09'
source_filename: chorilo-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.chorilo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chorilo\naid: chorilo-com\nurl: https://www.chorilo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: nonprofit\n  text: Chorilo steht Chören, Ensembles, Vereinen, Verbänden und ihren Mitgliedern für die eigene Chor- und Vereinsarbeit\n    zur Verfügung.\n- type: business\n  text: Ist das Ensemble Unternehmer im Sinne des Umsatzsteuergesetzes, unterliegt die Provision grundsätzlich dem\n    allgemeinen Steuersatz.\nrestricted_uses:\n- summary: Chat illegal content\n  text: Keine Verbreitung von illegalen Inhalten\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chorilo-com/eligibility/chorilo-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Chorilo's own page on 2026-11-09.
synthetic: false
tags:
- Choir Management
- Sheet Music
- Event Planning
- Finance
- Membership
- Collaboration
- GDPR
- Mobile App
---
