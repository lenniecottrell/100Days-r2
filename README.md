# 100DaysOfCode - Round 2

Here are my [stated objectives](https://lenniecottrell.github.io/100DaysOfCode-Round-2/) for this round:

>  - Learn DS&A
>  - Learn how to solve leetcode questions
>  - Build small React projects with different free APIs
>  - Build sample CRUD apps

### Week 5 - June 27-July 3, 2022

<details>
  <summary>Day 33: July 3, 2022</summary>

  #### Things I accomplished today:
  #### Things I want to focus on tomorrow:
  #### Notes/Learnings

</details>
<details>
  <summary>Day 32: July 2, 2022</summary>

  #### Things I accomplished today:
  #### Things I want to focus on tomorrow:
  #### Notes/Learnings

</details>
<details>
  <summary>Day 31: July 1, 2022</summary>

  #### Things I accomplished today:
  #### Things I want to focus on tomorrow:
  #### Notes/Learnings

</details>
<details>
  <summary>Day 30: June 30, 2022</summary>

  #### Things I accomplished today:
  - I FINALLY REVERSED A LINKED LIST!!!! The problem before was that I wasn't resetting `current` back to the head on subsequent interations, so after the first removal the loop didn't run.
  #### Things I want to focus on tomorrow:
  - My parents are in town but I'm still gonna try to get up early to code. Back to the book app, where I'm stuck on another problem. Hopefully coming back to it with fresh eyes will be helpful
  #### Notes/Learnings
  - I want to write a blog post about this process! I made so many mistakes!

</details>
<details>
  <summary>Day 29: June 29, 2022</summary>

  #### Things I accomplished today:
  - I was able to fix my `removeLast` method enough so that I can successfully reverse a linked list with up to two elements. It doesn't work when I add a third element. WHYYYYYYYYY
  #### Things I want to focus on tomorrow:
  - Keep working on this problem. If I can't figure it out tomorrow I will ask for help, but I won't look up alternate solutions until I have solved it at least once by myself.
  #### Notes/Learnings
  - Progress is slow when you have a very limited time each day.

</details>
<details>
  <summary>Day 28: June 28, 2022</summary>
  
 I went to a wedding this past weekend so I took satuday and sunday off, and I just couldn't fit it in on monday, so I'm starting back up Tuesday. This upcoming weekend will also be weird because my aprents are in town - I will try to code in the mornings as usual but might not get to it every day.
 
  #### Things I accomplished today:
  - I'm still working on reversing a linked list - as I was debugging I learned that there were issues with my `removeLast` and `addFirst` methods. I think I successfully debugged and tested `addFirst` but I have more to do with `removeLast`. I'm getting closer though
  #### Things I want to focus on tomorrow:
  - Solve. This. Problem.
  #### Notes/Learnings
  - On leetcode the implementation will have to be different - right now I'm implementing methods as part of the LinkedList class, but I don't know if I can manipulate the class on leetcode. 

</details>

### Week 4 - June 19-June 25, 2022

<details>
  <summary>Day 27: June 24, 2022</summary>
  
  #### Things I accomplished today:
  - I reworked my implementation of the linked list and I got really close to figuring out the right syntax to reverse it, but I'm not quite there yet. I'm close though, and I'm confident that I can come up with my own (brute force) solution before I need to look up answers
  #### Things I want to focus on tomorrow:
  - Tomorrow I will be taking a break since I'm going to a wedding. Back to in on Sunday!
  - On sunday I will solve this problem!
  #### Notes/Learnings
  - I did the beginning of this process on paper, which allowed me to think through the problem fully before jumping in to actual code. Now that I'm just struggling with implementation, I think it's better that I'm able to test it in VScode.

</details>
<details>
  <summary>Day 26: June 23, 2022</summary>

  #### Things I accomplished today:
  - Back to the book app. I'm struggling with a problem that feels trivial, and all I accomplished today was more struggle
  #### Things I want to focus on tomorrow:
  - I try to balance time between working a project and DSA study, but it's hard to be patient with progress when you're stuck on a problem in both realms. I think I might try to go back to reversing a linked list tomorrow, and come back to this problem in my app once I solve that one.
  #### Notes/Learnings
  - Sometimes I feel like I really understand how to do this work, and sometimes I still feel like a dumb baby. I hope I can get a job as a developer even when there are still times I feel like a dumb baby. Is that the bar for getting a dev job? Not ever feeling like a dumb baby anymore?

</details>
<details>
  <summary>Day 25: June 22, 2022</summary>

  #### Things I accomplished today:
  - I started actually working on reversing a linked list. I have some pseudocode I think will work, I just need to do the hard part of actually implementing it
  #### Things I want to focus on tomorrow:
  - I'll keep working away at this problem.
  #### Notes/Learnings
  - I tried to modularize the implementation of a linked list and an addLast() method and got caught up in the npm requirements of modules, but when I was testing my implementation it was working and I only had to look up one thing
  - This will take me a little while, but I really want to figure this out before looking up an answer

</details>
<details>
  <summary>Day 24: June 21, 2022</summary>

  #### Things I accomplished today:
  - I was really tired today and had a busy day, so I didn't accomplish much, but I started thinking about how to reverse a linked list. With the time and mental space I have this week it will probably take me a few days to work out a test solution. 
  #### Things I want to focus on tomorrow:
  - I want to keep working on reversing a linked list
  - work on the card if I have time
  #### Notes/Learnings
  - Must. Not. Criticize. Myself. For. Being. Tired.

</details>
<details>
  <summary>Day 23: June 20, 2022</summary>

  #### Things I accomplished today:
  - I tried to refactor my list component with `map()` instead of creating an array with a for loop, but I ended up breaking it a lot more :(
  - On the upside, I submitted two PRs to my company codebase today, so that's pretty exciting, and I think should count towards this project
  #### Things I want to focus on tomorrow:
  - Keep working on the card grid state
  - Start a new linked list problem so I don't let it get stale
  #### Notes/Learnings
  - This is an annoying problem!!!

</details>

<details>
  <summary>Day 22: June 19, 2022</summary>

  #### Things I accomplished today:
  - I watched a new linked list video about the Iterable interface in Java. I'm not sure if I'll end up using the info from this video because I'm not using Java, but I'm sure that the concept is valuable, and it was the last video before getting into doubly linked lists and circular lists
  - I realized that moving my API call did not, in fact, solve my problem of selecting a specific card. I need to figure out how to set the state of the card grid with a "selected" card.
  #### Things I want to focus on tomorrow:
  - Keep working on the grid
  #### Notes/Learnings
  - This is my first major stumbling block on this project. I hate to be impeded by something that feels so fundamental to React, but I need to remind myself that I'm still learning, people have solved this problem before, and I'll figure it out eventually if I keep at it.

</details>

### Week 3 - June 12-June 18, 2022

<details>
  <summary>Day 21: June 18, 2022</summary>

  #### Things I accomplished today:
  - I realized I didn't know how to get book data into my book detail page, and started thinking I might need Redux for that. After reading a bit about Redux I realized I just needed to move my API call to the book grid component instead.
  - I'm actually not 100% sure this solves my problem, but I'm going to work on it for a while to see if I can make it work. Then I'll revisit redux if I can't.
  #### Things I want to focus on tomorrow:
  - Keep working on the book detail page
  #### Notes/Learnings
  - Reading about use cases for redux was helpful before I just dove right in. The idea that planning and preparation is a better approach than just jumping right into the code is sinking deeper and deeper into my awareness as I work on this.

</details>

<details>
  <summary>Day 20: June 17, 2022</summary>

  #### Things I accomplished today:
  - I built out the basic skeleton of the book detail page and added it as a modal on the main page
  #### Things I want to focus on tomorrow:
  - Keep styling the modal so it looks right and displays the right information
  #### Notes/Learnings
  - Getting that modal working was way trickier than I thought it would be!
  - Don't forget to put the right day in the commit message

</details>

<details>
  <summary>Day 19: June 16, 2022</summary>

  #### Things I accomplished today:
  - I worked through Leetcode 203 with a one pointer and two pointers today to really make sure I knew what was going on, and created a little visual helper for myself with sticky notes.
  - I designed and started building the skeleton for a book detail page in my book app
  #### Things I want to focus on tomorrow:
  - Build out the book detail page
  #### Notes/Learnings
  - My main app page is currently rendering twice on initial load - I gotta figure that out.
  - Things not to forget about: TDD, Redux

</details>

<details>
  <summary>Day 18: June 15, 2022</summary>

  #### Things I accomplished today:
  - I worked through Leetcode 203 again focusing on understanding each step
  #### Things I want to focus on tomorrow:
  - I'm going to keep working on LinkedList problems for now - I'll get to the book app this weekend
  #### Notes/Learnings
  - It's tedious to work the same problems multiple times, but if the focus is on understanding, I think it's still a good use of my time. I want a deep knowledge of these concepts, and since I'm not in school full time I need to be wrestling with them as much as possible during my limited time I have to study and practice.

</details>

<details>
  <summary>Day 17: June 14, 2022</summary>

  #### Things I accomplished today:
  - worked on leetcode #203
  - I wrestled with it for a while before looking at solutions - I'll need to do that for a while as I'm learning, and with limited time I'll have to be patient. However! When I looked at some solutions I was really close 
  #### Things I want to focus on tomorrow:
  - I want to work through this problem again to review
  - I'd really like to not leave the book app for more than a day or two - maybe I can find a time in the middle of the day?
  #### Notes/Learnings
  - Doing this with limited time is a littel frustrating. Things are going pretty well at work, but my progress with learning/building an app is extra slow since I limited time. I'm leaning in to development opportunities at work, but I'd still like to build out my portfolio and I'd still like to learn DS&A

</details>

<details>
  <summary>Day 16: June 13, 2022</summary>

  #### Things I accomplished today:
  - Reviewed some linked list implementation and started a new problem
  #### Things I want to focus on tomorrow:
  - work on that problem!
  - If I have time start working on the book detail page
  #### Notes/Learnings
  -I like learning

</details>

<details>
  <summary>Day 15: June 12, 2022</summary>

  #### Things I accomplished today:
  - I built out a login page with Formik and Chakra. Doesn't do anything yet but the basic page is built
  #### Things I want to focus on tomorrow:
  - Review Linked List videos and code
  - Look at a new Linked List Problem
  - Start building a book detail page
  #### Notes/Learnings

</details>


### Week 2 - June 5-June 11, 2022
<details>
  <summary>Day 14: June 11, 2022</summary>

  #### Things I accomplished today:
  - Finished leetcode 141, but had to look up the full solution
  - Decided to switch my account login from a modal to a separate page
  - Did more reading and gathered some more resources on user auth. Beginning to feel a bit like [yak shaving](https://xkcd.com/1739/) -> I need to create a form, okay I can do that with Chakra, but chakra recommends integrating with Formik, okay now I have to read about Formik, plus I have this walkthrough open that I should read to get an overview of the process, and does user auth require React's context API? I need to read about that too...
  #### Things I want to focus on tomorrow:
  - Revisit the linked list videos to keep it fresh, maybe start a new problem
  - Build out the account page
  #### Notes/Learnings
  - There was a trick to finding a linked list cycle that I didn't know where a pointer that moves by two and a pointer that moves by one will eventually meet up if there is a cycle. Seems straightforward and I wonder what other kinds of problems there are where I can use that concept
  - I looked a bit deeper into using google sign-in and I think it might be ambitious for now. I should focus on building out the rest of the app before adding user auth. 
  - Refocus: make a book details page, make a way to populate "my library"


</details>
<details>
  <summary>Day 13: June 10, 2022</summary>

  #### Things I accomplished today:
  - I looked at LeetCode #237 on linked lists. I reviewed a couple of solutions after thinking about it for a while and made sure I understood the solutions before moving on.
  - Started working on LeetCode #141 also. I got close! my initial attempt passed some of the test cases but didn't pass submission. I'll take one more crack at it before looking up solutions.
  #### Things I want to focus on tomorrow:
  - finish this problem
  - keep reading about user auth
  #### Notes/Learnings
  - I'm very proud of myself for beginning to tackle leetcode questions, and actually starting to feel like I understand the basics of DS&A


</details>
<details>
  <summary>Day 12: June 9, 2022</summary>

  #### Things I accomplished today:
  - I finished building the "My Library" page when its blank - I think I need to implement user authentication before I can populate shelves? Maybe not....
  - Cleaned up some components
  - Started studying how another dev implemented user auth on a simple to do app (he used Redux)
  #### Things I want to focus on tomorrow:
  - I want to keep working on this, but I also want to keep picking away at linked lists. I'm gonna do some review and maybe look at a problem
  - If I have more time I'll keep studying how to do user authentication
  #### Notes/Learnings
  - I am feeling very confident with my CSS/Fundamental React skills. I obviously have a ton to learn still, but it's time to start challenging myself to get outside my comfort zone.
  - Adding user auth will definitely be a challenge!
  - Add redux to this app would also be a very useful challenge


</details>
<details>
  <summary>Day 11: June 8, 2022</summary>

  #### Things I accomplished today:
  - Today I made some design decions about UI/UX and started implementing them in my book app
  - "My Library" will be its own page with tabs for different shelves
  - Account login is a modal box for now
  #### Things I want to focus on tomorrow:
  - finish building the "My Library" page
  - study how to add authentication
  #### Notes/Learnings
  - I can't stress enough how important and valuable it is to plan before starting to code. Let this be a lesson I drive deep into my brain.


</details>
<details>
  <summary>Day 10: June 7, 2022</summary>

  #### Things I accomplished today:
  - did some planning for the next pages of my book app
  - Built out the about page
  - Researched some components I want to use for the account page and book detail page
  #### Things I want to focus on tomorrow:
  - Build the account page and book detail page
  - Connect the routes to the new pages
  #### Notes/Learnings
  - Design choices are hard! There are many different ways a design could go, and planning definitely helps but it's hard to know if you're picking a good UI/UX until you actually start using the thing I think.


</details>
<details>
  <summary>Day 9: June 6, 2022</summary>

  #### Things I accomplished today:
  - attempted to implement a linked list from memory
  - reviewed some of the linked list videos as a refresher
  #### Things I want to focus on tomorrow:
  - don't lose steam on the book app - do some planning
  #### Notes/Learnings
  - false confidence when you're learning is super real. 
  - The concept of a linked list isn't hard to understand, but remembering how to implement it in code is more difficult than I expected
  - Practice more. Maybe look at some problems and solutions to get more context on how to use a linked list?

</details>
<details>
  <summary>Day 8: June 5, 2022</summary>

  #### Things I accomplished today:
  * standardized the card size and position of the images/text on the cards
  * used a SimpleGrid instead of normal Grid in ChakraUI to make easy breakpoints for the grid
  * added a small hover animation to the cards and a fade in for when they load
  * I started making my routes, and I realized I have more planning to do to figure out what the other pages will look like
  #### Things I want to focus on tomorrow:
  - Start with reviewing what I know about linked lists
  - Introduce the next problem in Cracking the Coding Interview
  - Work on the plan for the additional pages in my book app
  #### Notes/Learnings
  - Working in support has made using documentation way easier. Since I reference our own docs and KB at work, I'm used to the language and how it applies Also, since I just know more about code now, implementing things with the docs makes more sense.

</details>



### Week 1 - May 29-June 4, 2022
<details>
  <summary>Day 7: June 4, 2022</summary>

  ###### Things I accomplished today:
    - learned about remove(), find(), and peek() methods in linked lists
    - populated my book cards with titles, authors, and images
  ###### Things I want to focus on tomorrow:
    - try to write out a linked list in javascript from memory and my notes without referencing the one I already wrote
    - make a working branch on the book app so I don't accidentally ruin the good work I've done :)
    - set breakpoints on the grid
    - standardize the title/author text position
    - add a hover animation to the cards
    - add routes to the other pages and start building them
  ###### Notes/Learnings
    - other future to-dos include publishing to github pages, adding authentication
    - I had to deal with what happens when there are no image links, so that was a interesting edge case to have to work around. It wasn't too tricky, but I didn't expect it

</details>

<details>
  <summary>Day 6: June 3, 2022</summary>

  ###### Things I accomplished today:
    - I solved the first problem in Cracking the Coding Interview with a brute force method and O(n^2) time. I looked up other more efficient solutions - time to learn about hash tables!
    - I learned how to implement a queue in Javascript
    - I got to spend some hours building my book app UI with ChakraUI and the google books API. It was good practice to fetch API data and display it with useEffect(). I have a kind of clunky solution at the moment, I'll go back and refactor after I clean up the UI a little bit
  ###### Things I want to focus on tomorrow:
    - clean the UI so the cards are all the same size
    - consider a different way to display the book data
    - watch another linked list video
  ###### Notes/Learnings
    - I learned a lot about Chakra UI today, and hot damn using a component library really speeds things up. I don't regret all the time I've spent struggling with CSS, but I'm grateful for a component library that can speed up UI development. 
</details>

<details>
  <summary>Day 5: June 2, 2022</summary>

  ###### Things I accomplished today:
    - Researched UI libraries a bit more and devcided to change to ChakraUI, started learning about it
    - Started building my component skeleton
    - Watched 2 more Linked List videos about removeFirst() and removeLast()
    - I started working on the first problem from Cracking the Coding Interview. It's a type of question I've seen before, I just need to remember how to do it.
  ###### Things I want to focus on tomorrow:
    - I want to start building the UI at least, if not start to import some data
    - finish this algo problem
  ###### Notes/Learnings
    - I actually think data structures are super interesting. The videos I'm watching explain everything very clearly and make it seem way easier than I'm sure it is in reality, so I'm excited to start actually applying this stuff to problems.
</details>

<details>
  <summary>Day 4: June 1, 2022</summary>

  ###### Things I accomplished today:
    - I started planning the UI for the book app and made a list of the tools I plan to use
  ###### Things I want to focus on tomorrow:
    - Another couple of linked list vids
    - Review the linked list implementation in Javascript
  ###### Notes/Learnings
    - Planning before coding is good and helpful!
</details>

<details>
  <summary>Day 3: May 31, 2022</summary>

  ###### Things I accomplished today:
    - watched some videos about adding to the beginning or adding to the ending of an array
    - I started reviewing the Google Books API docs
    - I started reading Cracking the Coding Interview to get an idea of what's ahead.
  ###### Things I want to focus on tomorrow:
    - start sketching out my plans for a personal library app - what are all the parts and pieces, what does the UI look like?
  ###### Notes/Learnings
    - I was reminded today as I dove in the deep end of the google books API how much better off I'll be if I spend some time planning before jumping into the code. A solid plan will give me the mental framework and conceptual skeleton I need to be more efficient when I actually start diving in
</details>

<details>
  <summary>Day 2: May 30, 2022</summary>

  ###### Things I accomplished today:
    - I learned about considering boundary conditions in data structures, and adding an element to the beginning of a linked list
    - Reviewed some of the basic of BigO notation
    - I initialized a new app for organizing books using the google boks API
  ###### Things I want to focus on tomorrow:
    - more linked list videos
    - dig deeper into the google books API and start building an app
  ###### Notes/Learnings
    - the 5 boundary conditions for data structures should be considered regardless of the type od structure:
      - what to do if it's empty
      - what to do if there's a single element
      - how to add/remove from the beginning
      - how to add/remove from the end
      - working in the middle
</details>

<details>
  <summary>Day 1: May 29, 2022</summary>

  ###### Things I accomplished today:
    - I started learning about linked lists
    - I wrote some code to define a linked list in javascript
  ###### Things I want to focus on tomorrow:
    - Watch the next lectures on linked lists from SDSU
    - Start looking at leetcode?
  ###### Notes/Learnings:
    - Each node in a lists contains a pointer and data
    - List are always complexity O(n) (technically Theta(n)), because each item always needs to be counted and the time it takes to count them increases linearly with the number of items
    - The nodes in a linked list are stored in separate objects that contain pointers to the next objects in the list. This is different from an array, where elements are stored in contiguous memory locations (each location being an increment of 4 bytes)
    - Search operations are slow because nodes are accessed sequentially
    - Uses more memory than arrays because of the pointers
    - Nodes can be more easily manipulated than arrays
</details>
