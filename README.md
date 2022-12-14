# bi101-portfolio
This is my first completed project, a static site that I used for my Biology final. The purpose of this site was to satisify the final portfolio requirement of the class, but also to gain experience in web development and create a finished product for my tech portfolio as well. 

## Frameworks used:
**Jekyll**,
**Swiper.js**,

## Features
- Swiping through slides can be done with the mouse, keyboard, dragging, or finger if on mobile. 
- Dynamic buttons that jump through different sections of the slides, and update with Javascript as the slides change
- Navigation buttons that appear at the first slide and the last slide of each section
- Dynamic information cards that provide a learning outcome for each slide.
- Responsive design that supports multiple screen sizes

## Lessons learned
- Initial experience with Jekyll
- Introduction to GitHub pages and GitHub actions
- CSS media queries and responsive design
- I deleted some very important items with git rm -rf before the first commit. Fortunately, I was able to recover them by doing the following:
  ```bash
  git prune -n
  ```
  This generated a very long list of item ids that were deleted, but still in memory, waiting to be overwritten. 
  I took each item id one by one and used the following command to recover the file:
  ```bash
  git cat-file -p <item-d> <restored item name>
  ```
  
  The big lesson here is, **commit early**, **commit often**, and **don't blindly use git commands without checking what they do first.**

## Things I could do better next time
- Although knowing how to manipulate the page with Javascript is really useful, I noticed that the more dynamic usage I needed, the more "hacky" the solutions became. Although I got a working product, I had to jump through hoops to piece together the front end logic. If I had to built it again, I would use React.
- Have the option to collapse the sidebar
- Consider accessibility
