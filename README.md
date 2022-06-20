# Reviewpad Catalog

This repository contains a catalog of Reviewpad specification for multiple workflows.

## Schema

In order to have the correct `yml` schema for reviewpad please add the following settings to your workspace settings.

```json
"yaml.schemas": {
    "https://github.com/reviewpad/schemas/blob/main/latest/schema.json": [
        "*.yml"
    ]
}
```