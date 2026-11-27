---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Those who access or use the Website and Services from other countries do so at their own volition and are responsible for compliance with local law. You represent that You are not located in or a national or resident of any country that is subject to U.S. trade sanctions
  entity_types:
  - text: The Websites and Services are intended solely for and are only available to individuals who are at least eighteen (18) years of age
    type: individual
  - text: If you are registering as a business or other entity, you further represent that you have the authority to bind the entity to these Terms
    type: business
  minimum_age:
    text: The Websites and Services are intended solely for and are only available to individuals who are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Age 21+ for certain services
    text: certain of the Websites and Services require you to be at least twenty-one (21) years of age to access and use such Websites and Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: HERB does not review each User Profile to determine if they were created by an appropriate party.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Herb
provenance_date: '2026-11-09'
provider_name: Herb
provider_slug: herb
slug: herb-eligibility
source_date: '2026-11-09'
source_filename: herb-eligibility.yml
source_heading: Eligibility
source_page: https://herb.co/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Herb\naid: herb\nurl: https://herb.co/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Those who access or use the Website and Services from other countries do so at their own volition and are\n    responsible for compliance with local law. You represent that You are not located in or a national or resident\n    of any country that is subject to U.S. trade sanctions\nentity_types:\n- type: individual\n  text: The Websites and Services are intended solely for and are only available to individuals who are at least\n    eighteen (18) years of age\n- type: business\n  text: If you\
  \ are registering as a business or other entity, you further represent that you have the authority\n    to bind the entity to these Terms\nrestricted_uses:\n- summary: Age 21+ for certain services\n  text: certain of the Websites and Services require you to be at least twenty-one (21) years of age to access and\n    use such Websites and Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: HERB does not review each User Profile to determine if they were created by an appropriate party.\nminimum_age:\n  value: '18'\n  text: The Websites and Services are intended solely for and are only available to individuals who are at least\n    eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/herb/eligibility/herb-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Herb's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cannabis
- Media
- Content
- E-Commerce
- Marketplace
- Education
- Lifestyle
---
