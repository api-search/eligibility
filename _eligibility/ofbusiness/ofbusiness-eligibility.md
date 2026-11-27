---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Web Site is provided by OfBusiness and available only to entities and persons who have reached the age of legal majority and are competent to enter into a legally binding agreement(s) under the applicable laws.
    type: business
  - text: available only to entities and persons who have reached the age of legal majority and are competent to enter into a legally binding agreement(s) under the applicable laws.
    type: individual
  minimum_age:
    text: available only to entities and persons who have reached the age of legal majority
    value: age of legal majority
  restricted_uses:
  - summary: Automated access
    text: using any automated software, hardware or any other similar mechanism to use access, navigate or search the website and/or mobile application
  - summary: Unsolicited advertising
    text: posting or transmitting any information on the website and/or mobile application including unauthorized or unsolicited advertising, promotional materials, or any other forms of unauthorized solicitation to other users
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
name: Ofbusiness
provenance_date: '2026-11-10'
provider_name: Ofbusiness
provider_slug: ofbusiness
slug: ofbusiness-eligibility
source_date: '2026-11-10'
source_filename: ofbusiness-eligibility.yml
source_heading: Eligibility
source_page: https://www.ofbusiness.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ofbusiness\naid: ofbusiness\nurl: https://www.ofbusiness.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Web Site is provided by OfBusiness and available only to entities and persons who have reached the age\n    of legal majority and are competent to enter into a legally binding agreement(s) under the applicable laws.\n- type: individual\n  text: available only to entities and persons who have reached the age of legal majority and are competent to enter\n    into a legally binding agreement(s) under the applicable\
  \ laws.\nrestricted_uses:\n- summary: Automated access\n  text: using any automated software, hardware or any other similar mechanism to use access, navigate or search\n    the website and/or mobile application\n- summary: Unsolicited advertising\n  text: posting or transmitting any information on the website and/or mobile application including unauthorized\n    or unsolicited advertising, promotional materials, or any other forms of unauthorized solicitation to other\n    users\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of legal majority\n  text: available only to entities and persons who have reached the age of legal majority\n"
source_yaml_url: https://artifacts.apis.io/ofbusiness/eligibility/ofbusiness-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Ofbusiness's own page on 2026-11-10.
synthetic: false
tags:
- Company
- B2B
- Procurement
- Commerce
- Fintech
- Lending
- Supply Chain
- India
---
