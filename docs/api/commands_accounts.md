Commands related to accounts
=========

#### Find out your account ID
```
keys:pubkey().
```
It returns pub key that identifies an account


### Find out your address:
```
keys:address().
```

#### Check your balance
```
api:balance().
```

#### Spend to account ID `To`
```
api:spend(To, Amount).
```

####Create Account
[WARNING!!! Before creating an account, make sure your wallet is secure!](keys.md)
To create a new account, and give it some money:
```
api:create_account(Address, AmountOfMoney).
```

####Delete Account
To delete an account and send all it's money to account ID:
```
api:delete_account(ID).
```

####Look up an account
```
api:account(ID).
```
