Country Codes
=============

Utility to fetch country codes viz ISO2, ISO3 and Phone code of all the countries listed in http://countrycode.org/.

Exposes the below APIs:
- Pass in any of the PhoneCode,ISO2/ISO3 country code to get other details of the country.
- Get ISO2 country code.
- Get ISO3 country code.
- Get Phone code of country.

Version
----
0.0.2

Installation
--------------
```sh
npm install countrycodes
```
Examples
-----
```sh
CountryCodes.getCountry('India') > {"countryName":"India","iso2":"IN","iso3":"IND","phoneCode":"91"}
CountryCodes.getISO2('India') > IN
CountryCodes.getISO2('IND') > IN
CountryCodes.getISO2('91') > IN
CountryCodes.getISO3('India') > IND
CountryCodes.getISO3('In') > IND
CountryCodes.getISO3('91') > IND
CountryCodes.getPhoneCode('India') > 91
CountryCodes.getPhoneCode('IND') > 91
```

License
----
BSD
