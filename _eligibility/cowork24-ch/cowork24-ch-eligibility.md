---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Die Nutzung setzt voraus, dass du mindestens 18 Jahre alt bist oder die erforderliche Einwilligung deiner gesetzlichen Vertretung hast.
    value: '18'
  restricted_uses:
  - summary: Offensive or abusive content prohibited
    text: Der Betreiber duldet keinerlei anstössige, beleidigende, diskriminierende, hetzerische, sexuell explizite, gewaltverherrlichende, belästigende, bedrohliche oder anderweitig rechtswidrige Inhalte
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
name: cowork24
provenance_date: '2026-11-09'
provider_name: cowork24
provider_slug: cowork24-ch
slug: cowork24-ch-eligibility
source_date: '2026-11-09'
source_filename: cowork24-ch-eligibility.yml
source_heading: Eligibility
source_page: https://www.cowork24.ch/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: cowork24\naid: cowork24-ch\nurl: https://www.cowork24.ch/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Offensive or abusive content prohibited\n  text: Der Betreiber duldet keinerlei anstössige, beleidigende, diskriminierende, hetzerische, sexuell explizite,\n    gewaltverherrlichende, belästigende, bedrohliche oder anderweitig rechtswidrige Inhalte\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Die Nutzung setzt voraus, dass du mindestens\
  \ 18 Jahre alt bist oder die erforderliche Einwilligung deiner\n    gesetzlichen Vertretung hast.\n"
source_yaml_url: https://artifacts.apis.io/cowork24-ch/eligibility/cowork24-ch-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from cowork24's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Co-Working
- Workspace Booking
- Meeting Rooms
- Marketplace
- Switzerland
- MCP
---
