---
api_specs:
- filename: camdentools-com-mcp-api-openapi.yml
  format: yaml
  label: Camden Tools MCP API
  slug: camdentools-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/camdentools-com/openapi/camdentools-com-mcp-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We deliver worldwide, with the exception of countries subject to international trade restrictions, embargoes, or regions where reliable delivery cannot be guaranteed.
  entity_types:
  - text: 'Usage of this Application and the Service is age restricted : to access and use this Application and its Service the User must be an adult under applicable law.'
    type: individual
  - text: There are no restrictions for Users in terms of being Consumers or Business Users
    type: business
  minimum_age:
    text: to access and use this Application and its Service the User must be an adult under applicable law.
    value: adult under applicable law
  restricted_uses:
  - summary: Sanctioned locations and parties
    text: Users aren’t located in a country that is subject to a U.S. government embargo, or that has been designated by the U.S. government as a “terrorist-supporting” country; Users aren’t listed on any U.S. government list of prohibited or restricted parties
  - summary: Bot-registered accounts
    text: Accounts registered by bots or any other automated methods are not permitted.
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
name: Camden Tools
provenance_date: '2026-11-09'
provider_name: Camden Tools
provider_slug: camdentools-com
slug: camdentools-com-eligibility
source_date: '2026-11-09'
source_filename: camdentools-com-eligibility.yml
source_heading: Eligibility
source_page: https://camdentools.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Camden Tools\naid: camdentools-com\nurl: https://camdentools.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We deliver worldwide, with the exception of countries subject to international trade restrictions, embargoes,\n    or regions where reliable delivery cannot be guaranteed.\nentity_types:\n- type: individual\n  text: 'Usage of this Application and the Service is age restricted : to access and use this Application and its\n    Service the User must be an adult under applicable law.'\n- type: business\n  text: There are no restrictions for Users in terms\
  \ of being Consumers or Business Users\nrestricted_uses:\n- summary: Sanctioned locations and parties\n  text: Users aren’t located in a country that is subject to a U.S. government embargo, or that has been designated\n    by the U.S. government as a “terrorist-supporting” country; Users aren’t listed on any U.S. government list\n    of prohibited or restricted parties\n- summary: Bot-registered accounts\n  text: Accounts registered by bots or any other automated methods are not permitted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adult under applicable law\n  text: to access and use this Application and its Service the User must be an adult under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/camdentools-com/eligibility/camdentools-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Camden Tools's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Tools
- Construction
- Retail
- United Kingdom
---
