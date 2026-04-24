AI Prompt Log Template
Copy everything below this line into a file called ai-log.md in your project folder.

AI Prompt Log — My Personal Webpage
Student name:
Course: CSN150
Date:

How to use this log
Each time you use AI (GitHub Copilot, Claude, ChatGPT, or any other tool), add an entry below. Copy the template block and fill it in. You need at least 5 entries to receive full credit. Be honest — there are no wrong answers. The goal is to show your thinking process.

Entry 1
Tool used: GitHub Copilot inline chat
What I was trying to do: add my picture
Prompt I gave the AI:

I want to add my picture in the middle of the page

What the AI gave me:

Analyzing your answers...

Q: What is the path or filename of your picture? (e.g., 'myphoto.jpg' if in the same folder, or full path if elsewhere)
A: PabloC.jpg
Edited
index.html+2-2
I've added your picture (PabloC.jpg) to the center of the page. The image is now centered both horizontally and vertically using flexbox styling on the body element. If the image file isn't in the same directory as index.html, make sure to provide the correct path. You can open index.html in a browser to see the changes.

What I changed or decided:

Left it as is not much to change.

Entry 2
Tool used: GitHub Copilot inline chat
What I was trying to do: add my name
Prompt I gave the AI:

add my name Pablo Cuellar at the top of the page with bold letters, size letter 30 and a fun font

What the AI gave me:

Updating the page layout to include your name at the top with bold text and a fun font.

Edited
index.html+2-1
Your name has been added at the top in bold, 30px, and a fun cursive font (Comic Sans MS fallback included). The page now shows:

Pablo Cuellar as the heading
centered above the image
with spacing before the picture
Open index.html in the browser to verify the result. If you want a different font style or color, I can adjust it.

What I changed or decided:

 I changed the font size and style till I was happy with it

Entry 3
Tool used: GitHub Copilot inline chat
What I was trying to do: add the video and fix a bug not showing up
Prompt I gave the AI:

Looking at the website the video does not show, what could be the problem?

What the AI gave me:

The issue is that the .video-wrapper doesn't have a defined width. It needs one to display properly. Currently it has height: 0 and a percentage-based padding, but without a width, the video won't render.

I'll add width and max-width styling to the video wrapper:

Done! I added width: 100% and max-width: 560px to the .video-wrapper. This gives it proper dimensions so the video will display. Refresh your page and the video should now be visible below your picture.


What I changed or decided:

ketp it since that fixed the problem just changed the pixel width till I like it 

Entry 4
Tool used: GitHub Copilot inline chat
What I was trying to do: add the about me paragraph
Prompt I gave the AI:

how can I text after the video

What the AI gave me:

<!p style="font-size: 18px; margin: 50px 20px; color: white;">Welcome to my personal website where I share my passion and creativity with the world.</!p>

What I changed or decided:

played with the font size, color and style till i liked it.

Entry 5
Tool used: GitHub Copilot inline chat
What I was trying to do: making the paragraph align
Prompt I gave the AI:

what am typig is too long and taking almost all across the screen how can I force it to take a new line

What the AI gave me:

I've added max-width: 600px and text-align: center to your paragraph. This will keep the text centered and prevent it from stretching too wide across the screen—it will wrap to new lines as needed. If you want it even narrower or have specific line breaks, let me know!

What I changed or decided:

I changed the maxed width till I liked and aligend with the other elements on site