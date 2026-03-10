# Onboarding Guide

**Getting started with the KBase BER Data Lakehouse (K-BERDL)**

This guide walks new users, tenants, and BER program teams through the steps to get up and running on the K-BERDL platform — from account setup to data ingestion and analysis.

---

## Who Is This Guide For?

- **New users** accessing the platform for the first time
- **BER program teams** onboarding as a new tenant
- **Developers** integrating external systems or building on the K-BERDL APIs

---

## Step 1: Request Access

Contact the K-BERDL platform team to request access. You will need to provide:

- Your name, institution, and DOE program affiliation
- The type of access required (user, tenant admin, developer)
- A brief description of your intended use case

Once approved, you will receive credentials and be assigned to the appropriate tenant.

---

## Step 2: Set Up Your Account

After receiving your credentials:

1. Log in to the K-BERDL portal
2. Complete your user profile and institutional affiliation
3. Review and accept the platform data use policy
4. Configure multi-factor authentication (MFA)

---

## Step 3: Explore the Data Catalog

The unified BER-wide metadata catalog allows you to discover datasets across all tenants you have access to.

- Browse datasets by program, data type, or keyword
- View metadata, lineage, and access policies for each dataset
- Request access to embargoed or restricted datasets through the catalog UI

---

## Step 4: Ingest Your Data

Use the KBase Data Transfer Server (DTS) to bring your data into the platform:

```bash
# Authenticate
kbase-dts auth login

# Upload data to your tenant bucket
kbase-dts cp -r /path/to/data dts://my-bucket/my-project/
```

Refer to the [K-BERDL Data Ingestion](kberdl-data-ingestion.md) guide for supported formats, batch ingestion, and streaming options.

---

## Step 5: Run Your First Analysis

Once your data is ingested:

- Launch a **JupyterLab** workspace from the platform portal to explore your data interactively
- Submit a **Spark job** for large-scale processing
- Use a **KBase Narrative** to build and share reproducible analysis workflows

---

## Tenant Onboarding (BER Programs)

If you are onboarding a BER program as a new tenant, the following additional steps apply:

1. **Tenant Registration** — Define administrative contacts and resource requirements
2. **Policy Configuration** — Set default access policies (Public / Private / Embargoed)
3. **Schema Definition** — Work with the platform team to define your metadata models and table schemas
4. **Data Migration** — Batch ingest historical data via DTS
5. **API Integration** — Connect existing program APIs to the Lakehouse ingestion endpoints

See the [Tenant Model](tenant-model.md) documentation for full details.

---

## Support & Resources

- **Platform documentation:** [https://gazimahmud.github.io/kberdl-docs/](https://gazimahmud.github.io/kberdl-docs/)
- **Issues & requests:** Contact the K-BERDL platform team
- **Architecture overview:** [Architecture](architecture.md)
- **Data governance:** [Governance & Security](governance.md)
