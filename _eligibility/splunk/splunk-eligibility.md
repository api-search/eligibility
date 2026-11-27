---
api_specs:
- filename: splunk-data-inputs-api-openapi.yml
  format: yaml
  label: Splunk Data Inputs API
  slug: splunk-data-inputs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splunk/openapi/splunk-data-inputs-api-openapi.yml
- filename: splunk-index-api-openapi.yml
  format: yaml
  label: Splunk Index API
  slug: splunk-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splunk/openapi/splunk-index-api-openapi.yml
- filename: splunk-search-api-openapi.yml
  format: yaml
  label: Splunk Search API
  slug: splunk-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splunk/openapi/splunk-search-api-openapi.yml
claim_count: 8
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: a citizen or permanent resident of any country on which the United States has embargoed goods, technology and/or services (e.g., Cuba, Iran, North Korea, Sudan, Syria, or Crimea)
  entity_types:
  - text: “you” or “your” refer to you personally (i.e., the individual who reads and agrees to be bound by these Terms)
    type: individual
  - text: if you access this Site on behalf of a corporation or other legal entity, you and such corporation or other legal entity on whose behalf you access the Site.
    type: business
  - source: https://www.splunk.com/en_us/legal/splunk-general-terms.html
    text: If you are entering into these General Terms on behalf of Customer, you represent that you have the authority to bind Customer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or unlawful purpose
    text: Use the Site for any fraudulent or unlawful purpose.
  - summary: AI Search used to develop machine learning models
    text: You may not use AI Search to develop machine learning models, related technology, or to create any competing products or services.
  - source: https://www.splunk.com/en_us/legal/splunk-general-terms.html
    summary: No PHI, PCI or ITAR data in Hosted Services unless specifically acquired
    text: You may not transmit or store PHI, PCI Data or ITAR Data within a Hosted Services unless you have specifically acquired an Offering for that applicable regulated Hosted Services environment.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with Splunk in order to access certain areas of the Site.
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Splunk
provenance_date: '2026-11-10'
provider_name: Splunk
provider_slug: splunk
slug: splunk-eligibility
source_date: '2026-11-10'
source_filename: splunk-eligibility.yml
source_heading: Eligibility
source_page: https://www.splunk.com/en_us/legal/terms/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Splunk\naid: splunk\nurl: https://www.splunk.com/en_us/legal/terms/terms-of-use.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.splunk.com/en_us/legal/splunk-general-terms.html\n  - https://www.splunk.com/en_us/legal/terms/terms-of-use.html\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: a citizen or permanent resident of any country on which the United States has embargoed goods, technology\n    and/or services (e.g., Cuba, Iran, North Korea, Sudan, Syria, or Crimea)\nentity_types:\n- type: individual\n  text: “you” or “your” refer to you personally (i.e.,\
  \ the individual who reads and agrees to be bound by these\n    Terms)\n- type: business\n  text: if you access this Site on behalf of a corporation or other legal entity, you and such corporation or other\n    legal entity on whose behalf you access the Site.\n- type: business\n  text: If you are entering into these General Terms on behalf of Customer, you represent that you have the authority\n    to bind Customer.\n  source: https://www.splunk.com/en_us/legal/splunk-general-terms.html\nrestricted_uses:\n- summary: Fraudulent or unlawful purpose\n  text: Use the Site for any fraudulent or unlawful purpose.\n- summary: AI Search used to develop machine learning models\n  text: You may not use AI Search to develop machine learning models, related technology, or to create any competing\n    products or services.\n- summary: No PHI, PCI or ITAR data in Hosted Services unless specifically acquired\n  text: You may not transmit or store PHI, PCI Data or ITAR Data within a Hosted Services unless\
  \ you have specifically\n    acquired an Offering for that applicable regulated Hosted Services environment.\n  source: https://www.splunk.com/en_us/legal/splunk-general-terms.html\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with Splunk in order to access certain areas of the Site.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/splunk/eligibility/splunk-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 8 quoted statements, read from Splunk's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Data Analysis
- Logging
- Machine Data
- Monitoring
- Observability
- Platform
- Security
- SIEM
---
