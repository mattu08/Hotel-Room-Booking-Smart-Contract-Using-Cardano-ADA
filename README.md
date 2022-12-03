# Hotel-Room-Booking-Smart-Contract-Using-Cardano-ADA
Is a hotel room booking Cardano ADA smart contract created using Marlowe and Blocks programming languages. This is just a proof of concept, I created while playing about with ADA smart contracts.
* Option 1. Book standard room. ₳ 0.000090
* Option 2. Book standard room with breakfast included. ₳ 0.000120
* Option 3. Book luxury room includes breakfast. ₳ 0.000150
- Created using: https://play.marlowe-finance.io/
- Help from: https://docs.cardano.org/marlowe/learn-about-marlowe/
## Example of when the Smart Contract has been executed:
```
TRANSACTION LOG
Event
Time
Contract started
21:26
Guest choosed the value Book Room 1 for choice with id "Book Room"
21:26
Guest deposited ₳ 0.000090 from his/her wallet into Guest account
21:26
The contract pays ₳ 0.000090 from account of Guest to Hotel wallet
21:26
Contract ended
21:26
```
## Example of when the Smart Contract has expired (No ADA was exchanged, due to the contract expiring):
```
Current time:
3 Dec 2022 21:26 GMT
expiration time:
Closed
ACTIONS
No valid inputs can be added to the transaction
TRANSACTION LOG
Event
Time
Contract started
21:26
Contract ended
21:26
```
