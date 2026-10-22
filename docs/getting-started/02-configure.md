---
title: Configure the CLI
sidebar_label: Configure
---

Create an `acme.config.json` in your project:

```json
{ "project": "my-app", "region": "eu-west-1" }
```

| Key | Required | Description |
| --- | --- | --- |
| `project` | Yes | Your project name. |
| `region` | No | Where builds run. Defaults to `us-east-1`. |
