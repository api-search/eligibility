---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 1.7.Visitante:éapessoafísicaqueutilizaoWebsite.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Only legally capable persons may use the website
    text: oWebsitesópodeserutilizadoporpessoalegalmentecapazoudevidamenterepresentadaouassistida
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Poderáserexigidodousuárioetapadevalidaçãodosdadoscadastraisfornecidosnacriaçãodaconta;
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kovi
provenance_date: '2026-11-09'
provider_name: Kovi
provider_slug: kovi
slug: kovi-eligibility
source_date: '2026-11-09'
source_filename: kovi-eligibility.yml
source_heading: Eligibility
source_page: https://www.kovi.com.br/hubfs/Arquivos%20rodap%C3%A9/Termos%20de%20Uso%20do%20site%20e%20do%20aplicativo.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kovi\naid: kovi\nurl: https://www.kovi.com.br/hubfs/Arquivos%20rodap%C3%A9/Termos%20de%20Uso%20do%20site%20e%20do%20aplicativo.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 1.7.Visitante:éapessoafísicaqueutilizaoWebsite.\nrestricted_uses:\n- summary: Only legally capable persons may use the website\n  text: oWebsitesópodeserutilizadoporpessoalegalmentecapazoudevidamenterepresentadaouassistida\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Poderáserexigidodousuárioetapadevalidaçãodosdadoscadastraisfornecidosnacriaçãodaconta;\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kovi/eligibility/kovi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Kovi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobility
- Car Rental
- Car Subscription
- Ride Hailing
- Fleet Management
- Transportation
- Brazil
- Latin America
---
