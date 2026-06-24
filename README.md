# Hollow-Knight-Pinball
Hollow Knight Pinball - Custom Pinball Machine

For stardance (if your not here for stardance just ignore this) I am submitting my playfield CAD which is in "CAD Files" it is done and is currently being produced

<img width="701" height="447" alt="Screenshot 2026-06-24 at 7 18 13 AM" src="https://github.com/user-attachments/assets/dbb1ed91-87fd-4b12-b3e5-cf3be65db2d3" />

The Demo Link is: https://cad.onshape.com/documents/46a9741959470dc46e7c739c/w/06598aae82bc74cde6aa571a/e/faa4b0390295b76dec385a50?renderMode=0&uiState=6a3bd65cf6d661f4c8947f64

Quickstart:
The onshape link should work right out of the box if you just want to look. 

If you are looking to produce your own playfield you can either download it from the onshape link or use the .step in the repository under "CAD Files" it is named "Hollow_Knight_Pinball_Playfield.step" you will need access to a CNC machine obviously to produce it (use 1/2 inch plywood 9+ plies ideally make sure it is very flat). In terms of settings you want a small ish bit the smallest hole on the playfield is 0.125 inches or 1/8th so it has to be smaller than that however some of the other parts have fine details so you might want to use something even smaller at least for those although it would probably work with a 1/8th bit. Keep the depth of your cut under half your bit diameter and run at 16-18000 RPMs. I highly recommend doing some tests before trying to cut the whole large piece.

Features
- Holes for posts and ball guide for playfield geometry (the path of the ball)
- Holes for mechs such as pop bumpers, slingshots, ball troughs, targets, etc
- Curved cuts for the shooter lane exit to have a smooth transition onto the playfield and to have better contact from the plunger and keep the ball going straight
- Holes for general illumination lighting
- Holes for inserts (clear pieces of plastic that are lit underneath) with a ledge at the correct height for easier setting

How it works
Most of the sketches are drawn on a plane that is set to be at the top of the playfield, I then use an extrude remove to remove as much material down as I need to (typically all the way through the playfield). For complicated shapes I made templates which could be helpful if you wanted to make your own machine (that isn't the same layout as mine). Here are some photos of the templates for the inserts and for the 1 inch circular target cutout.

<img width="292" height="527" alt="Screenshot 2026-06-09 at 10 05 55 PM" src="https://github.com/user-attachments/assets/e158f7ff-359b-4d36-943b-41bfb2690e64" />
<img width="255" height="158" alt="Screenshot 2026-06-21 at 9 42 10 AM" src="https://github.com/user-attachments/assets/39def6bc-4ca9-456b-9dca-632423804dff" />

Other than that there was obviously a lot of measuring to convert my physical first draft into the CAD so that it could be machined and much neater. The only other thing I want to talk about is the indent in the shooter lane because I think it's kind of cool and was quite a challenge. 

<img width="479" height="380" alt="Screenshot 2026-06-24 at 7 55 51 AM" src="https://github.com/user-attachments/assets/1582a68d-56df-41d9-83f6-2a61b5ad2a7d" />

^ is what I am talking about. First off I'm sure there are better ways to do this but what other people ultimately helped me figure out is that I could draw a v shape on a plane tilted just a couple of degrees and then I could do a remove extrude out of both sides of that to get the general shape. Then I just used some other tools to round the edges to help it function better but more importantly to reduce damage over time from the ball.

Credits
My friends and also the custom pinball community were both incredibly helpful and I can't even count the number of stupid questions they answered for me about how to do the most basic things.

AI Disclaimer: I used AI to help me figure out what tools to use since I'm new to CAD and too help with a little bit of math to figure out the radius of the rounded corners. AI did not do any of the modeling.
