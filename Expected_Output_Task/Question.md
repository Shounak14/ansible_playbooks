# Data Processing
## Can you process the data I have updated the payload
## The same thing that you did I have modified the payload


Expected output 
```
  output_data:
    - id: user_001
      first_name: Alice
      zip_code: 12345
      total_money_spend_on_orders: <Sum of all the orders of this user>
      total_order: 1
      list_of_order_id:
        - ORD-0001
        - ORD-0101
        - ORD-0102


```
`NOTE: Ensure the playbook will work for everyone who clones the repo` 

- eg: no local reference in the playbook