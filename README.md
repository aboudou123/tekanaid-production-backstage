# TechCorp Backstage Catalog

This repository contains the catalog entities for TechCorp's Backstage developer portal.

## Structure

```
catalog/
├── all.yaml              # Root location file (Backstage entry point)
├── domains/              # Business domain definitions
├── systems/              # System definitions
├── components/           # Service/component definitions
├── resources/            # Infrastructure resource definitions
└── templates/            # Golden path templates
```

## Usage

This repository is automatically read by Backstage using the GitHub integration.
Changes pushed to this repo will be discovered by Backstage within a few minutes.

## Adding New Entities

1. Create YAML files in the appropriate subdirectory
2. Add a reference to the new file in `catalog/all.yaml`
3. Push changes to GitHub
4. Wait for Backstage to discover the new entities (usually 1-5 minutes)


<img width="686" height="432" alt="5b" src="https://github.com/user-attachments/assets/18977eff-340a-47d1-ad56-8576f54eb9ec" />

<img width="849" height="516" alt="6d" src="https://github.com/user-attachments/assets/8f25c0e6-5997-4da3-a7d9-3a896990f2aa" />

<img width="862" height="549" alt="10d" src="https://github.com/user-attachments/assets/bec4482e-09ad-4cc7-965a-8110f54daba7" />

<img width="849" height="516" alt="6d" src="https://github.com/user-attachments/assets/efc3ea5d-0b02-41e3-87b9-cd637b4cd234" />

<img width="686" height="432" alt="5b" src="https://github.com/user-attachments/assets/540d229d-2c16-463d-af5c-f05bcfc04df1" />




