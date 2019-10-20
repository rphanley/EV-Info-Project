# EV-Info-Project (Electric Cars Explained)

This project was produced by a fictional "EV Info" organisation to promote the adoption of electric cars in Ireland ("EV" being electric vehicle). It aims to provide basic information for anyone thinking of buying an electric car in Ireland. There is a lot of jargon involved in buying and running an electric car,
and the website aims to help demystify the terms used. There are also some myths around electric cars in regard to usefulness and range, which the site provides some clarity on. 
The site explains what electric cars are, and what the current environment looks like for electric cars worldwide and in Ireland. It describes the various methods of charging an electric car, with particular focus on the infrastructure in Ireland. The site provides a concise overview for anyone considering buying an electric car. The lowest priced models currently available in Ireland are listed. If the user is concerned more with the distance range of the car, they can view the cars having the top range in kilometres also. 

 
## UX

I created this project partly because I drive an electric car, and have a keen interest in them and sustainability generally. From my experience driving an electric car for almost 5 years, I felt there was a need for a resource that gives people a quick and digestible introduction to them. There is a lot of misconceptions from the general public around electric cars. While some fears would have been valid 5 years ago, they are largely resolved now. 

The target user of the site is someone who is considering moving to an electric car in the near future. They know little about them, but are curious to find out more. The site is aimed at the following user stories: 

1) I am generally curious about electric cars, but don't know anything about them. I want to get a quick overview of what they are. With that information, I can compare them to regular petrol/diesel cars. I can make an assessment of their suitability to my particular driving patterns and needs.
The site gives an overview of what an electric car is compared to a fuel car, and the recent history and environment around them.

2) I already know a little about electric cars, and am looking for more information on running them, especially the charging options. With that information, I can decide what my options would be to suit my charging needs.
The site describes the options for charging an electric car at home or on the road. The various connectors used for charging are described. It gives the approximate times needed for each type of charging, and how to access public chargers.

3) I am interested in buying an electric car, but cost is the major concern. I need basic information on what options are available on a limited budget.
The site lists the 10 lowest price electric cars currently available in Ireland, inclusive of government grants.

4) I am interested in buying an electric car, and my main concern is the range, since I drive long distances regularly. I need basic information on the best options available. The site lists the 10 highest range electric cars available in Ireland, with prices again inclusive of government grants.

5) I want to continue learning more about electric cars, and connect with EV-related social media to keep up to date.
The site has links to social media, e.g the Facebook page for the Irish EV Owners Association, and a download link for a glossary of electric car related terms.


My wireframe sketches were uploaded to the "wireframes" folder under the EV-Info-Project. My initial sketch is included (first_wireframe.jpg). More detailed sketches are shown for each page in Home_Start.jpg and Price_Range_Charging.jpg files.


 


## Features

The site consists of a landing/home page to draw in the user with a picture of an electric car and questioning if they "want to make the switch?". The user can respond directly by clicking the "power switch" icon to move to the Start page. The user can return to the home page by clicking the logo in the top left corner of each page. 
There are navigation links on the top right of each page to bring up the relevant information the user is looking for. A footer at the bottom of each page shows "About" information and links for social media, email feedback and a download link for a EV glossary document. 
 
### Existing Features
- The landing page invites users to "make the switch" and find out more by clicking the power switch icon. This links to the Start page, which can also be reached from the menu on the top right of each page.

- The menu also links to the Price, Range and Charging pages:

- The Price page displays a table listing the 10 lowest priced electric cars in Ireland, in ascending price order. The real-life range of each car in kilometres is also shown. Links are provided to the external Irish websites of each car manufacturer, which open in a new tab so that the user can get further information on the particular model.

- The Range page displays a table showing the 10 highest range electric cars currently available in Ireland. They are listed in descending range order (kilometres).

- The Charging page describes the different options for charging electric cars: slow/AC and fast or rapid DC. the difference between AC and DC chargers is discussed. The limitations of AC charging at home or away is explained, and the expected time taken to charge at slow and fast chargers. A diagram shows the different types of connector used to charge electric cars. Access to the public charging network is explained.

- A footer section on each page shows About text with copyright information and the aim of the website. Icons on the bottom left link to social media (LinkedIn and Facebook), and an email feedback option. A download link allows the user to get a printable .pdf file with a glossary of electric car related terms.

- On each page, the user can click the electric car logo/icon on the top left of the page to return to the home page.

- Screen reader only tags have been included in the HTML to provide brief descriptions of the icons used.

### Features Left to Implement

- A future version of the website could incorporate a form allowing the user to enter their preferred criteria, such as budget, required range, car size etc, and return a list of any suitable cars.

- To further assist the user, a future version could also bring up a map displaying the public charging options in their immediate area. This would help them in the car selection process by showing if there were any restrictions, for example on the type of connectors available.

## Technologies Used

- This project uses HTML for basic layout and text, and CSS for styling the content.

- [Bootstrap](https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css)
    - This project uses **Bootstrap** to ease development by use of the Bootstrap grid system and design templates. It provides responsive CSS to adjust to 
      different screen sizes in phones, tablet and desktop devices. The Bootstrap Navbar feature is used to provide the menu and logo at the top of each            page. The menu collapses into a "burger icon" for use on smaller/mobile devices.

- This project also uses the 3 JavaScript files recommended for use with Bootstrap e.g for the collapsing menu feature of Navbar:

- [Bootstrap](https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js)

- [JQuery](https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js)

- [Popper](https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js)



- [FontAwesome](https://use.fontawesome.com/releases/v5.1.1/css/all.css)
   This project uses FontAwesome icons for clickable links: the power button icon on the home page, and the footer links for social media, email and             download options.


## Testing

The website was tested with the following devices and scenarios:

- Asus F553M laptop with Google Chrome,Microsoft Edge and Opera browsers
- Asus F553M laptop with Google Chrome developer tools used to view various mobile (phone and tablet) device screen sizes
- Motorola Moto G4 Android smartphone with Google Chrome
- Samsung Galaxy Tab 2 Android tablet with FlashFox browser

Testing showed the following results:

- Basic functions performed well. All page links and clickable icons operated correctly. Navigation between one page and all others worked. 
- Colour transitions performed well where used on clickable icons.
- It was never necessary to use the "back" or "forward" options on the browser to navigate around the site.
- The page information was visible on all phone views in dev tools, and on the Motorola phone, in both portrait and landscape views. However,
  the iPhone 5/SE view revealed the drop down menu on the right encroaching on the body of the page ("Charging" option).
- On wider screens (full screen view on Chrome and Edge, and the iPad Pro in landscape view), there was an issue with the "banner" picture of the blue car
  not covering the full width of the top of the window. This did not affect the main content, but put the Home electric car icon and Charging options in a      different background to the others.
- The iPadPro portrait view in dev tools showed a lot of empty space at the bottom of the pages. This could probably be resolved with media rules to space      out the content, increase the font size etc.



## Deployment

Originally I had named the project "User centric frontend development milestone project". But in the interests of making the site more user friendly, and on the recommendation of my mentor, I renamed it to "EV-Info-Project". 
The project was deployed on GitHub Pages. To do this, I clicked on the "Settings" tab of the EV-Info-Project repository in GitHub. Then I scrolled down to the GitHub Pages section. From the Source drop-down menu I selected "master branch" to deploy the website from the latest master code. GitHub then published the website at: [EV-Info-Project](https://rphanley.github.io/EV-Info-Project/)


## Credits

### Content
- The clickable icons featured in this website had their icons sourced from [Font Awesome](https://fontawesome.com).

- The new car pricing and range information contained in this website is courtesy of the [Irish EV Owners Association]https://www.irishevowners.ie). A link to their Facebook page is included also.

- The "Zap-Map" EV rapid charger guide diagram is copyright of [Next Green Car Ltd](https://www.zap-map.com).

### Media
- The photos used in this site were obtained from Nissan Motor Corporation and Tesla, Inc.

### Acknowledgements

- I want to acknowledge the help and guidance of my Code Institute tutor Xavier, and mentor Ignatius, in developing this project.