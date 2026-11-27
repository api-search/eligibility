---
api_specs:
- filename: empowerly-status-api-openapi.yml
  format: yaml
  label: Empowerly Status API
  slug: empowerly-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empowerly/openapi/empowerly-status-api-openapi.yml
- filename: empowerly-components-api-openapi.yml
  format: yaml
  label: Empowerly Components API
  slug: empowerly-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empowerly/openapi/empowerly-components-api-openapi.yml
- filename: empowerly-incidents-api-openapi.yml
  format: yaml
  label: Empowerly Incidents API
  slug: empowerly-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empowerly/openapi/empowerly-incidents-api-openapi.yml
- filename: empowerly-maintenance-api-openapi.yml
  format: yaml
  label: Empowerly Maintenance API
  slug: empowerly-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empowerly/openapi/empowerly-maintenance-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Empowerly operates the majority of its Services in the United States. Empowerly makes no representations or warranties that the Services are appropriate for use or access in other locations.
  entity_types:
  - text: The Services are available to individuals age 13 and over.
    type: individual
  minimum_age:
    text: The Services are available to individuals age 13 and over. If you are between the ages of 13 and the age of majority where you live, you must review these Terms of Service with your parent or guardian
    value: '13'
  restricted_uses:
  - summary: Noncommercial use only
    text: Your permission to use the website is conditioned upon the following Use Restrictions and Conduct Restrictions for noncommercial use only.
  - summary: Restricted persons and unlawful jurisdictions
    text: By using this site, you certify that you are not on any list of restricted persons with whom it is unlawful for a U.S. company to do business.
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
name: Empowerly
provenance_date: '2026-11-09'
provider_name: Empowerly
provider_slug: empowerly
slug: empowerly-eligibility
source_date: '2026-11-09'
source_filename: empowerly-eligibility.yml
source_heading: Eligibility
source_page: https://empowerly.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Empowerly\naid: empowerly\nurl: https://empowerly.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Empowerly operates the majority of its Services in the United States. Empowerly makes no representations\n    or warranties that the Services are appropriate for use or access in other locations.\nentity_types:\n- type: individual\n  text: The Services are available to individuals age 13 and over.\nrestricted_uses:\n- summary: Noncommercial use only\n  text: Your permission to use the website is conditioned upon the following Use Restrictions and Conduct Restrictions\n\
  \    for noncommercial use only.\n- summary: Restricted persons and unlawful jurisdictions\n  text: By using this site, you certify that you are not on any list of restricted persons with whom it is unlawful\n    for a U.S. company to do business.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are available to individuals age 13 and over. If you are between the ages of 13 and the age\n    of majority where you live, you must review these Terms of Service with your parent or guardian\n"
source_yaml_url: https://artifacts.apis.io/empowerly/eligibility/empowerly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Empowerly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- College Admissions
- Counseling
- Students
- Career Services
- Consumer Services
- Status Pages
---
