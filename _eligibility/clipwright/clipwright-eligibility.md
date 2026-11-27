---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We sell worldwide, and we sell in US dollars. The Service is a digital service available in any country where using it is lawful.
  entity_types:
  - text: If you are a consumer in the European Union, the 14 days above are the period of your statutory right to withdraw from a distance contract
    type: individual
  - text: If you are a business customer, disputes arising from these Terms or your use of the Service are subject to the jurisdiction of the courts competent for the registered seat of Dimantika in Gdańsk, Poland.
    type: business
  minimum_age:
    text: Be at least 16 years of age, or older where your jurisdiction sets a higher minimum
    value: '16'
  restricted_uses:
  - summary: Illegal or harmful content
    text: Generate illegal, harmful, threatening, abusive, or defamatory content
  - summary: Impersonation
    text: Impersonate any person or entity or misrepresent your affiliation
  - summary: Infringing content
    text: Generate content that infringes on intellectual property rights
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access certain features of the Service, you must register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clipwright
provenance_date: '2026-11-09'
provider_name: Clipwright
provider_slug: clipwright
slug: clipwright-eligibility
source_date: '2026-11-09'
source_filename: clipwright-eligibility.yml
source_heading: Eligibility
source_page: https://clipwright.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clipwright\naid: clipwright\nurl: https://clipwright.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We sell worldwide, and we sell in US dollars. The Service is a digital service available in any country\n    where using it is lawful.\nentity_types:\n- type: individual\n  text: If you are a consumer in the European Union, the 14 days above are the period of your statutory right to\n    withdraw from a distance contract\n- type: business\n  text: If you are a business customer, disputes arising from these Terms or your use of the Service are subject\n    to the jurisdiction\
  \ of the courts competent for the registered seat of Dimantika in Gdańsk, Poland.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Generate illegal, harmful, threatening, abusive, or defamatory content\n- summary: Impersonation\n  text: Impersonate any person or entity or misrepresent your affiliation\n- summary: Infringing content\n  text: Generate content that infringes on intellectual property rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access certain features of the Service, you must register for an account.\nminimum_age:\n  value: '16'\n  text: Be at least 16 years of age, or older where your jurisdiction sets a higher minimum\n"
source_yaml_url: https://artifacts.apis.io/clipwright/eligibility/clipwright-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Clipwright's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- UGC
- Automation
---
