# Serverless Setup

Install python and pandas/jupyter and connect it to the required MSRC DB.

## Create Data

Run the jupyter notebooks. Automate them with papermill if you want. Data will be output into following folder structure:

```
# year/entities/entities.json
# year/facts/entitid/aggregationcode.json

YEAR (2017)
├── entities
│   └── entities.json
└── facts
    ├── ENTITYID(0000-000)
    │   ├── AGGREGATIONCODE(ALL).json
```
