---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any individual or agribusiness can access the site smartfarm.cropin.inand Register himself or herself
    type: individual
  - text: any legal person or entity accessing or using the services provided on this Website/Application, who is competent to enter into binding contracts
    type: business
  minimum_age:
    text: Registration for this Website/Application is available only to those above the age of 21 years.
    value: '21'
  restricted_uses:
  - summary: No unlawful use
    text: Use the Website/Application or any material or content therein for any purpose that is unlawful or prohibited by these Terms
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: After registration, the system sends an email to registrants email to activate the login.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cropin
provenance_date: '2026-11-09'
provider_name: Cropin
provider_slug: cropintechnologies
slug: cropintechnologies-eligibility
source_date: '2026-11-09'
source_filename: cropintechnologies-eligibility.yml
source_heading: Eligibility
source_page: https://www.cropin.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cropin\naid: cropintechnologies\nurl: https://www.cropin.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any individual or agribusiness can access the site smartfarm.cropin.inand Register himself or herself\n- type: business\n  text: any legal person or entity accessing or using the services provided on this Website/Application, who is\n    competent to enter into binding contracts\nrestricted_uses:\n- summary: No unlawful use\n  text: Use the Website/Application or any material or content therein for any purpose\
  \ that is unlawful or prohibited\n    by these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: After registration, the system sends an email to registrants email to activate the login.\nminimum_age:\n  value: '21'\n  text: Registration for this Website/Application is available only to those above the age of 21 years.\n"
source_yaml_url: https://artifacts.apis.io/cropintechnologies/eligibility/cropintechnologies-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Cropin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- Satellite Intelligence
- Climate Data
- Crop Intelligence
- Supply Chain
- Sustainability
- AI Agents
- EUDR Compliance
---
