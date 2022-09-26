# DepthTouchSensing Dataset
Reducing the Latency of Touch Tracking on Ad-hoc Surfaces

## Paper abstract: 
Touch sensing on ad-hoc surfaces has the potential to transform everyday surfaces in the environment - desks, tables and walls - into
tactile, touch-interactive surfaces, creating large, comfortable interactive spaces without the cost of large touch sensors. Depth sensors
are a promising way to provide touch sensing on arbitrary surfaces, but past systems have suffered from high latency and poor touch
detection accuracy. We apply a novel state machine-based approach to analyzing touch events, combined with a machine-learning
approach to predictively classify touch events from depth data with lower latency and higher touch accuracy than previous approaches.
Our system can reduce end-to-end touch latency to under 70ms, comparable to conventional capacitive touchscreens. Additionally, we
open-source our dataset of over 30,000 touch events recorded in depth, infrared and RGB for the benefit of future researchers.

link: TODO!!!

## Data description:
19 users' screen touching data are collected. 
User 1-3 are pilot studies. User 4-19 (16 users) are used for our paper. Each folder named from 01 to 19 corresponding to the data of one user.
Each participant was paid $15 for an 80 minute long session. 
Participant skin colours ranged from Type I to Type V on the Fitzpatrick scale [8] (I: 3; II: 5; III: 4; IV: 3; V: 1). 

They were randomly assigned to 4 balanced groups (4 people per group). The camera was set up at a different height and angle for each group. 
Within each group, the iPad is set up at a different location for each participant, to cover a larger touch area. 
All the participants were asked to do the same task during the study. The data was collected in a room with constant indoor artificial light condition (about 200 lux).

Each participant recorded 6 sessions. Since tapping is the most common touch interaction, 4 sessions were designed to collect tapping data. (session 1,3,4,6)
Each tapping session is broken into 4 subsections. This can be seen from the name of the videos (X_Y, X corresponding to the session number and Y corresponding to the subsections)
In these 16 subsections, 3 tapping conditions are explored: different tapping speed (participants are asked to follow a metronome played at 80 vs. 120 taps per minute),
different finger lifting distance (1-2 vs. 7-8 cm), and different angle between finger and surface (30 vs. 60 degrees).
For the finger lifting distance and finger angle, participants are given a chance to practice before the data collection.
The tapping conditions are constantly monitored by the researcher. A reminder would be given to the participants
when the condition is not met. Each condition has two levels, and each combination of conditions is recorded twice
(2 × 2 × 2 × 2 = 16). In total, each participant collected on average 2400 taps. 

The remaining two sessions recorded dragging and multi-touch interactions. In the dragging session, participants were asked to draw lines in different
directions. In the multi-touch session, participants were asked to perform different multi-touch gestures including pinches and multi-finger taps. 
The dragging (session 2) and multi-touch (session 5) sessions are inserted between the tapping sessions, as
sessions 2 and 5 respectively, to break the tapping pattern and reduce monotony. Dragging and multi-touch data were
collected and provided for future research, but were not used in this project.
1_1 in user 10 got accidentially overwritten due to a technical error. 
