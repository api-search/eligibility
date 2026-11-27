---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users must not be located in a country subject to an embargo or designated as a 'terrorist supporting' country (Section 5.3).
  entity_types:
  - text: Our Platform is only available to users who are at least 18 years old.
    type: individual
  - text: If you are using the Platform for an organization, you agree to these Terms on behalf of that organization, and represent you have authority to bind that organization to the terms contained in these Terms.
    type: business
  minimum_age:
    text: You need to be at least 18 years old to use our Platform.
    value: '18'
  restricted_uses:
  - summary: Collecting sensitive personal data
    text: You also agree that you will not use the Platform to solicit or collect (i) personal data from others except as necessary for the administration of or participation in a group or event or (ii) sensitive personal data
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
name: Meetup
provenance_date: '2026-11-10'
provider_name: Meetup
provider_slug: meetup
slug: meetup-eligibility
source_date: '2026-11-10'
source_filename: meetup-eligibility.yml
source_heading: Eligibility
source_page: https://help.meetup.com/hc/en-us/articles/360027447252-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meetup\naid: meetup\nurl: https://help.meetup.com/hc/en-us/articles/360027447252-Terms-of-Service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Users must not be located in a country subject to an embargo or designated as a 'terrorist supporting' country\n    (Section 5.3).\nentity_types:\n- type: individual\n  text: Our Platform is only available to users who are at least 18 years old.\n- type: business\n  text: If you are using the Platform for an organization, you agree to these Terms on behalf of that organization,\n    and represent you have authority to\
  \ bind that organization to the terms contained in these Terms.\nrestricted_uses:\n- summary: Collecting sensitive personal data\n  text: You also agree that you will not use the Platform to solicit or collect (i) personal data from others except\n    as necessary for the administration of or participation in a group or event or (ii) sensitive personal data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You need to be at least 18 years old to use our Platform.\n"
source_yaml_url: https://artifacts.apis.io/meetup/eligibility/meetup-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Meetup's own page on 2026-11-10.
synthetic: false
tags:
- Event
- Community
- Group
- Meetups
- Social
- GraphQL
---
