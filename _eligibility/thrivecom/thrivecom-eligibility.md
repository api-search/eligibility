---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU HAVE THE AUTHORITY TO ENTER INTO THIS AGREEMENT PERSONALLY OR ON BEHALF OF THE ENTITY YOU REPRESENT, AND TO BIND THAT ENTITY TO THIS AGREEMENT.
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH RINGCAPTCHA
    value: legal age
  restricted_uses:
  - summary: Harmful or unlawful applications
    text: (iii) be harassing, abusive, tortious, threatening, harmful, invasive of another’s privacy, vulgar, defamatory, false, intentionally misleading
  - summary: Widget on objectionable sites
    text: place the Widget on any website that includes content that is offensive, harassing, threatening, abusive, discriminatory, vulgar, pornographic, or otherwise inappropriate
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: RingCaptcha will have the right, in its sole discretion, to refuse to permit your use of the RingCaptcha Offerings with a particular Application.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RingCaptcha (ThriveCom)
provenance_date: '2026-11-10'
provider_name: RingCaptcha (ThriveCom)
provider_slug: thrivecom
slug: thrivecom-eligibility
source_date: '2026-11-10'
source_filename: thrivecom-eligibility.yml
source_heading: Eligibility
source_page: https://www.ringcaptcha.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RingCaptcha (ThriveCom)\naid: thrivecom\nurl: https://www.ringcaptcha.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: YOU HAVE THE AUTHORITY TO ENTER INTO THIS AGREEMENT PERSONALLY OR ON BEHALF OF THE ENTITY YOU REPRESENT,\n    AND TO BIND THAT ENTITY TO THIS AGREEMENT.\nrestricted_uses:\n- summary: Harmful or unlawful applications\n  text: (iii) be harassing, abusive, tortious, threatening, harmful, invasive of another’s privacy, vulgar, defamatory,\n    false, intentionally misleading\n- summary: Widget on objectionable\
  \ sites\n  text: place the Widget on any website that includes content that is offensive, harassing, threatening, abusive,\n    discriminatory, vulgar, pornographic, or otherwise inappropriate\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: RingCaptcha will have the right, in its sole discretion, to refuse to permit your use of the RingCaptcha\n    Offerings with a particular Application.\nminimum_age:\n  value: legal age\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH RINGCAPTCHA\n"
source_yaml_url: https://artifacts.apis.io/thrivecom/eligibility/thrivecom-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from RingCaptcha (ThriveCom)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Two-Factor Authentication
- Phone Verification
- One-Time Passcode
- SMS
- Voice
- Fraud Prevention
- Identity Verification
- Authentication
---
