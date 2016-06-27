# product-order

RESTFul webservice for the Product Order (Add, update, delete)

GET : http://localhost:8080/productorder-0.0.1-SNAPSHOT/rest/orderservice/or1/getorder/2

EDIT : http://localhost:8080/productorder-0.0.1-SNAPSHOT/rest/orderservice/or1/updateorder/

DELETE : http://localhost:8080/productorder-0.0.1-SNAPSHOT/rest/orderservice/or1/deleteorder/2

ADD : http://localhost:8080/productorder-0.0.1-SNAPSHOT/rest/orderservice/or1/addorder/

Header : 
Content-Type : Application/json

Body:  Request for the Add and Update order  
{
    "orderdetails": {
        "orderId": 2,
        "productId": 234,
        "orderQuantity": 333,
        "orderTotal": 333,
        "customerId": 2
    }
}
