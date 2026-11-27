---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Ethic makes no representations that the Services are appropriate or available for use in other locations. The Services are controlled and offered by Ethic from its facilities in the United States of America.
  entity_types:
  - text: investors contracting directly with Ethic as an adviser to manage their own assets
    type: individual
  minimum_age:
    text: You represent that you are (1) at least thirteen (13) years old
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Ethic does not make any attempt to verify the statements of users of the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ethic
provenance_date: '2026-11-09'
provider_name: Ethic
provider_slug: ethic
slug: ethic-eligibility
source_date: '2026-11-09'
source_filename: ethic-eligibility.yml
source_heading: Eligibility
source_page: https://www.ethic.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ethic\naid: ethic\nurl: https://www.ethic.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Ethic makes no representations that the Services are appropriate or available for use in other locations.\n    The Services are controlled and offered by Ethic from its facilities in the United States of America.\nentity_types:\n- type: individual\n  text: investors contracting directly with Ethic as an adviser to manage their own assets\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Ethic does not make any attempt to\
  \ verify the statements of users of the Services\nminimum_age:\n  value: '13'\n  text: You represent that you are (1) at least thirteen (13) years old\n"
source_yaml_url: https://artifacts.apis.io/ethic/eligibility/ethic-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Ethic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Investing
- Asset Management
- Wealth Management
- Fintech
- Direct Indexing
- ESG
- Values-Based Investing
- Portfolio Management
---
