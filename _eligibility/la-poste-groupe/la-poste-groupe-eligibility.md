---
api_specs:
- filename: la-poste-groupe-administration-api-openapi.yml
  format: yaml
  label: La Poste Groupe Administration API
  slug: la-poste-groupe-administration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-administration-api-openapi.yml
- filename: la-poste-groupe-applications-api-openapi.yml
  format: yaml
  label: La Poste Groupe Applications API
  slug: la-poste-groupe-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-applications-api-openapi.yml
- filename: la-poste-groupe-digiposte-api-openapi.yml
  format: yaml
  label: La Poste Groupe Digiposte API
  slug: la-poste-groupe-digiposte-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-digiposte-api-openapi.yml
- filename: la-poste-groupe-jdd-ditable-api-openapi.yml
  format: yaml
  label: La Poste Groupe JDD / Éditable API
  slug: la-poste-groupe-jdd-ditable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-jdd-ditable-api-openapi.yml
- filename: la-poste-groupe-jdd-donn-es-api-openapi.yml
  format: yaml
  label: La Poste Groupe JDD / Données API
  slug: la-poste-groupe-jdd-donn-es-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-jdd-donn-es-api-openapi.yml
- filename: la-poste-groupe-jdd-m-tadonn-es-api-openapi.yml
  format: yaml
  label: La Poste Groupe JDD / Métadonnées API
  slug: la-poste-groupe-jdd-m-tadonn-es-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-jdd-m-tadonn-es-api-openapi.yml
- filename: la-poste-groupe-jeux-de-donn-es-jdd-api-openapi.yml
  format: yaml
  label: La Poste Groupe Jeux de données (JDD) API
  slug: la-poste-groupe-jeux-de-donn-es-jdd-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-jeux-de-donn-es-jdd-api-openapi.yml
- filename: la-poste-groupe-lh-pro-resources-api-openapi.yml
  format: yaml
  label: La Poste Groupe LH PRO resources API
  slug: la-poste-groupe-lh-pro-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-lh-pro-resources-api-openapi.yml
- filename: la-poste-groupe-partner-api-openapi.yml
  format: yaml
  label: La Poste Groupe Partner API
  slug: la-poste-groupe-partner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-partner-api-openapi.yml
- filename: la-poste-groupe-resend-purl-api-openapi.yml
  format: yaml
  label: La Poste Groupe Resend Purl API
  slug: la-poste-groupe-resend-purl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-resend-purl-api-openapi.yml
- filename: la-poste-groupe-suivi-api-openapi.yml
  format: yaml
  label: La Poste Groupe Suivi API
  slug: la-poste-groupe-suivi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-suivi-api-openapi.yml
- filename: la-poste-groupe-user-api-openapi.yml
  format: yaml
  label: La Poste Groupe User API
  slug: la-poste-groupe-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/la-poste-groupe/openapi/la-poste-groupe-user-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: toute personne physique ou morale identifiée via un Compte Pro La Poste qui agit à des fins entrant le cadre de son activité professionnelle
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal content or activities
    text: Utiliser les Services pour diffuser ou exploiter des contenus ou activités illicites
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Disposer ou créer d’un Compte Pro la Poste ; Valider les CGU puis souscrire en ligne au(x) Service(s) de son choix.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: La Poste Groupe
provenance_date: '2026-11-09'
provider_name: La Poste Groupe
provider_slug: la-poste-groupe
slug: la-poste-groupe-eligibility
source_date: '2026-11-09'
source_filename: la-poste-groupe-eligibility.yml
source_heading: Eligibility
source_page: https://developer.laposte.fr/cgu
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: La Poste Groupe\naid: la-poste-groupe\nurl: https://developer.laposte.fr/cgu\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: toute personne physique ou morale identifiée via un Compte Pro La Poste qui agit à des fins entrant le cadre\n    de son activité professionnelle\nrestricted_uses:\n- summary: Illegal content or activities\n  text: Utiliser les Services pour diffuser ou exploiter des contenus ou activités illicites\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Disposer ou créer d’un Compte Pro la\
  \ Poste ; Valider les CGU puis souscrire en ligne au(x) Service(s) de\n    son choix.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/la-poste-groupe/eligibility/la-poste-groupe-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from La Poste Groupe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- Package Tracking
- Postal
- Addresses
- Geocoding
- Open Data
- Document Management
- Identity
- Government
- France
---
