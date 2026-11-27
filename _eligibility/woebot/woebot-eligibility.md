---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you can provide consent to data processing under the laws of your territory)
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity’s behalf
    type: business
  minimum_age:
    text: You may use the Services only if you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Not for emergencies
    text: USE OF THE SERVICES IS NOT FOR EMERGENCIES.
  - summary: Not medical care or professional services
    text: The Services do not include the provision of medical care, mental health services or other professional services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you may be required to sign up for an account, and select a password and username
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Woebot Health
provenance_date: '2026-11-10'
provider_name: Woebot Health
provider_slug: woebot
slug: woebot-eligibility
source_date: '2026-11-10'
source_filename: woebot-eligibility.yml
source_heading: Eligibility
source_page: https://woebothealth.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Woebot Health\naid: woebot\nurl: https://woebothealth.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or\n    that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you\n    can provide consent to data processing under the laws of your territory)\n- type: business\n  text: If you’re agreeing to these\
  \ Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization or entity’s behalf\nrestricted_uses:\n- summary: Not for emergencies\n  text: USE OF THE SERVICES IS NOT FOR EMERGENCIES.\n- summary: Not medical care or professional services\n  text: The Services do not include the provision of medical care, mental health services or other professional\n    services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you may be required to sign up for an account, and select a password and username\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/woebot/eligibility/woebot-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Woebot Health's own page on 2026-11-10.
synthetic: false
tags:
- Mental Health
- Digital Therapeutics
- CBT
- Chatbots
- Clinical
- Healthcare
- B2B
- Enterprise
---
