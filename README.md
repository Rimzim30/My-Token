# My-Token
This is a simple token contract.

The state variable used for this contract are 

- tokenName : It is a string type public variable used for the token name.
- tokenAbb : It is a string type public variable used for the token abbrevation.
- totalSupply : This uint type public variable is used for the total supply of the token and it is initialised with 0.


The mapping was done from address to the uint where address was a key type and uint was a value type. Mapping is generally used for state variables.
The two functions were used named- Mint function and Burn function.
The mint function increases the value of total supply and balance address . In this _value type local variable was used.

The burn function reduces the value of total supply and balance address .In this _value type local variable was used.

When the code was deployed, the tokenName, tokenAbb and the totalSupply was 
