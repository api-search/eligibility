---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: toute personne physique accédant à la plateforme
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spam or harassment
    text: Ne pas utiliser le Service à des fins de spam ou harcèlement
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'L''accès au Service nécessite la création d''un compte via l''une des méthodes d''authentification suivantes : Google OAuth 2.0 Magic Link (lien de connexion par email)'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ArchiCollab
provenance_date: '2026-11-09'
provider_name: ArchiCollab
provider_slug: collab-archi
slug: collab-archi-eligibility
source_date: '2026-11-09'
source_filename: collab-archi-eligibility.yml
source_heading: Eligibility
source_page: https://collab.archi/legal/cgu
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ArchiCollab\naid: collab-archi\nurl: https://collab.archi/legal/cgu\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: toute personne physique accédant à la plateforme\nrestricted_uses:\n- summary: Spam or harassment\n  text: Ne pas utiliser le Service à des fins de spam ou harcèlement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'L''accès au Service nécessite la création d''un compte via l''une des méthodes d''authentification suivantes\n    : Google OAuth 2.0 Magic Link (lien de connexion par email)'\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/collab-archi/eligibility/collab-archi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from ArchiCollab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Architecture
- Collaboration
- PDF Annotation
- Construction
- Document Management
- MCP
- SaaS
- France
---
