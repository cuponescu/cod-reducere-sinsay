# Cod Reducere Sinsay

O colecție de coduri de reducere Sinsay. Le folosim pentru testarea cuvintelor cheie [cod reducere Sinsay](https://cuponescu.ro/magazin/sinsay), [voucher Sinsay](https://cuponescu.ro/magazin/sinsay), [cupon Sinsay](https://cuponescu.ro/magazin/sinsay), și [cod promotional Sinsay](https://cuponescu.ro/magazin/sinsay) de pe Cuponescu.ro.

## Instalare

Instalează `cod-reducere-sinsay` prin NPM:

```bash
npm install cod-reducere-sinsay
```

## Utilizare

Pachetul conține un array de obiecte reprezentând coduri de reducere.

În Node:

```javascript
var codes = require('cod-reducere-sinsay')

console.log(codes)

// [
//   {
//     site: 'https://www.sinsay.com/ro',
//     cod_reducere: 'SINSAY10',
//     reducere: '10% reducere',
//     descriere: 'Reducere de 10% la toate produsele'
//   },
//   ...
// ]
```

## Despre

Cod-reducere-sinsay a fost creat de echipa de la Cuponescu pentru a ajuta cu testarea.

https://cuponescu.ro
