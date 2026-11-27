---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - DE
    - JP
    - GB
    text: The Services are intended for use in the United States, Germany, Japan and the UK only.
  entity_types:
  - text: unless you are a natural person and acting in your individual capacity
    type: individual
  - text: If you are using the Services on behalf of a Provider Customer, these Terms supplement any Provider Agreements.
    type: other
  minimum_age:
    text: The Services are not intended for or directed to children under 18 years old
    value: '18'
  restricted_uses:
  - summary: No advice for another person via portal
    text: asking for advice on behalf of another person is prohibited
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to provide verification to establish your Patient Portal account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Flatiron Health
provenance_date: '2026-11-09'
provider_name: Flatiron Health
provider_slug: flatiron-health
slug: flatiron-health-eligibility
source_date: '2026-11-09'
source_filename: flatiron-health-eligibility.yml
source_heading: Eligibility
source_page: https://flatironhealth.legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flatiron Health\naid: flatiron-health\nurl: https://flatironhealth.legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - DE\n  - JP\n  - GB\n  excluded: []\n  text: The Services are intended for use in the United States, Germany, Japan and the UK only.\nentity_types:\n- type: individual\n  text: unless you are a natural person and acting in your individual capacity\n- type: other\n  text: If you are using the Services on behalf of a Provider Customer, these Terms supplement any Provider Agreements.\nrestricted_uses:\n- summary: No advice for another person via portal\n  text: asking for advice\
  \ on behalf of another person is prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to provide verification to establish your Patient Portal account.\nminimum_age:\n  value: '18'\n  text: The Services are not intended for or directed to children under 18 years old\n"
source_yaml_url: https://artifacts.apis.io/flatiron-health/eligibility/flatiron-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Flatiron Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Oncology
- Real-World Data
- Real-World Evidence
- Clinical Trials
- Life Sciences
- Electronic Health Records
- Clinical Research
---
