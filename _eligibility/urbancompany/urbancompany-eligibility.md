---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Platform is intended for use only within India. You agree that in the event you avail the Services or Pro Services from a legal jurisdiction other than the territory of India, you will be deemed to have accepted the UC terms and conditions applicable to that jurisdiction.
  entity_types:
  - text: you, a user of the Services, or any legal entity that books Pro Services (defined below) on behalf of end-users
    type: individual
  - text: any legal entity that books Pro Services (defined below) on behalf of end-users
    type: business
  minimum_age:
    text: To create an Account, you must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No discrimination against Service Professionals
    text: UC prohibits discrimination against Service Professionals, including on the basis of race, religion, caste, national origin, disability, sexual orientation, sex, marital status, gender identity, age, or any other characteristic that may be protected under applicable law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In certain instances, you may be required to furnish identification proof to avail the Services or the Pro Services, and hereby agree to do so.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: UrbanCompany
provenance_date: '2026-11-10'
provider_name: UrbanCompany
provider_slug: urbancompany
slug: urbancompany-eligibility
source_date: '2026-11-10'
source_filename: urbancompany-eligibility.yml
source_heading: Eligibility
source_page: https://www.urbancompany.com/policies?countryId=IND&language=en&policyType=terms_and_conditions&userType=customer
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UrbanCompany\naid: urbancompany\nurl: https://www.urbancompany.com/policies?countryId=IND&language=en&policyType=terms_and_conditions&userType=customer\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Platform is intended for use only within India. You agree that in the event you avail the Services or Pro\n    Services from a legal jurisdiction other than the territory of India, you will be deemed to have accepted the\n    UC terms and conditions applicable to that jurisdiction.\nentity_types:\n- type: individual\n  text: you, a user of the Services, or any legal entity that\
  \ books Pro Services (defined below) on behalf of end-users\n- type: business\n  text: any legal entity that books Pro Services (defined below) on behalf of end-users\nrestricted_uses:\n- summary: No discrimination against Service Professionals\n  text: UC prohibits discrimination against Service Professionals, including on the basis of race, religion, caste,\n    national origin, disability, sexual orientation, sex, marital status, gender identity, age, or any other characteristic\n    that may be protected under applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In certain instances, you may be required to furnish identification proof to avail the Services or the Pro\n    Services, and hereby agree to do so.\nminimum_age:\n  value: '18'\n  text: To create an Account, you must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/urbancompany/eligibility/urbancompany-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from UrbanCompany's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Home Services
- Marketplace
- Beauty
- Cleaning
- Repair
---
