
![Image of web design tools](http://kyreenahay.com/imgs/intro-kyreena.png)


Designing for web
=================

###An open source handbook 

v 1.0 - By Kyreena Hay. Special thanks to Thomas Bredin-Grey for proof-reading.


####Contents

1.	Introduction					
2.	General							
3.	Client expectations				
4.	Responsive Design				
5.	Image Optimisation				
6.	Accessibility				
7.	Usability					
8.	User Experience					
9.	Technology						
10.	Preparing the design for devs
11.	Some useful links	
12.	Checklist					




####Introduction
  The purpose of this document is to act as an informal, comprehensive outline of the considerations at every stage of the web design process. I am hopeful that we can use and expand upon this as a reference point that can help us all build upon our existing knowledge so that we can all grow together - and of course build awesome web products for our clients!

####General
  1.	Progressive enhancement is an important web design principle where design is considered for the content first. In practical terms, we design for the most feature-restricted scenarios first, adding on additional layers for those devices and scenarios with wider support for better features. For example you might want a stickied navigation bar, but if your target audience largely uses devices that don’t support them, then you will need to forego a stickied navigation in favour of an approach with wider support.

  2.	Graceful Degradation is another principle that is quite similar, but instead focuses on finding viable solutions for the more restrictive scenarios, rather than cutting something just because one technology can’t support it. A good example of use for this principle, is in considering mobile devices when creating hover effects. As mobile doesn’t have hover, an alternative needs to be found, that serves the same function as hover does for desktop e.g. if something is revealed on hover, simply display it by default for mobile.

  3.	It’s very important to use fonts that are optimised for web (web hinted), or you will have issues with font-rendering. Windows in particular renders fonts with little regard for curve precision, so many fonts are specifically optimised to prevent this issue and maintain legibility. You will also need to consider a fallback font-stack that is found on all computers eg. Arial, Times, etc, in case your custom font doesn’t load for whatever reason. 

  4.	Further on type in web: where your audience is located will matter, so you will want to host your custom fonts in the same locale to reduce load delay. Note that licensing is also very important (so as not to open the company up to lawsuits) so ensure that typefaces used have an appropriate, DRM-free license attached (DRM is pretty terrible in NZ). 

  5. Any text in the design should not be an image, unless it is a decorative/ illustrative device. Otherwise, text should be inputted in the CMS, or coding process. There are many reasons for this; chief being for SEO, and accessibility (screen readers can't read images).

  6.	If you have to plan the usability: draw wireframes. I recommend against doing them digitally, as you become attached to them in that more polished format, which reduces the effectiveness of wireframing - which is to explore the usability, flow, and functionality of the website iteratively. Post-it notes arranged on a board, with lines drawn between each page is a great way to visualise large sites that can't all fit on paper. From there you can see what can be simplified. I like to apply a common rule of fashion, to interface design; before you head out, look in the mirror, and remove one item - or in UI terms; before you sign-off, look at it as a whole, and see what can be removed. 

  7.	Once you’re happy with the use-flow of the website, the general layout of elements, and have sign-off from the client, you move on to the more detailed wireframes - or, mockups. These require content, and are again iteratively designed, through exploring many concepts. Here you can also do some prototyping, which will help. InVision is a great, basic, application for this sort of thing.

  8.	Once a final mockup is chosen and signed off, you move on to the final design stage, which is where you flesh out the full responsive look, then sign-off before handing off all deliverables to the devs. Design absolutely needs to be finalised before it’s handed to devs, as design changes after this stage require very costly and time consuming code revisions.

  9.	Maximum website size should be 990px; even if you design for responsive, and simply allow the design to fill the screen, you should do so with caution. The further a user has to move their cursor - or "reach" - the more uncomfortable the usability becomes.

  10. Always use a grid. The best, easily divisible for responsive grid is 12 columns with 20px gutters, and 20px margins. In Photoshop, you can use the GuideGuide plugin to generate accurate grids - well, as accurate as is possible anyway; don’t be alarmed when one column isn’t quite as wide as the others, as this is the limitation of pixel rounding.

  11.	Resolution independence is important on the web, so utilise vector layers and high resolution smart objects where possible (In Photoshop). 

  12.	Use layer comps for different page layouts (In Photoshop). This is good for a more efficient workflow, and is something that makes your file much easier for other designers and devs to read and use.

  13.	Don’t design in Illustrator if you can help it. Fireworks and Photoshop are better - Photoshop being best, as Fireworks will be discontinued soon sadly. Even better, would be moving to Sketch, which is the new “Photoshop” for interface design. There are a number of reasons for this, from the pixel rendering in Ai being less accurate than PS, to PS being better equipped for website design, as well as more accessible for developers who may need to jump in and grab colour hex values, images etc. Though really, developers shouldn’t ever have to do any of that (see point 10).

  14.	Never forget the importance of the content “above the fold”; this is where users first land, and your main priority for getting the user to stay on the page/ website. Get them interested, let them know that this is where they want to be by appealing to their needs - this is generally considered to mean providing them with information on the site, so they know they’re in the right place for what they’re after.

  15.	Be consistent in your design. Don’t have many different sized buttons and other elements. This is where smart objects really come in handy, as you can duplicate them and have changes saved across every duplicate, for consistency.

  16.	I highly recommend trying to “break” your design, by adding in more content than you designed for, then fixing the result. You need to make sure the design is flexible, particularly because the text will inevitably be translated to a different language, which WILL break it. Another aspect of this, is not using lorem ipsum, but instead using similar content thrown in with some language context. For example, if I’m designing a user name display for a user profile, I’ll try names from different cultures, like Liu Sam, Sanchan Prajeet, Bjork Rykasdottar, as well as hyphenated names, like Sarah-Jane Innott-Lester.

  17.	On the note of cultures and names: if you need a user to provide their name, a single field is best, due to the many different name treatments across cultures e.g. the Chinese traditionally place their last name first, which makes "first name" and "last name" unhelpful.

  18.	Consult with the developers frequently about whether something will be possible or not, or if they may know a better way of doing it. An open dialogue throughout the project is very important.


####Client expectations
1.	As a web designer you have a responsibility not only to fulfill client requests, but to go above and beyond their expectations and produce a highly successful website for your client. Web results & effectiveness are directly measurable & no client will be satisfied if their website does not perform well. Thus, it is important to realise that clients aren’t trained in web design - they will not often know what will bring them the most success and often do not have their real best interests at heart. With this in mind, consider:

  1.	The single biggest stakeholder in the success of any website is the Users, by a very large margin. If you can teach clients that sound usability practice will lead them to success, then they will trust you to execute this effectively. 

  2.	Factors like user flow, accessibility and especially load times (see progressive enhancement, image optimisation) have been shown again and again to directly influence bounce rate/ conversions and thus are strongly correlated with resulting revenue and profit margins. Emphasise this to your client and sound usability practices should be an easy sell!

####Responsive Design
1.	Responsive design is a progressive enhancement concept. In practical terms - the mobile design will lack features that the tablet and desktop have, as the use case and technological requirements are different. Mobile may even gain functionality or elements to make up for the loss of larger elements; it’s all a part of the usability considerations important for responsive web design.

2.	Designing how the site looks on mobile and tablet is imperative, and in some cases it may be necessary to include desktop view as well, though desktop and tablet are often very similar. Some good approximations: Mobile width when designing is 480px (600-800px for ‘above the fold’), tablet width is 768px, and desktop is 990px+. Try not to focus too much on devices as our websites need to be future-proofed against any possible new device that may emerge in a rapidly, ever diversifying market.

####Image optimisation
1.	Compression for web (72dpi, consideration of formats, and ratio of compression to image quality), and ensuring the image size is exactly the size it will display at in web. Images should be saved exactly at the size required for the website.

2.	Again consider progressive enhancement - but balanced with the needs of retina screens, and the current limitations that CMS’s have for serving up images. Right now, the best solution is to save images at 1.5x size (retina requires 2x, but 1.5x is a good compromise), as CMS's can only serve up one version of an image. But, when there is no CMS involved, you will need to save out a different sized image for each break-point, which is the best way to do treat images for responsive web.

####Accessibility
1.	Consideration for disabilities, by default, is important. Color blindness, and complete blindness are especially common. For design, this means design that has high contrast (i.e. black text on white is high contrast design, while light grey text on white is low contrast and bad), body text preferably 12pt+, usability that is so simple your grandmother could use it, and copy that isn’t excessive and is laid out in an easily scannable manner. For blind users your user flow must be accessible to screen-readers.

2.	 Some companies - like government organisations - require a full stack, unique consideration for disabilities, so if the brief requires it, often times you have to design in such a way that people with disabilities can make changes to the website by toggling the design according to their needs. See: government accessibility guidelines.

####Usability
 1.	It is important to remember that while you may think a layout makes sense to you, it might not for others (especially people of different cultures or where english isn’t the first language, eg right-to-left languages), which means they will become frustrated trying to find what they want. Besides doing thorough User Research and testing; it’s good to observe common use patterns on similar websites and interfaces, and adhere to common layout patterns, after establishing the information hierarchy and designing for common use cases. This can end up resistricting your creative freedom, but is best for the project. 

 2.	Affordance is when something has a visual cue that indicates how you interact with it. Like a door that has a handle should be pulled, not pushed. If you have to push that door, you become frustrated because the affordance indicator suggests to pull it, which you naturally attempt first. In UI, an example is a button that looks like a button - if it doesn’t look like a button, the user won’t know to click it, so keep affordance in mind.

 3.	As few clicks as possible - Very important. This is a particularly good rule of thumb when thinking about navigation layers. I try really hard to not have more than one layer of navigation, and find other ways to have sub-navigation to prevent too much clicking. More than one layer of navigation requires breadcrumbs. Avoid more than 2 layers at all costs - this usually indicates something has gone wrong at the wireframing stage and represents an overcomplicated user flow.

 4.	For websites that have generated content and pages, the devs will tell you they need a 404 error page design. 404 is what you get when an error occurred locating a page, so it needs clear instructions to help the user find what they were looking for, or just go elsewhere on the site. Github has the best example of a 404 page done right.

 5.	Icons are a complex issue and need to be treated with delicacy. It’s best to accompany an icon with text, as there are very few that all users easily recognise; and it doesn’t help that we’re not all using the same icons for the same functions either. The Hamburger icon is a good example of an icon being abused without consideration for the user, and it’s looking like there’s now a movement away from just assuming you can use it to represent a “menu” (does Joe Blogg user even know what a “menu” is, in the context of web? We’re assuming too much with this interface element). In reference to what was said before about “designing for your grandmother”; my grandmother would not make use of that icon, according to a study conducted recently.

 6.	Mobile has a lot of considerations as well:

  1.	Using your fingers means you need large buttons and spaces for scrolling - you don’t have the accuracy of a mouse cursor. I once designed a mobile app that had both vertical and horizontal scroll functions, and you really needed a lot of space to put your finger and swipe in the specific direction you wanted, or the device became confused and swiped the wrong way.

  2.	You need to consider the use-case scenario for viewing a website on your mobile phone vs tablet vs desktop. The reading experience on mobile is less comfortable than it is on tablet or desktop, so you want to reduce scrolling and reading on mobile phones; I recommend a quick “back to top” solution for all devices.

####User Experience
 1.	It’s good to consider animations and transitions for the website, as it creates an entertaining, unique, personable, and more real experience for the user. When something moves like it’s affected by external factors such as gravity, it makes an otherwise robotic interaction more real for users. Web technology has advanced a lot, and there are many, many possibilities these days. I recommend checking out Codrops for a plethora of lovely animations and transitions that most frontend devs can implement with ease. Many things can be animated, from drop-downs, to buttons, and interesting elements. Keep in mind that an alternative state to hover needs to be included (progressive enhancement again), for devices that do not have hover capabilities i.e. tablets. Additionally, animations and transitional effects can slow down the website, so use them wisely.

 2.	All objects that a user interacts with in some way, like a button, link, drop-down, or form, needs a state for every stage of interaction: hover, active, focus (when you select a field in a form to fill out), and disabled. You will need to design each state, where needed. This is again where you keep affordance and use of animation in mind e.g. a button pushes down when you click it, a lot like a real life button.

 3.	You will also need to design user feedback - positive affirmation being an important one (which is when you tell a user when something was successfully done e.g. email sent). Examples are: error messages; success message; loader when something is being processed, like an email being sent, progress bar, and more.

 4.	Ensure a smooth user flow at all times. Things like login, sign-up, and payment processes commonly trip up on this. Consider that the user wants as few steps and things to fill out as possible, wants to be moved to as few screens as possible, not be taken to a third party site if possible, and return back to what they were doing before without issue. This is largely fleshed out in wireframes, but there will be design elements and compliment the process. 

 5.	Design for states other than the standard. What happens if there is no content, on a page where content is generated (i.e. an empty cart) - do you have a call to action to rectify this? What happens if there’s an error? What happens if they lose internet connection? What happens if they start a process, get interrupted, and return hours later having completely forgotten what they were doing? What happens when generated content is loading? How does that generated content look when it loads?

 6.	Web users are largely scanners first, readers second (they’ll scan to find what they want, and read more if they’re interested) - often they don’t progress on from scanning. Make sure you don’t lose your audience in a wall of text, and format text using principles of strong information hierarchy (ie: use strong headings, lists, and other highly scannable content formats to direct user attention rapidly through the page).

####Technology
You will need to understand and consider the limitations of the technology that will be used. Here are a few examples:

1.	Internet Explorer can’t do a lot of things that other browsers can, so you’ll need to weigh up how important it is that Internet Explorer users don’t miss out on designed features because the browser can’t make it look the way you designed. This depends on your user base, and how important it is that the feature looks like it does - maybe you could have an image fallback in the code, or maybe you will just forego that design. A good example is rounded corners; IE7 doesn’t support those, so we either decide to let IE7 suffer and have no rounded corners, completely forego rounded corners, or IE7 gets an image fall-back which isn’t very flexible code-wise.

2.	There are a LOT of mobile browsers out there; kindle has a browser, which is fairly limited, older versions of opera mini are a relative write-off, the default android browser is a shocker, whilst safari, opera, and chrome all have their own limitations on mobile. Keep in mind your target user base and what they’ll likely be using.

3.	Content Management Systems have their own limitations, in particular, a good rule-of-thumb is to create “components/ modules” -  sections of design that are cloneable and re-usable across the site. 

4.	While your design may look beautiful on your mac screen, most users have a cheap monitor that isn’t calibrated, so it may look bad on theirs, or faded out (lack of decent contrast). What saves this is upping contrast, not using colours that are very close to white for important elements.

5.	Moodle again has limitations - largely there seems to be limited responsive capabilities. Same goes for online courses. If it can’t be made to adapt to a smaller screen, a different solution that won’t impede on the mobile experience needs to be found.

6.	Touch devices have no hover, as well as different common UI patterns i.e. Android doesn’t traditionally use the “hamburger icon” or the subsequent drawer menu functionality, they instead use a drop-down menu aka a “pop-over”. The hamburger icon is currently under great debate, and your mobile menu design decision needs to be well considered for usability.

 7. When designing for emails, keep in mind that email technology is very far behind browser technology. To avoid headaches, it's recommended you style the email design as little as possible; the most successful email design is one with nothing but standard text, and a company logo. Anything more will mean an increase in time spent trying to ensure it looks good across all email clients, so embellish with care.

####Preparing the design to be handed to Devs
My first piece of advice for this chapter is: sit down and talk to your Devs about what you can do to make their job easier, and of course explain to them what would make your job easier. While the following guidelines are important, everyone has different backgrounds; I’ve met Devs that prefer being handed SVGs to .psds, and I’ve met Devs who have a great eye for detail so they need less educating than others on replicating my designs. Obviously, pixel perfection is impossible in web, but that doesn’t excuse a shoddy job from a Dev.

2.	The majority of Backend Devs have little design training - which usually means they won’t have your same level of attention to detail. This can range from not seeing that you used a sans-serif font (not a serif!), to not understanding the importance of that 10px space between two elements and setting it to 20px instead. Your best bet is to simply assume the worst, and hand them all of the images and icons exactly as they should be on the site, give them a .txt file with all hex colour values and fonts used, and send them screenshots with grids visible, so they see how things line up. Additionally, give them the raw .psd file so they can get exact measurements of things.

3.	Name files according to the BEM (Block, Object, Modifier) convention for easy and transferable storage and use. For example, an arrow icon that points right, will be called “icon_arrow_right.png” (“block_object_modifier.format”). All icons will start with “icon”, and all arrow variants will be suffixed with a descriptor. This means like objects can be grouped alphabetically by name in the file system, and makes it easier to find, and reference them.

4.	Best case scenario would be if you could create image spritesheets. This is when you save the same type of images into one file, all nicely ordered and aligned. Then, just one image loads, which reduces site load time, and in the code we reference one image and just change the background position. This will however require good grasp of code due to some very complex positioning cases (leaving space for related content) - so don’t stress too hard about learning this.

5.	Show devs your planned use-flow. They need to see how you intend the user to navigate the website.

6.	An optimum scenario that we don’t always get time for, is to give devs “functional specs”, which is a matrix table of every interactive object on the site, and what its hover, active, and focus states are, what happens when you interact with them etc. 

####Some useful links
  1.	Smashing Magazine: http://www.smashingmagazine.com/ (If you’re going to read any of these, Smashing Mag is the one; it is the best.)
  2.	Responsive Resources (most comprehensive list on the web): http://bradfrost.github.io/this-is-responsive/resources.html 
  3.	A List Apart: http://alistapart.com/
  4.	Excellent resource for high quality web design patterns and examples: http://tympanus.net/codrops/
  5.	A fairly important resource for design pattern inspiration: http://patterntap.com/
  6.	Great icon search engine: https://www.iconfinder.com/
  7.	A more general resource for everything you could possibly need: http://www.agiledesigners.com/
  8.	The following are great sources of web design inspiration*:
	1.	http://www.siteinspire.com/
	2.	http://httpster.net/
	3.	http://www.designmadeingermany.de/sites-we-like/
	4.	http://www.verynicesites.com/
	5.	http://www.minimalsites.com/
	6.	http://designspiration.net/ (all types of design here)
	9.	A library of UI and interaction patterns: http://useyourinterface.com/
	10.	These guys are the leaders in UX research: http://www.nngroup.com/
	11.	Excellent articles discussing aspects of web: http://24ways.org/

*Many of these are self-indulgent and don’t have much regard for end-users; it’s always good to find out how feasible things are - every website has a different user base and tech consideration, so what works for one, may not work for another.


##A Web Design Checklist:

- Fonts are web optimised.
- The font license suits our needs.
- Where your fonts are sourced from (and therefore hosted) has been considered.
- Your working file is laid out with mobile, tablet, and web, lain side-by-side, with the appropriate dimensions.
- Images in your file are imported at their largest possible size, turned into smart objects, then the smart object downsized according to your needs, so that they can ultimately be saved out at least 1.5x their viewed size.
- A grid is being used.
- Principles of Progressive Enhancement, and graceful degradation, are kept in mind. 
- Your design has a consistent use of sizes, colours, elements, etc.
- There are no images that are text, unless they are purely decorative elements.
- Technological limitations are kept in mind.
- Emails are as uncomplicated as possible.
- If designing a site that will use a CMS; your design contains "modular" components.
- Your design won't break if more text than was planned for, is used.
- Accessibility has been considered.
- The usability of icon choices and treatment have been considered.
- Transitional effects have been considered. 
- All interactive elements have the necessary states, like:
  - hover
  - active
  - focus
  - disabled
- Alternate states are considered eg:
  - No content
  - Search returned nothing
- All necessary user feedback has been designed:
  - Error messages 
  - 404 page that makes sense and can easily direct you to where you want to be.
  - Success feedback
  - Processing/ loading feedback
- All images have been optimised for web, and labelled so that images that fall within the same category are grouped together through naming convention.
- You’ve made it easy for devs to be able to obtain hex values and sizes, either by handing over a raw file, or a document outlining all colour values and sizes.
 
