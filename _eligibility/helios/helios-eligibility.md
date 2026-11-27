---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: aucun des produits et services ne sera fourni par l’éditeur à une personne si la loi de son pays d'origine ou de tout autre pays qui la concernerait l'interdit.
  minimum_age:
    text: null
    value: null
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
name: helios
provenance_date: '2026-11-09'
provider_name: helios
provider_slug: helios
slug: helios-eligibility
source_date: '2026-11-09'
source_filename: helios-eligibility.yml
source_heading: Eligibility
source_page: https://www.helios.do/documents/Conditions_Generales_Helios.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: helios\naid: helios\nurl: https://www.helios.do/documents/Conditions_Generales_Helios.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: aucun des produits et services ne sera fourni par l’éditeur à une personne si la loi de son pays d'origine\n    ou de tout autre pays qui la concernerait l'interdit.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/helios/eligibility/helios-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from helios's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Fintech
- Neobank
- Sustainable Finance
- Payments
- Climate Tech
- France
---
