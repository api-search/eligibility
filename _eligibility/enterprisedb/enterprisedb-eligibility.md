---
api_specs:
- filename: enterprisedb-utility-api-openapi.yml
  format: yaml
  label: EDB Utility API
  slug: enterprisedb-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enterprisedb/openapi/enterprisedb-utility-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement for an entity, such as the company you work for, you represent to us that you have legal authority to bind that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You will not, directly or indirectly, export, reexport, transfer (in-country), or allow access to or use of any EDB Software (including the Beta Software), Support, Services, or related technology to, in, by, or for any sanctioned or prohibited country, region, person, or end use under U.S. law without authorization from the U.S. government.
  - summary: AI output not for professional advice
    text: AI Features are provided for informational purposes only and should not be relied upon for professional, legal, or financial advice.
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
name: EDB
provenance_date: '2026-11-09'
provider_name: EDB
provider_slug: enterprisedb
slug: enterprisedb-eligibility
source_date: '2026-11-09'
source_filename: enterprisedb-eligibility.yml
source_heading: Eligibility
source_page: https://www.enterprisedb.com/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EDB\naid: enterprisedb\nurl: https://www.enterprisedb.com/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement for an entity, such as the company you work for, you represent to\n    us that you have legal authority to bind that entity.\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You will not, directly or indirectly, export, reexport, transfer (in-country), or allow access to or use\n    of any EDB Software (including the Beta Software), Support, Services, or related\
  \ technology to, in, by, or for\n    any sanctioned or prohibited country, region, person, or end use under U.S. law without authorization from the\n    U.S. government.\n- summary: AI output not for professional advice\n  text: AI Features are provided for informational purposes only and should not be relied upon for professional,\n    legal, or financial advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/enterprisedb/eligibility/enterprisedb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from EDB's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Database
- PostgreSQL
- Enterprise
- Open Source
---
