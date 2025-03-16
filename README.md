Responsive Web Design Project
This project is from the Responsive Web Design course by Kevin Powell on freeCodeCamp’s YouTube channel. I’ve learned a lot throughout the course, but here are some key things that really stood out to me—stuff I either didn’t know before or finally understood properly.

Key Takeaways
🎯 Making Images Responsive
Before this, I wasn’t sure how to make images truly responsive. Turns out, using max-width: 100% ensures the image scales properly without exceeding its container.

📏 em vs. rem — Finally Makes Sense!
I had heard of em and rem before but never really understood when to use them. Now I know that rem works well for font sizes, while em is useful for margin and padding. This approach makes layout adjustments much easier. However, the personal choice is totally depends on the situation and the user.

🖼️ Cropping Images Without Stretching
I learned that using object-fit: cover helps focus on the center of an image instead of stretching it awkwardly when adjusting width and height. It is just like cropping the image.

🔀 Flexbox order Property – A Better Way to Reorder Elements
At first, whenever I had to change the order of elements in a flex container, I used flex-direction: row-reverse or column-reverse, because that’s how I initially learned to do it. But when Kevin asked us to try rearranging elements ourselves, I instinctively reached for flex-direction instead of order.

Then I realized that using order is actually a cleaner way to reorder elements without modifying the HTML structure or affecting the entire flex direction. It allows for much more flexibility without messing up the natural flow of the layout. Now, I feel more in control when structuring my designs!

📱 Mobile-First Approach – Less CSS, Less Hassle
Thinking about the mobile layout first leads to writing less CSS and makes the design process much smoother.

Final Thoughts
Going through this course helped me understand responsive design in a much clearer way. Now, I feel more confident handling images, layouts, and flexible units in CSS.
