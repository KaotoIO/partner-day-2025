# Load generator
![Load generator routes](routes.png)

## Context
These routes are responsible for publishing 3 endpoints that will be used for querying mock data for the Data mapping demo.

### Routes
- `GET localhost:8080/account`: This endpoint will return a mock account XML document. f.i.
```xml
<Account>
    <Name>Jane Doe</Name>
    <Address>Purkyňova 111, 612 00</Address>
    <City>Brno-Medlánky</City>
    <Country>Česká republika</Country>
</Account>
```

- `GET localhost:8080/cart`: This endpoint will return a mock cart XML document. f.i.
```xml
<Cart>
    <Item>
        <Title>Shadowman T-shirts</Title>
        <Note>XL</Note>
        <Quantity>10</Quantity>
        <Price>25.00</Price>
    </Item>
    <Item>
        <Title>Kaoto T-shirts</Title>
        <Note>L</Note>
        <Quantity>5</Quantity>
        <Price>24.50</Price>
    </Item>
</Cart>
```

- `GET localhost:8080/sequence`: This endpoint will return a mock sequence number. f.i.
```
123456789
```
