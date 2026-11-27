---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Requests limited to Customers located in jurisdictions in which Lemonade is authorized to transact an insurance business
  entity_types:
  - text: This Agreement is a legally binding contract between You and Lemonade Insurance Agency, LLC, a New York limited liability company.
    type: business
  minimum_age:
    text: if you are a natural person, you are of legal age and have the right and authority to enter into this Agreement
    value: null
  restricted_uses:
  - summary: Insurance sales/advice without license
    text: You shall not sell, solicit or negotiate insurance, nor shall You engage in any activity for which a license is required without first having obtained the appropriate license.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All content and materials created to announce, market and/or advertise Lemonade or the API must be reviewed and approved in advance by Lemonade.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lemonade
provenance_date: '2026-11-09'
provider_name: Lemonade
provider_slug: lemonade
slug: lemonade-eligibility
source_date: '2026-11-09'
source_filename: lemonade-eligibility.yml
source_heading: Eligibility
source_page: https://www.lemonade.com/api-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lemonade\naid: lemonade\nurl: https://www.lemonade.com/api-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Requests limited to Customers located in jurisdictions in which Lemonade is authorized to transact an insurance\n    business\nentity_types:\n- type: business\n  text: This Agreement is a legally binding contract between You and Lemonade Insurance Agency, LLC, a New York\n    limited liability company.\nrestricted_uses:\n- summary: Insurance sales/advice without license\n  text: You shall not sell, solicit or negotiate insurance, nor shall You engage in any activity for\
  \ which a license\n    is required without first having obtained the appropriate license.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All content and materials created to announce, market and/or advertise Lemonade or the API must be reviewed\n    and approved in advance by Lemonade.\nminimum_age:\n  value: null\n  text: if you are a natural person, you are of legal age and have the right and authority to enter into this Agreement\n"
source_yaml_url: https://artifacts.apis.io/lemonade/eligibility/lemonade-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Lemonade's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Renters Insurance
- Home Insurance
- Embedded Insurance
- Property and Casualty
---
