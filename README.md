#deliverable5

##Vulnerability 1
  
  This vulnerability attack confidentiality and integrity. Modification active attack can exploit this vulnerability. This vulnerability may lead to data loss, unauthorized login, unauthorized actions to database. Use ADO Command Objects with strong type checking and parameterized queries may minimize this impac.

URL:[http://demo.testfire.net/bank/login.aspx](http://demo.testfire.net/bank/login.aspx)

Steps to exploit the vulnerability:

1. Enter website

2. Locate username input

3. Enter "[ZAP' OR '1'='1' -- ]"

4. Locate password input

5. Enter any string value
![alt text](https://github.com/lszlawrence/deliverable5/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-11-16%20%E4%B8%8B%E5%8D%884.12.03.png)
6. Click "Login"
![alt text](https://github.com/lszlawrence/deliverable5/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-11-16%20%E4%B8%8B%E5%8D%884.12.09.png)

##Vulnerability 2

This vulnerability attack confidentiality and integrity. Modification active attack can exploit this vulnerability. This vulnerability may lead to data loss, unauthorized login, unauthorized actions to database, unauthorized actions on account form. Apply a 'whitelist' of allowed characters, or a 'blacklist' of disallowed characters in user input may minimize this impact.

URL:[http://testphp.vulnweb.com/login.php](http://testphp.vulnweb.com/login.php)

Steps to exploit the vulnerability:

1. Enter website

2. Locate "domain" input element

3. Enter ""

2. Locate username input

3. Enter "[ZAP' OR '1'='1' -- ]"

4. Locate password input

5. Enter any string value
![alt text](https://github.com/lszlawrence/deliverable5/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-11-16%20%E4%B8%8B%E5%8D%883.37.49.png)
6. Click "Login"
![alt text](https://github.com/lszlawrence/deliverable5/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-11-16%20%E4%B8%8B%E5%8D%883.13.13.png)
##Vulnerability 3

  This vulnerability attack confidentialitt, integrity, availability. Interception and interruption active attack can exploit this vulnerability. This Vulnerability may lead to data loss, unauthorized access to server operating system. When constructing OS command strings, use stringent whitelists that limit the character set based on the expected value of the parameter in the request. This will indirectly limit the scope of an attack, but this technique is less important than proper output encoding and escaping.
URL:[http://www.webscantest.com/](http://www.webscantest.com/)

Steps to exploit the vulnerability:

1. Enter website

2. Locate "domain" input element

3. Enter "[ZAP&cat /etc/passwd&]"
![alt text](https://github.com/lszlawrence/deliverable5/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-11-16%20%E4%B8%8B%E5%8D%883.35.25.png)
4. Click "Lookup"
![alt text](https://github.com/lszlawrence/deliverable5/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-11-16%20%E4%B8%8B%E5%8D%883.35.31.png)
