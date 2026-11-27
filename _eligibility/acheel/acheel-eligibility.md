---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: Client doit être un résident fiscal en France.
  entity_types:
  - text: Le Client soit majeur et juridiquement capable ;
    type: individual
  minimum_age:
    text: Le Client soit majeur et juridiquement capable ;
    value: '18'
  restricted_uses:
  - summary: Fraudulent use of personal space
    text: en cas d’utilisation frauduleuse ou tentative d’utilisation frauduleuse de son Espace Personnel, Acheel pourra procéder à la suppression de son compte.
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
name: Acheel
provenance_date: '2026-11-09'
provider_name: Acheel
provider_slug: acheel
slug: acheel-eligibility
source_date: '2026-11-09'
source_filename: acheel-eligibility.yml
source_heading: Eligibility
source_page: https://v2.acheel.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Acheel\naid: acheel\nurl: https://v2.acheel.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: Client doit être un résident fiscal en France.\nentity_types:\n- type: individual\n  text: Le Client soit majeur et juridiquement capable ;\nrestricted_uses:\n- summary: Fraudulent use of personal space\n  text: en cas d’utilisation frauduleuse ou tentative d’utilisation frauduleuse de son Espace Personnel, Acheel\n    pourra procéder à la suppression de son compte.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: Le Client soit majeur et juridiquement capable ;\n"
source_yaml_url: https://artifacts.apis.io/acheel/eligibility/acheel-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Acheel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech Insurtech
- Insurance
- Insurtech
- Digital Insurance
- Home Insurance
- Auto Insurance
- Health Insurance
- Pet Insurance
- White Label
- B2B2C
- Embedded Insurance
- France
---
