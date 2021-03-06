# bootstrap_COURSERA

## viewport

**npm init -y**

**npm install lite-server --save**

**npm install bootstrap jquery popper.js --save**

*All the development dependencies will be stored in package.json -->*

***"start": "npm run lite"***

***""lite": "lite-server"***

*code index.html --> The **viewport** meta tag ensures that the screen width is set to the device width and the content is rendered with this width in mind.*

**npm start**

*lite-server is a lightweight development web server with support for ***Single Page Apps (SPAs)*** *, serves a web app, opens it in the browser, refreshes when html or javascript change, injects CSS changes using sockets, and has a fallback page when a route is not found.*

## grid_system

*The viewport meta tag ensures that the screen width is set to the device width and the content is rendered with this width in mind. This brings us to the second issue, designing the websites to be responsive to the size of the viewport. This is where the Bootstrap grid system comes to our aid. Bootstrap makes available four sizes, xs for extra small, sm for small, md for medium and lg for large screen sizes. We would like our website to have the content stacked on extra small devices, but become horizontal within each row for smaller devices and beyond. Towards this goal, we will make use of the classes .col-*, .col-sm-*, col-md-*, and .col-lg-* for defining the layouts for the various device sizes. We can specify how many columns each piece of content will occupy within a row, all adding up to 12 or a multiple thereof.*

**offset-1** *This shift one column away*

**order-sm-last && order-sm-first** *It orders the elements in container*

**list-unstyled** *This removes the bullets from bulleted list in ul tag*

**align-items-center** *It vertically centers the content*

**justify-content-center** *It horizintally centers the content*

**text-center** *It centers the text*

**align-self-center** It centers the whole content*

**custom css classes** *-added styles.css under css folder-->some code*

## navbar_breadcrumbs_iconFont

###### navbar_breadcrumbs

**navbar** *It adds the navbar to the screen*

**navbar-nav** *specify that the items should be displayed inline inside the navigation bar*

**navbar-dark** *Id adds the dark color to navbar*

**navbar-expand-sm** *It's for small and extra-small screens*

**bg-primary** *primary background color-blue*

**fixed-top** *It fits the navigation bar to the top*

**navbar-brand** *in navigation bar, there is a brand name or a company name*

**mr-auto** *margin from right*

**active** *link will be active*

**navbar-toggler** *toggle button for small and extra-small screens*

**data-toggle="collapse"** *js component used to collapse the navbar when seen in small and extra small screens*

**data-target="#Navbar"** *This here is the id for the button so that it can be targeted when needs to change with css or other styling and also it can be used to target other                      elements*

**navbar-toggler-icon** *icon for navbar toggler*

**breadcrumb** *To know the hierarchy of steps to move through a website*

**breadcrumb-item** *elements of a page*

###### iconFont

**npm install font-awesome bootstrap-social --save**

*font awesome and bootstrap-social modules included in index.html and aboutus.html*

**fa** *this is font-awesome class*

**fa-home** *this is font icon for home*

**fa-info** *this is font icon for about us*

**fa-list** *this is font icon for menu*

**fa-address-card** *this is font icon for contacts*

**fa-lg** *this is for larger font icon*

***we use i or span to specify the font-awesome icons***

**fa-phone** *this is font-icon for telephone*

**fa-fax** *this is font-icon for fax*

**fa-envelope** *this is font-icon for email*

**this is the use of bootstrap social icons and font-awesome icons**

**google-plus** *btn btn-social-icon btn-google* *fa fa-google-plus*

**facebook** *btn btn-social-icon btn-facebook* *fa fa-facebook*

**linkedin** *btn btn-social-icon btn-linkedin* *fa fa-linkedin*

**twitter** *btn btn-social-icon btn-twitter* *fa fa-twitter*

**youtube** *btn btn-social-icon btn-google* *fa fa-youtube*

**email** *btn btn-social-icon* *fa fa-envelope-o*

## buttons_forms

###### buttons

**button-group** && **role="group"** *it takes all the buttons in a group*

**btn-primary** *primary color for button - dark blue*

**btn-info** *button color - blue*

**btn-success** *button color - green*

**fa-skype** *font icon for skype*

###### forms

*form tag of html to make a form*

**form-group** *it takes all the forms elements in one group*

***created firstname, lastname, areacode, telephone number, email***

***Adding a checkbox and select***

***Adding a textarea***

***Adding a submit button***

## tables_cards

###### tables

**table-responsive** *This makes the table responsive to different screens*

**table** *default table stye rendering on browser with bootstrap own classes*

**table-striped** *striped tables - tables as stripes, alternate rows having different colors*

**thead-dark** *head of the table as dark*

###### cards

**card** *bootstrap classes for cards*

**card-header** *the header or title of the card*

**text-white** *to make the text white*

**card-body** *actual content of the card*

**dl && dt && dd** *description list*

**bg-light** *background will be light*

**blockquote** *adding quotes in a block*

**mb-0** *utility class for bootstrap - margin bottom = 0*

**footer && blockquote-footer** *to add the author of the quote*

**cite** *we can get the source of the quotation*

## images_thumbnails_media

**d-flex** *flexbox classes for bootstrap*

**mr-3** *right margin space upto 3*

**img-thumbnail**

**media-body** *this is so that the content should be properly placed - image with description*

**mt-0** *margin top is equal to 0*

###### badges_alerts_progressBars

**badge-danger** *red color for badge*

**badge-pill** *color for badge*

## bootstrap and js

Bootstraps javaScript support is through javaScript's plugins(plugins written based on jQuery or individually included)

js components can all be used without writing a single line of js(data-*attributes,i.e, data-toggle, data-spy), it is a straightforward approach to use plugins.

## tabs_pills_tabbedNavigation

Tabbed Navigation is used to change the contents on the same page when particular tabs is clicked.

**nav-tab && role="tab" && data-toggle="tab"** *It is for making use of navigation tabs*

**role="tab-panel" && tab-pane** *it is for changing the content in a same page*

**fade** *bootsrap animation for fading*

**show** *bootstrap animation for show*

## collapse_accordion

###### collapse

collapse plugin provides a quick way of revealing and hiding contents

Toggling of content requires the use of a button or a link to trigger the toggle

**data-toggle="collapse"

###### accordion

accordion use is like clicking on one link, seeing it's content while other links are closed & when clicking on other link closes the first link and shows the content of the other.

## tooltips_popovers_modals

Revealing content upon interacting with an element on the web page, information is displayed as an overlay.

order of flexibility(tooltips-->popovers-->modals)

###### tooltips

when we hover over any element, additional information will be shown.

**data-toggle="tooltip"** *It is js component to add tooltip functionality.*

**data-html="true"** *It is js component to activate the html use*

**title** *It is where contents of the tootips will be stored*

**data-placement="bottom"** *It will emerge to the bottom of the button*

add the javasript code to activate the tooltip

###### popovers

when we click on any element, additional information will be shown.

###### modals

more detailed information can be presented than tooltips and popovers.

modal contains header, body and footer.

can use the bootstrap grid in the body to organize content

modal code should be places at the top

**modal** *to bring in the modal function*

**role="dialog"** *to put in to the top of the page*

**modal-dialog** *

**modal-lg**

**role="content" && model-content** *main content of modal*

**modal-header** *head content of modal*

**modal-body** *body content of modal*

**class="close" && data-dismiss="modal"** *to display the button and when clicked it closes the modal page*

code added in navbar to show the modal button

**fa-sign-in** *font awesome icon for login*

the usual login form structure is built

## carousel

It allows the inclusion of a slideshow with captions, can be manually controlled

**carousel && data-ride="carousel"** *It gives the feature of carousel*

**slide** *carousel slide option to slide the contents*

## bootstrap_jquery

Here we will make use of bootstrap to add pause and play button for carousel component and make the slides play and pause with the help of jquery.

**btn-group** *to group the buttons as one entity*

**carouselButton** *to add button for carousel feature*

**carousel-pause** *to add carousal button to pause*

**fa-pause** *to add font icon for pause button*

**carousel-play** *to add carousel button to play*

**fa-play** *to add font icon for play button*

*added some jquery code to add both play and pause button*

*updated jquery code to give pause and play button the functionality to single button*

## css_preprocessors_less_sass

css is great for defining styles for html elements, but it shows limitation as compared to other programming languages coz we can't define variables, nest selectors or use functions.
So css preprocessors comes to it's rescue

**css preprocessors**

***1.less**

***2.sass-syntactically awesome style sheets & scss-sassy css***

***3.stylus***

all are compiled into traditional css syntax automatically before use in a web page. Bootstrap itself
uses Sass for defining its source for its CSS classes. And so if you go into customizing Bootstrap, then you would have to work with Sass code. 

**Typical css preprocessors features**

***1.variables***

***2.nesting selectors***

***3.mixins - mixins can hold multiple css declarations unlike variables, we can also give parameters, we can also do mathematical operations***

***functions and expressions***

###### less

rename the previous styles.css file to styles-old.css

make a file named as styles.less

**npm install -g less**

move to css directory where less file you created

**lessc styles.less styles.css** - This will make styles.css file

###### sass

make a file named styles.scss under css folder

add code to it

**npm install --save-dev node-sass**

go to package.json and add a script to it

**"scss": "node-sass -o css/ css/"**

**npm run scss**

this will make styles.css file under css folder
