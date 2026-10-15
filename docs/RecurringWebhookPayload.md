# GriffNode::RecurringWebhookPayload

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **event** | **String** |  |  |
| **timestamp** | **Time** |  |  |
| **schedule_id** | **String** |  |  |
| **reference** | **String** | Your own customer/order id, as entered on the schedule. | [optional] |
| **customer_email** | **String** |  | [optional] |
| **description** | **String** |  | [optional] |
| **amount_fiat** | **String** | Decimal string. | [optional] |
| **currency_fiat** | **String** |  | [optional] |
| **interval** | **String** |  | [optional] |
| **status** | **String** |  |  |
| **period_no** | **Integer** | recurring.payment.* only. | [optional] |
| **transaction_id** | **String** | recurring.payment.completed only. | [optional] |
| **reason** | **String** | recurring.stopped only. | [optional] |

## Example

```ruby
require 'griffnode'

instance = GriffNode::RecurringWebhookPayload.new(
  id: null,
  event: null,
  timestamp: null,
  schedule_id: null,
  reference: null,
  customer_email: null,
  description: null,
  amount_fiat: null,
  currency_fiat: null,
  interval: null,
  status: null,
  period_no: null,
  transaction_id: null,
  reason: null
)
```

