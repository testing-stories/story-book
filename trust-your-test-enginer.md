#Trust your test engineer

I believe forthcoming episode is quite common for test engineers.

Engineering manager (M) run to test engineer’s (T) office

M: Our customer has found blocker bug in our release. How on earth it is possible that you haven’t found this bug during earlier??

T: Actually, We reported same issue already 2 months ago as a blocker.

M: What?? Why it’s not fixed?

T: Management set the priority lower; they said that it cannot be blocker. So it’s set as major.

M: We need to deliver fix for customer ASAP! Is it fixed in our master branch?

T: Let me see; No, it’s not. We have test running in CI and test case seems to be red.

M: Who is working with fix? We need it in next release.

T: It’s not assigned yet. It’s not planned in next release content.

M: What? Raise the priority. We need someone to look the bug from development team, ASAP!!

T: No problem, will do


I strongly believe that good test engineer is more than writing bug reports and verifying fixed issues but have usually best understanding how to use system or service.

Quite often system test engineer is the first one to try out real end to end use cases. If reported issue is set as blocker by test engineer no matter if area is usability or functionality bug is usually ‘real’ blocker; and need to get fixed. Sooner the better.

Keep clear difference between severity and priority. In this case it would have been better to keep severity same all the time and just adjust priority by management.
