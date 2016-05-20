# person-generator

Generate a fake person with "real" data

## Description

When creating analytics software, having data is crucial, 
this generator is different from others, because it is 
utilizing real information, without using online APIs to 
create a person that can pass various validations in your
code.

## Installation

```
npm install person-generator
```

## Synopsis
```
var Person = require('person-generator');

console.log(Person.get());

/*
{ pid: 
   { set: 1,
     external: '0VBD0NMFI20W5UCGXF6H',
     internal: 'KJDZBFMNIOLDTBXDHYZP',
     alternate: '01522798582610954454' },
  ssn: '262153012',
  dob: '1951-01-30 12:05:16',
  lastName: 'MCKERLIE',
  firstName: 'COLBY',
  middleName: 'AMOS',
  middleInitial: 'A',
  phoneNumber: { home: '(197)427-9527', business: '(326)501-2942' },
  gender: 'male',
  appointment: 
   { start: '2016-05-20 23:10:57',
     end: '2016-05-21 02:23:57',
     duration: 193,
     durationUnits: 'MIN' },
  dmv: { id: 'M264-101-51-030-0' } }
*/
```

