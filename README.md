# Mochaboard
A keyboard. Just a keyboard...

I started designing the 'Mochaboard' (named after the best caffieneted drink) because I feel most keyboards now are full of unnescary features and don't achieve what a good keyboard is - allow for extremely fast typing. The mochaboard is purely a keyboard, nothing else. No screens, no knobs, just keys.


Project is extremely simple but sometimes it's the simplest things in life that just work... and that's what I'm looking for in a keyboard, something that works.

"The design of the keyboard was perfected like 20 years ago" - Some random person who goes to the same hackerspace as me, 2026

Now to go drink a mocha

<img width="1186" height="764" alt="MochaboardCase3" src="https://github.com/user-attachments/assets/53ab4df0-4f13-49af-aff6-e1523a6b80b0" />

<h2>Schematic!</h2><br><br>
<p>The schematic is quite simple with just a key matrix and the Pi Pico. This is good, simple is good.</p>

<img width="1034" height="415" alt="MochaboardSCH" src="https://github.com/user-attachments/assets/3eec7966-b8c5-45ff-9bd2-694c673a4770" />
<br><br>

<h2>PCB!</h2><br><br>
<p>The PCB is also simple with a very basic layout and a small silk-screen coffee cup. Sometimes you just have to purely focus on one feature (typing) and ignore or entirely leave out any bells and whistles. </p>

<img width="906" height="410" alt="MochaboardPCBFINAL" src="https://github.com/user-attachments/assets/816ca8e1-8e7c-459b-88f2-3753c1105fc2" />
<br><br>

<h2>Case!</h2><br><br>
<p>The case is simple. It is set up for sandwich mounting because of the simplicity of sandwich mounting. It has holes for all the keys, one for the Pico and and last one to show off the silkscreen.</p>

<img width="1071" height="459" alt="MochaboardCaseLonely" src="https://github.com/user-attachments/assets/aec742af-494d-46d0-b42f-2086e599254d" />
<br><br>

<h2>firmware...</h2><br><br>
<p>Firmware is probably my second-to-least favourite thing in the world, because of how complicated it is. Because of my smol brain I did enlist the help of some AI to assist in making the firmware. I attempted to make the QMK firmware as simple as possible and include all comments from the AI so if I do realise I need to change something I could atleast be looking in the right spot. It's all a learning experience I guess, maybe one day I'll enjoy doing this, just definitely not today</p><br><br>
<h2>BOM</h2>

| Reference | Qty | Value | DNP | Exclude from BOM | Exclude from Board | Footprint | Datasheet |
|---|---:|---|---|---|---|---|---|
| A1 | 1 | RaspberryPi_Pico |  |  |  | Module:RaspberryPi_Pico_Common_THT | https://datasheets.raspberrypi.com/pico/pico-datasheet.pdf |
| D1,D2,D3,D4,D5,D6,D7,D8,D9,D10,D11,D12,D13,D14,D15,D16,D17,D18,D19,D20,D21,D22,D23,D24,D25,D26,D27,D28,D29,D30,D31,D32,D33,D34,D35,D36,D37,D38,D39,D40,D41,D42,D43,D44,D45,D46,D47,D48,D49,D50,D51,D52,D53,D54,D55,D56,D57,D58,D59,D60,D61 | 61 | 1N4148 |  |  |  | Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal | https://assets.nexperia.com/documents/data-sheet/1N4148_1N4448.pdf |
| S1 | 1 | MX_stab |  |  |  | PCM_marbastlib-mx:STAB_MX_P_2u |  |
| S2,S3 | 2 | MX_stab |  |  |  | PCM_marbastlib-mx:STAB_MX_2.25u |  |
| S4 | 1 | MX_stab |  |  |  | PCM_marbastlib-mx:STAB_MX_2.75u |  |
| S5 | 1 | MX_stab |  |  |  | PCM_marbastlib-mx:STAB_MX_P_6.25u |  |
| SW1,SW2,SW3,SW4,SW5,SW6,SW7,SW8,SW9,SW10,SW11,SW12,SW13,SW14,SW15,SW16,SW17,SW18,SW19,SW20,SW21,SW22,SW23,SW24,SW25,SW26,SW27,SW28,SW29,SW30,SW31,SW32,SW33,SW34,SW35,SW36,SW37,SW38,SW39,SW40,SW41,SW42,SW43,SW44,SW45,SW46,SW47,SW48,SW49,SW50,SW51,SW52,SW53,SW54,SW55,SW56,SW57,SW58,SW59,SW60,SW61 | 61 | SW_Push |  |  |  | PCM_marbastlib-mx:SW_MX_1u |  |
