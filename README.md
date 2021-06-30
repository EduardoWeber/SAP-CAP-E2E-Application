# Getting Started
 
Project done following this SAP Developer mission: [Build an Application End-to-End using CAP, Node.js and VS Code](https://developers.sap.com/mission.btp-application-cap-e2e.html)

Recommended project layout:

| File or Folder | Purpose |
|---------|----------|
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide

## Next Steps

- Open a new terminal and run `cds watch`
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).

## Deploy

Ps: To deploy use branch [deploy-to-sap-btp](https://github.com/EduardoWeber/SAP-CAP-E2E-Application/tree/deploy-to-sap-btp)

- Build with `mtb build -t ./`
- Deploy with `cf deploy cpapp_1.0.0.mtar`

## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.
