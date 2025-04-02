# Create your BTP Account structure in SAP LeanIX

## Overview
Having transparency about your BTP account structure in SAP LeanIX allows you to take more focussed actions, as it can be used to tell:
* who (person, team) is _responsible_ for which account
* who (team, org unit) is _using_ which account
* which services are subscribed by an account - and vice-versa: which accounts have subscribed which BTP service
* which BTP extesions run on top of which BTP sub-accounts, and vice-versa: which BTP sub-accounts are used to run which BTP extensions

> [!NOTE]
> In a future version, SAP landscape discovery is planned to support automated discovery of your BTP account structure as well as the account-level service subscriptions. Please find details and track progress in  the [corresponding road map item](https://roadmap.leanix.net/c/537-application-discovery-sap-btp-service-discovery)

## Excercise

1. Open the Inventory
2. You will use the 'Import' action to import 1..5 BTP sub-accounts. For this, download [BTP Account Structure.xlsx](BTP%20Account%20Structure.xlsx) and input the sub-account and global account. Please make sure to adapt the 'Parent' link accordingly.
> [!TIP]
> The Excel import is a versatile approach to load "mass data"
3. Perform the 'Import'.
5. Review the results.
6. For some of _your_ BTP sub-acounts ...
   - add yourself as Responsible
   - add 1..3 'IT Compponent' relations
   - create and add an Application representing a BTP extension
  
> [!TIP]
> You can use the "Add relation" form to create an Application by searching for it - and then adding it on the fly
