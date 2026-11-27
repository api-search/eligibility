---
api_specs:
- filename: deepl-voice-api-openapi.yml
  format: yaml
  label: DeepL Voice API
  slug: deepl-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-voice-api-openapi.yml
- filename: deepl-adminapi-api-openapi.yml
  format: yaml
  label: DeepL Admin API
  slug: deepl-adminapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-adminapi-api-openapi.yml
- filename: deepl-correcttext-api-openapi.yml
  format: yaml
  label: DeepL Correct Text API
  slug: deepl-correcttext-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-correcttext-api-openapi.yml
- filename: deepl-manageglossaries-api-openapi.yml
  format: yaml
  label: DeepL Manage Glossaries API
  slug: deepl-manageglossaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-manageglossaries-api-openapi.yml
- filename: deepl-managemultilingualglossaries-api-openapi.yml
  format: yaml
  label: DeepL Manage Multilingual Glossaries API
  slug: deepl-managemultilingualglossaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-managemultilingualglossaries-api-openapi.yml
- filename: deepl-managespokenterms-api-openapi.yml
  format: yaml
  label: DeepL Manage Spoken Terms API
  slug: deepl-managespokenterms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-managespokenterms-api-openapi.yml
- filename: deepl-metainformation-api-openapi.yml
  format: yaml
  label: DeepL Meta Information API
  slug: deepl-metainformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-metainformation-api-openapi.yml
- filename: deepl-qualityevaluation-api-openapi.yml
  format: yaml
  label: DeepL Quality Evaluation API
  slug: deepl-qualityevaluation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-qualityevaluation-api-openapi.yml
- filename: deepl-rephrasetext-api-openapi.yml
  format: yaml
  label: DeepL Rephrase Text API
  slug: deepl-rephrasetext-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-rephrasetext-api-openapi.yml
- filename: deepl-style-rules-api-openapi.yml
  format: yaml
  label: DeepL Style Rules API
  slug: deepl-style-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-style-rules-api-openapi.yml
- filename: deepl-translatedocuments-api-openapi.yml
  format: yaml
  label: DeepL Translate Documents API
  slug: deepl-translatedocuments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-translatedocuments-api-openapi.yml
- filename: deepl-translatetext-api-openapi.yml
  format: yaml
  label: DeepL Translate Text API
  slug: deepl-translatetext-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-translatetext-api-openapi.yml
- filename: deepl-translationmemories-api-openapi.yml
  format: yaml
  label: DeepL Translation Memories API
  slug: deepl-translationmemories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-translationmemories-api-openapi.yml
- filename: deepl-voiceapi-api-openapi.yml
  format: yaml
  label: DeepL Voice API
  slug: deepl-voiceapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-voiceapi-api-openapi.yml
- filename: deepl-voicetranslatejob-api-openapi.yml
  format: yaml
  label: DeepL Voice Translate Job API
  slug: deepl-voicetranslatejob-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepl/openapi/deepl-voicetranslatejob-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: DeepL does not offer the Services in the listed restricted territories which may be updated from time to time giving reasonable notice.
  entity_types:
  - text: refers to the person or entity ordering or subscribing to the DeepL Services
    type: individual
  - text: If you place the order in a business capacity, the entity you work for will be the Customer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Critical infrastructure and defence
    text: in connection with or for the purpose of operating critical infrastructure such as electrical power stations, military or defence equipment, medical appliances
  - summary: Prohibited AI uses under EU AI Act
    text: in such a way that Article 5 of the EU AI Act
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: DeepL reserves the right to reject Customer requests to conclude a contract.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DeepL
provenance_date: '2026-11-09'
provider_name: DeepL
provider_slug: deepl
slug: deepl-eligibility
source_date: '2026-11-09'
source_filename: deepl-eligibility.yml
source_heading: Eligibility
source_page: https://www.deepl.com/en/pro-license
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DeepL\naid: deepl\nurl: https://www.deepl.com/en/pro-license\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: DeepL does not offer the Services in the listed restricted territories which may be updated from time to\n    time giving reasonable notice.\nentity_types:\n- type: individual\n  text: refers to the person or entity ordering or subscribing to the DeepL Services\n- type: business\n  text: If you place the order in a business capacity, the entity you work for will be the Customer.\nrestricted_uses:\n- summary: Critical infrastructure and defence\n  text: in\
  \ connection with or for the purpose of operating critical infrastructure such as electrical power stations,\n    military or defence equipment, medical appliances\n- summary: Prohibited AI uses under EU AI Act\n  text: in such a way that Article 5 of the EU AI Act\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: DeepL reserves the right to reject Customer requests to conclude a contract.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/deepl/eligibility/deepl-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from DeepL's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Deep Learning
- Glossary
- Localization
- Machine Learning
- Machine Translation
- Translation
- Real-Time
---
