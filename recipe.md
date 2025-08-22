# Take Away Solo Project
## User Story
```python
'''
As a customer
So that I can check if I want to order something
I would like to see a list of dishes with prices.

As a customer
So that I can order the meal I want
I would like to be able to select some number of several available dishes.

As a customer
So that I can verify that my order is correct
I would like to see an itemised receipt with a grand total.
'''
```
### Bonus User Story
``` python
#Using the twilio-python library
'''
As a customer
So that I am reassured that my order will be delivered on time
I would like to receive a text such as "Thank you! Your order was placed and will be delivered before 18:52" after I have ordered.
'''
```
## Class Design
```python
#lib/Menu.py
```
```python
#lib/Order.py
```
```python
#lib/Messenger.py
```
```python
#lib/Restaurant.py
```

## Unit Tests
```python
#tests/test_Menu.py
```
```python
#tests/test_Order.py
```
```python
#tests/test_Messenger.py
```
```python
#tests/test_Restaurant.py
```

## Integration Tests
```python
#tests/test_integration.py
```