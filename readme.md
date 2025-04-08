Since the goal is finding pet products easier for customers, here are my thoughts on the current navbar:

1. Labelling:

- It already shows 'Dog' & 'Cat' as two main categories of product, but clicking them will show another sidebar for filtering, while the site /dog or /cat can handle it.
  => This can be improved with 'For Dogs' & 'For Cats' for clearer labeling.

- 'All Products' is fine but can be shown on the body (when filtering or right from the home page).

- 'Human' can be confusing (food for humans? Is that like pet food? It feels weird for me haha).
  Is this prioritized as a best-selling or unique product?
  If not, then remove it and show it when customers see 'All Products.'

- 'Pet Life' I thought was something about on-going service but rather just 'Articles'

- 'Store Locator' is not a common label; I was confused at first as a tool for something. "Location" can be a clearer term.
  Also, it's not a main activity, so it can be moved as a footer link or included in an "About Us" dropdown menu.

- 'Our Story,' 'Contact Us,' & 'Investors' are for "learning more" activities and not just for customers; they should be included in "About Us."

- Also, it's confusing when I see "United States" stand close to "Investors" (is that for a language option, market, or something for investors?).
  It seems to only show "Investor" in US mode, which is more confusing.

2. Layout:

- 3 rows for a banner are space-consuming if people want to view products in a big picture instead of scrolling.

- The top banner currently is supposed to display sales info, but now it is just two links and requires signing in -> not so helpful; should be disabled unless there are sales.

- The sidebar has replicated info like the navbar and takes too much space, given that the navbar already takes a lot at the top of the page;

- also, it cannot be easily closed unless clicking the "X" icon instead of just clicking the outer area.

- the number of products is not that huge, and unless the user knows the name of the product in mind, I'd minimize it into a Search icon (only show a popup of a search bar when clicked). Going to the Dog or Cat site and use the filter can handle the job.

- In case customers cannot find what they need and want to contact, & the Contact Us page currently doesn't have any form and just has email and phone

=> Phone and Email can be shown right away in the footer. If they have any other inquiries via mail, then they can go to the About Us/Contact Us site.

TL;DR: My suggested navbar would be

![demo image](demo.png)

- 1 row of Logo, navlinks that some of them have dropdown menu
- the architecture would be

<Nav left>

- Logo
- About Us (optional, can be on footer)
  > Our Story
  > Sustainability statement/Whistleblower function
  > ...
  > For Investor (if on U.S mode)
  > Contact Us (if have form, otherwise show email & phone in Footer)
  > Location (better in Footer)
- For Dogs
- For Cats
- All products
- Articles

<Nav right> 
+ Search Icon 
+ Language icon & country name 
+ Sign in icon & label 
+ Cart icon & label
