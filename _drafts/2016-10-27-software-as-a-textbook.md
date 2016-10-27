---
published: false
---
## Software is like a textbook for your business 

If you were going to teach somebody how to run your business what would you tell them?   How would you explain the steps you take to buy products and invoice customers? How would you summarize that business operation?  What rules do you follow to generate revenue and keep your costs down?

That's what I do all day for customers.  They explain to me what they do to make a living and I turn that into software.  Imagine software is an employee who always does exactly what you tell them exactly when you want them to.   How great is that?  That's what I try to recreate for my clients.

> When a customer confirms a quote we generate a purchase order for each vendor on the confirmed quote.
-Client

I would then think to myself.  
- How does a customer confirm a quote?  
- What data is needed to generate a purchase order and where does it come from? 
- Do I need to update the data model?  
- Finally, what are the exact steps to create a purchase order?

After confirming with my client I would translate this business rule into psuedo-code

1. Click the confirm button on the quote details page.
2. Get all the unique vendor id's from the quote items
3. For each vendor generate a new purchase order
	a. Get quote Items for that vendor
    b. Create a purchase order item for each quote item
4. Inform the user that the purchase orders have been created.

Something like that. :smile:


