---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or malicious use
    text: imagetyperz.com don’t allow the use of our services for illegal software or activities like any kind of spam, viruses, trojans, malware or any other malicious software that can cause our services to be banned/backlisted.
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
name: ImageTyperz
provenance_date: '2026-11-09'
provider_name: ImageTyperz
provider_slug: imagetyperz
slug: imagetyperz-eligibility
source_date: '2026-11-09'
source_filename: imagetyperz-eligibility.yml
source_heading: Eligibility
source_page: https://www.imagetyperz.com/Forms/terms-of-service.aspx
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ImageTyperz\naid: imagetyperz\nurl: https://www.imagetyperz.com/Forms/terms-of-service.aspx\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or malicious use\n  text: imagetyperz.com don’t allow the use of our services for illegal software or activities like any kind of\n    spam, viruses, trojans, malware or any other malicious software that can cause our services to be banned/backlisted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/imagetyperz/eligibility/imagetyperz-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ImageTyperz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CAPTCHA
- Automation
- Services
- Image Processing
---
