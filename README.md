# My-Token
This is a simple token contract.

The state variable used for this contract are 

- tokenName : It is a string type public variable used for the token name.
- tokenAbb : It is a string type public variable used for the token abbrevation.
- totalSupply : This uint type public variable is used for the total supply of the token and it is initialised with 0.


The mapping was done from address to the uint where address was a key and uint was a value .
The two functions were used named- Mint function and Burn function.
The mint function increases the value of total supply and balance address . In this _value type local variable was used.
As the code was deployed , the total supply was given as the subtraction of the burn value from the mint value.
