---
title: Edit Orders
excerpt: >
  This endpoint allows users to update the status of one or more orders. Valid
  status values include:
    - `pending`: The order has not been delivered.
    - `delivery`: The order is in shipment.
    - `completed`: The order is finalized and delivered.

  Users must provide the `orderId` and the new `status` for each order.
api:
  file: orders.json
  operationId: post_orders-change-status
hidden: false
---