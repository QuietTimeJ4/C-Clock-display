# C-Clock-display
A program that can incrementally increase time and display it in both military and ordinary time.

I did well at planning and designing the value clean-up. After any changes to the time, I would need to change the value of seconds, minutes, and hours to match the relationship as the actual time measurements. For example, if the user increases minutes by 70, the clean-up step would add 1 to hours and subtract 60 from minutes.

A possible improvement to the code is verifying the input from the user, so they would not create errors. If I wanted to expand the code, I could create a GUI and have the clock add a second every second to mimic a real clock.

Planning and creating the value clean-up was the most challenging part of the code due to its complexity. Though having to puzzle out through planning and brainstorming was a valuable lesson. I believe I will use that skill on future projects when complexity stumps me.

Since I put most of the code in functions, I can just copy and paste the functions into other projects without completely redesigning the code. The code is broken up into multiple functions for readability, test purposes, and maintenance.
