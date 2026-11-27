---
api_specs:
- filename: lingk-openapi-generated.yml
  format: yaml
  label: Lingk API
  slug: lingk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lingk/openapi/_ae-authored/lingk-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals, companies, or other entities located in the United States. You may not use the Service if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: This Agreement applies to all visitors, users, and others who access the Service, including, without limitation, commercial enterprises, governments, schools, universities and other institutions,
    type: business
  - text: This Agreement applies to all visitors, users, and others who access the Service, including, without limitation, commercial enterprises, governments, schools, universities and other institutions,
    type: government
  minimum_age:
    text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: Users under 13
    text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.
  - summary: Embargoed or blocked persons
    text: You may not use the Service if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
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
name: Lingk
provenance_date: '2026-11-09'
provider_name: Lingk
provider_slug: lingk
slug: lingk-eligibility
source_date: '2026-11-09'
source_filename: lingk-eligibility.yml
source_heading: Eligibility
source_page: https://www.lingk.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lingk\naid: lingk\nurl: https://www.lingk.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals,\n    companies, or other entities located in the United States. You may not use the Service if you are a resident\n    of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United\n    States government.\nentity_types:\n- type: business\n  text: This Agreement applies to all visitors, users, and others who access the\
  \ Service, including, without limitation,\n    commercial enterprises, governments, schools, universities and other institutions,\n- type: government\n  text: This Agreement applies to all visitors, users, and others who access the Service, including, without limitation,\n    commercial enterprises, governments, schools, universities and other institutions,\nrestricted_uses:\n- summary: Users under 13\n  text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.\n- summary: Embargoed or blocked persons\n  text: You may not use the Service if you are a resident of a country embargoed by the United States, or are a\n    foreign person or entity blocked or denied by the United States government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/lingk/eligibility/lingk-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Lingk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- iPaaS
- Automation
- Artificial Intelligence
---
