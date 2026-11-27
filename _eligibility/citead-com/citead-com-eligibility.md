---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: La Solution est réservée aux professionnels établis dans l'Union européenne.
  entity_types:
  - text: agissant dans le cadre de leur activité commerciale, industrielle, artisanale, libérale ou agricole
    type: business
  - text: toute personne morale ou physique agissant à des fins professionnelles
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive or regulated data
    text: de soumettre à la Solution des données relevant des catégories particulières visées à l'article 9 du RGPD, des données relatives à des condamnations pénales, des données de santé, des données bancaires ou des données concernant des mineurs
  - summary: High-risk AI uses
    text: Le Client s'interdit d'utiliser la Solution dans le cadre de l'un des cas d'usage visés à l'annexe III de l'AI Act
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: TW3 se réserve la faculté de solliciter à tout moment tout justificatif de la qualité et de l'établissement du Client
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Citead
provenance_date: '2026-11-09'
provider_name: Citead
provider_slug: citead-com
slug: citead-com-eligibility
source_date: '2026-11-09'
source_filename: citead-com-eligibility.yml
source_heading: Eligibility
source_page: https://citead.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Citead\naid: citead-com\nurl: https://citead.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: La Solution est réservée aux professionnels établis dans l'Union européenne.\nentity_types:\n- type: business\n  text: agissant dans le cadre de leur activité commerciale, industrielle, artisanale, libérale ou agricole\n- type: individual\n  text: toute personne morale ou physique agissant à des fins professionnelles\nrestricted_uses:\n- summary: Sensitive or regulated data\n  text: de soumettre à la Solution des données relevant des catégories particulières visées à l'article 9\
  \ du RGPD,\n    des données relatives à des condamnations pénales, des données de santé, des données bancaires ou des données\n    concernant des mineurs\n- summary: High-risk AI uses\n  text: Le Client s'interdit d'utiliser la Solution dans le cadre de l'un des cas d'usage visés à l'annexe III de\n    l'AI Act\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: TW3 se réserve la faculté de solliciter à tout moment tout justificatif de la qualité et de l'établissement\n    du Client\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/citead-com/eligibility/citead-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Citead's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- SEO
- Content Optimization
- Generative
---
