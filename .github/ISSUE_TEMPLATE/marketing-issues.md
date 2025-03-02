---
name: Marketing Issues
about: this is about Marketing Issues
title: ''
labels: ''
assignees: ''

---

As a Marketing Manager
I need a list of customer names and emails
So that I can notify them of marketing promotions
Assumptions and Details:
* ﻿﻿We maintain customer emails
* ﻿﻿Customers have opted-in to promotions
Acceptance Criteria(done):
Given there are 100 customers in the database And 90 have opted into email promotions
When I request the customer email list
Then I should see a list of 90 customer emails
