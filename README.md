# Ex04 Places Around Me
# Date: 27.11.2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
## IMAGE MAPPING CODE
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>image map</title>
</head>
<body>
    <img src="Screenshot 2024-10-20 202016.png" width="1500" alt="map image" usemap="#raganadan street">
    <map name="raganadan street">
        <area shape="rect" coords="424,540,620,698" href="file:///C:/Users/admin/Desktop/saravana%20store/saravanastore.html" target="_blank" title="SARAVANA STORE">
        <area shape="rect" coords="671,566,698,637" href="file:///C:/Users/admin/Desktop/gani/gani.html" target="_blank" title="GANI">
        <area shape="rect" coords="980,536,1416,660" href="file:///C:/Users/admin/Desktop/saravana%20store%20celebrity/saravanacelebrity.html" title="SARAVANA STORE CELEBRITY">
        <area shape="rect" coords="0,462,391,661" href="file:///C:/Users/admin/Desktop/royal%20foot%20wear/rf.html" title="ROYAL FOOT WEAR">
        <area shape="rect" coords="747,613,828,697" href="file:///C:/Users/admin/Desktop/saravana%20store%20selva%20rathinam/saravanaselvaratinam.html" title="SARAVANA STORE SELVA RATHINAM">
    </map>
</body>
</html>
~~~
## CODE FOR SARAVANA STORE IMAGE
~~~
<p>Saravana Stores, founded in 1969, is a chain of retail stores in India. It is the largest family owned business retail chain in India. It is the first store to introduce Aadi Thallupadi sale concept.</p>
<a href="https://www.google.com/search?q=about+saravana+stores&oq=about+sarava&gs_lcrp=EgZjaHJvbWUqBwgAEAAYgAQyBwgAEAAYgAQyBwgBEAAYgAQyBggCEEUYOTIICAMQABgWGB4yDQgEEAAYhgMYgAQYigUyDQgFEAAYhgMYgAQYigUyDQgGEAAYhgMYgAQYigUyDQgHEAAYhgMYgAQYigUyCggIEAAYgAQYogQyCggJEAAYgAQYogTSAQwyMTY3ODE5ajBqMTWoAgiwAgE&sourceid=chrome&ie=UTF-8" target="_blank">more to know click here</a>
~~~
## CODE FOR GANI IMAGE
~~~
<p>"A popular garment shop in T. Nagar, this is a great spot to browse through a wide range of readymade garments. It is a preferred haunt of people to find clothing for any occasion without upsetting the budget. With a vivid collection of clothing available the store encourages you to find apparels that you feel comfortable in."</p>
<a href="https://www.google.com/search?q=about+gani+stores+t+nagar&sca_esv=5a02a879fec8af02&sxsrf=ADLYWILWTbtlqDG91dGcXCtZEJEE5UG4nQ%3A1729438636956&ei=rCMVZ9uNOs-X4-EPtsSEyAo&ved=0ahUKEwjbk_f8pJ2JAxXPyzgGHTYiAakQ4dUDCA8&uact=5&oq=about+gani+stores+t+nagar&gs_lp=Egxnd3Mtd2l6LXNlcnAiGWFib3V0IGdhbmkgc3RvcmVzIHQgbmFnYXIyCBAAGIAEGKIEMggQABiABBiiBDIIEAAYgAQYogQyCBAAGIAEGKIEMggQABiABBiiBEjAJFDnCVjGHXABeAGQAQCYAecDoAHtCKoBBzAuNS40LTG4AQPIAQD4AQGYAgagApUFwgIKEAAYsAMY1gQYR8ICBxAAGIAEGA3CAgoQIRigARjDBBgKmAMAiAYBkAYEkgcDMS41oAfPEQ&sclient=gws-wiz-serp">click here to know more</a>
~~~

## CODE FOR SARAVANA STORE CELEBRITY IMAGE
~~~
<p>Saravana Stores Celebrity Private Limited is a Private company incorporated on 17 July 2020. It is classified as Non-government company and is registered at Registrar of Companies, Chennai. Its authorized share capital is Rs. 1,500,000 and its paid up capital is Rs. 1,500,000. It's NIC code is 521 (which is part of its CIN). As per the NIC code, it is inolved in Non-specialized retail trade in stores.

    Saravana Stores Celebrity's Annual General Meeting (AGM) was last held on N/A and as per records from Ministry of Corporate Affairs (MCA), its balance sheet was last filed on 31 March 2023.
    
    Directors of Saravana Stores Celebrity are . SHANMUGA DURAI and . VANITHA.
    
    Saravana Stores Celebrity's Corporate Identification Number (CIN) is U52100TN2020PTC136465 and its registration number is 136465. Users may contact Saravana Stores Celebrity on its Email address - saravanastoresvessels@gmail.com. Registered address of Saravana Stores Celebrity is No 13, Ranganathan Street, T Nagar , Chennai, Tamil Nadu, India - 600017.
    
    Current status of Saravana Stores Celebrity Private Limited is - Active.</p>
    <a href="https://www.google.com/search?q=saravana+stores+celebrity&oq=saravana+stores+ce&gs_lcrp=EgZjaHJvbWUqCggAEAAY4wIYgAQyCggAEAAY4wIYgAQyEAgBEC4YrwEYxwEYgAQYjgUyBwgCEAAYgAQyBwgDEAAYgAQyBwgEEAAYgAQyBggFEEUYOTIQCAYQLhivARjHARiABBiOBTIMCAcQABgUGIcCGIAEMhAICBAuGK8BGMcBGIAEGI4FMg0ICRAAGIYDGIAEGIoF0gEKMTY2NzFqMGoxNagCCLACAQ&sourceid=chrome&ie=UTF-8">to know about more click here</a>
~~~
## CODE FOR ROYAL FOOT WEAR IMAGE
~~~
<p>... PREMIUM CAPS AVAILABLE FOR ORDER CONTACT ON 6379998284 ADD-498 MTH ROAD VARADHARAJAPURAM AMBATTUR CHENNAI-600053 #caps #trending #trend #instagood #tamil ...
    https://www.justdial.com › Chennai
    Royal Shoes in Kodambakkam,Chennai - Justdial
    Established in the year 1990, Royal Shoes in Kodambakkam, Chennai is a top player in the category Shoe Dealers in the Chennai. This well-known establishment ...
</p>
<a href="https://www.google.com/search?q=royal+foot+wear+ranganathan+street&sca_esv=5a02a879fec8af02&sxsrf=ADLYWIJytR0uL6KQEWFPFZ84t2uJE4Vjsg%3A1729439057377&ei=USUVZ47dFv674-EP7JOKuAM&oq=royal+foot+wear+rangana&gs_lp=Egxnd3Mtd2l6LXNlcnAiF3JveWFsIGZvb3Qgd2VhciByYW5nYW5hKgIIADIHECEYoAEYCjIHECEYoAEYCjIHECEYoAEYCjIHECEYoAEYCjIHECEYoAEYCjIEECEYFUj6qAFQgQNYlJ0BcAR4AJABBJgBqgGgAZ4pqgEEMS40M7gBAcgBAPgBAZgCHqACvRqoAhTCAgoQABiwAxjWBBhHwgIWEC4YgAQYsAMYQxjHARiKBRiOBRivAcICChAjGIAEGCcYigXCAhMQLhiABBhDGMcBGIoFGI4FGK8BwgIOEC4YgAQYxwEYjgUYrwHCAgUQABiABMICChAAGIAEGBQYhwLCAgsQABiABBiGAxiKBcICIhAuGIAEGEMYxwEYigUYjgUYrwEYlwUY3AQY3gQY4ATYAQHCAgcQIxgnGOoCwgIHEC4YJxjqAsICFhAAGAMYtAIY5QIY6gIYjAMYjwHYAQHCAhQQABiABBjjBBi0AhjpBBjqAtgBAcICCxAAGIAEGJECGIoFwgIFEC4YgATCAg4QLhiABBixAxjRAxjHAcICFxAuGIAEGLEDGIMBGMcBGIoFGI4FGK8BwgIOEC4YgAQYsQMYgwEYigXCAgsQABiABBixAxiDAcICCxAuGIAEGLEDGIMBwgIIEAAYgAQYsQPCAhAQLhiABBjRAxhDGMcBGIoFwgIKEAAYgAQYQxiKBcICFBAuGIAEGLEDGIMBGMcBGIoFGK8BwgIIEC4YgAQYsQPCAgsQLhiABBiRAhiKBcICGhAuGIAEGJECGIoFGJcFGNwEGN4EGOAE2AEBwgIfEC4YgAQY0QMYQxjHARiKBRiXBRjcBBjeBBjgBNgBAcICDhAAGIAEGLEDGIMBGIoFwgILEAAYgAQYsQMYyQPCAgsQABiABBixAxiKBcICCxAuGIAEGMcBGK8BwgIHEAAYgAQYCsICERAuGIAEGMcBGJgFGJkFGK8BwgIHEAAYgAQYDcICHRAuGIAEGMcBGI4FGK8BGJcFGNwEGN4EGOAE2AEBwgINEC4YgAQYxwEYDRivAcICAhAmwgIIEAAYgAQYogTCAhwQLhiABBjHARgNGK8BGJcFGNwEGN4EGOAE2AEBmAMFiAYBkAYJugYGCAEQARgUkgcENC4yNqAHtuUE&sclient=gws-wiz-serp">to know more click here</a>
~~~
## CODE FOR SARAVANA STORE SELVA RATHINAM IMAGE
~~~
<p>Saravana Stores, founded in 1969, is a chain of retail stores in India. It is the largest family owned business retail chain in India.[3][4] It is the first store to introduce Aadi Thallupadi sale concept.

    Locations
    Saravana Stores operates seven stores in Chennai, at T. Nagar, Purasawalkam, Porur, Padi, Sholinganallur, Pallavaram and Usman Road. The company has mega stores in Madurai, Tirunelveli and Coimbatore. The company is growing rapidly and has plans to open stores in Mumbai, New Delhi, and Bengaluru. The company also operates the Saravana Selvarathinam Stores in Tirunelveli and Madurai.
    
    Revenue
    In 2023, the company reported an annual turnover of about ₹ 2495 crore (300 million US dollars).[5][6][7]
    
    Foray into 100% milk based ice cream
    In 2004, Saravana Groups launched a new ice cream brand named Jamaai, a 100% milk based ice-cream brand. The factory is located at Padappai, a suburb of Chennai en route Sriperumbudur and sold across Tamil Nadu. It has a capacity of 10,000-litres per day ice cream production and expected to expand to 30,000 litres per day.[5]
    
    
    Super Saravana Store automated car parking
    Fire incident
    On 2 September 2008, a fire inside the building led to the death of two of its employees and damages worth crores of rupees. Unauthorized construction and ignoring safety measures are believed to be the reason.[8][9][10]
    
    Super Saravana Stores: On March 1,2023 around 4.30 p.m. the flames were noticed in the Food Court on 9floor. The staff and the customers from all the floors were evacuated. No one was injured in the accident. Property worth 37 crore has been damaged in the major fire that broke out on Melur Main Road in Madurai city.[11]
    
    References
     "'We will all be slaves to MNCs,' says Saravana Stores founder". Archived from the original on 19 February 2023. Retrieved 19 February 2023.
     "Saravana Stores allegedly rigged accounting software to show less income". 7 February 2019. Archived from the original on 19 February 2023. Retrieved 19 February 2023.
     "'We will all be slaves to MNCs,' says Saravana Stores founder". Rediff. Archived from the original on 19 February 2023. Retrieved 19 February 2023.
     Hiscock, Geoff (30 November 2012). "India's Store Wars: Retail Revolution and the Battle for the Next 500 Million Shoppers". John Wiley & Sons. Archived from the original on 15 September 2023. Retrieved 16 March 2023 – via Google Books.
     "Saravana Stores steps into the ice-cream parlour where". The Hindu Businessline. 17 August 2004. Archived from the original on 25 April 2009. Retrieved 31 March 2009.
     "Momentum Strategy Consultants: A Low Price for Success, Unsung Heroes of Indian Retailing". www.dharenchadha.com. Archived from the original on 21 October 2013. Retrieved 24 May 2013.
     ""Total Turnover"". Archived from the original on 25 October 2013. Retrieved 24 May 2013.
     "Blaze exposes fire hazards in T Nagar". Times of India. 2 September 2008. Archived from the original on 20 December 2016. Retrieved 31 March 2009.
     "Demolition of unsafe Saravana Stores floors begins it was also sealed". The Hindu. 20 November 2008. Archived from the original on 28 July 2009.
     "Saravana fire and the Tamil apathy". Chennai Television. 5 September 2008. Archived from the original on 22 February 2012. Retrieved 31 March 2009.
     "Fire breaks out at Super Saravana Stores, Madurai – Tamil Nadu Fire & Rescue Services". Archived from the original on 23 December 2023. Retrieved 23 December 2023.</p>
     <a href="https://www.google.com/search?q=saravana+store+selvarathinam&oq=saravana+store+se&gs_lcrp=EgZjaHJvbWUqBwgAEAAYgAQyBwgAEAAYgAQyBggBEEUYOTIICAIQABgWGB4yCAgDEAAYFhgeMggIBBAAGBYYHjIICAUQABgWGB4yCAgGEAAYFhgeMggIBxAAGBYYHjIICAgQABgWGB4yCAgJEAAYFhge0gEKMjA5NjBqMGoxNagCCLACAQ&sourceid=chrome&ie=UTF-8">click here to know more</a>
~~~
# OUTPUT
## IMAGE MAP IMAGE
![Screenshot 2024-11-27 000413](https://github.com/user-attachments/assets/c5c01522-7a32-42f1-a13c-0e9dfa61e071)
## SARAVANA STORE IMAGE
![Screenshot 2024-11-27 000726](https://github.com/user-attachments/assets/bb64f6e7-249e-48bd-bcf9-4a65e95a949b)
## GANI
![Screenshot 2024-11-27 000524](https://github.com/user-attachments/assets/8a32ce97-7b17-41e2-a497-a74d52d57f76)
## SARAVANA STORE CELEBRITY
![Screenshot 2024-11-27 000544](https://github.com/user-attachments/assets/d2b9f91b-cf37-417b-b850-bdd35e210e2e)
## ROYAL FOOT WEAR
![Screenshot 2024-11-27 000603](https://github.com/user-attachments/assets/23ef051d-834f-47c2-b879-cc19e246635f)
## SARAVANA STORE SELVA RATHINAM
![Screenshot 2024-11-27 000618](https://github.com/user-attachments/assets/b8091abb-fc99-42f8-814e-4f3b89dc1e98)

# RESULT
The program for implementing image maps using HTML is executed successfully.
