---
api_specs:
- filename: re-max-canada-blog-wp-json-index.json
  format: json
  label: RE/MAX Canada Website (WordPress REST)
  slug: blog-remax-ca-website-wordpress-rest
  spec_type: OpenAPI
  url: https://artifacts.apis.io/re-max-canada/openapi/re-max-canada-blog-wp-json-index.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Les services fournissent des renseignements sur des propriétés dans les provinces et territoires de l’Alberta, de la Colombie-Britannique, du Manitoba
  entity_types:
  - text: Si la personne qui accepte les présentes conditions d’utilisation le fait au nom d’une société ou d’une autre entité juridique
    type: business
  minimum_age:
    text: Si vous n’avez pas atteint l’âge de la majorité dans votre province de résidence, soit 18 ou 19 ans selon la province (un “mineur” ), vous pouvez utiliser nos services avec la supervision d’un parent seulement.
    value: 18 or 19 (by province)
  restricted_uses:
  - summary: Price estimates for personal use only
    text: les estimations de prix peuvent uniquement être utilisées à des fins personnelles, et non professionnelles, pour votre évaluation de propriétés
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
name: RE/MAX Canada
provenance_date: '2026-11-10'
provider_name: RE/MAX Canada
provider_slug: re-max-canada
slug: re-max-canada-eligibility
source_date: '2026-11-10'
source_filename: re-max-canada-eligibility.yml
source_heading: Eligibility
source_page: https://www.remax.ca/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RE/MAX Canada\naid: re-max-canada\nurl: https://www.remax.ca/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Les services fournissent des renseignements sur des propriétés dans les provinces et territoires de l’Alberta,\n    de la Colombie-Britannique, du Manitoba\nentity_types:\n- type: business\n  text: Si la personne qui accepte les présentes conditions d’utilisation le fait au nom d’une société ou d’une\n    autre entité juridique\nrestricted_uses:\n- summary: Price estimates for personal use only\n  text: les estimations de prix peuvent uniquement\
  \ être utilisées à des fins personnelles, et non professionnelles,\n    pour votre évaluation de propriétés\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 18 or 19 (by province)\n  text: Si vous n’avez pas atteint l’âge de la majorité dans votre province de résidence, soit 18 ou 19 ans selon\n    la province (un “mineur” ), vous pouvez utiliser nos services avec la supervision d’un parent seulement.\n"
source_yaml_url: https://artifacts.apis.io/re-max-canada/eligibility/re-max-canada-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from RE/MAX Canada's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Canada
- Brokerage
- Property Listings
- MLS
- RESO
- IDX
- PropTech
- Land Registry
- Valuation
- Rentals
- Franchising
---
