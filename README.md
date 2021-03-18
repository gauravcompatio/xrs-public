# xrs-public

1. The xrs-recommendations.liquid is the liquid snippet code and required jquery javascript code to handle the configuration part of XRS
2. The liquid code has some fields it gets from the shop level metafields such as - shop.metafields["global"]["XRSExtension"] - One needs to make sure that all such fields exists in order to see XRS working. The metafields are either automatically generated while custom/public app installation or created manually.
3. It can be changed or enhanced based on needs of the shopify store's theme or any other requirements
4. The backing data provided as a default case considering the specific product type ( Reels, in Fishing industry in this case) and also the values are specific to a demo store and may not be applicable, in which case you can keep the backing as []
5. The text file includes the posisble changes you require for the theme javascript to handle the cart drawer and the variant change 
6. If the theme does not have a cart drawer then that step wo'nt be needed
7. If _OnSelectChange method is not found, similar method will be there which handles the variant change for the theme
