# Recurring jobs

MRQ provides a simple scheduler to help you run tasks every X units of time like a crontab does.

See the [tests](https://github.com/pricingassistant/mrq/blob/master/tests/test_scheduler.py)

Please note that scheduling jobs once (setting a precise time for them to be executed in the future) is supported by `timed_set` [raw queues](queues.md#raw-queues).