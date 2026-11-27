---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users must be residents of a country outside Europe to which the international dialing code of their registered phone number belongs. Services may be unavailable in some locations; no specific country list is given.
  entity_types:
  - text: If You are registering with Truecaller as a business entity, You represent that You have the authority to legally bind that entity.
    type: business
  minimum_age:
    text: Services are neither intended for nor designed to attract anyone under the relevant age of consent to enter into binding legal contracts under the laws of their respective jurisdictions.
    value: not stated
  restricted_uses:
  - summary: Export restrictions
    text: The Services may not be exported, re-exported or otherwise made available (a) into any country or region embargoed by the U.S. Government, or (b) to anyone on the U.S. Treasury Department's Specially Designated Nationals List or the U.S. Department of Commerce Denied Persons List or Entity List.
  - summary: Harassment and illegal use
    text: You may not use the Services or the Content in any way, which is illegal, harmful, or may be considered offensive by Truecaller, other Users or third parties.
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
name: Truecaller
provenance_date: '2026-11-10'
provider_name: Truecaller
provider_slug: truecaller
slug: truecaller-eligibility
source_date: '2026-11-10'
source_filename: truecaller-eligibility.yml
source_heading: Eligibility
source_page: https://www.truecaller.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Truecaller\naid: truecaller\nurl: https://www.truecaller.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users must be residents of a country outside Europe to which the international dialing code of their registered\n    phone number belongs. Services may be unavailable in some locations; no specific country list is given.\nentity_types:\n- type: business\n  text: If You are registering with Truecaller as a business entity, You represent that You have the authority to\n    legally bind that entity.\nrestricted_uses:\n- summary: Export restrictions\n  text: The\
  \ Services may not be exported, re-exported or otherwise made available (a) into any country or region\n    embargoed by the U.S. Government, or (b) to anyone on the U.S. Treasury Department's Specially Designated Nationals\n    List or the U.S. Department of Commerce Denied Persons List or Entity List.\n- summary: Harassment and illegal use\n  text: You may not use the Services or the Content in any way, which is illegal, harmful, or may be considered\n    offensive by Truecaller, other Users or third parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: not stated\n  text: Services are neither intended for nor designed to attract anyone under the relevant age of consent to enter\n    into binding legal contracts under the laws of their respective jurisdictions.\n"
source_yaml_url: https://artifacts.apis.io/truecaller/eligibility/truecaller-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Truecaller's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Caller ID
- Phone Verification
- Identity
- OAuth
- Spam Detection
- Communications
- Mobile SDK
- Authentication
---
