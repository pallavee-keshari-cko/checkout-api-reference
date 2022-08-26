# Changelog

| Date       | Description of change                                                                                                 |
| ---------- | --------------------------------------------------------------------------------------------------------------------- |
| 2022/08/25 | Add P24 NAS Request and Response source.                                                                               |
| 2022/08/19 | Add Benefit PG specific requirements to `reference` description                                                       |
| 2022/08/19 | Added alipay_plus type                                                                                                |
| 2022/08/17 | Added Reports API                                                                                                     |
| 2022/08/10 | Add Giropay, EPS Request and Response source.                                                                         |
| 2022/08/09 | Add Mbway NAS Request and Response source.                                                                            |
| 2022/08/09 | Add QPay Payment Request &  Response source.                                                                          |
| 2022/08/09 | Add Benefit PG Request and Response sources                                                                           |
| 2022/08/08 | Fixing document types for platforms                                                                                   |
| 2022/08/05 | Add AfterPay NAS Request and Response source.                                                                         |
| 2022/08/03 | Add missing `token_format` to Google Pay and Apple Pay token responses.                                               |
| 2022/07/29 | Adding `marketplace` object to capture and other minor fixes to IP space                                              |
| 2022/07/29 | Update Java, C#, PHP & Python code samples to match new SDK Version.                                                  |
| 2022/07/20 | Added Alipay Plus's e-wallets supports                                                                                |
| 2022/07/20 | Adding required fields for Platforms payment instruments and separate `corporate` and `individual` examples           |
| 2022/07/20 | Added `knet`, `giropay`, `bancontact`, `eps`, `p24`, and `multibanco` to Hosted Payments and Payment Links.           |
| 2022/07/19 | Updated example for Platforms payout schedules from `currency` to `GBP` and `ISO`                                     |
| 2022/07/19 | Update WeChat Pay NAS structure                                                                                       |
| 2022/07/14 | Add Sofort NAS Request and Response source.  

| 2022/08/19 | Add Multibanco NAS Request and Response source.                                                                           |
| 2022/07/14 | Add `locale` property to Get Payment Link details response                                                            |
| 2022/07/14 | Added `customer`, `description`, `billing descriptor`, `shipping`, and `items` objects to Capture requests            |
| 2022/07/13 | Added fields for Level 2 and Level 3 data.                                                                            |
| 2022/07/13 | Added the `phone` object to `customer` object for payments.                                                           |
| 2022/07/13 | Adds fields required EU sellers using the Accounts API                                                                |
| 2022/07/13 | Added the `phone` object to `customer` object for payments.                                                           |
| 2022/07/11 | Replaced `identification` enum with `identity_verification` for Platform Files purpose                                |
| 2022/07/06 | Change `by_day` and `by_month_day` within Platform payout schedule to support multiple values.                        |
| 2022/07/04 | Rename instances of `instalment` to `installment` in Sessions.                                                        |
| 2022/05/28 | Add `instalment`, `add_card`, `maintain_card` authentication type in Sessions.                                        |
| 2022/06/27 | Added iDEAL NAS Request and Response Source                                                                           |
| 2022/05/23 | Update Alipay Plus NAS structure                                                                                      |
| 2022/06/01 | Marketplace API renamed to Accounts API                                                                               |
| 2022/05/23 | Added Alipay Plus NAS structure                                                                                       |
| 2022/05/19 | Added WeChat Pay NAS structure                                                                                        |
| 2022/05/18 | Added "Get transfer details"                                                                                          |
| 2022/05/11 | Added Arabic locale option to Hosted Payments Page and Payment Links.                                                 |
| 2022/05/10 | Added `3ds.challenge_indicator` to Hosted Payments Page and Payment Links.                                            |
| 2022/04/28 | Add recurring authentication type in Sessions.                                                                        |
| 2022/04/27 | Added Scandinavian locale options to Hosted Payments Page and Payment Links.                                          |
| 2022/04/27 | Added the `challenged` field to the GET payments response schema.                                                     |
| 2022/04/20 | Added required idempotency key to Transfers API                                                                       |
| 2022/04/19 | Update `3ds.exemption` available enums                                                                                |
| 2022/04/06 | Added `/payout-schedules` endpoint with `GET` and `PUT` methods to the Marketplace API                                |
| 2022/03/30 | Adds "Get action invocations" endpoint                                                                                |
| 2022/03/28 | Update PHP code samples                                                                                               |
| 2022/03/25 | Increased max length for `reference` in "Onboard a sub-entity" to 50 characters                                       |
| 2022/03/22 | Added new scheme `cartes_bancaires` to enum `scheme` in Get and Create Sessions Responses                             |
| 2022/03/22 | Fixed invalid format for `authentication_date`                                                                        |
| 2022/03/18 | Added Cartes Bancaires changes to Sessions request and response.                                                      |
| 2022/03/16 | Adds `document` object to the `company` object in the Marketplace API                                                 |
| 2022/03/09 | Added the `provider_token` payment request source type.                                                               |
| 2022/03/08 | Change C# samples to suggest the usage of `await` instead of `.Result`                                                |
| 2022/03/02 | Adds Transfers and Balances                                                                                           |
| 2022/02/23 | Adds Hosted Payments Page and Payment Links                                                                           |
| 2022/02/18 | Added `Increment Payment Authorization` code samples for Java & C#                                                    |
| 2022/02/02 | Adds `active` property for workflows                                                                                  |
| 2022/01/26 | Update code samples for Java.                                                                                         |
| 2022/01/25 | Update code samples for C#.                                                                                           |
| 2022/01/19 | Added test a workflow endpoint.                                                                                       |
| 2022/01/13 | Update code samples for Node JS.                                                                                      |
| 2021/11/29 | Increase max length of the NAS `success_url` and `failure_url` fields of the payment request (both from 255 to 1024). |
| 2021/11/11 | Added `3ds.challenge_indicator` to card payment requests.                                                             |
| 2021/11/03 | Adds `identification` object under parent `sender` object in payment request.                                         |
| 2021/10/18 | Added the `marketplaces.sub-entities` object to support split payments.                                               |
