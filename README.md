# Dmoney API Performance Test (Dmoney)

## About this project:

## Tools Used
- Jmeter


## How to run this project

- Clone This project
- Then run the following command 

```bash
 $ jmeter -n -t Jmeter Performance test using API Chaining.jmx -l Dmoney-Load-Test.csv -e -o Reports
```
## d-money URL
- http://dmoney.roadtocareer.net/

## Genarated HTML Report
![image](https://github.com/RajaulIslam/demo-transaction-api-jmeter/assets/171759757/53751cc1-50e2-4651-a306-fdfcdc772513)
![image](https://github.com/RajaulIslam/demo-transaction-api-jmeter/assets/171759757/16e32151-e915-4599-9970-9affda01c527)

## Performance test have done based on following scenario.

1. Admin creates an agent and a customer
2. Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
3. Deposit 1000 tk to customer from agent account
4. Check balance from customer account
5. Withdraw 500 tk from customer account
6. Payment 200 tk from customer account (Merchant account: 01686606905)

## Request I have Covered

1. Login to user
2. Create a new agent/customer
3. Give balance to the newly created agent from system
4. Search the customer's current balance by using phone number
5. Withdraw money from customer to agent account.
6. Payment form customer account to merchant account.
7. Delete the user
