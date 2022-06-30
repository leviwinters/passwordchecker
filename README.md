# passwordchecker

The most secure way for you to check if your password has ever been hacked. Input your password and a result will be returned indicating whether or not your password is secure.

Imported the requests library to recieve data from the following API: https://api.pwnedpasswords.com/range/

In order to protect the source password, a k-anonymity model is implemented and ensures the password is being searched for by partial hash.
