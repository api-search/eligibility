---
api_specs:
- filename: agendapro-available-slots-api-openapi.yml
  format: yaml
  label: AgendaPro Available Slots API
  slug: agendapro-available-slots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendapro/openapi/agendapro-available-slots-api-openapi.yml
- filename: agendapro-bookings-api-openapi.yml
  format: yaml
  label: AgendaPro Bookings API
  slug: agendapro-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendapro/openapi/agendapro-bookings-api-openapi.yml
- filename: agendapro-carts-api-openapi.yml
  format: yaml
  label: AgendaPro Carts API
  slug: agendapro-carts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendapro/openapi/agendapro-carts-api-openapi.yml
- filename: agendapro-clients-api-openapi.yml
  format: yaml
  label: AgendaPro Clients API
  slug: agendapro-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendapro/openapi/agendapro-clients-api-openapi.yml
- filename: agendapro-custom-attributes-api-openapi.yml
  format: yaml
  label: AgendaPro Custom Attributes API
  slug: agendapro-custom-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendapro/openapi/agendapro-custom-attributes-api-openapi.yml
- filename: agendapro-locations-api-openapi.yml
  format: yaml
  label: AgendaPro Locations API
  slug: agendapro-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendapro/openapi/agendapro-locations-api-openapi.yml
- filename: agendapro-payment-requests-api-openapi.yml
  format: yaml
  label: AgendaPro Payment Requests API
  slug: agendapro-payment-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendapro/openapi/agendapro-payment-requests-api-openapi.yml
- filename: agendapro-providers-api-openapi.yml
  format: yaml
  label: AgendaPro Providers API
  slug: agendapro-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendapro/openapi/agendapro-providers-api-openapi.yml
- filename: agendapro-sales-api-openapi.yml
  format: yaml
  label: AgendaPro Sales API
  slug: agendapro-sales-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendapro/openapi/agendapro-sales-api-openapi.yml
- filename: agendapro-services-api-openapi.yml
  format: yaml
  label: AgendaPro Services API
  slug: agendapro-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendapro/openapi/agendapro-services-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Cualquier Comercio que navegue, desee acceder y/o usar la Plataforma
    type: business
  minimum_age:
    text: No está permitido el uso de los Servicios por personas incapaces ni menores de dieciocho años.
    value: '18'
  restricted_uses:
  - summary: Prohibited content and illegal activities
    text: 'La utilización de la Plataforma para realizar servicios que: (i) tengan contenido o permitan o realicen cualquier actividad contraria a las disposiciones legales y administrativas, la moral y las buenas costumbres'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: AgendaPro podrá solicitar al Comercio, en cualquier momento y como condición para la activación o continuidad del Servicio de Pago en Línea, la entrega de documentación que acredite su identidad, domicilio, actividad comercial y/o titularidad de la cuenta bancaria registrada.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgendaPro
provenance_date: '2026-11-09'
provider_name: AgendaPro
provider_slug: agendapro
slug: agendapro-eligibility
source_date: '2026-11-09'
source_filename: agendapro-eligibility.yml
source_heading: Eligibility
source_page: https://agendapro.com/en/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgendaPro\naid: agendapro\nurl: https://agendapro.com/en/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Cualquier Comercio que navegue, desee acceder y/o usar la Plataforma\nrestricted_uses:\n- summary: Prohibited content and illegal activities\n  text: 'La utilización de la Plataforma para realizar servicios que: (i) tengan contenido o permitan o realicen\n    cualquier actividad contraria a las disposiciones legales y administrativas, la moral y las buenas costumbres'\nverification:\n  kyc:\
  \ true\n  kyb: null\n  approval_required: null\n  text: AgendaPro podrá solicitar al Comercio, en cualquier momento y como condición para la activación o continuidad\n    del Servicio de Pago en Línea, la entrega de documentación que acredite su identidad, domicilio, actividad comercial\n    y/o titularidad de la cuenta bancaria registrada.\nminimum_age:\n  value: '18'\n  text: No está permitido el uso de los Servicios por personas incapaces ni menores de dieciocho años.\n"
source_yaml_url: https://artifacts.apis.io/agendapro/eligibility/agendapro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from AgendaPro's own page on 2026-11-09.
synthetic: false
tags:
- Appointment Scheduling
- Booking
- Salon Software
- Spa and Wellness
- Point-of-Sale
- Clinic Management
- CRM
- Payments
- Webhook
- Vertical SaaS
- Latin America
- Small Business
- Scheduling
---
