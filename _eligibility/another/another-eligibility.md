---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are located in, a national or resident of, or a segment of the government of, any country or territory for which the United States maintains trade or economic sanctions or embargoes or that has been designated by the U.S. Government as a “terrorist supporting” region.
  entity_types:
  - text: To use the Service, you must be at least 18 years old (or the age of majority in your jurisdiction).
    type: individual
  - text: solely for your personal use or internal business purposes, as permitted by the features of the Service.
    type: business
  minimum_age:
    text: To use the Service, you must be at least 18 years old (or the age of majority in your jurisdiction).
    value: '18'
  restricted_uses:
  - summary: Scraping or automated access
    text: use any automated or non-automated means to access the Service for “scraping”
  - summary: Competing products
    text: use the Service in competition with us, to develop competing products or services
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Service is available on an invite-only basis. To create a User Account, you must have a valid invitation code issued by us or by an existing User.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Another
provenance_date: '2026-11-09'
provider_name: Another
provider_slug: another
slug: another-eligibility
source_date: '2026-11-09'
source_filename: another-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinanother.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Another\naid: another\nurl: https://www.joinanother.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are located in, a national or resident of, or a segment of the government\n    of, any country or territory for which the United States maintains trade or economic sanctions or embargoes\n    or that has been designated by the U.S. Government as a “terrorist supporting” region.\nentity_types:\n- type: individual\n  text: To use the Service, you must be at least 18 years old (or the age of majority in your jurisdiction).\n\
  - type: business\n  text: solely for your personal use or internal business purposes, as permitted by the features of the Service.\nrestricted_uses:\n- summary: Scraping or automated access\n  text: use any automated or non-automated means to access the Service for “scraping”\n- summary: Competing products\n  text: use the Service in competition with us, to develop competing products or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Service is available on an invite-only basis. To create a User Account, you must have a valid invitation\n    code issued by us or by an existing User.\nminimum_age:\n  value: '18'\n  text: To use the Service, you must be at least 18 years old (or the age of majority in your jurisdiction).\n"
source_yaml_url: https://artifacts.apis.io/another/eligibility/another-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Another's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- Inventory
- Artificial Intelligence
- Fashion
- E-Commerce
- Supply Chain
---
