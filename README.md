# Business Central Samples - Take Order

The **Take Order** sample demonstrates how you can build a customized user experience for servers at restaurants, using Power Apps powered by Business Central.

The app allows servers to seat guests at a table and provides an intuitive UI for easily taking their orders. The sample includes a Business Central extension, a Power App, and a Power Automate flow. The extension adds the appropriate APIs and extends the items and customer tables with the following fields:

**Items**
- *SoldInRestaurant*: Indicates if the item should appear in the app
- *LongItemDescription* and *AllergenInformation*: Optional fields that the app can utilize

**Customers**
- *IsTable*: Indicates that the customer should appear as a table within the app

The extension also includes a sample data page called **Take Order sample data**, which contains an action to generate sample items and tables for the app to use. 

*Note: The sample data generator has only been tested with US versions of Business Central. Adjustments may be necessary for other locales.*

## Try the sample yourself
Follow the steps in the [Try our sample apps](https://github.com/BusinessCentralDemos/AL-Go/blob/main/Scenarios/TryPowerPlatformSamples.md) guide to try the sample with your own tenant.

## Per Tenant Extension Project
This repository is based on the preview AL-Go for GitHub template, which is available [here](https://github.com/BusinessCentralDemos/AL-Go-PTE).
