# Revolut Excel exports to QIF

Convert Revolut Excel (CSV) exports to QIF file

### How to use ?

You need to have `node.js` >= 10.5

```bash
git@github.com:hqro/revolut-csv-to-qif.git
cd revolut-csv-to-qif
npm install --production
node src/index.js $FILE
```

Replace `$FILE` with your *Revolut* export. You can now find a `*.qif` file on your current directory

```
more Revolut-Statement-*.qif

!Type:Bank
D06/12/2018
T-14.09
P<label>
^
D05/12/2018
T-2.80
P<label>
^
```