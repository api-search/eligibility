---
api_specs:
- filename: evaboot-com-account-api-openapi.yml
  format: yaml
  label: Evaboot Account API
  slug: evaboot-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evaboot-com/openapi/evaboot-com-account-api-openapi.yml
- filename: evaboot-com-email-finder-api-openapi.yml
  format: yaml
  label: Evaboot Email Finder API
  slug: evaboot-com-email-finder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evaboot-com/openapi/evaboot-com-email-finder-api-openapi.yml
- filename: evaboot-com-email-verifier-api-openapi.yml
  format: yaml
  label: Evaboot Email Verifier API
  slug: evaboot-com-email-verifier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evaboot-com/openapi/evaboot-com-email-verifier-api-openapi.yml
- filename: evaboot-com-linkedin-extraction-api-openapi.yml
  format: yaml
  label: Evaboot LinkedIn Extraction API
  slug: evaboot-com-linkedin-extraction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evaboot-com/openapi/evaboot-com-linkedin-extraction-api-openapi.yml
- filename: evaboot-com-search-builder-api-openapi.yml
  format: yaml
  label: Evaboot Search Builder API
  slug: evaboot-com-search-builder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evaboot-com/openapi/evaboot-com-search-builder-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are available only to individuals who are at least 18 years old.
    type: individual
  - text: '"Customer" : designates the natural person or legal entity having entered into these Terms and Conditions for professional purposes.'
    type: business
  minimum_age:
    text: The Services are available only to individuals who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Lawful LinkedIn Sales Navigator users only
    text: The Customer shall only use the Services provided that it is a legitimate and registered user of LinkedIn Sales Navigator
  - summary: No competing service
    text: Build a similar or competitive service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Customer must be a human. Accounts registered by "bots" or other automated methods are not permitted.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Evaboot
provenance_date: '2026-11-09'
provider_name: Evaboot
provider_slug: evaboot-com
slug: evaboot-com-eligibility
source_date: '2026-11-09'
source_filename: evaboot-com-eligibility.yml
source_heading: Eligibility
source_page: https://evaboot.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evaboot\naid: evaboot-com\nurl: https://evaboot.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are available only to individuals who are at least 18 years old.\n- type: business\n  text: '\"Customer\" : designates the natural person or legal entity having entered into these Terms and Conditions\n    for professional purposes.'\nrestricted_uses:\n- summary: Lawful LinkedIn Sales Navigator users only\n  text: The Customer shall only use the Services provided that it is a legitimate and registered user\
  \ of LinkedIn\n    Sales Navigator\n- summary: No competing service\n  text: Build a similar or competitive service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Customer must be a human. Accounts registered by \"bots\" or other automated methods are not permitted.\nminimum_age:\n  value: '18'\n  text: The Services are available only to individuals who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/evaboot-com/eligibility/evaboot-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Evaboot's own page on 2026-11-09.
synthetic: false
tags:
- Lead Generation
- Sales
- Data Cleaning
- Email Verification
- Chrome Extension
---
