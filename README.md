# payment-reference

All team members have write access here and at https://github.com/DoliGreece/dolibarr/tree/payment-reference branch of develop

Please use discussions, Issues and Wiki here to collaborate

Please feel free to modify bellow steps

### Suggested implementation

1.
- [x] Add field payment_reference in llx_facture table https://github.com/Dolibarr/dolibarr/pull/31553
- [x] Add field tp_payment_reference in llx_societe table https://github.com/Dolibarr/dolibarr/pull/31553

2.
- [ ] Add method to create user configurable payment_reference using Customer code, contract ref, invoice ref or a combination.
- [x] Commit https://github.com/Dolibarr/dolibarr/pull/31376 for Belgian type
- [ ] Add QR code for Finnish RF
- [ ] Add Finnish legacy payment reference
- [ ] Add Finnish legacy payment barcode (PDF) / virtual barcode (email) 
- [ ] Add methods for "European" RF generation and QR code support
- [x] Structured communication in sepa xml https://github.com/Dolibarr/dolibarr/pull/31383
- [ ] Add RF in sepa xml
- [ ] Add FI/RF in sepa xml 
- [ ] Add payment_reference in EPC QR code and Swiss QR-Bill 

3.
- [ ] Add option for user to select payment reference  type 
- [ ] Add per third party RF generation options like customer/vendor code in societe/card.php
- [ ] Show selected type generated field in validated invoice, proposal, sales cards
- [ ] Add payment_reference in relevant PDF templates
