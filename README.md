# jigsaw_puzzle
A browser-based puzzle game controlled entirely by hand gestures via your webcam. Use both hands to frame a rectangle around anything on camera — the app captures it, splits it into 9 shuffled pieces, and challenges you to restore the image by pinching and dragging pieces back into place.
How it works in a nutshell:

You use your bare hands — no controllers, no clicks needed — to interact with the game through the camera. MediaPipe tracks your hand landmarks in real time, detecting when you pinch your fingers together.

Three stages:

Draw — Pinch both hands simultaneously and hold them at two opposite corners. The game draws a live rectangle between them. Hold steady for half a second and it captures whatever is framed inside — your face, a object, anything in view.
Puzzle — That captured image is sliced into a 3×3 grid of 9 pieces and shuffled. Pinch any piece and drag your hand to swap it into another slot. Correctly placed pieces glow green.
Win — Once all 9 pieces are back in the right place, the full image is revealed with a burst of confetti and a big bold rating based on how fast you solved it — PERFECT under a minute, SUPER under two and a half, FABULOUS for anything after that.

The key idea is that the camera feed never goes black — it stays live the whole time, so the puzzle pieces literally contain a frozen moment of your real world, while your hands keep moving in the background behind the board.
