## Swiss Accounting Integration

ERPNext Functionality with Swiss QR Integration 
and Abacus Export


### Structure

App Contains 3 Modules

1. Abacus Exports
2. Swiss QR Bill
3. CAMT Import for Switzerland

#### Swiss QR Bill

It Contains 1 Doctype Called **Swiss QR Bill Settings**

In order to Setup QR Bill to Working Following Things are Required

1. Create A Company With Proper Address
2. Create A Customer with Proper Address and Language
3. Create A Bank Account For Company with IBAN
4. Add Entry in Swiss QR Bill Settings for Company

### To build updated js code
```
npx webpack --config webpack.config.js
Bench build
Bench restart
```

#### License

GNU GPL V3
