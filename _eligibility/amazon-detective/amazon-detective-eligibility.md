---
api_specs:
- filename: amazon-detective-graph-api-openapi.yml
  format: yaml
  label: Amazon Detective Graph API
  slug: amazon-detective-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-detective/openapi/amazon-detective-graph-api-openapi.yml
- filename: amazon-detective-investigations-api-openapi.yml
  format: yaml
  label: Amazon Detective Investigations API
  slug: amazon-detective-investigations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-detective/openapi/amazon-detective-investigations-api-openapi.yml
- filename: amazon-detective-invitations-api-openapi.yml
  format: yaml
  label: Amazon Detective Invitations API
  slug: amazon-detective-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-detective/openapi/amazon-detective-invitations-api-openapi.yml
- filename: amazon-detective-members-api-openapi.yml
  format: yaml
  label: Amazon Detective Members API
  slug: amazon-detective-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-detective/openapi/amazon-detective-members-api-openapi.yml
- filename: amazon-detective-organizations-api-openapi.yml
  format: yaml
  label: Amazon Detective Organizations API
  slug: amazon-detective-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-detective/openapi/amazon-detective-organizations-api-openapi.yml
- filename: amazon-detective-tags-api-openapi.yml
  format: yaml
  label: Amazon Detective Tags API
  slug: amazon-detective-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-detective/openapi/amazon-detective-tags-api-openapi.yml
- filename: amazon-detective-data-sources-api-openapi.yml
  format: yaml
  label: Amazon Detective Data Sources API
  slug: amazon-detective-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-detective/openapi/amazon-detective-data-sources-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Microsoft Software not for High Risk Use
    text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical equipment, motor vehicles, weaponry systems, or any similar scenario
  - summary: Spend limits not for critical systems
    text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of any hazardous environments or critical systems, any regulated content (such as protected health information), government data, or any content of government entities.
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
name: Amazon Detective
provenance_date: '2026-11-09'
provider_name: Amazon Detective
provider_slug: amazon-detective
slug: amazon-detective-eligibility
source_date: '2026-11-09'
source_filename: amazon-detective-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon Detective\naid: amazon-detective\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Microsoft Software not for High Risk Use\n  text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other\n    modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical\n    equipment, motor vehicles, weaponry systems, or any similar scenario\n- summary: Spend limits not for critical\
  \ systems\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems, any regulated content (such as protected health information),\n    government data, or any content of government entities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-detective/eligibility/amazon-detective-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Amazon Detective's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Forensics
- Investigations
- Security
---
