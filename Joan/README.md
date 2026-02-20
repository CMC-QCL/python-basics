# QCL Workshop Series
## Practical Programming with Python


## Teacher's Notes
- Update the price of NVDIA, GOOG, APPL before starting workshop

### `buy_snacks` function
```
# Combining a for loop, lists, dict, and an if statement
def buy_snacks(snack_options, budget):
  # An empty list
  purchased_snacks = []

  # Printing our budget
  print(f"--- Starting Budget: ${budget}--- ")

  # Printing our snack options
  print(f"--- Snack Options: {snack_options}")

  for snack in snack_options:
    price = snack_options[snack]

    # if we have the budget, we will buy the snack
    if price <= snack_budget:
      # buy
      purchased_snacks.append(snack)
      snack_budget -= snack
      print(f"We bought {snack} at price ${price}.")
    else:
      # hold
      print(f"We did not buy {snack} at price ${price}, it exceeded our budget of {snack_budget}")

  print(f"Remaining Cash: ${budget:.2f}")
  print(f"Purchased Snacks: {purchased_snacks}")
```

## Localist Info

### Summary
Python is one of the most popular programming languages for data scientists, web developers, and machine learning practitioners. Its simple syntax makes it an easy-to-write (and an easy-to-learn) language. In this workshop, you will learn the basics of the Python programming language by creating, step by step, a function that will potentially make grocery shopping easier.

This is a workshop designed for beginners, so no prior knowledge of Python or any programming language is needed.

### Learning Objectives
By the end of this workshop you will be able to:

* Create and use functions
* Create lists and dictionaries and access its elements
* Read error messages
* Use for loops
* Use conditional statements (if, elif and else)

### Prerequisites
This is a Level 1 Workshop, so no programming knowledge is assumed.

### Last updated: 
February 19, 2026

## Workshop Attendees
Thank you for registering for this Workshop.  
If you need to cancel, please do so earlier rather than later to give others a chance to register.

## Ticket Cancellation and No-Show Policy:
If you need to cancel your reservation, please contact us by email at qcl@cmc.edu at least 24 hours prior to the event. A prompt cancellation will help us contact the next person on the waitlist. In case of 2 or more no-shows (without cancellation), you will lose your privilege to take our free workshops during the semester.
