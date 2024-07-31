---
layout: "ssg-theme-astro/layouts/main.astro"
tag: ""
title: "Spices 3 辣妹子 - Best Food Today"
favicon: "logo.svg"
logo: "logo.svg"
primaryColor: "#DF733C" # logo color
secondaryColor: "#3E617D"
primaryColorScheme: "dark" # dark | light
secondaryColorScheme: "dark"
dataGlfCuid: "8dc58126-94b0-4fe9-8a4e-f5c9545c6c67"
dataGlfRuid: "1b46614b-2a6b-4463-8fff-68ba208a3c79"
orderOnlineLink: ""
tableReservationLink: ""
tel: ""

# banner:
#   text: 
#     - boldText: "🥳 Special Offer"
#     - text: "Lorem ipsum dolor sit amet:"
#     - smText: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
#     - text: " Lorem ipsum dolor sit amet,:"
#   # add more text...
#   textColor: "#ffffff"
#   bgColor: "#FF2D2F"
#   bgOpacity: "1" # 0~1

# header
header:
  logoSize: 40
  textAfterLogo: 
    text: "Spices 3 辣妹子 - Best Food Today"
    size: 20
    color: "#ffffff"
  bgColor: "#000000"
  bgOpacity: "0.5" # 0~1
  menuTextColor: "#ffffff"
  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "#about-us" }
    - { text: "Contact Us", link: "#contact-us" }
    - { text: "中文", link: "/zh-cn" }
  addOrderOnlineBtn: true
  orderOnlineBtnInsteadText: "See MENU & Order"
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: false
  telTextColor: "#ffffff"
  addOtherBtn: false
  otherBtnInsteadText: "See MENU & Order"
  otherBtnHref: ""

sections:
# hero
  - type: "hero" 
    id: ""
    height: "80" # Conditionally use only when sectionType is imgBg
    sectionType: "imgBg" # video | imgWithText | imgBg
    bgVideoType: "" # youtube | vimeo | gjw
    bgVideoId: ""
    bgImg: "Spices 3 辣妹子 - Best Food Today.webp"
    bgImgAlt: "Spices 3 辣妹子 - Best Food Today"
    bgColor: "#000"
    bgOpacity: "0.5" # 0~1
    title: 
      - "Spices 3 辣妹子 - Best Food Today"
    titleColor: "#ffffff"
    description: 
      - "The Most Popular Cuisine In Oakland"
    descriptionColor: "#ffffff"

    addOrderOnlineBtn: true
    orderOnlineBtnInsteadText: "See MENU & Order"
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""
    showOtherBtn: false
    btn1Text: "See MENU & Order" # default: order online
    btn1Href: "" # default: order online
    btn2Text: "" # default: table reservation
    btn2Href: "" # default: table reservation

    bannerImg: ""
    imgAlt: ""
    imgPosition: "" # imgLeft | imgRight
    bannerMarginTopMobile: 96
    imgRounded: "" # sm | md | lg | xl | 2xl | 3xl | full
   
    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    bottomInfo: "We offer Takeout"

# # Video
#   - type: "video"
#     id: ""
#     title: 
#       - "Lorem ipsum dolor sit amet"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua." 
#     videoType: "vimeo" # vimeo | gjw | youtube
#     videoId: 
#       - "738770507"
#       - "738770507"
#     isOnlyDisplayOnMobile: false

# Gallery  - Food At Spices 3
  - type: "gallery"
    id: "gallery"
    mode: 3 # 1 - 3
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Food At Spices 3"
    titleColor: "#000000"
    description: 
      - "Sichuan food is most well-known for its hot and spicy flavor"
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: true # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full


# # textBlock 
#   - type: "textBlock" 
#     id: "about-us"
#     bgImg: ""
#     bgImgAlt: ""
#     bgColor: "#000"
#     bgOpacity: "" # 0~1
    # title: 
    #   - "A Corner of Tradition and Flavor"
    # titleColor: "#000000"
    # description: 
    #   - "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor. Every corner of our restaurant is infused with authenticity, from the décor to every bite we serve."
    #   # - text: "We serve Imperial Soup dishes plus other Asian dishes. Feel free to message us about inquiries! We'll get back to you as soon as we can!"
    # descriptionColor: "#000000"

# # textBlock - only title
#   - type: "textBlock" 
#     id: "about-us"
#     bgImg: ""
#     bgImgAlt: ""
#     bgColor: ""
#     bgOpacity: "" # 0~1
#     title: 
#       - "About Us"
#     titleColor: "#000000"
#     description: 
#       - "Lorem ipsum dolor sit amet"
#     descriptionColor: ""

# # feature - 2
#   - type: "feature" 
#     id: ""
#     height: "100" # Conditionally use only when sectionType is imgBg
#     noMarginTop: true
#     sectionType: "imgWithText" # video | imgWithText | imgBg
#     bgVideoType: "" # youtube | vimeo | gjw
#     bgVideoId: ""
#     bgImg: ""
#     bgImgAlt: ""
#     bgColor: ""
#     bgOpacity: "" # 0~1
#     title: 
#       - "Our Mission"
#     titleColor: "#000000"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
#     descriptionColor: "#000000"
#     # title2: 
#     #   - "A Corner of Tradition and Flavor"
#     # title2Color: "#000000"
#     # description2: 
#     #   - "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor. Every corner of our restaurant is infused with authenticity, from the décor to every bite we serve."
#     #   # - text: "We serve Imperial Soup dishes plus other Asian dishes. Feel free to message us about inquiries! We'll get back to you as soon as we can!"
#     # description2Color: "#000000"
#     # title2: 
#     #   - "Committed to the Community"
#     # title2Color: "#000000"
#     # description2: 
#     #   - "We are proud to be an active part of the Newark, CA community. Through special events, collaborations with local venues and participation in community initiatives, Crabby Crabby Restaurant seeks to strengthen the ties that bind us together."
#     # description2Color: "#000000"
#     isTextAlignCenter: false

#     addOrderOnlineBtn: false
#     orderOnlineBtnInsteadText: "See MENU & Order"
#     addTableReservationBtn: false
#     tableReservationBtnInsteadText: ""
#     showOtherBtn: false
#     btn1Text: "See MENU & Order" # default: order online
#     btn1Href: "#" # default: order online
#     btn2Text: "" # default: table reservation
#     btn2Href: "" # default: table reservation

#     bannerImg: "sample.webp"
#     imgAlt: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
#     imgPosition: "imgLeft" # imgLeft | imgRight
   
#     bottomRounded: "" # sm | md | lg | xl | 2xl | 3xl | full


# # feature - 3
#   - type: "feature" 
#     noMarginTop: true
#     id: ""
#     height: "100" # Conditionally use only when sectionType is imgBg
#     sectionType: "imgWithText" # video | imgWithText | imgBg
#     bgVideoType: "" # youtube | vimeo | gjw
#     bgVideoId: ""
#     bgImg: ""
#     bgImgAlt: ""
#     bgColor: ""
#     bgOpacity: "" # 0~1
#     title: 
#       - "Committed to the Community"
#     titleColor: "#000000"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
#     descriptionColor: "#000000"

#     addOrderOnlineBtn: false
#     orderOnlineBtnInsteadText: "See MENU & Order"
#     addTableReservationBtn: false
#     tableReservationBtnInsteadText: ""
#     showOtherBtn: false
#     btn1Text: "See MENU & Order" # default: order online
#     btn1Href: "#" # default: order online
#     btn2Text: "" # default: table reservation
#     btn2Href: "" # default: table reservation

#     bannerImg: "sample.webp"
#     imgAlt: "Lorem ipsum dolor sit amet"
#     imgPosition: "imgRight" # imgLeft | imgRight
   
#     bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

# textBlock 
  - type: "textBlock" 
    id: "about-us"
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "About Us"
    titleColor: "#000000"
    description: 
      - "Sichuan food is famous in China and abroad, If you want the most authentic Sichuan cuisine, the most authentic Sichuan food is still to be found at Spices 3 except Chengdu and Chongqing."
      - "The owner and all staff in Spices 3 will greet you with the warmest welcome, whether you are a habitual patron or come for the first time. We have made painstaking efforts to create the tidiest and cleanest dining place, and guarantee you with friendly and timely service. All of your demands and feelings will be cared in our restaurant."
    descriptionColor: "#000000"
# # feature - Map + Text section
#   - type: "feature" 
#     id: "contact-us"
#     noMarginTop: false
#     height: "100" # Conditionally use only when sectionType is imgBg
#     sectionType: "imgWithText" # video | imgWithText | imgBg
#     bgVideoType: "" # youtube | vimeo | gjw
#     bgVideoId: ""
#     bgImg: ""
#     bgImgAlt: ""
#     bgColor: ""
#     bgOpacity: "" # 0~1
#     title: 
#       - "Store 1: Kearny St"
#     titleColor: "#000000"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur"
#     descriptionColor: "#000000"
#     # title2: 
#     #   - "A Corner of Tradition and Flavor"
#     # title2Color: "#000000"
#     # description2: 
#     #   - "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor. Every corner of our restaurant is infused with authenticity, from the décor to every bite we serve."
#     #   # - text: "We serve Imperial Soup dishes plus other Asian dishes. Feel free to message us about inquiries! We'll get back to you as soon as we can!"
#     # description2Color: "#000000"
#     # title2: 
#     #   - "Committed to the Community"
#     # title2Color: "#000000"
#     # description2: 
#     #   - "We are proud to be an active part of the Newark, CA community. Through special events, collaborations with local venues and participation in community initiatives, Crabby Crabby Restaurant seeks to strengthen the ties that bind us together."
#     # description2Color: "#000000"
#     isTextAlignCenter: false

#     addOrderOnlineBtn: false
#     orderOnlineBtnInsteadText: "See MENU & Order"
#     addTableReservationBtn: false
#     tableReservationBtnInsteadText: ""
#     showOtherBtn: true
#     btn1Text: "Order online from Kearny St store" 
#     btn1Href: "#" 
#     btn2Text: "" 
#     btn2Href: "" 

#     bannerImg: ""
#     imgAlt: ""
#     imgPosition: "" # imgLeft | imgRight
    
#     map: true
#     url: "https://maps.app.goo.gl/nZ57LDJrofANer8J6"
#     iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d394.10234978168285!2d-122.4046165!3d37.7942861!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085808b1948e55b%3A0xcb3994bcd586810e!2sHon&#39;s%20Wun-Tun%20House!5e0!3m2!1sen!2sus!4v1722231832722!5m2!1sen!2sus"
#     addTelBtn: true
#     tel: "000000000"
#     telInsteadText: "Call: (000) 000-0000"
#     getDirectionBtnInsteadText: ""
    
    
#     bottomRounded: "" # sm | md | lg | xl | 2xl | 3xl | full (only for background)

# Gallery  - Welcome to Spices 3
  - type: "gallery"
    id: "gallery2"
    mode: 1 # 1 - 3
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Welcome To Spices 3 辣妹子"
    titleColor: "#000000"
    description: 
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery2"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full


# textBlock - Information
  - type: "textBlock" 
    noMarginTop: false
    id: ""
    bgImg: "Spices 3 辣妹子 - Best Food Today.webp"
    bgImgAlt: "Spices 3 辣妹子 - Best Food Today"
    bgColor: "#000"
    bgOpacity: "1" # 0~1
    title: 
      - "NEW! Online Ordering"
    titleColor: "#ffffff"
    description: 
      - "Online ordering NOW enabled for pick-up. Just tell us what you want and we'll prepare it as fast as we can. All orders are manually confirmed by us directly. Find out in real-time when your food is ready. All orders are manually confirmed by us in real-time. Watch on-screen when your food is ready for pickup."
    descriptionColor: "#ffffff"
  
# map  
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/GUkagbrN349JRRRs6"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d197.02968122305626!2d-122.270047!3d37.802344!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808f80b43ce2a90d%3A0x95429d5e7dd07c29!2zU3BpY2VzIDMg6L6j5aa55a2Q!5e0!3m2!1sen!2sus!4v1722409573339!5m2!1sen!2sus"
    addTelBtn: false
    getDirectionBtnInsteadText: ""
    telInsteadText: ""
 
#  # The modal will only appear once within 30 minutes."
#   - type: "modal" 
#     bgColor: "#333"
#     bgOpacity: "0.1" # 0~1
#     title: 
#       - "🥳 Special Offers"
#     titleColor: "#FF2D2F"
#     titleSize: 24
#     description: ""
#     descriptionColor: ""
#     descriptionSize: 16
#     imgName: "offer.png"
#     imgAlt: "🥳 [Special Offer 15 PC of Head On Shrimp + 1 Free Soda + Choose a Free Item: Steam Rice (10 oz cup) / Garlic Noodles (10 oz cup) / Cajun Fries (10 oz cup) only $13.50. Available Monday to Friday, 12 PM to 3 PM.](https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3171.4491088990403!2d-121.96119332425478!3d37.355548872094!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808fc90f1eb1cd07%3A0x2bd1578adf6247c1!2sNTD%20Digital!5e0!3m2!1sen!2sjp!4v1722389965147!5m2!1sen!2sjp)"
#     buttonText: "Order Now!"

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: ""
  bgImgAlt: ""
  bgColor: "#000000"
  bgOpacity: "0.9" # 0~1
  openingHours: 
    - "Saturday - Sunday: 11:30 AM - 09:40 PM"
    - "Monday - Friday: 10:30 AM - 09:40 PM"
  
  isLogo: false
  logoSize: 100

  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "/#about-us" }
    - { text: "Contact Us", link: "/#contact-us" }
    - { text: "中文", link: "/zh-cn" }

  FB: false
  FBLink: ""
  IG: false
  IGLink: ""
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: false
  yelpLink: ""

  paymentMethod: "cash,visa,amex,mastercard" #alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal

  # optional
  seo:
    metaDescription: "Order Online for Takeout / Pickup. Here at Spices 3 辣妹子 - Best Food Today - Oakland you'll experience delicious Chinese, Asian cuisine. Try our mouth-watering dishes, carefully prepared with fresh ingredients!"
    keywords: "spices 3,Asian cuisine"
    img: "Spices 3 辣妹子 - Best Food Today.webp"
    thisPageUrl: "https://www.spices3-oakland.com"
    locale: "en_US" # zh_TW | zh_CN
---
<!-- hello world -->