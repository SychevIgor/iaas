# Сервер
***  
**Наименование**: {{title}}

| Наименование | IP адреса                         | vApp Networks | vApp                      | VDC                     | DC/IaaS      |
|--------------|-----------------------------------|---------------|---------------------------|-------------------------|--------------|
| {{title}}     | {{#addresses}}{{.}}{{/addresses}} | {{subnet}}    | [{{vapp}}]({{vapp_link}}) | [{{vdc}}]({{vdc_link}}) | {{&dc_title}} |

{{#description}}
## Описание
{{.}}
{{/description}}

