






# 1960s Rock Band Website - FIVESKIN

Hi there! Welcome to my first milestone project!

I have been tasked to build a website, combining the Frontend skills I have learnt from the first three modules.

View it live it here: https://sps992.github.io/UCF-Milestone-Project/

<h5>What Now?</h5>

The band needs to be a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world. 
<br>After interviews with the client’s representatives I have learnt that their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.

<h5>Anything Else?</h5>

The band would also like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.
The band has provided you, the developer, with the following assets that they would like to showcase on their website:
Photos of the band members
A video clip
Audio clips
Also, they are in the process of creating a social media presence and would like to add links to their Facebook, Twitter and YouTube pages.

<h5>How Am I Going To Do It?</h5>

<ol>

<li>Firstly I am going to have a look at current band websites to research what is already out in the real world and see how they have utilised User Centric Frontend Design.</li>

<li>Next I am going to use this information to start wireframing ideas, using the briefs required content for the page. </li>

<li>I will then progress to implementing the intial code in order to made this happen.</li>

<li>Lastly, but by far not the least important! I wil check over my code with a fine tooth comb and makesure everything is looking as it should and look for grammatical errors.</li>

</ol>
 
## UX

I have intently followed the brief and modelled my website on a simple but effective navigation structure. This is to keep the older generation of fans safe and happy through the navigation and scrolling through the website. However I have kept a fresh minimalist theme in order to not scare away the potential younger fan base.

### User Stories

 EXAMPLE FORMAT{ As a user type, I want to perform an action, so that I can achieve a goal.}
 
- As an existing fan, I want to find out the details of the bands tour, So I can see if they are performing near me and to get tickets.

- As a new potential fan, I want to know more about the band, in order for me to choose whether I want to book them for my event.

- As a avid music fan, I want to find out whether they have any samples of their music, so I can satisfy my undying need to listen to new hot artists.

- As a mid 20's male with a short attention span, I want to see lots of big exciting pictures, in order for me to invest in the band.

- As a young woman who has multiple crushes on men who is a musician in a band, I want to easily navigate from all the media on the websites pages, to distinguish which member is going to be my next dreamboat.

### Wireframes

I have created a few wireframes before I started coding the initial structure. I did this to better understand what I needed to include, what it would roughly look like and the space it could potentially fill. To See them please follow the link below or navigate to the 'Wireframes' folder in my git repository:
https://github.com/sps992/UCF-Milestone-Project/tree/master/Wireframes

## Features

I have kept the overall layout and features simple and well spaced. This is to keep the user experience as positive as possible, which enables the end-user to freely and quickly navigate through the websites pages with ease, whilst not needing any prior knowledge of the website. In the next section I will describe the features that currently exist on the website, why I have used them the way I have and how it is in-keeping with the websites positive feel.
 
### Existing Features

- Hero Image - I have decided to use a full-width hero image on all of my pages. Why? It creates a nice starting place for any webpage and keeps the visitor engaged, more likely for them to scroll down the page than to navigate somewhere else. I have coded these images to look good on all devices by choosing to set them to scale proportionally to cover a certain area at all times. This ensures that the branding throughout the pages is consistent.  

- Contact Form - I have produced a contact form on the 'Hire Us' page of the website. I used the bootstrap website for help on shortcodes and code snippets. As I have written code like this before I found it quite easy to manipulate the contact form to fit the overall theme and branding of the site. Thanks to Bootstraps built in form validation, it gives a nice professional feel as you can set inputs as required fields and makesure the user can not submit the form without filling them in.

- Embedded Audio - This is not something I have needed to do before, so it took a bit of head scratching and browsing the w3schools website to gain the much needed knowledge. I located some royalty free audio which fit the brief( as best I could) and uploaded it to the cloud9 workspace( please see 'Media' for acknowledgements for the audio).

- Carousel - I have used the Bootstrap carousel as the framework to build my carousel on the 'photos' page. I used the Bootstrap version as its quite simple to implement and fairly pain free. It is also remarkably easy to manipulate the code to whatever dimensions you want and creating media queries so it falls into line with the expanding and collapsing of the page.

- Video - I have included a royalty free( please see 'Media' for reference) video which I have embedded nicely into the layout of the page. Compared to the carousel, this was a walk in the park and only took a little while to get it the way I wanted to without looking up any additional 'know-how'.


### Features Left to Implement
- Server-side Validation - As this project focuses solely on frontend web developing, I have not set up any server-side validation for the contact form. This is always good practice to have in the real world as you are not relying on frontend alone for validation and will then avoid the pitfulls that come with relying on frontend validation.

## Technologies Used

In this project I have used the following technologies to create my project...

- Bootstrap - I have used multiple snippets from Bootstrap. Including core parts of its pre-built css and javascript. https://getbootstrap.com/

- Javascript - As mentioned above, I needed the javascript to run the transitions on my carousel. 
https://www.javascript.com/

- JQuery - I used JQuery alongside the bootstrap framework, which helped add functionality to my site.
https://jquery.com/


## Testing

I feel I have throughly tested my site in multiple ways.
Firstly, I have used the top navigation bar to navigate from one page to another in all the different combinations to check I haven't got any deadlinks. I have also added dummy links to my social links at the bottom. Why? This way I have tested that the anchor tag is working correctly and can be implemented properly if my website was in the real world and had working links.
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.


I have used the W3C markup validator to double-check my code to make-sure there wasn't any errors. I have documented my results here:
https://github.com/sps992/UCF-Milestone-Project/blob/master/Nu%20Html%20Checker%20result.pdf

<h5>Testing User Stories</h5>

1. "As an existing fan, I want to find out the details of the bands tour, So I can see if they are performing near me and to get tickets."-Tour Date Table:
    1. Land on website from organic or generated search engine result.
    2. Scroll down "index.html" until tour table is centered in viewpoint.
    
2. "As a potential fan, I want to know more about the band, in order for me to choose whether I want to book them for my event." - About article on "index.html" and contact form on "hireus.html".
    1. Land on website from organic or generated search engine result.
    2. Read article titled "About Us" below hero image on "index.html".
    3. Navigate to "Hire Us" in the top navigational bar
    4. Successfully enter name in first box to avoid bootstrap validation error alert.
    5. Successfully enter contact number in second box to avoid bootstrap validation error alert.
    6. Successfully enter email in third box to avoid bootstrap validation error alert.
    7. Enter optional message in box to add booking details and extra comments needed. This step is optional as the form now has all contact details to contact end-user if this step was in fact skipped.
    8. Press "Send Project Request" to submit form.
    
3. "As a avid music fan, I want to find out whether they have any samples of their music, so I can satisfy my undying need to listen to new hot artists." - audio clips on "music.html".
    1. Land on website from organic or generated search engine result.
    2. Navigate to "Music" in the top navigational bar.
    3. Press the play button in the audio controls tag.
    4. Enjoy.

4. "As a mid 20's male with a short attention span, I want to see lots of big exciting pictures, in order for me to invest in the band." - Photo Carousel on "photos.html".
    1. Land on website from organic or generated search engine result.
    2. Navigate to "Photos" in the top navigational bar.
    3. Scroll down to photo carousel.
    4. Click directional pointers or either side of the image, to flick through the photos.
   
<h5>Media Queries and Viewport sizes</h5>

In this project I have worked heavily with the Bootstrap grid system. This has alowed me to easily create a website tha looks good on all devices and viewport dimensions. I have, to the best of my ability, made the content use the pre-programmed device breakpoints.
I had a bit of an issue with the footer sticking to the bottom on larger screen widths. I quick fixed this problem by adding more content and giving this content plenty of padding to push the footer to the bottom by default. I ran my website through a validator again to check if there was an issue but it didn't flag anything obvious. So I just kept with my quick fix.


## Deployment

My deployment was pretty simple as far as deployment goes. I was coding in a Cloud9 html5 workspace called 'fiveskin-rockband-project.
I had initialised the git repository using the console command 'git init'. After double-checking I was ready, I committed the initial commit using the console command 'git commit -m "initial commit"'. This commit was the base of the web project with the main structure of the pages and basic css, js and jQuery needed to run the navigational bar and other basic functions. 

Next, I linked the Cloud9 workspace to GitHub by using the 'push' command and entering my log in credientials for my GitHub account. I repeated this sequence until I was happy with the website in its entirety. My next step was to deploy it so it could be viewed as a live website. For ease, I did this using the 'GitHub Pages' feature. Which is located in the settings menu of the GitHub repository. You can view it now on:
https://sps992.github.io/UCF-Milestone-Project/

To run my code locally, you would just need to download my GitHub repository and extract it into local folder and VOILA.


## Credits
- As for credits I don't think there is anyone I haven't mentioned in 'Acknowledgements' at the bottom of this page. However I would like to thank Nescafé for its wonderful coffee...surely no explanation needed there!
### Content
- I created all the text and content filler for my website that I haven't included in the 'Media' paragraph myself using knowledge I already know. I would like to say that all information on the website is completely fictional and made up from the craziness in my head.

### Media
In this project I have used the following royalty free material...

- [Video](https://videos.pexels.com/videos/rock-band-concert-857173)
    - This project uses a royalty free video from a website called 'Pexels'. I have used this to visualise the dummy content for the band. 
   
- [Audio](https://www.free-stock-music.com/nicolai-heidlas)
    - This project uses a royalty free audio from a website called 'free-stock-music'. I took interest in a particular artist called Nicolai Heidlas, who made some great royalty free audio clips. I have used this accompolish the briefs target of embedding example music. 

### Acknowledgements
- I would like to thank the w3schools website( https://www.w3schools.com/default.asp ) for saving me hours of scrolling through half-decent threads on Stack Overflow before I got the information I need.

- On that note I would also like to thank multiple threads on Stack Overflow for giving me hints and tips on the more fiddly css elements that I wanted to manipulate.

- The Bootstrap website also helped me to further understand the code and bend it to my will. (https://getbootstrap.com/)

