---
api_specs:
- filename: coronet-webhooks-asyncapi.yml
  format: yaml
  label: Coro Public API
  slug: coro-public-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/coronet/asyncapi/coronet-webhooks-asyncapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms on behalf of a company or other legal entity, you represent and warrant that you have the full legal authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal business use only
    text: The Platform is intended for internal business use only.
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
name: CoroNet
provenance_date: '2026-11-09'
provider_name: CoroNet
provider_slug: coronet
slug: coronet-eligibility
source_date: '2026-11-09'
source_filename: coronet-eligibility.yml
source_heading: Eligibility
source_page: https://www.coro.net/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoroNet\naid: coronet\nurl: https://www.coro.net/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms on behalf of a company or other legal entity, you represent and warrant\n    that you have the full legal authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Internal business use only\n  text: The Platform is intended for internal business use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coronet/eligibility/coronet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CoroNet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Cybersecurity
- Security
- Endpoint Security
- Email Security
- Network Security
- Cloud Security
- Managed Service Providers
- Compliance
- Webhook
---
