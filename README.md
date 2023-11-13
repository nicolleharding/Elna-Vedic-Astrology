# Vedic Astrology

Elna McKenzie is a Vedic Astrologer with 15+ years experience. This website aims to share more information about Vedic Astrology, the differences between Western and Vedic Astrology, answer any questions a possible client may have and entice people to book a consultation reading wih Elna.

The goal of this website is to allow users to understand more about Vedic Astrology, learn about Elna's experience and credentials, have their concerns addressed through FAQs and easily book a consultation. 

The goal of the website is for Elna, is to share information about Vedic Astrology and the lifestyle, whilst increasing interest from possible customers allowing them to enquire about a consultation. 

![Screenshot 2023-11-09 at 15 50 27](https://github.com/nicolleharding/Elna-Vedic-Astrology/assets/146173473/e138be6f-5460-4e09-890c-9cb5a3e30eb2)

# Features

## Existing Features

**Navigation Bar**

- Positioned on top right of the page next to the logo which is on the left of the page and the nav bar on the right. The nav bar item selected is underline when on the page, and moves to the next page as the user hovers on that nav selection.
- The responsive navigation bar includes links to the Home page, FAQs page and Book page which is fully responsive and identical on each page for easy of use.

**Footer**

- Set on a blue background, the footer includes the email address and the social links centered on the page. The links are clickable and navigate to the desired destination in a new tab, with the email opening up a new email.
- The footer remains the same on each page of the website.

**The Landing Page (Home page)**

- Cover hero image of moon in night sky, with text that highlights services Elna offers and gives the user more information on what Vedic Astrology is. Included is a button to help users navigate to the Book page. This is to increase awareness of call to action and highlight why the user would want to enquire for a consultation.
- About Elna - Photo of Elna positioned on the left hand side to build trust and approachibility with the familiarity of a photo. - The section includes a discriptive write up of Elna's experience, how she started with Vedic Astrology and her study experience. - Many people may not know what Vedic Astrology is. To highlight to the user why they would want Vedic Astrology over Western Astrology, I have included a Why Vedic Astrology section on this page.

**FAQs**

- Centered at the top of the page is an accordian FAQs section. The questions are designed to be clickable exposing the answers. A hand appears on the scroller to ensure the user knows to click on the queston box. This creates a better user experience as it is more visually appealing.
- At the bottom of the FAQs page is an image of the zodiac on a black star sky. Overlayed on this image is the upcoming festivals and fasts for the next quarter.

**Book**

- Set on a background of stars in the galaxy, the "Book a Consultation" form includes collection fields of name, email, contact number, consult date and a message box. The email box is set to only accept email details. All boxes are required other than the message box.
- I have intentionally left off the price of a consulation as this is variable depending on country and the clients (Elna) preference.
- Under the boxes is a "Book Now" button, which sends the data collected directly to Elna via email.
- Included in the form is what a user will need to share for a consultation and what to expect. The for main points of the "What to Expect" content are in bold and purple to visually catch the users eye and highlight these points.

**Font and Color Pallet**

- Logo (h1) Font:
  - 'Hind Madurai', sans-seri
- Hero Font (h2):
  - 'Hind Madurai', sans-serif
- h2 Body Font:
  - 'Athiti', sans-serif
- Body Font:
  - 'Athiti', sans-serif
- Button Font:
  - Hind Madurai, sans-serif
- Color Pallet:
  - #2f4f4f (darkslategrey)
  - #ffffff (white)
  - #542875 (purple)
  - #f8f8ff (ghostwhite)

## Checklist of Things to Fix

Need to make everything responsive.

**Navigation Bar**

- Change burger image to white. - done

**Footer**

- Increase Contact Details font weight.- done (chose to remove this wording)
- Responsiveness on footer has issue with logos. - done
- Size of footer seems to high. - done
- Change FB and IG destination URL's to actual accounts. - done

**Index Page : Hero Image**

- Need to improve placement and colour of button. - done
- Make button navigate to Book page.v - done
- Column text, center and add padding. - done
- Not sure obout the copy on the Hero image. - done
- Add interesting layout for the bullets on the hero image. - decided not do
- Need to get rid of white line under nav bar.- done

**Index Page : Section**

- Look at the head shot when responsive as it's tiny. - done
- Adding padding to the image. - done
- Positioning the texton the right of the image. - done
- Need to figure out padding of text. - done

**FAQs Page : Section**

- Edit FAQs pay layout as it looks poor. - done
- Convert Faqs to a table which has dropdowns instead of all the copy visible.- done

**Book Page : Section**

- Change size of submit button.
- Change size of text boxes to be responsive.
- Change form submit to Code Institute deposit. 
- Layout is boring need to look at imagery. - done
- Add CSS to form layout. - done
- Fix background image. - done

## Features Left to Implement

- Pay gateway to allow user to pay for consulation.
- Animate hero image.
- Add a gallery for photos of Elna's travel in India.
- Add page that includes charts of famous people for interest and also to see output.
- Add an animated scroller to the Festivals and Fasts that allows me to inlcude all 12 months.
- Add more content on zodiac and perhaps some animation to explore this.

# Testing

**Navigation Bar**

- Burger image is correct color and is responsive.
- On smaller screen when clicked on nav drops down when burger is clicked on.
- Header text and background is responsive.

**Footer**

- Tested link to social platforms and like to Elna's pages. Opens in a new tab as intended.
- Tested link to email, opens email to Elna. Opens in a new tab as intended.
- Footer size is responsive.

**Index Page : Hero Image**
- Changed image to a WebP image. 
- Fixed Button to navigate to Book page. 

**Index Page : Section**
- Changed image to a WebP image and resized to 480px as this is the max size that was needed for this image. This was flagged in inital Lighthouse test. 
- Increased padding between paragraphs and headings not that <br> is removed. 

**FAQs Page : Section**
- Changed image to a WebP image. 

**Book Page : Section**
- Changed image to a WebP image. 
- Fixed font-size in input field. 

**All**
  - Adjusted body to accomodate extreely large screen sizes over 1600px. 
  - Removed use of <br>.
  - Fixed syntax to go from h1 > h2 > h3.

## Validator Testing

- HTML
No errors were returned when passing through the official W3C validator

HTML Errors Fixed
  - Missing "=" on line 12 after "name" for keyworks.
  - Fixed various elements with trailing slash. 
  - Remove duplicate class for "bold".
  - Fixed values for attributes on form collection for Book page. 
  - No errors returned on FAQS Page on first check with W3C. 
  - 

- CSS
  - No errors were found when passing through the official (Jigsaw) validator

  CSS Errors Fixed
- 

## Unfixed Bugs

**Navigation Bar**
  - None

**Footer**
  - None

**Index Page : Hero Image**
  - None

**Index Page : Section**
  - None 

**FAQs Page : Section**
  - None

**Book Page : Section**
  - Sizing of message box - rows and columns removed as impacted by responsiveness. 
  - Form container for Galaxy Fold is not formatted the same as other resolutions. 

# Deployment

**Adding and Commiting Files**
These are the steps that were followed:
1. Typed "git add" in the command line. Use "." to add a new change to a file. 
2. Then typed "git commit" to commit these files to the repository with a comment. To add a comment I typed -m "With a detailed explination of the change you have made". I did this on a regular basis to ensure I had versions of changes, should I need to go back to a previous version. I struggled with this in the beginning as Codeanywhere had significant delays, but since changing to writing code in Git Pod this has been resolved. 
3. Typed "git push" to push these changes to Git Hub from Codeanywhere of Git Pod.
4. After adding wireframe, text and ianges to website, before I started troubleshooting bugs I deployed the website. This is because some styling looks different on a deployed website to the staging area.  

**Ensuring the file path was correct to find images, navigation and files**
Used the file's path, such as assets/css/style.css or index.html, to add a single file. Used ../ before image files to ensure the file path was relative. 

**The live link can be found here** 
https://nicolleharding.github.io/Elna-Vedic-Astrology/

## Credits

# Content

The text for the Home page was taken from Wikipedia Article A
Instructions on how to implement form validation on the Sign Up page was taken from Specific YouTube Tutorial
The icons in the footer were taken from Font Awesome

# Media

The photos used on the home and sign up page are from This Open Source site
The images used for the gallery page were taken from this other open source site
Congratulations on completing your Readme, you have made another big stride in the direction of being a developer!
https://elementor.com/
<https://preview.themeforest.net/item/jyotish-html-template/full_screen_preview/24299144?_ga=2.1031095.781021030.1699353928-286597811.1698831490>
<https://www.istockphoto.com/
<https://ide.geeksforgeeks.org/online-html-editor/210fd03c-8cf7-462a-8981-1c80740d1f6f>

<<<<<<< HEAD
![image of Jyotish](../Elna-Vedic-Astrology/assets/images/faqs/parasara_jyotish.png)
=======

>>>>>>> 82350918435c4af2ab4942da0233206e5c8df25e
