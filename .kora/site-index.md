# Site index · format 2
Structure and the names of what each page offers. Values that change often — prices, hours, phone,
address — and body copy are deliberately not recorded here; read the page itself for those.

## index.html → /
title: India Avenue | Fine Indian Cuisine in Greenwich, CT | Naan, Roti, Soup, Rice & Beer
purpose: The landing page — an introduction to the restaurant with a featured-dish strip, hours, gallery, reviews and FAQ.
sections:
- `#hero` "Fine Indian Food in Greenwich , CT" — the hero, built from the label, title, description and action buttons below it
- `#heroBg` — the hero's background image layer
- `#heroLabel` — the small label above the hero title
- `#heroTitle` — the hero's h1
- `#heroDesc` — the hero's supporting paragraph
- `#heroActions` — the hero's call-to-action buttons
- `#marqueeTrack` — a scrolling strip of phrases: Tandoori Specialties, Fragrant Curries, Artisan Breads, Clay Oven Magic, Royal Biryani, Exotic Spices
- `#featuredTrack` "Chef's Favorites" — a carousel of 4 featured dishes: Masala Dosa, Butter Chicken, Garlic Naan, Lamb Chops
- `#about` "Where Tradition Meets Elegance" — the restaurant's story and cooking approach
- `#visit` "Hours & Location" — the weekly opening hours and the address
- `#faq` "Frequently Asked Questions" — an accordion covering: vegetarian, parking, reservations, large parties
- `#gallery` "Visual Feast" — photographs of the dishes and the room, opened in a lightbox
- `#reviews` "What Our Customers Say" — customer review quotes
- `#floatingCta` — a floating order button that follows the scroll
- `#cursor` — a custom cursor element, present on every page
also: The hero is assembled from five separately identified elements rather than one block, so a change to the hero's wording has to find the right one of heroLabel, heroTitle, heroDesc or heroActions.
also: The marquee phrases are written twice in a row inside marqueeTrack so the strip can scroll seamlessly. Changing one copy and not the other makes the loop visibly jump.

## lunch-specials.html → /lunch-specials
title: Lunch Specials | India Avenue
purpose: The lunch menu — a reduced dish list at lunch prices, served only during the lunch window.
sections:
- "Lunch Specials" — the page hero explaining that these are limited-time lunch prices
- "The Lunch Experience" — what a lunch special comes with and the lunch service hours
- Vegetarian — 7 priced items: Saag Paneer, Chana Masala, Aloo Gobi, Dal Tandoor Pasha, Kadai Veg, Kadai Paneer, Tadka Dal
- Chicken, Lamb and Seafood — 11 priced items: Chicken Tikka Masala, Chicken Chettinad, Chicken Vindaloo, Kadai Chicken, Chicken Curry, Lamb Rogan Josh, Lamb Saag, Lamb Vindaloo, Lamb Tikka Masala, Allepey Fish Curry, Shrimp Kabab Masala
- Kathi Rolls and Indo-Chinese — 7 priced items: Paneer Kathi Roll, Veg Kathi Roll, Chicken Kathi Roll, Lamb Kathi Roll, Gobi Manchurian, Chicken Manchurian, Hakka Noodle
also: This page has no ids on any of its content blocks, so a change here can only be located by its heading text or its dish names.
also: Most lunch dishes appear again on menu.html at dinner prices. Renaming a dish means finding it on both pages.

## menu.html → /menu
title: Menu | India Avenue
purpose: The full menu — every dish, drink and bottle, in twenty-three category blocks.
sections:
- "Our Menu" — the page heading above the category blocks
- `#featured` "Featured Items" — 3 highlighted dishes: Garlic Naan, Chicken Tikka Masala, Naan
- `#soup` "Soup" — 3 priced items: Mulligatawny Soup, Sweet Corn Soup, Rasam Soup
- `#chaat` "Chaat Corner" — 6 priced items: Bhel Puri, Dahi Aloo Puri, Ragada Patties, Samosa, Samosa Chaat
- `#salad` "Salad" — 2 priced items: Sprout Salad, Avocado Salad
- `#appetizer` "Appetizer" — 6 priced items: Onion Bhaji, Hara Bhara Kabab, Tofu Tandoori, Kalmi Kabab, Coriander Chicken, Jhinga Dum Nasha
- `#dosa` "Dosa Stand" — 3 priced items: Masala Dosa, Lamb Keema Dosa, Plain Dosa
- `#indochinese` "Indo-Chinese" — 7 priced items: Gobi Manchurian, Chili Paneer, Chicken Chili, Chicken Manchurian, Hakka Noodle, Garlic Shrimp, Fried Rice
- `#veg` "Vegetarian Entrees" — 18 priced items: Tadka Dal, Dal Tandoor Pasha, Avial, Saag Paneer, Malai Kofta, Mirch Baigan Salan, Shahi Paneer, Baingan Bharta, Kadai Paneer, Aamchur Bhindi, Navaratna Korma, Kadai Veg, Mutter Gobi, Mutter Paneer, Chana Saag, Paneer Tikka Masala, Tofu Saag, Vegetable Tikka Masala
- `#nonveg` "Non Vegetarian Entrees" — 20 priced items: Chicken Tikka Masala, Chicken Chettinad, Chicken Madras, Chicken Vindaloo, Kadai Chicken, Chicken Korma, Butter Chicken, Chicken Saag, Chicken Curry, Lamb Vindaloo, Lamb Pepper Fry, Lamb Saag, Lamb Madras, Lamb Pasanda, Lamb Rogan Josh, Lamb Tikka Masala, Lamb Korma, Shrimp Madras, Shrimp Vindaloo, Allepey Fish Curry
- `#tandoor` "Tandoor (From Clay Oven)" — 10 priced items: Tandoori Salmon, Mixed Grill, Chicken Tandoori, Chicken Tikka, Paneer Tikka, Chicken Malai Kabab, Basil Chicken Tikka, Seekh Kabab, Tandoori Shrimp, Lamb Chops
- `#rice` "Rice" — 4 priced items: Lemon Rice, Coconut Rice, Brown Rice, Basmati Rice
- `#biryani` "Biryani" — 1 priced item: Biryani
- `#breads` "Breads" — 9 priced items: Naan, Garlic Naan, Onion Naan, Chili Naan, Peshawari Naan, Roti, Lachcha Paratha, Mint Paratha, Aloo Paratha
- `#sides` "Sides" — 8 priced items: Cucumber Raita, Mango Chutney, Mixed Pickle, Papad, Tamarind Chutney, Onion & Chilies
- `#kids` "Kid's Menu" — 2 priced items: K- Chicken Nuggets, K- French Fries
- `#beverages` "Beverages" — 25 priced items: Mango Lassi, Sweet Lassi, Salted Lassi, Coke, Diet Coke, Sprite, Ginger Ale, Mango Juice, Lychee Juice, Orange Juice, Perrier, Poland Spring Water, San Pellegrino, Aqua Panna, Club Soda, Shirley Temple, Cranberry, Pineapple, Masala Chai, Madras Coffee, Iced Tea, Lemonade, Black Coffee, Apple Juice
- `#desserts` "Desserts" — 6 priced items: Rasmalai, Gulab Jamun, Gajar Halwa, Kheer, Ice Cream, Kulfi
- `#beer` "Beer" — 6 priced items: Stella Artois, Rupee IPA, Rupee Lager, Kingfisher, Taj Mahal
- `#liquor` "Liquor" — 43 priced pours: Jack Daniel's, Jameson, Dewar's White Label, Chivas Regal 12, Glenlivet 12, Glenfiddich 12, Macallan 12, Macallan 18, Johnnie Walker Red, Johnnie Walker Black, Johnnie Walker Blue, Maker's Mark, Fireball, Wild Turkey, Woodford Reserve, Oban, Bulleit, Jim Beam, Tito's, Grey Goose, Belvedere, Ketel One, Haku, Tanqueray, Bombay Sapphire, Hendrick's, Roku Gin, Bacardi, Captain Morgan, Pirate Rum, Espolon Blanco, Casamigos Blanco, Don Julio, Patron Silver, Hennessy, Remy Martin, Courvoisier, Grand Marnier, Kahlua, Cointreau, Bailey's
- `#sparkling` "Sparkling" — 1 bottle: Lamarca
- `#rose` "Rose" — 1 wine offered by glass and bottle: Fleurs De Prairie Rose
- `#whitewine` "White Wine" — 5 wines by glass or bottle: Conti Beretta Pinot Grigio, Matua Sauvignon Blanc, Dashwood Sauvignon Blanc, Raeburn Chardonnay, Chalk Hill Chardonnay
- `#redwine` "Red Wine" — 4 wines by glass or bottle: Erath Pinot Noir, Louis Martini Cabernet Sauvignon, Gougenheim Malbec, Slow Press Cabernet Sauvignon
- `#cocktails` "Cocktails" — 12 priced drinks: Cooch Behar, The Bengal Tiger, Love Martini, Lychee Martini, Bombay Dream, Cosmopolitan, Margarita, Mojito, Martini, Manhattan, Gin & Tonic, Crockage
also: Dietary markers are appended to the item name itself rather than kept in a separate field, so a dish reads as "Saag Paneer GF" and renaming the dish means preserving the marker.
also: Wines are listed as two separate rows per wine, one for the glass and one for the bottle, so a wine's name is written twice and a rename has to change both.
also: Menu rows repeat the same markup per item, so a change to one row's structure has to be made to every row in that category.

## support files
Files that are not pages. A line marked [content] holds words or data a visitor reads, so a
change to the site's content can land there; the rest only make the site work or look right.
- `robots.txt` — crawler rules and the sitemap link — derived from the site by the deploy, not written by hand
- `sitemap.xml` — the list of page URLs — derived from the site by the deploy, not written by hand
- `assets/kora-voice/voice-client.js` — the voice assistant's connection to the API
- `assets/kora-voice/voice-widget.css` — the voice assistant button and panel styling
- `assets/kora-voice/voice-widget.js` — the voice assistant's on-page behaviour

## shared (every page)
The header, navigation, mobile menu and footer are propagated from index.html to every other page by
`shell_propagation`. A change to any of them is made on index.html alone and copied automatically.
