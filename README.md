# ECOGW

В данном репозитории хранится конфигурация шлюза экосистемы

### Profile structure

.
+-- http_sowa_http_profile_name <br />
|&nbsp;&nbsp;&nbsp;&nbsp;+--http_proxy_services <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;+--http_sowa_http_hworld_http_proxy.yml <br />
|&nbsp;&nbsp;&nbsp;&nbsp;+--resources <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;+--schemes <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;+--service1_request_validation_scheme.json <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;+--service1_response_validation_scheme.json <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;... <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;+--error_pattern_file.json <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;+--error_rules.yml <br />



.
├── http_sowa_http_profile_name
|   ├──http_proxy_services
|   |   ├──http_sowa_http_hworld_http_proxy.yml
|   ├──resources
|   |   ├──schemes
|   |   |   ├──service1_request_validation_scheme.json
|   |   |   ├──service1_response_validation_scheme.json
|   |   |   ...
|   |   ├──error_pattern_file.json
|   |   ├──error_rules.yml

### TLS
