---
api_specs:
- filename: zerotier-controller-api-openapi.yml
  format: yaml
  label: ZeroTier Controller API
  slug: zerotier-controller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-controller-api-openapi.yml
- filename: zerotier-network-api-openapi.yml
  format: yaml
  label: ZeroTier Network API
  slug: zerotier-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-network-api-openapi.yml
- filename: zerotier-network-member-api-openapi.yml
  format: yaml
  label: ZeroTier Network Member API
  slug: zerotier-network-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-network-member-api-openapi.yml
- filename: zerotier-organizations-api-openapi.yml
  format: yaml
  label: ZeroTier Organizations API
  slug: zerotier-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-organizations-api-openapi.yml
- filename: zerotier-peer-api-openapi.yml
  format: yaml
  label: ZeroTier Peer API
  slug: zerotier-peer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-peer-api-openapi.yml
- filename: zerotier-status-api-openapi.yml
  format: yaml
  label: ZeroTier Status API
  slug: zerotier-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-status-api-openapi.yml
- filename: zerotier-user-api-openapi.yml
  format: yaml
  label: ZeroTier User API
  slug: zerotier-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-user-api-openapi.yml
- filename: zerotier-util-api-openapi.yml
  format: yaml
  label: ZeroTier Util API
  slug: zerotier-util-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-util-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users may not be nationals or residents of sanctioned countries or territories subject to U.S. trade and economic sanctions or embargoes.
  entity_types:
  - text: if you are an individual and you access or use our Service on behalf of a company or other entity, such as your employer (together with its affiliates, an “ Organization ”)
    type: individual
  - text: you represent and warrant that you have the authority to bind that Organization to these Terms
    type: business
  minimum_age:
    text: To use our Service, you must of legal age to form a binding contract in your jurisdiction.
    value: null
  restricted_uses:
  - summary: Export and sanctions compliance
    text: You agree to comply with all applicable export and re-export control and trade and economic sanctions laws
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
name: ZeroTier
provenance_date: '2026-11-10'
provider_name: ZeroTier
provider_slug: zerotier
slug: zerotier-eligibility
source_date: '2026-11-10'
source_filename: zerotier-eligibility.yml
source_heading: Eligibility
source_page: https://www.zerotier.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZeroTier\naid: zerotier\nurl: https://www.zerotier.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Users may not be nationals or residents of sanctioned countries or territories subject to U.S. trade and\n    economic sanctions or embargoes.\nentity_types:\n- type: individual\n  text: if you are an individual and you access or use our Service on behalf of a company or other entity, such\n    as your employer (together with its affiliates, an “ Organization ”)\n- type: business\n  text: you represent and warrant that you have the authority to bind that\
  \ Organization to these Terms\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: You agree to comply with all applicable export and re-export control and trade and economic sanctions laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: To use our Service, you must of legal age to form a binding contract in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/zerotier/eligibility/zerotier-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from ZeroTier's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Networking
- Software Defined Networking
- SDN
- VPN
- Security
- Connectivity
- Overlay Network
- Zero Trust
- Infrastructure
---
