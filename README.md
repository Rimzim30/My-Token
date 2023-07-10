# My-Token
This is a simple token contract.

The state variable used for this contract are :

- tokenName : It is a string type public variable used for the token name.
- tokenAbbrv : It is a string type public variable used for the token abbrevation.
- totalSupply : This uint type public variable is used for the total supply of the token and it is initialised with 0.

The mapping was done from address to the uint where address was a key type and uint was a value type. 

The two functions were used named:

- Mint function
- Burn function

The mint function increases the value of total supply and balance address . In this _value is the local variable was used.

The burn function reduces the value of total supply and balance address .In this _value is the local variable was used.

When the code was deployed, the total supply of token was reduced by changing the value of _value.
