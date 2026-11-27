---
api_specs:
- filename: linkedin-ads-adbudgetpricing-api-openapi.yml
  format: yaml
  label: LinkedIn Marketing API AdBudgetPricing API
  slug: linkedin-ads-adbudgetpricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkedin-ads/openapi/linkedin-ads-adbudgetpricing-api-openapi.yml
- filename: linkedin-ads-adtargetingfacets-api-openapi.yml
  format: yaml
  label: LinkedIn Marketing API AdTargetingFacets API
  slug: linkedin-ads-adtargetingfacets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkedin-ads/openapi/linkedin-ads-adtargetingfacets-api-openapi.yml
- filename: linkedin-ads-ad-accounts-api-openapi.yml
  format: yaml
  label: LinkedIn Marketing API Ad Accounts API
  slug: linkedin-ads-ad-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkedin-ads/openapi/linkedin-ads-ad-accounts-api-openapi.yml
- filename: linkedin-ads-ad-targeting-entities-api-openapi.yml
  format: yaml
  label: LinkedIn Marketing API Ad Targeting Entities API
  slug: linkedin-ads-ad-targeting-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkedin-ads/openapi/linkedin-ads-ad-targeting-entities-api-openapi.yml
- filename: linkedin-ads-audience-counts-api-openapi.yml
  format: yaml
  label: LinkedIn Marketing API Audience Counts API
  slug: linkedin-ads-audience-counts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkedin-ads/openapi/linkedin-ads-audience-counts-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Contracting entity depends on whether you reside in the Designated Countries (EU, EEA, Switzerland and the United Kingdom).
  entity_types:
  - text: If you are developing on our platform on behalf of a company or other entity, you represent and warrant that you have full legal authority to register an Application on behalf of that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Advertising use of Content
    text: you DO NOT intend to use, sell, transfer or process Content for the purposes of advertising.
  - summary: Surveillance use
    text: Use Content, or distribute or transfer Content for use, in any manner that facilitates surveillance, including by any government entity
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
name: LinkedIn Marketing API
provenance_date: '2026-11-09'
provider_name: LinkedIn Marketing API
provider_slug: linkedin-ads
slug: linkedin-ads-eligibility
source_date: '2026-11-09'
source_filename: linkedin-ads-eligibility.yml
source_heading: Eligibility
source_page: https://www.linkedin.com/legal/l/api-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LinkedIn Marketing API\naid: linkedin-ads\nurl: https://www.linkedin.com/legal/l/api-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Contracting entity depends on whether you reside in the Designated Countries (EU, EEA, Switzerland and the\n    United Kingdom).\nentity_types:\n- type: business\n  text: If you are developing on our platform on behalf of a company or other entity, you represent and warrant\n    that you have full legal authority to register an Application on behalf of that entity\nrestricted_uses:\n- summary: Advertising use of Content\n  text: you DO\
  \ NOT intend to use, sell, transfer or process Content for the purposes of advertising.\n- summary: Surveillance use\n  text: Use Content, or distribute or transfer Content for use, in any manner that facilitates surveillance, including\n    by any government entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/linkedin-ads/eligibility/linkedin-ads-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from LinkedIn Marketing API's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Marketing
- LinkedIn
- Lead Generation
- Audience Targeting
- Conversions API
- Social Marketing
---
