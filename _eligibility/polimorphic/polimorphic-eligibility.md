---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering for or using the Polimorphic Service on behalf of an organization or government entity, you are agreeing to these Terms for that entity
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: no service bureau or third-party benefit use
    text: otherwise use the Polimorphic Service for the benefit of a third party or to operate a service bureau
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
name: Polimorphic
provenance_date: '2026-11-10'
provider_name: Polimorphic
provider_slug: polimorphic
slug: polimorphic-eligibility
source_date: '2026-11-10'
source_filename: polimorphic-eligibility.yml
source_heading: Eligibility
source_page: https://www.polimorphic.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Polimorphic\naid: polimorphic\nurl: https://www.polimorphic.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If you are registering for or using the Polimorphic Service on behalf of an organization or government entity,\n    you are agreeing to these Terms for that entity\nrestricted_uses:\n- summary: no service bureau or third-party benefit use\n  text: otherwise use the Polimorphic Service for the benefit of a third party or to operate a service bureau\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/polimorphic/eligibility/polimorphic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Polimorphic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- GovTech
- Government
- Artificial Intelligence
- CRM
- Workflows
- Public Sector
- Constituent Services
- Voice AI
- Chatbots
---
