---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and offered by Publishizer, Inc. from its facilities in the United States of America. Publishizer makes no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: You affirm that you are either 18 years of age or older, or an emancipated minor, or possess legal parental or guardian consent
    type: individual
  - text: If you are a legal entity, you affirm that you are an authorized representative of the entity.
    type: business
  minimum_age:
    text: you affirm that you are over the age of 13, as the Service is not intended for children under 13.
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: Users are granted a limited, non-exclusive, license to use and access the Services and Content for non-commercial purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: That any campaign you wish to submit is conditioned on and subject to the conditions and procedures of the Service, including review and approval by Publishizer, which approval may be denied in Publishizer’s sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Publishizer
provenance_date: '2026-11-10'
provider_name: Publishizer
provider_slug: publishizer
slug: publishizer-eligibility
source_date: '2026-11-10'
source_filename: publishizer-eligibility.yml
source_heading: Eligibility
source_page: https://publishizer.com/about/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Publishizer\naid: publishizer\nurl: https://publishizer.com/about/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and offered by Publishizer, Inc. from its facilities in the United States of America.\n    Publishizer makes no representations that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You affirm that you are either 18 years of age or older, or an emancipated minor, or possess legal parental\n    or guardian consent\n- type: business\n  text: If you are a legal entity, you affirm\
  \ that you are an authorized representative of the entity.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: Users are granted a limited, non-exclusive, license to use and access the Services and Content for non-commercial\n    purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: That any campaign you wish to submit is conditioned on and subject to the conditions and procedures of the\n    Service, including review and approval by Publishizer, which approval may be denied in Publishizer’s sole discretion.\nminimum_age:\n  value: '13'\n  text: you affirm that you are over the age of 13, as the Service is not intended for children under 13.\n"
source_yaml_url: https://artifacts.apis.io/publishizer/eligibility/publishizer-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Publishizer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Publishing
- Crowdfunding
- Books
- Authors
- Literary Agency
- Marketplace
---
