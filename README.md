# amazon_reviews

## PRODUCT DETAILS JSON

{"Title": "OnePlus 6T (Midnight Black, 8GB RAM, 128GB Storage)",
"price": {"Deal Price": "37999"}, 
"image": 
      {"url": "https://images-eu.ssl-images-amazon.com/images/I/41VkqnrF85L._SY300_QL70_.jpg"}, 
  "reviews": 
      {"number_of_reviews": "14,761 customer reviews", 
      "avg_customer_review": "4.5 out of 5 stars"}, 
 "product_description": 
      {"Size name": "Size name", "Colour": "Colour"},
      "technical_details":
          {" OS ": "Android",
          " RAM ": "8 GB",
          "Item Weight": "186 g", 
          "Product Dimensions": "15.8 x 0.8 x 7.5 cm", 
          "Batteries:": "1 Lithium Polymer batteries required. (included)", 
          "Item model number": "A6010", 
          " Wireless communication technologies ": "Bluetooth;WiFi Hotspot", 
          " Connectivity technologies ": "2G;3G;GPS;GLONASS;Galileo;BeiDou;USB 2.0;OTG;WiFi 802.11 a/b/g/n/ac", 
          " Special features ": "SIM;GPS;Music Player;Video Player;E-mail", 
          " Other camera features ": "16MP (Front camera)", 
          " Form factor": "Touchscreen Phone", 
          " Weight ": "186 Grams", 
          " Colour ": "Midnight Black", 
          " Battery Power Rating ": "3700", 
          " Whats in the box ": 
                "Handset,\u00a0Screen Protector (pre-applied), Translucent Case, OnePlus Fast Charge Type-C Cable, OnePlus Fast Charge Power Adapter, SIM Tray Ejector, Quick Start Guide,\u00a0Safety Information and Type-C to 3.5mm Audio\u00a0Jack Adapter"}}
 
 
 ## REVIEWS JSON SAMPLE
 {"customer_profile": 
      {"profile_url": "https://www.amazon.in/gp/profile/amzn1.account.AH7IEBWSWSMS4GAJI5FC6FDY5FMQ", 
        "customer_name": "Angad Singh"}, 
 "review_rating": 5.0, 
 "review_title": "Feels like 10K overpriced still good  ",
 "review_date": "15 April 2019", 
 "review_text": "Former iPhone 6s userUi ugly but way fastBattery life omg wowStill camera niceVideo camera mehFinger print very slow. "}



## SENTIMENT ANALYSIS:
I HAVE USED VADER FROM NLTK (python standard lib) for sentiment analysis, to classify as positive, negative , neutral reviews.
