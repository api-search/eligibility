---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To access, use, or download the Services, you must be a resident of the 50 States of the United States of America, exclusive of its commonwealths, territories, and possessions.
  entity_types:
  - text: If you are a Provider or are accessing the Services on behalf of a Provider, you or the Provider may have signed a service agreement, business associate agreement, or other document with terms and conditions for the Services
    type: individual
  minimum_age:
    text: If you are under 13 years old, you may not access, use or download the Services.
    value: '13'
  restricted_uses:
  - summary: Lawful use only
    text: You may only use the Services for lawful purposes in compliance with Applicable Laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: eCW may terminate your access to the Services if you fail to provide truthful and accurate information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: eClinicalWorks
provenance_date: '2026-11-09'
provider_name: eClinicalWorks
provider_slug: eclinicalworks
slug: eclinicalworks-eligibility
source_date: '2026-11-09'
source_filename: eclinicalworks-eligibility.yml
source_heading: Eligibility
source_page: https://request.eclinicalworks.com/privacy/terms.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: eClinicalWorks\naid: eclinicalworks\nurl: https://request.eclinicalworks.com/privacy/terms.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To access, use, or download the Services, you must be a resident of the 50 States of the United States of\n    America, exclusive of its commonwealths, territories, and possessions.\nentity_types:\n- type: individual\n  text: If you are a Provider or are accessing the Services on behalf of a Provider, you or the Provider may have\n    signed a service agreement, business associate agreement, or other document with terms and conditions\
  \ for the\n    Services\nrestricted_uses:\n- summary: Lawful use only\n  text: You may only use the Services for lawful purposes in compliance with Applicable Laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: eCW may terminate your access to the Services if you fail to provide truthful and accurate information.\nminimum_age:\n  value: '13'\n  text: If you are under 13 years old, you may not access, use or download the Services.\n"
source_yaml_url: https://artifacts.apis.io/eclinicalworks/eligibility/eclinicalworks-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from eClinicalWorks's own page on 2026-11-09.
synthetic: false
tags:
- Electronic Health Records
- FHIR
- Healthcare
- Practice Management
- Clinical Data
- Health Information Exchange
- Patient Data
- Appointments
- Billing
- SMART on FHIR
- US Core
- USCDI
- Bulk Data
- Remote Patient Monitoring
- Interoperability
- ONC Certified
- CDS Hooks
- healow
---
