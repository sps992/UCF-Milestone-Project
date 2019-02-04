






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


In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

In this section, I am going to analyse the different parts of the website. What I have used in those parts and why.
 
### Existing Features

- Hero Image - I have decided to use a full-width hero image on all of my pages. Why? It creates a nice starting place for any webpage and keeps the visitor engaged, more likely for them to scroll down the page than to navigate somewhere else. I have coded these images to look good on all devices by choosing to set them to scale proportionally to cover a certain area at all times. This ensures that the branding throughout the pages is consistent.  

- Contact Form - I have produced a contact form on the 'Hire Us' page of the website. I used the bootstrap website for help on shortcodes and code snippets. As I have written code like this before I found it quite easy to manipulate the contact form to fit the overall theme and branding of the site. Thanks to Bootstraps built in form validation, it gives a nice professional feel as you can set inputs as required fields and makesure the user can not submit the form without filling them in.

- Embedded Audio - This is not something I have needed to do before, so it took a bit of head scratching and browsing the w3schools website to gain the much needed knowledge. I located some royalty free audio which fit the brief( as best I could) and uploaded it to the cloud9 workspace( please see 'Media' for acknowledgements for the audio).

- Carousel - I have used the Bootstrap carousel as the framework to build my carousel on the 'photos' page. I used the Bootstrap version as its quite simple to implement and fairly pain free. It is also remarkably easy to manipulate the code to whatever dimensions you want and creating media queries so it falls into line with the expanding and collapsing of the page.

- Video - I have included a royalty free( please see 'Media' for reference) video which I have embedded nicely into the layout of the page. Compared to the carousel, this was a walk in the park and only took a little while to get it the way I wanted to without looking up any additional 'know-how'.


### Features Left to Implement
- Server-side Validation - As this project focuses solely on frontend web developing, I have not set up any server-side validation for the contact form. This is always good practice to have in the real world as you are not relying on frontend alone for validation and will then avoid the pitfulls that come with relying on frontend validation.

- 

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

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
In this project I have used the following royalty free material...

- [Video](https://videos.pexels.com/videos/rock-band-concert-857173)
    - This project uses a royalty free video from a website called 'Pexels'. I have used this to visualise the dummy content for the band. 
   
- [Audio](https://www.free-stock-music.com/nicolai-heidlas)
    - This project uses a royalty free audio from a website called 'free-stock-music'. I took interest in a particular artist called Nicolai Heidlas, who made some great royalty free audio clips. I have used this accompolish the briefs target of embedding example music. 

### Acknowledgements
- I would like to thank the w3schools website( https://www.w3schools.com/default.asp ) for saving me hours of scrolling through half-decent threads on Stack Overflow before I got the information I need.

- On that note I would also like to thank multiple threads on Stack Overflow for giving me hints and tips on the more fiddly css elements that I wanted to manipulate.
