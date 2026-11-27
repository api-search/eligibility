---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if purchased or otherwise acquired by or for an entity, that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, violent, discriminatory, sexually explicit, or IP-infringing use
    text: 'LICENSEE shall not use the Software for any of the following uses: Engage in or promote illegal activities Promote violence'
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
name: PlusThis
provenance_date: '2026-11-10'
provider_name: PlusThis
provider_slug: plusthis
slug: plusthis-eligibility
source_date: '2026-11-10'
source_filename: plusthis-eligibility.yml
source_heading: Eligibility
source_page: https://www.plusthis.com/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PlusThis\naid: plusthis\nurl: https://www.plusthis.com/eula\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if purchased or otherwise acquired by or for an entity, that entity\nrestricted_uses:\n- summary: Illegal, violent, discriminatory, sexually explicit, or IP-infringing use\n  text: 'LICENSEE shall not use the Software for any of the following uses: Engage in or promote illegal activities\n    Promote violence'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/plusthis/eligibility/plusthis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from PlusThis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing Automation
- Marketing
- CRM
- Sales
- No-Code
- Automation
- Integration
- Webhook
- Email Marketing
- SMS
- Small Business
---
