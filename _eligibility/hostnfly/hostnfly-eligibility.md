---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Le Bailleur doit être une personne physique disposant de la pleine capacité juridique
    type: individual
  - text: ou une personne morale agissant par l’intermédiaire d’une personne physique disposant du pouvoir ou de l’habilitation requise pour contracter au nom du Bailleur
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: L’inscription du Bailleur est automatiquement validée et entraîne l’ouverture d’un compte
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HostnFly
provenance_date: '2026-11-09'
provider_name: HostnFly
provider_slug: hostnfly
slug: hostnfly-eligibility
source_date: '2026-11-09'
source_filename: hostnfly-eligibility.yml
source_heading: Eligibility
source_page: https://hostnfly.com/legal/conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HostnFly\naid: hostnfly\nurl: https://hostnfly.com/legal/conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Le Bailleur doit être une personne physique disposant de la pleine capacité juridique\n- type: business\n  text: ou une personne morale agissant par l’intermédiaire d’une personne physique disposant du pouvoir ou de l’habilitation\n    requise pour contracter au nom du Bailleur\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: L’inscription du Bailleur est automatiquement\
  \ validée et entraîne l’ouverture d’un compte\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hostnfly/eligibility/hostnfly-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from HostnFly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Applicative Saas
- Property Management
- Short-Term Rental
- Vacation Rentals
- Airbnb
- Hospitality
- Concierge
- Real Estate
- France
---
