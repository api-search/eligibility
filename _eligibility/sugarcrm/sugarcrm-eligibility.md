---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Site may not be legal by certain persons or in certain countries.
  minimum_age:
    text: The Site is offered and available to users 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: Unlawful or prohibited conduct
    text: You may use the Site only for lawful purposes and in accordance with these Terms of Use.
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
name: SugarCRM
provenance_date: '2026-11-10'
provider_name: SugarCRM
provider_slug: sugarcrm
slug: sugarcrm-eligibility
source_date: '2026-11-10'
source_filename: sugarcrm-eligibility.yml
source_heading: Eligibility
source_page: https://sugarai.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SugarCRM\naid: sugarcrm\nurl: https://sugarai.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Site may not be legal by certain persons or in certain countries.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited conduct\n  text: You may use the Site only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is offered and available to users 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/sugarcrm/eligibility/sugarcrm-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SugarCRM's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- CRM
- Sales
- Marketing
- Customer Service
- Sales Automation
- REST API
- Webhook
- Sales Intelligence
---
