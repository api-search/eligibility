---
api_specs:
- filename: gapup-io-openapi-generated.yml
  format: yaml
  label: gapup-io API
  slug: gapup-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gapup-io/openapi/_ae-authored/gapup-io-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Un abonnement est lié à une seule entité légale ou personne physique
    type: individual
  - text: Un abonnement est lié à une seule entité légale ou personne physique
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal, defamatory or hateful content
    text: d'utiliser le service pour générer des contenus illégaux, diffamatoires, haineux ou contraires à l'ordre public
  - summary: No non-consensual deepfakes or mass manipulative content
    text: d'utiliser le service pour générer du spam, des deepfakes non consentis, ou tout contenu manipulatoire à grande échelle
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
name: gapup-io
provenance_date: '2026-11-09'
provider_name: gapup-io
provider_slug: gapup-io
slug: gapup-io-eligibility
source_date: '2026-11-09'
source_filename: gapup-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.gapup.io/legal/cgu
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: gapup-io\naid: gapup-io\nurl: https://www.gapup.io/legal/cgu\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Un abonnement est lié à une seule entité légale ou personne physique\n- type: business\n  text: Un abonnement est lié à une seule entité légale ou personne physique\nrestricted_uses:\n- summary: No illegal, defamatory or hateful content\n  text: d'utiliser le service pour générer des contenus illégaux, diffamatoires, haineux ou contraires à l'ordre\n    public\n- summary: No non-consensual deepfakes or mass manipulative content\n\
  \  text: d'utiliser le service pour générer du spam, des deepfakes non consentis, ou tout contenu manipulatoire à\n    grande échelle\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gapup-io/eligibility/gapup-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from gapup-io's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Finance
- Compliance
- Enterprise
---
