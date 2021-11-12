{% docs order_status %}
	
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| placed         | Order placed, not yet shipped                    |
| shipped        | Order has been shipped, not yet been delivered   |
| completed      | Order has been received by customers             |
| return pending | Customer indicated they want to return this item |
| returned       | Item has been returned                           |

{% enddocs %}

{% docs payment_method %}
	
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| credit_card    | Credit card was used for this transaction        |
| coupon         | Voucher/Coupon was used for this transaction     |
| bank_transfer  | Cutomer paid via Bank Transfer (BACS)            |
| gift_card      | Gift Card was redeemed for this transaction      |


{% enddocs %}