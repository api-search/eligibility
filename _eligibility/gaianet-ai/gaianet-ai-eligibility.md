---
api_specs:
- filename: gaianet-ai-openapi-generated.yml
  format: yaml
  label: GaiaNet API
  slug: gaianet-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaianet-ai/openapi/_ae-authored/gaianet-ai-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are acting on behalf of a DAO or other entity, whether or not such entity is formally incorporated under the laws of your jurisdiction
    type: other
  minimum_age:
    text: at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Fundraising restriction
    text: uses the Services to participate in fundraising for a business, protocol, or platform, except in strict compliance with applicable law
  - summary: No solicitation of Users
    text: You may not use the Services to solicit, advertise for, or contact in any form, Users for employment or any other purpose not related to the Services facilitated through the Website.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to provide information and/or documentation to verify or confirm your eligibility, including on a periodic or ongoing basis.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GaiaNet
provenance_date: '2026-11-09'
provider_name: GaiaNet
provider_slug: gaianet-ai
slug: gaianet-ai-eligibility
source_date: '2026-11-09'
source_filename: gaianet-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.gaianet.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GaiaNet\naid: gaianet-ai\nurl: https://www.gaianet.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: If you are acting on behalf of a DAO or other entity, whether or not such entity is formally incorporated\n    under the laws of your jurisdiction\nrestricted_uses:\n- summary: Fundraising restriction\n  text: uses the Services to participate in fundraising for a business, protocol, or platform, except in strict\n    compliance with applicable law\n- summary: No solicitation of Users\n  text: You may\
  \ not use the Services to solicit, advertise for, or contact in any form, Users for employment or\n    any other purpose not related to the Services facilitated through the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require you to provide information and/or documentation to verify or confirm your eligibility, including\n    on a periodic or ongoing basis.\nminimum_age:\n  value: '18'\n  text: at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/gaianet-ai/eligibility/gaianet-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from GaiaNet's own page on 2026-11-09.
synthetic: false
tags:
- Decentralization
- Artificial Intelligence
- Privacy
- Security
- Governance
- Networks
---
