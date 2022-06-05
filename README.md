# 100DaysOfCode - Round 2

Here are my [stated objectives](https://lenniecottrell.github.io/100DaysOfCode-Round-2/) for this round:

>  - Learn DS&A
>  - Learn how to solve leetcode questions
>  - Build small React projects with different free APIs
>  - Build sample CRUD apps

### Week 1 - May 29-June 4, 2022
<details>
  <summary>Day 7: June 4, 2022</summary>

  ###### Things I accomplished today:
    - learned about remove(), find(), and peek() methods in linked lists
  ###### Things I want to focus on tomorrow:
    - try to write out a linked list in javascript from memory and my notes without referencing the one I already wrote
    - set breakpoints on the grid
    - standardize the title/author text position
    - add a hover animation to the cards
    - add routes to the other pages and start building them
  ###### Notes/Learnings

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
