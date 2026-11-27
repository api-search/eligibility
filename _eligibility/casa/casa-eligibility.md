---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: YOU ARE NOT BARRED FROM USING THE SERVICE UNDER THE LAWS OF THE UNITED STATES, YOUR PLACE OF RESIDENCE OR ANY OTHER APPLICABLE JURISDICTION
  entity_types:
  - text: IF YOU ARE ACCESSING OR USING THE SERVICE ON BEHALF OF AN ENTITY, ON BEHALF OF THE ENTITY IDENTIFIED IN THE ACCOUNT REGISTRATION PROCESS
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH CASA
    value: legal age
  restricted_uses:
  - summary: Prohibited unlawful or harmful content
    text: (A) is unlawful, threatening, abusive, harassing, defamatory, libelous, deceptive, fraudulent, invasive of another’s privacy, tortious, obscene, offensive, or profane
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access certain features of the Service, you may be required to register an account on the Service
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Casa
provenance_date: '2026-11-09'
provider_name: Casa
provider_slug: casa
slug: casa-eligibility
source_date: '2026-11-09'
source_filename: casa-eligibility.yml
source_heading: Eligibility
source_page: https://getcasa.com/legal/mtou
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Casa\naid: casa\nurl: https://getcasa.com/legal/mtou\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: YOU ARE NOT BARRED FROM USING THE SERVICE UNDER THE LAWS OF THE UNITED STATES, YOUR PLACE OF RESIDENCE OR\n    ANY OTHER APPLICABLE JURISDICTION\nentity_types:\n- type: business\n  text: IF YOU ARE ACCESSING OR USING THE SERVICE ON BEHALF OF AN ENTITY, ON BEHALF OF THE ENTITY IDENTIFIED IN\n    THE ACCOUNT REGISTRATION PROCESS\nrestricted_uses:\n- summary: Prohibited unlawful or harmful content\n  text: (A) is unlawful, threatening, abusive, harassing, defamatory,\
  \ libelous, deceptive, fraudulent, invasive\n    of another’s privacy, tortious, obscene, offensive, or profane\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access certain features of the Service, you may be required to register an account on the Service\nminimum_age:\n  value: legal age\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH CASA\n"
source_yaml_url: https://artifacts.apis.io/casa/eligibility/casa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Casa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Home Services
- Home Management
- Property Management
- Concierge
- Maintenance
- Membership
---
