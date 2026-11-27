---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: cualquier persona que brinda los Servicios de Digitalización de Trámites y Servicios Públicos a un tercero a través de ésta, le atribuye el carácter de Cliente
    type: other
  - text: Para acceder a los servicios prestados en la Plataforma, es necesario ser mayor de edad
    type: individual
  minimum_age:
    text: es necesario ser mayor de edad
    value: mayor de edad
  restricted_uses:
  - summary: Lawful use only
    text: El acceso y uso de la Plataforma se hará de conformidad con la ley, la moral y las buenas costumbres
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
name: Civica Digital
provenance_date: '2026-11-09'
provider_name: Civica Digital
provider_slug: civica-digital
slug: civica-digital-eligibility
source_date: '2026-11-09'
source_filename: civica-digital-eligibility.yml
source_heading: Eligibility
source_page: https://civica.digital/urbem/terminos-y-condiciones-urbem
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Civica Digital\naid: civica-digital\nurl: https://civica.digital/urbem/terminos-y-condiciones-urbem\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: cualquier persona que brinda los Servicios de Digitalización de Trámites y Servicios Públicos a un tercero\n    a través de ésta, le atribuye el carácter de Cliente\n- type: individual\n  text: Para acceder a los servicios prestados en la Plataforma, es necesario ser mayor de edad\nrestricted_uses:\n- summary: Lawful use only\n  text: El acceso y uso de la Plataforma se hará de conformidad con\
  \ la ley, la moral y las buenas costumbres\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: mayor de edad\n  text: es necesario ser mayor de edad\n"
source_yaml_url: https://artifacts.apis.io/civica-digital/eligibility/civica-digital-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Civica Digital's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Civic Technology
- Digital Government
- Public Sector
- GovTech
- Digital Transformation
- Document Management
- Conversational AI
- Mexico
---
