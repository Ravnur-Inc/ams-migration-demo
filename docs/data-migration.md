# Application Migration to RMS

To make all of yours media stored in AMS account playable in RMS you need to run migration procedure. It will extract all required resources from AMS account and save them in RMS database.

List of entities that will be migrated:
- Transforms
- Content Key Policies
- Streaming Policies
- Assets
- Streaming Locators

## Get AMS credentials
1. On the Azure Portal, go to RMS Managed Application resource: Managed Applications center -> Marketplace Applications -> Find RMS Application and open it.
2. Go to API Access.
      ![Console credentials](img/data-migration-select-api.png)
3. Scroll down to "Connect to Media Services API" section and select JSON view.
      ![Console credentials](img/data-migration-json.png)

   
## Start Migration

1. Go to RMS Console and press the "Data migration" button for your RMS account.
      ![Console credentials](img/data-migration-console.png)
You will se the form where you should enter AMS api access credentials in Json format and comma separated list of emails for notifications about migration status (optional).
      ![Console credentials](img/data-migration-start.png)
2. To get Api access Json go to Api Access