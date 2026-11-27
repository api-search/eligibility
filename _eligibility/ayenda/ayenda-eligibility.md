---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CO
    text: ALOJAMIENTO debe ser persona natural o jurídica legalmente constituida en Colombia.
  entity_types:
  - text: Los Servicios pueden ser contratados por personas naturales y jurídicas que tengan capacidad legal para contratar.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: El CLIENTE o ALOJAMIENTO solo puede utilizar la Plataforma para fines legales y de acuerdo con estos Términos.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: El ALOJAMIENTO, para poder utilizar la Plataforma de Ayenda, deberá registrarse creando una cuenta y proporcionando la información solicitada de manera veraz, completa y precisa.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ayenda
provenance_date: '2026-11-09'
provider_name: Ayenda
provider_slug: ayenda
slug: ayenda-eligibility
source_date: '2026-11-09'
source_filename: ayenda-eligibility.yml
source_heading: Eligibility
source_page: https://ayenda.com/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ayenda\naid: ayenda\nurl: https://ayenda.com/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - CO\n  excluded: []\n  text: ALOJAMIENTO debe ser persona natural o jurídica legalmente constituida en Colombia.\nentity_types:\n- type: business\n  text: Los Servicios pueden ser contratados por personas naturales y jurídicas que tengan capacidad legal para\n    contratar.\nrestricted_uses:\n- summary: Lawful use only\n  text: El CLIENTE o ALOJAMIENTO solo puede utilizar la Plataforma para fines legales y de acuerdo con estos Términos.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: El ALOJAMIENTO, para poder utilizar la Plataforma de Ayenda, deberá registrarse creando una cuenta y proporcionando\n    la información solicitada de manera veraz, completa y precisa.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ayenda/eligibility/ayenda-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Ayenda's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hotels
- Travel
- Hospitality
- Booking
- Reservations
- PMS
- Channel Manager
- Latin America
---
