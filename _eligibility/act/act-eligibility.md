---
api_specs:
- filename: v1
  format: yaml
  label: Act! Web API
  slug: web-api
  spec_type: OpenAPI
  url: https://apimta.act.com/act.web.api/swagger/docs/v1
- filename: act-activityseries-api-openapi.yml
  format: yaml
  label: Act! CRM Activity Series API
  slug: act-activityseries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-activityseries-api-openapi.yml
- filename: act-historytypes-api-openapi.yml
  format: yaml
  label: Act! CRM History Types API
  slug: act-historytypes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-historytypes-api-openapi.yml
- filename: act-marketingautomations-api-openapi.yml
  format: yaml
  label: Act! CRM Marketing Automations API
  slug: act-marketingautomations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-marketingautomations-api-openapi.yml
- filename: act-metadatainfo-api-openapi.yml
  format: yaml
  label: Act! CRM Metadata Info API
  slug: act-metadatainfo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-metadatainfo-api-openapi.yml
- filename: act-secondarycontacts-api-openapi.yml
  format: yaml
  label: Act! CRM Secondary Contacts API
  slug: act-secondarycontacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-secondarycontacts-api-openapi.yml
- filename: act-supplementalfiles-api-openapi.yml
  format: yaml
  label: Act! CRM Supplemental Files API
  slug: act-supplementalfiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-supplementalfiles-api-openapi.yml
- filename: act-custom-entities-api-openapi.yml
  format: yaml
  label: Act! CRM Custom Entities API
  slug: act-custom-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-custom-entities-api-openapi.yml
- filename: act-document-types-api-openapi.yml
  format: yaml
  label: Act! CRM Document Types API
  slug: act-document-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-document-types-api-openapi.yml
- filename: act-sync-data-api-openapi.yml
  format: yaml
  label: Act! CRM Sync Data API
  slug: act-sync-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-sync-data-api-openapi.yml
- filename: act-task-types-api-openapi.yml
  format: yaml
  label: Act! CRM Task Types API
  slug: act-task-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-task-types-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if You represent an entity or other organization, that entity or organization (in either case “You”)
    type: business
  minimum_age:
    text: The Services are not available to individuals under the age of 18 or who do not meet any of the other qualifications included in this Agreement.
    value: '18'
  restricted_uses:
  - summary: No unsolicited email harvesting
    text: use the Site, Services or any Software to harvest or collect e- mail addresses or other contact information of third parties by any means for the purposes of sending unsolicited e-mails or other unsolicited communications
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
name: Act! CRM
provenance_date: '2026-11-09'
provider_name: Act! CRM
provider_slug: act
slug: act-eligibility
source_date: '2026-11-09'
source_filename: act-eligibility.yml
source_heading: Eligibility
source_page: https://www.act.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Act! CRM\naid: act\nurl: https://www.act.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if You represent an entity or other organization, that entity or organization (in either case “You”)\nrestricted_uses:\n- summary: No unsolicited email harvesting\n  text: use the Site, Services or any Software to harvest or collect e- mail addresses or other contact information\n    of third parties by any means for the purposes of sending unsolicited e-mails or other unsolicited communications\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not available to individuals under the age of 18 or who do not meet any of the other qualifications\n    included in this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/act/eligibility/act-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Act! CRM's own page on 2026-11-09.
synthetic: false
tags:
- CRM
- Marketing Automation
- Contact Management
- Sales
- Opportunity Management
- OData
- Small Business
---
