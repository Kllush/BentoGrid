# BentoGrid
Frontend Mentor Challenge, [**BentoGrid**](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj)

# Introduction

Last year, I spent about two months exploring HTML, CSS, and a bit of JavaScript. However, I dropped it and have been trying to get back into it ever since. This project will serve as my demo project—an opportunity to rebuild my skills and regain momentum. I've chosen a Bento grid layout because it's simple enough that I won't get stuck for too long, allowing me to focus on consistency and progress.

### Objectives

- Become proficient in GitHub and its commands.
- Learn how to set up projects and follow a proper workflow.
- Improve my understanding of HTML terminology.
- Prove to myself that I can start and finish a project independently.
- Set a clear deadline to avoid procrastination and stay accountable.

This project is my way of making sure I follow through and build a solid foundation for future web development work. 🚀

## Day 1

I successfully made a repo, cloned it, and committed changes. I also added a new SSH key. I still have a couple of things I need to polish regarding GitHub but, so far, it is good progress.

## Day 2

Since I've been working with a JPEG, some measurements are not accurate. I will recreate the file in Figma to better understand it and link it here. Aside from that, I managed to add the fonts and give some color to the page, It shouldn't take me long to position all the sentences correctly.

I still have some issues with GitHub, mostly that my commits apply to all the changes I've made.

### <ins>Done:</ins>
- 4.5 grids out of 8

### <ins>To Do after Figma + sentences:</ins>
- Work out the `@media` logic

## Day 3

I read the supporting documents of the challenge and there are a few issues, mostly with the font sizes (I've been eyeballing rems). The documents also mentioned using the provided JPGs. I'm not opposed to the idea, and I'm using most of the images they provided, but there are a few where the background is not transparent and the pixel dithering damages the quality. For those cases, I replicated the image in Adobe Illustrator (Ai from now on).

### <ins>Done:</ins>
- 8/8 grid elements
- Redid the fonts and colors
- Fixed the minor margin issues on the page
- Finished the Ai main template

### <ins>To Do:</ins>
- Create a tablet version of the page
- Transfer files from Ai to Figma
- Figure out the commits
- Work out the `@media` logic

## Day 4

Today I focused on the design part of the challenge, and barely did any HTML. I have the Ai file almost done and I made some minor changes to the HTML, basically just adding a hover style because it looked so plain and I was feeling guilty about spending my whole day just on Ai.

### <ins>Done:</ins>
- Ai Template 70% done
- Hover style for the elements

### <ins>To Do:</ins>
- Create the tablet version
- Expand singular elements of mobile version
- Transfer files from Ai to Figma
- Fix a typography issue, XM and M are basically the same
- Work out the `@media` logic

## Day 5

It was a half day, I was experimenting with `@media` and realized that instead of using pixels for the dimensions I should use a combination of rems and aspect ratio. I changed some dimensions which broke the website, therefore I'm not pushing today's changes~~,~~ I feel confident that I can finish soon.

### <ins>Done:</ins>
- Experimented with `@media`

### <ins>To Do:</ins>
- Create the tablet version (just scale it down)
- Expand singular elements of mobile version
- Transfer files from Ai to Figma
- Fix a typography issue, XM and M are basically the same.
- Work out the `@media` logic

## Day 6

I was researching more about media queries because I feel like the breaking points are something left for the developer to figure out independently. I decided to use only 4:
- Large Desktop: >1440px (16:9)
- Desktop: 1440x (16:9)
- Tablet: 1024px (16:9 Landscape-mode)
- Mobile: <600px (9:16)

Im also trying to make the dimensions as aspect:ratio instead of REMs or pixels, in that way I could scale the whole thing by just adjusting the main container size. I think I could do the same with REMs and just change the HTML font size but I will try that after I give up on percentages and aspect ratios.

### <ins>Done:</ins>
- Experimented with `@media`

### <ins>To Do:</ins>
- Create the tablet version (just scale it down)
- Expand singular elements of mobile version
- Transfer files from Ai to Figma
- Fix a typography issue, XM and M are basically the same.