---
api_specs:
- filename: delphi-audience-api-openapi.yml
  format: yaml
  label: Delphi Audience API
  slug: delphi-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-audience-api-openapi.yml
- filename: delphi-clone-api-openapi.yml
  format: yaml
  label: Delphi Clone API
  slug: delphi-clone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-clone-api-openapi.yml
- filename: delphi-conversations-api-openapi.yml
  format: yaml
  label: Delphi Conversations API
  slug: delphi-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-conversations-api-openapi.yml
- filename: delphi-questions-api-openapi.yml
  format: yaml
  label: Delphi Questions API
  slug: delphi-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-questions-api-openapi.yml
- filename: delphi-search-api-openapi.yml
  format: yaml
  label: Delphi Search API
  slug: delphi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-search-api-openapi.yml
- filename: delphi-tags-api-openapi.yml
  format: yaml
  label: Delphi Tags API
  slug: delphi-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-tags-api-openapi.yml
- filename: delphi-usage-api-openapi.yml
  format: yaml
  label: Delphi Usage API
  slug: delphi-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-usage-api-openapi.yml
- filename: delphi-voice-api-openapi.yml
  format: yaml
  label: Delphi Voice API
  slug: delphi-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-voice-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you've received your parent's or guardian's permission to use the Services and have gotten your parent or guardian to agree to these Terms on your behalf).
    type: individual
  - text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization's or entity's behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 13 years of age; if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services
    value: '13'
  restricted_uses:
  - summary: Children under 13
    text: We do not knowingly collect or solicit personally identifiable information from children under 13 years of age; if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Services
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
name: Delphi
provenance_date: '2026-11-09'
provider_name: Delphi
provider_slug: delphi
slug: delphi-eligibility
source_date: '2026-11-09'
source_filename: delphi-eligibility.yml
source_heading: Eligibility
source_page: https://www.delphi.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Delphi\naid: delphi\nurl: https://www.delphi.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you've received your parent's or guardian's permission to use the Services and have gotten your parent or guardian\n    to agree to these Terms on your behalf).\n- type: business\n  text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are\
  \ authorized to agree to these Terms on that organization's or entity's behalf\nrestricted_uses:\n- summary: Children under 13\n  text: We do not knowingly collect or solicit personally identifiable information from children under 13 years\n    of age; if you are a child under 13 years of age, please do not attempt to register for or otherwise use the\n    Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 13 years\n    of age; if you are a child under 13 years of age, please do not attempt to register for or otherwise use the\n    Services\n"
source_yaml_url: https://artifacts.apis.io/delphi/eligibility/delphi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Delphi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Clones
- Digital Minds
- Conversational AI
- Voice
- Search
- RAG
- Knowledge Base
- Creator Economy
- Webhook
---
