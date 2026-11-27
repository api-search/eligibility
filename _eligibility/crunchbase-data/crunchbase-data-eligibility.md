---
api_specs:
- filename: crunchbase-data-autocomplete-api-openapi.yml
  format: yaml
  label: Crunchbase Autocomplete API
  slug: crunchbase-data-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-autocomplete-api-openapi.yml
- filename: crunchbase-data-deleted-entities-api-openapi.yml
  format: yaml
  label: Crunchbase Deleted Entities API
  slug: crunchbase-data-deleted-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-deleted-entities-api-openapi.yml
- filename: crunchbase-data-entity-api-openapi.yml
  format: yaml
  label: Crunchbase Entity API
  slug: crunchbase-data-entity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-entity-api-openapi.yml
- filename: crunchbase-data-metadata-api-openapi.yml
  format: yaml
  label: Crunchbase Metadata API
  slug: crunchbase-data-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-metadata-api-openapi.yml
- filename: crunchbase-data-search-api-openapi.yml
  format: yaml
  label: Crunchbase Search API
  slug: crunchbase-data-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-search-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: the Service may not be exported or re-exported (a) into any U.S. embargoed countries or any country that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: You represent and warrant that you are of legal age to form a binding contract
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity’s behalf
    type: business
  minimum_age:
    text: if you are a child under 16, please do not attempt to register for the Service or send any personal information about yourself to us.
    value: '16'
  restricted_uses:
  - summary: Model training on Content
    text: Uses or allows the Content to be used to train models (including generative artificial intelligence technologies)
  - summary: Sensitive personal information in submissions
    text: You are prohibited from including Social Security Numbers, driver’s license numbers, passport numbers, financial account and payment card information, precise geolocation, health and biometric information
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
name: Crunchbase
provenance_date: '2026-11-09'
provider_name: Crunchbase
provider_slug: crunchbase-data
slug: crunchbase-data-eligibility
source_date: '2026-11-09'
source_filename: crunchbase-data-eligibility.yml
source_heading: Eligibility
source_page: https://about.crunchbase.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crunchbase\naid: crunchbase-data\nurl: https://about.crunchbase.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: the Service may not be exported or re-exported (a) into any U.S. embargoed countries or any country that\n    has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: You represent and warrant that you are of legal age to form a binding contract\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you\
  \ are authorized to agree to these Terms on that organization or entity’s behalf\nrestricted_uses:\n- summary: Model training on Content\n  text: Uses or allows the Content to be used to train models (including generative artificial intelligence technologies)\n- summary: Sensitive personal information in submissions\n  text: You are prohibited from including Social Security Numbers, driver’s license numbers, passport numbers, financial\n    account and payment card information, precise geolocation, health and biometric information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: if you are a child under 16, please do not attempt to register for the Service or send any personal information\n    about yourself to us.\n"
source_yaml_url: https://artifacts.apis.io/crunchbase-data/eligibility/crunchbase-data-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Crunchbase's own page on 2026-11-09.
synthetic: false
tags:
- Company Data
- Web Intelligence
- Funding Data
- Firmographics
- B2B Data
- investor-data
- Reference Data
- Private Markets
- Predictions
- Market Insights
- MCP
- Fortune 1000
- Startups
---
