## FinAPI - Financial

---

### Requirements

- [x] It should be possible to create an account
- [x] It must be possible to retrieve the customer's bank statement
- [] It must be possible to make a deposit
- [] It must be possible to make a withdrawal
- [] It must be possible to retrieve the customer's bank statement by date
- [] It must be possible to update customer account data
- [] It must be possible to obtain customer account data
- [] It should be possible to delete an account

---

### Business rules

- [x] It should not be possible to register an account with an existing CPF
- [x] It should not be possible to deposit to a non-existing account
- [] It should not be possible to fetch a statement from a non-existing account
- [] It should not be possible to withdraw to a non-existing account
- [] It should not be possible to delete a non-existing account
- [] It should not be possible to withdraw when the balance is insufficient

---

### Comments

- cpf (string)
- name (string)
- id (uuid)
- statement []