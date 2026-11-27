---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Si Usted accede y/o utiliza la Plataforma, el Sitio, y los Contenidos y Servicios de WoowUp en nombre de una Persona Jurídica
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or fraudulent purposes
    text: fines ilícitos, actividades ilegales, fraudulentas, falsas o engañosa o no autorizados por WoowUp
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
name: WoowUp
provenance_date: '2026-11-10'
provider_name: WoowUp
provider_slug: woowup
slug: woowup-eligibility
source_date: '2026-11-10'
source_filename: woowup-eligibility.yml
source_heading: Eligibility
source_page: https://www.woowup.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WoowUp\naid: woowup\nurl: https://www.woowup.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Si Usted accede y/o utiliza la Plataforma, el Sitio, y los Contenidos y Servicios de WoowUp en nombre de\n    una Persona Jurídica\nrestricted_uses:\n- summary: Illegal or fraudulent purposes\n  text: fines ilícitos, actividades ilegales, fraudulentas, falsas o engañosa o no autorizados por WoowUp\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/woowup/eligibility/woowup-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from WoowUp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- CRM
- Loyalty
- Customer Data
- Marketing Automation
- Retail
- E-Commerce
- Push Notifications
- Loyalty & Incentives
---
