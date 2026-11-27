---
api_specs:
- filename: languagetool-check-api-openapi.yml
  format: yaml
  label: LanguageTool Check API
  slug: languagetool-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/languagetool/openapi/languagetool-check-api-openapi.yml
- filename: languagetool-languages-api-openapi.yml
  format: yaml
  label: LanguageTool Languages API
  slug: languagetool-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/languagetool/openapi/languagetool-languages-api-openapi.yml
- filename: languagetool-words-api-openapi.yml
  format: yaml
  label: LanguageTool Words API
  slug: languagetool-words-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/languagetool/openapi/languagetool-words-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The LanguageTool Services may only be used for personal, non-commercial purposes
    type: individual
  - text: If you are a business customer who signed a separate services agreement for your use of the LanguageTool Services, these General Terms and Conditions do not apply to you
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal non-commercial only
    text: The LanguageTool Services may only be used for personal, non-commercial purposes
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
name: LanguageTool
provenance_date: '2026-11-09'
provider_name: LanguageTool
provider_slug: languagetool
slug: languagetool-eligibility
source_date: '2026-11-09'
source_filename: languagetool-eligibility.yml
source_heading: Eligibility
source_page: https://languagetool.org/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LanguageTool\naid: languagetool\nurl: https://languagetool.org/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The LanguageTool Services may only be used for personal, non-commercial purposes\n- type: business\n  text: If you are a business customer who signed a separate services agreement for your use of the LanguageTool\n    Services, these General Terms and Conditions do not apply to you\nrestricted_uses:\n- summary: Personal non-commercial only\n  text: The LanguageTool Services may only be used for personal, non-commercial\
  \ purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/languagetool/eligibility/languagetool-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from LanguageTool's own page on 2026-11-09.
synthetic: false
tags:
- Grammar
- Language
- Proofreading
- Spell Check
- Style Check
- Text Analysis
---
