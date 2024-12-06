---
title: Get all Orders
excerpt: >
  This endpoint allows you to get the orders of the user. Order can either be:

  - `pending`: Order is in the `pending` state. It has not been delivered. 

  - `delivery`: Order is in the `delivery` state. It is still in shipment and
  not completed.

  - `completed`: Order is completed an finalized. 


  To change the status of an order, use the **POST Edit Orders** endpoint.
api:
  file: orders.json
  operationId: get_orders-get-all
hidden: false
---