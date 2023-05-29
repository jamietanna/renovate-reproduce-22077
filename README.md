# Invalid hashicorp constraint for valid `.terraform-version`

https://github.com/renovatebot/renovate/discussions/22077

# Expected

No error, parses `0.14` as `0.14.11`.

# Actual

```
 WARN: Invalid hashicorp constraint (repository=jamietanna/renovate-reproduce-22077)
       "constraint": "latest:^0.14",
       "element": "latest:^0.14"
```
