---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual, you may only use the Service if you have the power to form a contract with College Pulse.
    type: individual
  - text: If you are enrolling on behalf of a Poll Creator that is an organization, by accepting these Terms you are doing so on behalf of such organization and are representing that you have the authority to do so.
    type: business
  minimum_age:
    text: (b) be the age of majority in your territory of residence;
    value: age of majority
  restricted_uses:
  - summary: no protected health information without BAA
    text: you may not use the Services to collect, protect, or otherwise handle “protected health information” (as defined in 45 C.F.R. §160.103 under United States federal regulations) without entering into a separate business associate agreement with College Pulse that permits you to do so.
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
name: Collegepulse
provenance_date: '2026-11-09'
provider_name: Collegepulse
provider_slug: collegepulse
slug: collegepulse-eligibility
source_date: '2026-11-09'
source_filename: collegepulse-eligibility.yml
source_heading: Eligibility
source_page: https://collegepulse.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Collegepulse\naid: collegepulse\nurl: https://collegepulse.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual, you may only use the Service if you have the power to form a contract with College\n    Pulse.\n- type: business\n  text: If you are enrolling on behalf of a Poll Creator that is an organization, by accepting these Terms you are\n    doing so on behalf of such organization and are representing that you have the authority to do so.\nrestricted_uses:\n- summary: no protected health information\
  \ without BAA\n  text: you may not use the Services to collect, protect, or otherwise handle “protected health information” (as\n    defined in 45 C.F.R. §160.103 under United States federal regulations) without entering into a separate business\n    associate agreement with College Pulse that permits you to do so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: (b) be the age of majority in your territory of residence;\n"
source_yaml_url: https://artifacts.apis.io/collegepulse/eligibility/collegepulse-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Collegepulse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Market Research
- Surveys
- Polling
- Higher Education
- College Students
- Data
- Insights
---
