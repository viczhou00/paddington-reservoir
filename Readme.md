### This prototype works correctly with Google Chrome 

## Introduction
This document provides a comprehensive overview of the design and development process for the Paddington Reservoir Gardens microsite. It outlines the justifications for my implementation decisions, highlighting the rationale behind my design choices and their alignment with user needs informed through user testing. To demonstrate the development process, I compare the wireframes with the final prototype, 
showcasing the evolution of my design. 

The design of the microsite took into account four key considerations: Visual Hierarchy, Colour Palette and Imagery, Responsive Design, and Accessibility.

### Visual Hierarchy
Visual Hierarchy is vital for effectively delivering information to the end user (Gordon, 2021). To communicate details about the Gardens, I used differentiated heading and paragraph tags to create varied typography. This distinction enhances readability, allowing users to scan the content and find key information quickly.

![Alt text](<Markdown images/Hierarchy 1.png>)

Additionally, I incorporated images and icons of varying sizes. Larger images highlight significant features, while smaller icons complement the text, providing visual cues that support the narrative. By strategically placing these elements, I guide the viewer’s line of sight, enriching the user experience and ensuring they gain a deeper appreciation of Paddington Reservoir Gardens.

![Alt text](<Markdown images/Hierarchy 2.png>)
![Alt text](<Markdown images/Hierarchy 3.png>)
![Alt text](<Markdown images/Hierarchy 4.png>)

### Colour Palette
I selected a colour palette of green, dark grey, and white to convey the lush elements of Paddington Reservoir Gardens. The vibrant greens evoke tranquillity and connection to nature, while dark grey adds sophistication and contrast, and the white background enhances readability.
This consistent application across the microsite reinforces the garden’s identity and guides users’ responses.

![Alt text](<Markdown images/Colour Palette 3.png>)
![Alt text](<Markdown images/Colour Palette 2.png>)

### Responsive Design 

Responsive web design enables websites to adapt to various screen sizes, greatly enhancing user experience (Shallard, 2023). To achieve this, I implemented flexible grid layouts that scale across devices and used CSS media queries to adjust styles based on screen size. This approach improves usability and accessibility, ensuring a consistent experience for all users.

![Alt text](<Markdown images/Responsiveness 1.png>)
![Alt text](<Markdown images/Responsiveness 2.png>)

### Accessibility 

To make the microsite accessible, I applied design practices aligned with Web Content Accessibility Guidelines (WCAG). Key features include alternative text for images to support screen readers, and high-contrast colours for improved readability, especially for users with colour vision deficiencies. These choices create an inclusive experience, enabling all users to engage easily with the Paddington Reservoir Gardens’ content.
![Alt text](<Markdown images/Accessibility 1.png>)

## Comparisons between Wireframe and Prototype
### First Design Iteration

When creating the prototype, I incorporated several adjustments based on both user feedback and design practices observed in other websites. For example, I added a scrollable gallery section to the homepage in response to User 2’s suggestion. This allows users to explore images of Paddington Reservoir Gardens, enhancing visual engagement and offering visitors a preview of the garden's atmosphere that may inspire them to visit.

In addition to the gallery, I introduced a footer containing quick links to other pages and social media channels for the garden. This enhancement improves navigation by providing users with easy access to essential sections and resources, thereby boosting overall usability and providing more ways for users to connect with the garden online.

![Alt text](<Markdown images/Iterations 1.png>)
![Alt text](<Markdown images/Iterations 2.png>)
![Alt text](<Markdown images/Iterations 3.png>)

Expanding on the navigation elements, I initially intended to implement a marker on the navbar to indicate which page the user is currently visiting. However I found it too challenging to execute effectively, so I decided against it.

Similarly, I aimed to create an expandable search bar that would enlarge and minimise when clicked. However, due to the complexities involved in its implementation, I ultimately decided to remove the entire search bar from the design.

![Alt text](<Markdown images/navbar 2.png>)
![Alt text](<Markdown images/navbar 1.png>)

Through this, I learned the importance of balancing ambitious features with technical feasibility. While these elements initially seemed great, their complexity made them difficult to implement effectively within the project's constraints. Ultimately, focusing on simpler, more impactful design changes allowed me to improve the user experience in other areas, reinforcing the need to prioritise features that align with both user needs and technical limitations.

For the map page, I added a section on nearby attractions based on user feedback from User 2. This enhancement provides users with more exploration options and encourages them to consider points of interest in the area. By including details about attractions near Paddington Reservoir Gardens, visitors can better plan their trips, enriching their experience and prompting them to spend more time nearby. This addition aligns with the goal of providing a comprehensive resource for users to maximise their visit.

![Alt text](<Markdown images/Iterations 4.png>)
![Alt text](<Markdown images/Iterations 5.png>)
![Alt text](<Markdown images/Iterations 6.png>)

For the events page, I adjusted the spacing between the title and the list of events from the wireframe to the prototype based on feedback from User 1, who suggested a tighter layout for improved readability. This change brings the title closer to the event descriptions, creating a more cohesive and visually connected presentation.

![Alt text](<Markdown images/Events 1.png>)
![Alt text](<Markdown images/Events 2.png>)

Finally, during the wireframing phase, I did not account for the narrower screen sizes of mobile devices, which resulted in tightly packed elements. In response, I addressed this issue in the prototype by arranging all elements in a vertical column. This adjustment allows for better spacing and significantly improves usability for mobile users.

![Alt text](<Markdown images/Iterations 7.png>)
![Alt text](<Markdown images/Responsiveness 2.png>)

### Second Design Iteration

My second design iteration consisted of refining the elements on my prototype based on the user feedback from testing. Things like contrast and interactive elements were considered to increase readability and create a more engaging experience, addressing usability concerns highlighted during testing to ensure the design better meets user needs.

During user testing with User 4, it was noted that the scroll-down button on the homepage had low contrast, making it difficult to spot. In response, I increased the button’s contrast by increasing the border size and the size of the arrow to improve visibility, ensuring that users can easily find it to navigate through the content. This adjustment enhances usability and aligns with the goal of creating a seamless user experience on the homepage.

![Alt text](<Markdown images/Iterations 8.png>)
![Alt text](<Markdown images/Iterations 9.png>)

This insight highlighted the importance of ensuring accessibility and visibility for key interactive elements, especially for users with different visual abilities. By adjusting the scroll-down button's contrast and size, I was able to make it more noticeable and intuitive to use. This change not only improved the user experience but also reinforced my understanding of how even small design elements, like a button, can significantly impact the overall usability of a site.


During user testing with User 3, it was suggested that the event titles on the events page should be clickable. To address this, I replaced the title's p (paragraph) tags with a (anchor link) tags, using the same links as the titles. Additionally, I added a hover effect that changes the title color to green, enhancing interactivity.

![Alt text](<Markdown images/Iterations 10.png>)

This highlighted the importance of making key elements interactive, which I hadn’t initially prioritised. This feedback made me realise that usability and interaction should be considered early in the design process, rather than as an afterthought. Going forward, I will focus more on making key elements interactive from the start.

It was noted during user testing that the nearby attractions on the website were not clickable yet. To improve the user experience, I made the nearby attractions clickable by converting the related images into anchor links. This change allows users to directly access more details about each nearby attraction, enhancing navigation and overall usability on the site. In the image bellow you can see the cursor showing that the image is a clickable link. 

![Alt text](<Markdown images/Iterations 11.png>)

Finally, to simplify the mobile view, I decided to remove the footer navigation links. Since the navigation menu is sticky, users can access it at any time, even at the bottom of the page. This reduces the need for footer links, which were crowded and difficult to click, enhancing the overall user experience.

![Alt text](<Markdown images/Footer 1.png>)
![Alt text](<Markdown images/Footer 2.png>)

## Issues and Next Steps 
While working on making the website responsive, I encountered an issue with the photo gallery in mobile view. Specifically, the gallery was designed to display two rows of three images, but when viewed on a smaller screen, it only shows one image at a time. As a result, users could only scroll through two images total, which limits their ability to view all six images in the gallery. This was due to the JavaScript implementation, which was only set up to accommodate the original layout. If I had more time, I would revisit the photo gallery's functionality sooner and test it on various screen sizes earlier in the process to avoid the issues with mobile layout that arose later. 

For next steps, I need to adjust the JavaScript for the gallery to enable the display of all six images individually in mobile view, improving user experience and responsiveness.

I would also like to conduct further user testing with participants who have a variety of accessibility needs to gain deeper insights into how well the site performs across different user experiences.  

## Reflection 
This project challenged my ability to create a user-friendly, responsive design that could scale across multiple devices. I learned a great deal about how to balance aesthetics with functionality, and how to make deliberate design decisions that prioritize accessibility and usability. I also recognised the importance of simplifying designs and making iterative adjustments based on feedback.

# References

GreatStack. (2023, March). How To Create Image Gallery In JavaScript | Horizontal Scrolling Using JavaScript. YouTube. https://youtu.be/gzXyRa7jwk4?si=xd9GWR_nak7cii6y

SA7MAN. (2022, November 11). Complete responsive website design using HTML CSS and JavaScript / Landing page design From Scratch. YouTube. https://youtu.be/BiehtJHToT8?si=126keYbpAIYqLPE2

Gordon, K. (2021, January 17). Visual Hierarchy in UX: Definition. Nielsen Norman Group. https://www.nngroup.com/articles/visual-hierarchy-ux-definition/

Dillon-Shallard, D. (2023, July 17). The Importance of Responsive Web Design | Butterfly. Butterfly. https://butterfly.com.au/blog/responsive-web-design/

### Images: 
JMD Design . (n.d.). Paddington Reservoir [Online Image]. https://jmddesign.com.au/projects/paddington-reservoir/

Nixon, R. (n.d.). The Garden of Maggie Victoria [Online Image]. In Head On Foundation. https://headon.org.au/exhibitions/the-garden-of-maggie-victoria

Stevens, T. (n.d.). We Were Just Little Boys [Online Image]. In Head On Foundation. https://headon.org.au/exhibitions/we-were-just-little-boys

Franks, T. (n.d.). The Second. [Online Image]. In Head On Foundation. https://headon.org.au/exhibitions/the-second

Hooper, M. (n.d.). My Son’s Skin is NOT a Weapon [Online Image]. In Head On Foundation. https://headon.org.au/exhibitions/my-sons-skin-is-not-a-weapon

Barbé, C. (n.d.). Ghana: pollution of the shortage, pollution of abundance [Online Image]. In Head On Foundation. https://headon.org.au/exhibitions/ghana-pollution-of-destitution-pollution-of-abundance

Cómo Ser Fotógrafa. (n.d.). EnEscena [Online Image]. In Head On Foundation. https://headon.org.au/exhibitions/enescena

Dalmulder, M. (2016). Sydney Cricket Ground just before the start of the fifth ODI between Australia and India. [Online Image]. In Wikipedia. https://en.wikipedia.org/wiki/Sydney_Cricket_Ground

Paddington Uniting Church. (n.d.). About Paddington Markets [Online Image]. In Paddington Markets. https://www.paddingtonmarkets.com.au/about

dunedoo. (2012). The Imperial Hotel, Paddington, Sydney, NSW [Online Image]. In Flickr. https://www.flickr.com/photos/29029178@N03/6989685391

Flicks. (n.d.). Palace Chauvel Cinema [Online Image]. In Flicks. https://www.flicks.com.au/cinema/palace-chauvel-cinema/




# Appendix
## Low fidelity User testing: 
### Transcript 1
Victoria:
Hello, my name is Victoria and I'm a current student studying interaction design at the University of Sydney.

Today, we’ll be testing a low-fidelity prototype of a website I’m developing for the Paddington Reservoir Gardens, aimed at tourism and travel. The goal of this session is to observe how you interact with the site, understand what works well, and identify any areas that may need improvement.

For your information, any data, recordings, or personal information collected will be handled with confidentiality. The feedback collected may be reviewed by myself and the teaching team to inform further development. Participation in this session is entirely voluntary.

Do you consent to proceed with the user test?

User 1:
Yes.

Victoria:
Great. Throughout the session, I’d like you to describe the steps you’re taking and share what you’re thinking as you navigate through the website.

User 1:
Okay, sure.

Victoria:
Alright, let’s begin. Please start by exploring the homepage.

User 1:
Okay, I’m looking at the homepage now. I see the headers here at the top — Home, About, Events, Map, and Visit Us. Overall, the page looks good.

Now I’m going to click on About the Garden.

Yeah, looks nice here too. I can see the main information about the garden.

Moving on to the Events page. I think the layout of the events section looks fine, but I noticed there’s a bit of a gap between the events text and the pictures. Maybe those could be moved up a little closer to avoid that gap.

Next, I’ll go to the Map page. Yes, I see the garden map here. That’s definitely convenient for users who need directions.

Finally, let’s check the Visit Us page. I can see the opening hours, directions, and a list of features. Here again, there’s a bit of a gap between the opening hours section and the features. It might look better if you closed that gap a bit.

But overall, I think everything looks good.

Victoria:
Thanks for the feedback. I’ll take a note of those spacing suggestions. Let’s switch now to the app version.

User 1:
Alright, so I’m back on the homepage on the app. Again, I can see the basic information, and there’s a section about the garden history.

I’d suggest moving the text slightly away from the image so they don’t overlap visually.

Now, let’s check the Events page. It looks good here too, clear and well-organised.

Moving to the Map page. I see you’ve added travel directions here. That’s great — it really adds to the user experience!

And then onto the Visit Us page. I can see the features section here, and I notice there’s a scroll bar to move up and down, which is useful for browsing.

So overall, I think it’s quite user-friendly.

Victoria:
That’s great to hear. How did you feel about navigating the website?

User 1:
It felt quite smooth and easy to navigate.

Victoria:
Did the purpose of the website come across clearly?

User 1:
Yes, definitely. It’s clear that the website is focused on providing information about Paddington Reservoir Gardens for visitors.

Victoria:
Were there any points where you felt unsure of what to do or where to go next?

User 1:
No, not really. Navigation felt straightforward throughout.

Victoria:
What are your thoughts on the website’s design? Did you find it appealing?

User 1:
Yes, it’s simple and clear. The layout is easy to follow, and the photos add a nice touch. They make the design feel inviting without cluttering the screen.

Victoria:
Do you have any other thoughts or suggestions you’d like to share?

User 1:
Just one — on the Events page, it might be worth adjusting the spacing, like moving the images a little closer to the header. But other than that, everything looks good to me.

Victoria:
Thank you for taking the time to participate in this test and for sharing your feedback. It’s been very helpful!

User 1:
Thank you! I’m glad I could help.

## Transcript 2

Victoria:
Hello, my name is Victoria, and I’m currently studying Interaction Design at the University of Sydney. Today we’ll be testing a low-fidelity website I’m developing for the Paddington Reservoir Gardens, aimed at tourism and travel.

The purpose of this session is to observe how you interact with the site, to find out what’s working well, and to identify any areas that might be confusing. Just so you know, any data, recordings, or personal information collected about you will be treated confidentially. I may use recordings and notes to review feedback with the teaching team. Your participation is completely voluntary. Do you consent to proceed with the test?

User 2:
Yes, I consent.

Victoria:
Alright, so as you go through the website, please describe each step you’re taking and share what you’re thinking as you navigate.

User 2:
Sure, let’s get started.

Victoria:
Please go ahead.

User 2:
Okay, I’m looking at the homepage now. I see a clear header here at the top—this lets me know what the website is about, which is nice. I can see options like Home, About, Event, Map, and Visit Us, so it’s clear what’s available on the site. Moving to the "About the Gardens" page...

Alright, here on the About section, there’s information about the history of the gardens and the reservoir itself. Everything’s easy to find.

Now going to the Events page… I think there’s a bit of a gap here between the events header and the pictures. Maybe that could be tightened up a bit, just to make it look more connected.

Next, let’s check out the Garden Map page. I see the map here, which is straightforward, but it does look a bit simple to me. Maybe adding nearby attractions could make this section more engaging. People might appreciate suggestions of places nearby to visit in one trip. Links and a few pictures could enhance this page as well.

And now, moving to the Visit Us page. There’s no scroll bar here—I think adding a scroll bar might help users move up and down more easily.

Okay, I’ll switch to the app version now.

User 2:
Alright, looking at the app homepage now. It’s clear and easy to navigate from here. Moving to About the Gardens… Yep, there’s a toolbar, and everything looks good on this page as well.

Going to the Events page… scrolling down here, I can see past events listed, along with the current ones at the top. That makes sense. The layout is straightforward, with current events at the top and past ones below. Good structure.

Next, checking the Map page again… as I mentioned earlier, it might be nice to add nearby attractions or events around the gardens. That could make the map more appealing and might draw in more visitors.

And finally, the Visit Us page. It has the opening hours. Is there contact information listed here? I was thinking it might be useful for visitors to have.

Victoria:
The garden itself doesn’t have specific contact details since it’s a public space.

User 2:
Oh, I see. Alright, that makes sense. So it’s just an open garden then.

Victoria:
Yes, that’s right.

User 2:
Got it, that’s helpful to know.

Victoria:
Alright, now we’ll move into a few follow-up questions. How did you feel about navigating the website?

User 2:
The navigation was very smooth and straightforward. It was easy to get around.

Victoria:
Was the purpose of the website clear to you?

User 2:
Yes, it was. Right from the homepage, it’s clear what the website is for. The About section provides a good background, and the Events section highlights activities happening at the gardens. The Map shows how to get there, so it’s all quite informative and useful.

Victoria:
Were there any parts where the information felt unclear?

User 2:
Maybe in the Events section. I feel like adding more events could make it more appealing—maybe including upcoming activities and some background on what visitors can expect. Since the garden itself isn’t large, adding extra details or other attractions could give visitors a reason to spend more time there. I think this could encourage repeat visits.

Victoria:
Do you have any other thoughts or suggestions?

User 2:
Yes, I think adding a gallery with more photos on the homepage would be a great idea. That way, people get a visual sense of the gardens right when they land on the page.

Victoria:
Thanks so much for that suggestion; I’ll definitely consider it.

User 2:
No problem!

Victoria:
Thank you for participating in this user test!

User 2:
Thank you for having me.

## High Fidelity User Testing 
### Transcript 3 

Victoria: Hello, my name is Victoria, and I am currently studying Interaction Design at the University of Sydney.

Today, we'll be testing a website I'm developing for Paddington Reservoir Gardens for tourism and travel. The goal is to see how you interact with it, find out what works well, and identify any confusing areas.

For your information, any data, recordings, or other personal information collected will be treated confidentially. We may use recordings and notes to review the feedback with the teaching team, and your participation is voluntary.

Do you consent to proceeding with the user test?

User 3: Yes, I do.

Victoria: Please describe the steps you're taking and tell me what you're thinking as you navigate the website.

User 3: First, I can see the hero section is really big and attractive. I think it's good, and as I scroll down, I see the nice can hover image slider. It provides a really good view and angle.

The footer is clear, with quick links to each page. Overall, I feel like it's good, but maybe the navigation bar could be a bit thicker compared to the hero section. It doesn’t affect my experience too much, though.

Victoria: Thank you for your insights.

User 3: I like that it clearly shows where I'm navigating. In the About section, I like the zigzag layout of images and text. It’s detailed and has a lot of information for people curious about the location and history. Maybe highlight some keywords to make it easier for those who don’t want to read everything.

Victoria: That's a good idea.

User 3: The quality of the images is great.

Victoria: I had to take them myself. Not all, but the green ones are mine.

User 3: So nice. Moving to the Events section, I like how each event is described, with the title being noticeable and attractive. Clicking on an event takes me to an external link, which works well. Clicking the image also leads to the event’s page, which is intuitive.

Victoria: Should I make the text clickable too?

User 3: Yes, people might be inclined to click the text. Also, maybe add a hover effect on images, like a slight zoom, to help guide the user’s focus. The "Upcoming Events" text could also be a bit larger.

Victoria: Good point.

User 3: The map section looks great. I recognize the same map link from tutorials. The nearby attractions feature is also a great addition.

Victoria: Yes, it's not clickable yet, but that’s a good suggestion.

User 3: In the Visit section, I like the layout, with icons for features. However, the “bus stop” icon is a bit unclear, making me wonder if it refers to transport or something else in the garden.

Victoria: Yes, it represents features in the garden.

User 3: Overall, I like the contrast and clarity of the site, with well-sized text. Navigation is clear, and everything is well-structured. Just minor adjustments for sizing and hover effects would help.

Victoria: Thank you for noting that about the events.
Would you like to check the responsiveness?

User 3: Sure. I think it looks good. Maybe if the images broke up the text blocks more, it could make reading easier. That way, it’s less overwhelming.

Victoria: That makes sense.

User 3: I see the navigation bar disappears on smaller screens. For me, it could maybe cover only part of the screen instead of the whole space, just for easier orientation.

Victoria: Good feedback.
The homepage gallery is clickable, but there are two images that aren’t, which I'll note in my justification.

User 3: Everything in the Events section is laid out well, and placing images at the top might improve readability. I think that’s it.

Victoria: Thank you for participating in my user test.

User 3: No worries.

### Transcript 4 


Victoria: Hello, my name is Victoria, and I'm currently studying Interaction Design at the University of Sydney.

Today, we'll be testing my website prototype that I'm developing for Paddington Reservoir Gardens, aimed at tourism and travel. The goal is to observe how you interact with it, identify what works well, and uncover any confusing aspects.

For your information, any data, recordings, or other personal information collected about you will be treated confidentially. We may use recordings and notes to review feedback between myself and the teaching team. Participation in this session is voluntary.

Do you consent to proceed with the user test?

User 4: Yes.

Victoria: Great, so please describe the steps you're taking and share your thoughts as you navigate through the website.

User 4: I'll start from the homepage. This is the homepage. Oh, is this the Aboriginal language? Bajuri Gamaruwa—does that refer to the reservoir?

Victoria: It means good day.

User 4: Great to learn something new. The homepage looks welcoming, with beautiful photos. Did you take them yourself?

Victoria: Yes I did.

User 4: Nice! The headers here are straightforward: Home, About, Events, Map, and Visit Us. There's also a navigation bar and a down arrow key. Clicking on it brings up a photo gallery. I see back-and-forth arrows here for more photos—beautiful shots.

Is it possible to make the down arrow key bigger or change the color?

Victoria: The white is higher contrast than other colors, but I can make it larger and thicker if that would help.

User 4: I almost missed it, so that might be helpful. Moving on, clicking the navigation bar brings me to the About page. I see information about the gardens with a nice green image, and a black-and-white photo for the history—echoing the historical feel. It’s clear, and the layout really works with the themes of the past and present.

Then, on the Events page, I see upcoming events with the date and descriptions. This is helpful for tourists who want to know about future events rather than past ones.

Now, the Map page has the location with nearby attractions. That’s a good idea since people might want other things to do nearby after visiting the gardens. There is some empty space here; not sure if you want to use it.

Victoria: I considered underlining the headers but felt it wasn't necessary.

User 4: That’s fair. Moving on to Visit Us—I see two levels, with a photo of the stairs. The features include bus stops, seating, and hours. There’s no train station, right?

Victoria: Right.

User 4: Got it. Maybe a small note that the upper level is animal-friendly would be nice?

Victoria: I could consider that.

User 4: Overall, I think it’s an excellent website. I can test it on the phone as well.

Victoria: Yes, thank you.

User 4: What does “M M” stand for?

Victoria: It’s the logo I designed.

User 4: It’s unique and cool! In the mobile version, all elements line up vertically for scrolling.

Would it help to use colors for the icons, like blue for the bus and green for the garden?

Victoria: I’ll think about it.

User 4: The hamburger menu opens the navigation list—Home, About, Events, Map, and Visit Us. It’s straightforward, and the same text appears as on the desktop. The Events page here also pops up with descriptions, dates, and details. The map page includes a clickable link for navigation.

In the Visit Us section, I see the features and the photo gallery, which was a nice touch on the homepage. Is this the same page I scrolled through at the beginning?

Victoria: Yes, you started on the Visit Us page because we inspected elements there first.

User 4: I see. 

Victoria: Now for some post-test questions:

How did you feel about navigating the website?

User 4: Very easy to navigate. It’s clear and straightforward.

Victoria: Was the purpose of the website clear?

User 4: Yes, because the homepage clearly introduces Paddington’s historical garden, and the hamburger menu gives easy access to important sections.

Victoria: What are your thoughts on the design? Was it appealing?

User 4: Definitely. The vibrant photos are attractive, and it’s easy to navigate. The design reflects the garden’s historical and touristic appeal.

Victoria: Were there any sections where information felt unclear?

User 4: Not really, though on the Visit Us page, it might help to add a line or two about things like pet-friendliness or no entry fee.

Victoria: Any other suggestions or thoughts?

User 4: No, I think you’ve covered almost everything.

Victoria: Thank you for participating in this user test.

User 4: Thank you for having me!