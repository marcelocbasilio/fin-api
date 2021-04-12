## FinAPI - Financial

---

### Requirements

- [x] It should be possible to create an account
- [x] It must be possible to retrieve the customer's bank statement
- [x] It must be possible to make a deposit
- [x] It must be possible to make a withdrawal
- [x] It must be possible to retrieve the customer's bank statement by date
- [x] It must be possible to update customer account data
- [x] It must be possible to obtain customer account data
- [x] It should be possible to delete an account

---

### Business rules

- [x] It should not be possible to register an account with an existing CPF
- [x] It should not be possible to deposit to a non-existing account
- [x] It should not be possible to fetch a statement from a non-existing account
- [x] It should not be possible to withdraw to a non-existing account
- [x] It should not be possible to withdraw when the balance is insufficient
- [x] It should not be possible to delete a non-existing account
- [x] It should be possible to return the balance

---

### Comments

- cpf (string)
- name (string)
- id (uuid)
- statement []