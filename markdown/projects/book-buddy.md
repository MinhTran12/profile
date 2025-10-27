# Book Buddy

Book Buddy is a tree-shaped smart bookmark created to enhance the users' reading experience through tracking reading goals and connecting fellow readers.

The project followed an user-centered design approach using the Triple Design Diamond method. The core idea of the framework is to split the design process into workable phases while enabling diverging thoughts and ideas at the beginning of each step before convergence.

<!-- I participated in all phases of the project, though a lot of my efforts went into prototyping, programming, and user testing. -->

## Discovery and Defining

The theme of the project was to design an **"enchanting everyday object"**. In my mind, that meant to transform something mundane into a majestic item.

We first began by concept mapping to come up with potential ideas between the team members. Then we synthesized the gathered ideas into interesting combinations before we rated them based on feasibility, novelty, and "enchantedness".

Choosing the bookmark as our core object, we then created various items such as user personas and story boards to explore the user needs while further narrowing down the main functionalities.

<div class="double-img">
    <img src="images/book-buddy/design-ideas-eval.jpg">
    <img src="images/book-buddy/User Persona - Paige Anouar.png">
</div>

## Prototyping and Development

With the design semi-refined, we proceeded with prototyping. The team began with low fidelity prototyping, where we were most concerned about how the bookmark should look and function.

A touchscreen was proposed for displaying information, but the team favored a more **nature-themed aesthetic**. This led us to designing a tree-shaped bookmark with the following features:

- **LED Tracking Lights:** Track the user's reading goals and active reading friends using the LED lights.
- **Book Reading Sensors:** Detect when the book is open or closed based on the light level, and provide haptic feedback to let users know when their friends open their books.
- **Application and Social Connectivity:** A mobile application connected to the device using bluetooth for personalization, setting goals, and managing books and friend contacts.

<div class="double-img">
    <img src="images/book-buddy/bookmark-designs.jpg">
    <img src="images/book-buddy/app-lowfi-1.jpg">
</div>

<div class="single-img">
    <img src="images/book-buddy/bookmark-lowfi-1.jpg" style="width:50%; height:auto;">
</div>

\
I personally consider the reading sensor to be the most ambitious feature, as there’s no straightforward solution. The approach I came up with and implemented in the end was to place **a light sensor by the top of the bendable bookmark**: when the bookmark is inside the book, the low light level indicates the book is closed, and when the light level rises (as the bookmark is out of the book), it suggests the book is open.

<div class="triple-img">
    <img src="images\book-buddy\IMG_4838.jpg">
    <img src="images\book-buddy\IMG_4833.jpg">
    <img src="images\book-buddy\IMG_4836.jpg">
</div>

\
For the high-fidelity prototype, the team members and I assembled the electronic components and 3D printed parts. In addition, I programmed the behavior of the bookmark as well as the companion application. Given the feedback from the volunteers on the low-fi prototype and due to various compromises made during the construction, the final result looked visually different yet still retained the core functionalities.

<div class="triple-img">
    <img src="images/book-buddy/bookmark-highfi-1.jpg" alt="bookmark high-fidelity 1">
    <img src="images/book-buddy/bookmark-highfi-2.jpg" alt="bookmark high-fidelity 2">
    <img src="images/book-buddy/web-app-1.png" alt="web app screenshot" style="width:20%; height:auto;">
</div>

## Validation

Two main user studies were done at different stages:

1. We first conducted a vignette study using the low-fi prototype along with crafted scenarios, user personas, and storyboards mentioned previously to evaluate the prototype's effectiveness as well as gather users' early feedback.
2. For the second study, participants were observed interacting with Book Buddy, and then were interviewed to understand their thought processes. We found avid readers appreciated the social aspect and the enchantment of bookmark, while new readers saw the goal tracking feature to be motivating.

<!-- ## Reflection

The Book Buddy project let me apply theory into practice, one of which is to translate ideations and initial research findings into actionable decisions as shown in the conception and refinement of the team's product. I also learned to design and develop physical products in contrast to my experiences working with software.

The most impactful lesson for me is during the ideation/prototyping phase, where I learned that my smart screen idea for a bookmark did not appeal to the testers in the context of "enchantment". I had really liked the idea and thought that the potential users would agree, so what happened was a real humbling experience, teaching me that my design expectation and that of the users can be very different. -->
