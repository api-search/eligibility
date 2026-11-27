---
api_specs:
- filename: callfire-callfire-api-api-openapi.yml
  format: yaml
  label: Callfire Callfire API
  slug: callfire-callfire-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-callfire-api-api-openapi.yml
- filename: callfire-callfirexml-api-openapi.yml
  format: yaml
  label: Callfire Callfirexml API
  slug: callfire-callfirexml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-callfirexml-api-openapi.yml
- filename: callfire-calls-api-openapi.yml
  format: yaml
  label: Callfire Calls API
  slug: callfire-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-calls-api-openapi.yml
- filename: callfire-campaign-api-openapi.yml
  format: yaml
  label: Callfire Campaign API
  slug: callfire-campaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-campaign-api-openapi.yml
- filename: callfire-contacts-api-openapi.yml
  format: yaml
  label: Callfire Contacts API
  slug: callfire-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-contacts-api-openapi.yml
- filename: callfire-files-api-openapi.yml
  format: yaml
  label: Callfire Files API
  slug: callfire-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-files-api-openapi.yml
- filename: callfire-inbound-api-openapi.yml
  format: yaml
  label: Callfire Inbound API
  slug: callfire-inbound-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-inbound-api-openapi.yml
- filename: callfire-me-api-openapi.yml
  format: yaml
  label: Callfire Me API
  slug: callfire-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-me-api-openapi.yml
- filename: callfire-reports-api-openapi.yml
  format: yaml
  label: Callfire Reports API
  slug: callfire-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-reports-api-openapi.yml
- filename: callfire-service-api-openapi.yml
  format: yaml
  label: Callfire Service API
  slug: callfire-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-service-api-openapi.yml
- filename: callfire-sms-api-openapi.yml
  format: yaml
  label: Callfire Sms API
  slug: callfire-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-sms-api-openapi.yml
- filename: callfire-utils-api-openapi.yml
  format: yaml
  label: Callfire Utils API
  slug: callfire-utils-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callfire/openapi/callfire-utils-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services described on the EZ Texting Sites may or may not be available in all countries or regions of the world
  entity_types:
  - text: By accessing one of our Services, you represent that you have reached the age of majority for where you live or that you have had a parent or legal guardian consent to be bound by these Terms.
    type: individual
  minimum_age:
    text: By accessing one of our Services, you represent that you have reached the age of majority for where you live or that you have had a parent or legal guardian consent
    value: null
  restricted_uses:
  - summary: Prohibited uses
    text: Transmitting, associating, or publishing any unlawful, racist, harassing, defamatory, abusive, threatening, demeaning, immoral, harmful, vulgar, obscene, pornographic, or otherwise objectionable material of any kind
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
name: Callfire
provenance_date: '2026-11-09'
provider_name: Callfire
provider_slug: callfire
slug: callfire-eligibility
source_date: '2026-11-09'
source_filename: callfire-eligibility.yml
source_heading: Eligibility
source_page: https://www.callfire.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Callfire\naid: callfire\nurl: https://www.callfire.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Services described on the EZ Texting Sites may or may not be available in all countries or regions of the\n    world\nentity_types:\n- type: individual\n  text: By accessing one of our Services, you represent that you have reached the age of majority for where you\n    live or that you have had a parent or legal guardian consent to be bound by these Terms.\nrestricted_uses:\n- summary: Prohibited uses\n  text: Transmitting, associating, or publishing any unlawful, racist,\
  \ harassing, defamatory, abusive, threatening,\n    demeaning, immoral, harmful, vulgar, obscene, pornographic, or otherwise objectionable material of any kind\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By accessing one of our Services, you represent that you have reached the age of majority for where you\n    live or that you have had a parent or legal guardian consent\n"
source_yaml_url: https://artifacts.apis.io/callfire/eligibility/callfire-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Callfire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Communications
- Cloud
- Messaging
- Voice
---
