# ph-numbers
Philippine Telephone &amp; Mobile Phone Parser

## Plan

````
const PHN = require('ph-numbers');

PHN.parse();
// raw
// '09215345708', '+639215345708', '0921-5345-708', '639 21 534 5708'

// strip non-digits & whitespaces
// '09215345708', '639215345708', '09215345708', '639215345708'

// strip trailing country code or zero
// '9215345708', '9215345708', '9215345708', '9215345708'

// classify
// {
//   number: 9215345708
//   provider : 'Globe Telecom',
//   providerCode: 'G'
// }

```

## References

 * https://en.wikipedia.org/wiki/Telephone_numbers_in_the_Philippines
