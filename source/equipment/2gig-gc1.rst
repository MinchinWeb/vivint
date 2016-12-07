2GIG GoControl 1
================

.. _2gig-gc1:

.. source: http://tridfx.com/wp-content/uploads/2016/03/2gig-cheat-sheet.pdf


Introduction
------------

.. note::

    The following is specifically for the 2Gig GoContol (aka the "GoControl One"), but may prove useful for the Vivint SkyPanel and the GoContol 3.


Features
--------

Programming Guide
-----------------

Q1. Wireless Zones
""""""""""""""""""

.. move table to an external file and use include-literal

Sensor Type
'''''''''''

=== =========================== ====================================================================================================================================================================================
1   Entry/Exit 1                Main doors. Gives an entry delay.
2   Entry/Exit 2                Secondary doors. Gives an entry delay, possibly different from Type 1. I often use these for garage overhead and basement doors.
3   Perimeter                   Windows and "window-like" (e.g. Glass breaks, doors that aren't typically used for entry and exit). Unlike Types 1 & 2, these sensors, when opened, set off the alarm without delay.
4   Interior Follower           Motion detectors, although I usually use Type 10 instead.
5   Trouble Day/Alarm Night     I've never actually used this...
6   24 Hour Silent              Similiar to the Duress Code.
7   24 Hour Audible             Similiar to the Police "panic" button.
8   24 hour Auxiliary           Flood and Freeze detectors. Has a series of sub-types to cover medical issues, general panics, freeze (low temperatue), water, etc; be sure to select the right one.
9   Fire                        Smoke Detectors. Doesn't require verification.
10  Interior with Delay         Motion Detectors. When set off, gives you a delay before setting off the alarm, similiar to Type 1.
14  Carbon Monoxide             \
16  Fire (with Verification)    "Firefighters". Used for a sensor that doesn't have the fire detection on-board, but relies to something else to detect the fire.
23  No Response                 Information-only sensors. Won't set off the alarm. Also useful as a temporary measure if a sensor is mis- behaving.
24  Silent Burglary             I've never used this.
25  Repeater                    For signal repeaters. Not available on GoControl; use *Type 8 -- Contact* instead.
=== =========================== ====================================================================================================================================================================================


Equipement Codes
''''''''''''''''

If the peice of equipment you're installing insn't listed, select *0000*,
and then on the next option enter the approriate 4 digit code.

.. note::

    This list is incomplete.

==== =======================================================================
0000 Other
\    \
0862 2GIG-DW10-345 Thin D/W (Surface) Contact
0863 2GIG-DW20-345 Recessed Door Contact
0869 2GIG-PIR-345 Motion With Pet Immunity
0864 2GIG-GB1-345 Glass Break Detector
0872 2GIG-SMKE1-345 Smoke Detector (USA)
0871 2GIG-SMK1-345C Smoke Detector (Canada)
0868 2GIG-PANIC1-345 Panic Button Remote
0860 2GIG-CO1-345 CO Detector (USA)
0859 2GIG-CO1-345C CO Detector (Canada)
0873 2GIG-TAKE-345 Takeover Module
0866 2GIG-KEY1-345 Keyfob
0867 2GIG-PAD1-345 Keypad
\	 \
1248 Vivint GB2 Glass Break Detector
1249 Vivint PIR2 Motion Detector
1250 Vivint SKEY2 Keyfob
1251 Vivint DW11 Thin D/W (Surface) Contact
1252 Vivint DW21R Recessed Door Contact
1253 Vivint Panic2 Panic Pendant
\    \
0637 Honeywell D/W "5816"
0470 Honeywell R-D/W "5818MNL"
0533 Honeywell PIR "5890"
0530 Honeywell PIR "5894PI"
0519 Honeywell Glass Break "5853"
0589 Honeywell Smoke "5008W3"
0557 Honeywell Heat Sensor "5809"
0624 Honeywell Flood Sensor "5821"
0491 Honeywell Panic Pendant "5802MN2"
==== =======================================================================


Voice Descirptions
''''''''''''''''''

.. note::

    This list is incomplete.

======= =====================
**002** **abort**
003     ac
004     access
005     alarm
006     and
007     announcement
008     area
009     arm
010     armed
011     arming
012     at
013     attic
014     audio
015     auto
016     automation
017     auxiliary
018     away
**019** **babys**
020     back
021     basement
022     bathroom
023     battery
024     bedroom
025     bonus
026     break
027     button
028     bypass
029     bypassed
**030** **cabinet**
031     cancel
032     carbon monoxide
033     cellar
034     cellular
035     cell radio
036     center
037     check
038     chest
039     childrens
040     chime
041     closet
042     code
043     communications
044     computer
045     control
046     cool
047     crawl
048     current
**049** **day**
050     degrees
051     den
052     detector
053     dim
054     dining
055     disarm
056     disarmed
057     dock
058     door
059     downstairs
060     driveway
**061** **east**
062     eight
063     eighteen
064     eighty
065     electric
066     eleven
067     emergency
068     enter
069     entrance
070     entry
071     error
072     exercise
073     exit
074     exit now
075     exterior
076     external
**077** **failure**
078     family
079     fan
080     fifteen
081     fifty
082     fire
083     fire alert
084     fire detector
085     first
086     five
087     flood
088     floor
089     fluid
090     foil
091     for
092     forty
093     four
094     fourteen
095     fourth
096     freeze
097     freezer
098     front
099     furnace
**100** **game**
101     garage
102     gas
103     glass
104     glassbreak
105     guest
106     gun
**107** **hall**
108     hallway
109     hanging
110     hang up
111     heat
112     high
113     home
114     house
**115** **ice**
116     inside
117     instant
118     interior
119     intrusion
120     is
**121** **key**
122     keyfob
123     keypad
124     kids
125     kitchen
**126** **laundry**
127     left
128     level
129     library
130     light
131     lights
132     liquor
133     living
134     loading
135     lock
136     loft
137     low
**138** **main**
139     maintenance
140     master
141     medical
142     medicine
143     menu
144     middle
145     monitor
146     motion
147     motion detector
148     mud
**149** **nine**
150     nineteen
151     ninety
152     north
153     not
154     not ready
155     no delay
156     no entry delay
157     nursery
**158** **off**
159     o#ce
160     on
161     one
162     one hundred
163     output
164     outside
**165** **panel**
166     panic
167     pantry
168     patio
169     perimeter
170     phone line
171     play
172     police
173     pool
174     pound
175     power
176     press
177     previous
178     pump
**179** **radio**
180     ready
181     rear
182     relay
183     remote
184     repeat
185     rf jam
186     right
187     room
**188** **safe**
189     second
190     security
191     sensor
192     sensors
193     session
194     set
195     seven
196     seventeen
197     seventy
198     shed
199     shop
200     side
201     silent
202     siren
203     six
204     sixteen
205     sixty
206     skylight
207     sliding
208     smoke
209     sounder
210     south
211     space
212     spare
213     stairs
214     star
215     status
216     stay
217     stop
218     storage
219     study
220     sump
221     supervision
**222** **system**
223     tamper
224     temperature
225     ten
226     terminated
227     thermostat
228     third
229     thirteen
230     thirty
231     three
232     to
233     tool
234     transmitted
235     transmitter
236     trouble
237     turn
238     twelve
239     twenty
240     two
**241** **unlock**
242     upper
243     upstairs
244     user
245     utility
**246** **valve**
247     voice
248     wall
**249** **water**
250     west
251     window
252     wireless
**253** **yard**
**254** **zero**
255     zone
======= =====================

Q2. Wired Zones
"""""""""""""""

There are two "ports" at attach wired sensors to the GoControl. In general,
they are programmed the same as wireless zones, except that their "normal
state" must be specified.

Normal State
''''''''''''

= ===============================
0 Not Used
1 Normally Closed
3 Normally Open
4 Mixed with no EOL (End of Line)
= ===============================

Q3. Keyfobs
"""""""""""

Emergency Key
'''''''''''''

= ==============
0 Disables
1 Auxiliary
2 Audible
3 Silent Panic
4 Fire
= ==============

Q4. Keypads
"""""""""""
