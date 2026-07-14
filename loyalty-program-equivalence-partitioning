| Type          | Class/Value    | Expecting result     |                                                            |
|---------------|----------------|----------------------|------------------------------------------------------------|
| years         | Invalid [0; 1) | discount not applies |                                                            |
| years         | Valid [1; inf) | discount applies     |                                                            |
| returnedOrder | true           | discount not applies |                                                            |
| returnedOrder | false          | discount applies     |                                                            |
| paymentMethod | MasterCard     | discount = 0.1       |                                                            |
| paymentMethod | Visa           | discount = 0         |                                                            |
| paymentMethod | None           | validation error     |                                                            |
| birthday      | true           | discount = 0.5       | *birthday = getCustomerBirthdayDate() === getCurrentDate() |
| birthday      | false          | discount = 0         |                                                            |
