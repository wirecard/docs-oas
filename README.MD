# YAML Files as OpenAPI documentation

With the help of the already existing documentation on https://doc.wirecard.com/ YAML files are created using Swagger Editor. These files picture the most common workflows in a simple and user-friendly way.

Workflows:

1. Wirecard Payment Page workflows
   - Payment-Processing of type _authorization_ with Credit Card
   - Payment-Processing of type _purchase_ with Credit Card
1. Wirecard Payment Gateway workflows
   - Capture with Credit Card
     - Full amount
     - Partial amount
   - Refund with Credit Card
     - Full amount
     - Partial amount
   - Void with Credit Card
   - Debit with PayPal

To use the Wirecard test Rest service Basic Authentication is needed.
