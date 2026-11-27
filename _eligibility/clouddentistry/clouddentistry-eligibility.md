---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: User represents it will not use the Site Services outside of the U.S or Canada.
  entity_types:
  - text: a legal entity or an individual 18 years or older who can form legally binding contracts
    type: individual
  - text: User must have, and hereby represent that it has, an independent business (whether it be as a self-employed individual/sole proprietor or as a corporation or other entity).
    type: business
  minimum_age:
    text: an individual 18 years or older who can form legally binding contracts
    value: '18'
  restricted_uses:
  - summary: Not for personal or consumer use
    text: Company offers the Platform for User’s business purposes, and not for personal, household, or consumer use.
  - summary: Medicare/Medicaid payor restriction
    text: Practice agrees that it will not, using a Specialist found through the Platform, now or in the future, treat any patients, using said Specialist, who pay with funds from any federal program of the United States of America, including without limitation Medicare and Medicaid.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: When User registers for an Account and from time to time thereafter, User’s Account will be subject to verification, including, but not limited to, validation against third-party databases or the verification of one or more official government or legal documents that confirm User’s identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clouddentistry
provenance_date: '2026-11-09'
provider_name: Clouddentistry
provider_slug: clouddentistry
slug: clouddentistry-eligibility
source_date: '2026-11-09'
source_filename: clouddentistry-eligibility.yml
source_heading: Eligibility
source_page: https://www.clouddentistry.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clouddentistry\naid: clouddentistry\nurl: https://www.clouddentistry.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: User represents it will not use the Site Services outside of the U.S or Canada.\nentity_types:\n- type: individual\n  text: a legal entity or an individual 18 years or older who can form legally binding contracts\n- type: business\n  text: User must have, and hereby represent that it has, an independent business (whether it be as a self-employed\n    individual/sole proprietor or as a corporation or other entity).\nrestricted_uses:\n\
  - summary: Not for personal or consumer use\n  text: Company offers the Platform for User’s business purposes, and not for personal, household, or consumer use.\n- summary: Medicare/Medicaid payor restriction\n  text: Practice agrees that it will not, using a Specialist found through the Platform, now or in the future, treat\n    any patients, using said Specialist, who pay with funds from any federal program of the United States of America,\n    including without limitation Medicare and Medicaid.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: When User registers for an Account and from time to time thereafter, User’s Account will be subject to verification,\n    including, but not limited to, validation against third-party databases or the verification of one or more official\n    government or legal documents that confirm User’s identity.\nminimum_age:\n  value: '18'\n  text: an individual 18 years or older who can form legally binding contracts\n"
source_yaml_url: https://artifacts.apis.io/clouddentistry/eligibility/clouddentistry-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Clouddentistry's own page on 2026-11-09.
synthetic: false
tags:
- Dental
- Cloud
- Software-as-a-Service
- Healthcare
- Platform
- Company
---
