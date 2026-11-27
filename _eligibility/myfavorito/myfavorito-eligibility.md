---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: For residents in Germany, Austria, Switzerland, Italy, France, The United Kingdom and all countries of the European Union, your contracting entity will be MyFavorito GmbH, Strasse des Friedens 15a, 99094 Erfurt, Germany.
  entity_types:
  - text: By downloading and installing MyFavorito, the End-User confirms that he/she is at least 16 years old or has parental permission to enter into this Agreement.
    type: individual
  - text: The Sponsor ensures that registration is carried out exclusively by authorised company representatives
    type: business
  - text: As a sports club you are obliged to sign up to MyFavorito only if you are an authorized and elected representative of the sports club.
    type: other
  minimum_age:
    text: the End-User confirms that he/she is at least 16 years old or has parental permission
    value: '16'
  restricted_uses:
  - summary: Prohibited sponsor content
    text: Prohibited in particular are extremist or pornographic content, misleading offers and intransparent sales processes.
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
name: MyFavorito
provenance_date: '2026-11-10'
provider_name: MyFavorito
provider_slug: myfavorito
slug: myfavorito-eligibility
source_date: '2026-11-10'
source_filename: myfavorito-eligibility.yml
source_heading: Eligibility
source_page: https://www.myfavorito.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MyFavorito\naid: myfavorito\nurl: https://www.myfavorito.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: For residents in Germany, Austria, Switzerland, Italy, France, The United Kingdom and all countries of the\n    European Union, your contracting entity will be MyFavorito GmbH, Strasse des Friedens 15a, 99094 Erfurt, Germany.\nentity_types:\n- type: individual\n  text: By downloading and installing MyFavorito, the End-User confirms that he/she is at least 16 years old or\n    has parental permission to enter into this Agreement.\n- type: business\n  text: The Sponsor\
  \ ensures that registration is carried out exclusively by authorised company representatives\n- type: other\n  text: As a sports club you are obliged to sign up to MyFavorito only if you are an authorized and elected representative\n    of the sports club.\nrestricted_uses:\n- summary: Prohibited sponsor content\n  text: Prohibited in particular are extremist or pornographic content, misleading offers and intransparent sales\n    processes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: the End-User confirms that he/she is at least 16 years old or has parental permission\n"
source_yaml_url: https://artifacts.apis.io/myfavorito/eligibility/myfavorito-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from MyFavorito's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports
- Sponsorship
- Fan Engagement
- SportsTech
- CRM
- Marketing
- Software-as-a-Service
---
