---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: for the benefit of Clients’ employees in the United States
  entity_types:
  - text: Employee Navigator Solutions and Services are for the use of insurance carriers, insurance brokers, administrators and related businesses and employees of businesses.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitors excluded
    text: or if you are a competitor of Employee Navigator
  - summary: Sanctioned jurisdictions
    text: being incorporated in or operating from any jurisdiction subject to Sanctions Laws
  - summary: PHI not designed for upload
    text: Employee Navigator Solutions and Services are not designed for Subscriber or Authorized Entities to upload or enter any protected health information (PHI)
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Subscriber shall have the right to request the purchase of a Subscription by completing a Subscription Order or similar document approved by Employee Navigator
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Employee Navigator
provenance_date: '2026-11-09'
provider_name: Employee Navigator
provider_slug: employeenavigator
slug: employeenavigator-eligibility
source_date: '2026-11-09'
source_filename: employeenavigator-eligibility.yml
source_heading: Eligibility
source_page: https://www.employeenavigator.com/master-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Employee Navigator\naid: employeenavigator\nurl: https://www.employeenavigator.com/master-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: for the benefit of Clients’ employees in the United States\nentity_types:\n- type: business\n  text: Employee Navigator Solutions and Services are for the use of insurance carriers, insurance brokers, administrators\n    and related businesses and employees of businesses.\nrestricted_uses:\n- summary: Competitors excluded\n  text: or if you are a competitor of Employee Navigator\n- summary: Sanctioned jurisdictions\n\
  \  text: being incorporated in or operating from any jurisdiction subject to Sanctions Laws\n- summary: PHI not designed for upload\n  text: Employee Navigator Solutions and Services are not designed for Subscriber or Authorized Entities to upload\n    or enter any protected health information (PHI)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Subscriber shall have the right to request the purchase of a Subscription by completing a Subscription Order\n    or similar document approved by Employee Navigator\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/employeenavigator/eligibility/employeenavigator-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Employee Navigator's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Benefits Administration
- Human Resources
- Insurance
- Employee Benefits
- Payroll
- Health Insurance
- HRIS
- Open Enrollment
- ACA Compliance
- Identity
---
