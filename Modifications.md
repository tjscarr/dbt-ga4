# Fork Modifications

## src_ga4.yml
Convert variables to env_variables
```
    database: "{{env_var('DBT_PROJECT')}}" 
    schema: "{{env_var('DBT_GA4_ID')}}" 
```