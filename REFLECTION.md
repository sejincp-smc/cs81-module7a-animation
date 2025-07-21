# REFLECTION.md

- What part of the code was most confusing and why?
  This line: "loader.textContent = frames[index % frames.length];"  
  At first, it was hard to understand how the modulo operator (%) worked with the index and frame array to create a loop. It took a moment to realize that this was cycling through the frames repeatedly in order.

- How does the animation help visualize asynchronous behavior?
  The animation is very intuitive, which makes it easy to explain even to people who speak different languages.

- What did you change or improve, and what effect did it have?
  I changed the background color when the loading completed. It’s a small change, but I think it shows a clear visual signal that the task is finished.
