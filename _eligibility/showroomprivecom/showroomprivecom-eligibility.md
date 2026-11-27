---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    - BE
    - MC
    - LU
    text: Nous livrons vos commandes en France métropolitaine (Corse comprise), DOM-TOM, Belgique, Monaco et Luxembourg
  entity_types:
  - text: nos ventes évènementielles ne sont proposées qu'aux particuliers inscrits sur le Site (« les Membres ») pour leur usage personnel.
    type: individual
  minimum_age:
    text: En créant votre compte personnel vous confirmez avoir plus de 15 ans
    value: '15'
  restricted_uses:
  - summary: Personal use only
    text: pour leur usage personnel
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Le cas échéant, nous pouvons vous demander de nous transmettre par mail une copie recto de votre pièce d'identité ainsi qu'un justificatif de domicile datant de moins de trois (3) mois.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Showroomprive.com
provenance_date: '2026-11-10'
provider_name: Showroomprive.com
provider_slug: showroomprivecom
slug: showroomprivecom-eligibility
source_date: '2026-11-10'
source_filename: showroomprivecom-eligibility.yml
source_heading: Eligibility
source_page: https://www.showroomprive.com/contratcgv.aspx
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Showroomprive.com\naid: showroomprivecom\nurl: https://www.showroomprive.com/contratcgv.aspx\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  - BE\n  - MC\n  - LU\n  excluded: []\n  text: Nous livrons vos commandes en France métropolitaine (Corse comprise), DOM-TOM, Belgique, Monaco et Luxembourg\nentity_types:\n- type: individual\n  text: nos ventes évènementielles ne sont proposées qu'aux particuliers inscrits sur le Site (« les Membres »)\n    pour leur usage personnel.\nrestricted_uses:\n- summary: Personal use only\n  text: pour leur usage personnel\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: Le cas échéant, nous pouvons vous demander de nous transmettre par mail une copie recto de votre pièce d'identité\n    ainsi qu'un justificatif de domicile datant de moins de trois (3) mois.\nminimum_age:\n  value: '15'\n  text: En créant votre compte personnel vous confirmez avoir plus de 15 ans\n"
source_yaml_url: https://artifacts.apis.io/showroomprivecom/eligibility/showroomprivecom-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Showroomprive.com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- E-Commerce
- Retail
- Marketplace
- Fashion
- Flash Sales
- France
---
