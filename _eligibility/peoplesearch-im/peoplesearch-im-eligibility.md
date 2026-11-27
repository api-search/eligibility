---
api_specs:
- filename: peoplesearch-im-credits-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Credits API
  slug: peoplesearch-im-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-credits-api-openapi.yml
- filename: peoplesearch-im-deliver-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Deliver API
  slug: peoplesearch-im-deliver-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-deliver-api-openapi.yml
- filename: peoplesearch-im-email-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Email API
  slug: peoplesearch-im-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-email-api-openapi.yml
- filename: peoplesearch-im-reveal-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Reveal API
  slug: peoplesearch-im-reveal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-reveal-api-openapi.yml
- filename: peoplesearch-im-search-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Search API
  slug: peoplesearch-im-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-search-api-openapi.yml
- filename: peoplesearch-im-tools-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Tools API
  slug: peoplesearch-im-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-tools-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company or other organization, you represent that you have authority to bind that entity to these Terms, and in that case "you" refers to that entity.
    type: business
  minimum_age:
    text: You may use it only if you meet the minimum age required to consent to the processing of your personal data in your country, or the age of majority where that is higher.
    value: null
  restricted_uses:
  - summary: Unlawful or objectionable content
    text: upload, post, or transmit any content that is unlawful, harmful, harassing, defamatory, obscene, deceptive, or otherwise objectionable
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
name: PeopleSearch.im
provenance_date: '2026-11-10'
provider_name: PeopleSearch.im
provider_slug: peoplesearch-im
slug: peoplesearch-im-eligibility
source_date: '2026-11-10'
source_filename: peoplesearch-im-eligibility.yml
source_heading: Eligibility
source_page: https://peoplesearch.im/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PeopleSearch.im\naid: peoplesearch-im\nurl: https://peoplesearch.im/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company or other organization, you represent that you have authority\n    to bind that entity to these Terms, and in that case \"you\" refers to that entity.\nrestricted_uses:\n- summary: Unlawful or objectionable content\n  text: upload, post, or transmit any content that is unlawful, harmful, harassing, defamatory, obscene, deceptive,\n    or otherwise objectionable\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may use it only if you meet the minimum age required to consent to the processing of your personal data\n    in your country, or the age of majority where that is higher.\n"
source_yaml_url: https://artifacts.apis.io/peoplesearch-im/eligibility/peoplesearch-im-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from PeopleSearch.im's own page on 2026-11-10.
synthetic: false
tags:
- Company
- People Search
- Email Lookup
- Artificial Intelligence
- Software-as-a-Service
---
