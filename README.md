# WorldTelephoneFormatterJS
A useful tool for formatting phone numbers with the correct prefix by given country code

Instalation
Paste code inside your project folder, 
include it inside header or just in any class.

Use :
  let countryCode = "CZ";
  let telephoneToFormat = "225321486"
  
  let telephoneFormatted = TelephoneFormatter.normalize(telephoneToFormat, countryCode);
  
  OUTPUT: +420 225 321 486
  
  
Important! If you want to change spacing between numbers, change it in makeSpaces() there is a number 3, for making spaces after 3 chars.
 
  Any contribution is welcomed!  :)
