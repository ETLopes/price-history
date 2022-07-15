# ROADMAP
## v1
- App opens file picker
- You upload a jpeg of a supermarket receipt
- The app calls Google Vision API and parses:
  - all the line items (name, quantity, price and currency)
  - supermaket name
  - date of purchase
- The app returns an object with the parsed data
- The app can handle Brazilian and Italian receipts

## v1.1
- App returns parsed data in csv format

## v2
- Users can login into the app with OAuth (mainly google account)
- App is transformed in PWA can be be fully used with a cellphone
- App opens camera to take photo of the receipt
- App saves parsed data to the DB
- Users have a web-only interface to query all their data

## v3
- Users have multiple visualization options containing all their historical data
