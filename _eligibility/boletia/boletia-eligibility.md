---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: Los Servicios prestados por Boletia deberán de entenderse como servicios prestados en la República Mexicana sin importar en donde fueron originados o solicitados.
  entity_types:
  - text: La Plataforma Digital, tiene el objetivo de ser utilizada únicamente por personas mayores de edad
    type: individual
  minimum_age:
    text: La Plataforma Digital, tiene el objetivo de ser utilizada únicamente por personas mayores de edad, cualquier uso realizado por un menor de edad queda estrictamente prohibido.
    value: '18'
  restricted_uses:
  - summary: Prohibited event types
    text: Prácticas discriminatorias ya sea en razón de raza, creencia y/o preferencia sexual.
  - summary: No rifas or unrelated fundraising
    text: Rifas, servicios relacionados con agencia de viajes, o cualquier actividad recaudatoria que no se encuentre dentro del mercado de un evento que se vaya a llevar a cabo.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Dichos documentos deberán ser enviados a contratos@boletia.com para proceder con la realización del contrato. Cuando Boletia lo requiera podrá pedir más información relativa al cliente o al evento en cuestión.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Boletia
provenance_date: '2026-11-09'
provider_name: Boletia
provider_slug: boletia
slug: boletia-eligibility
source_date: '2026-11-09'
source_filename: boletia-eligibility.yml
source_heading: Eligibility
source_page: https://boletia.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boletia\naid: boletia\nurl: https://boletia.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: Los Servicios prestados por Boletia deberán de entenderse como servicios prestados en la República Mexicana\n    sin importar en donde fueron originados o solicitados.\nentity_types:\n- type: individual\n  text: La Plataforma Digital, tiene el objetivo de ser utilizada únicamente por personas mayores de edad\nrestricted_uses:\n- summary: Prohibited event types\n  text: Prácticas discriminatorias ya sea en razón de raza, creencia y/o preferencia sexual.\n- summary:\
  \ No rifas or unrelated fundraising\n  text: Rifas, servicios relacionados con agencia de viajes, o cualquier actividad recaudatoria que no se encuentre\n    dentro del mercado de un evento que se vaya a llevar a cabo.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Dichos documentos deberán ser enviados a contratos@boletia.com para proceder con la realización del contrato.\n    Cuando Boletia lo requiera podrá pedir más información relativa al cliente o al evento en cuestión.\nminimum_age:\n  value: '18'\n  text: La Plataforma Digital, tiene el objetivo de ser utilizada únicamente por personas mayores de edad, cualquier\n    uso realizado por un menor de edad queda estrictamente prohibido.\n"
source_yaml_url: https://artifacts.apis.io/boletia/eligibility/boletia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Boletia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ticketing
- Event
- Event Management
- Registration
- Payments
- Access Control
- Entertainment
- Mexico
---
