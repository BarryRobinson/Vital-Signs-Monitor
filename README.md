# Vital-Signs-Monitor
A virtual Vital Signs Monitor that runs in a web browser and can be controlled remotely via a peer-to-peer connection.

Trying to use screen sharing with our existing screen-based vitals monitors didn’t seem to work very well. I have developed a web-based, virtual Vitals Monitor for simulations with SPs/mannequins that use web conferencing software (Microsoft Teams, Zoom, Blackboard Collaborate). Try it out and let me know what you think.

•	Web-based: operates in any browser, very easy to use. Does not require downloading or installing any special software. Does not require admin privileges. Works with all collaboration software since it runs on its own in its own browser window.
•	Lightweight: uses peer-to-peer communication (not through a server), minimal web traffic. See https://peerjs.com/  for details.
•	Learner actions are time-stamped and logged in the Control Window for debriefing. The simulationist or the simulation operations specialist can add time-stamped comments as needed.
•	Realistic: Learner operates the Vitals Monitor just like the real thing. Buttons are used to activate the various functions. When using the blood pressure function, the learner will hear the pump inflate the cuff and see the pressure go up, then drop at the standard rate (2mmHg/sec). Both blood pressure and MAP are displayed.
•	Vital signs can be changed on-the-fly and can trend (change) over time. Vitals can be updated based on learner interventions.
•	Vital signs monitor can be minimized or positioned where convenient on the learner’s screen. It can even be run on a separate device such as an iPad.
•	Can use preprogrammed scenarios. The simulationist or the simulation operations specialist can preprogram sets of vitals in small text files that can be instantly sent to the monitor. The preprogrammed vitals can be tweaked, if necessary, before being sent. Start value, end value, delay and trend values can be loaded and sent.
•	Free. No charge.
This is now fully functional and ready for beta testing. Tested on Firefox, Chrome, Safari, and Edge. I plan to finish the ECG display, which is currently disabled, as time permits. 
