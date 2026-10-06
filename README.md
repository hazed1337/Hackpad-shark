This is my Hack pad that I made for the hack club Stardance challenge.
It a 3x3 pad with a matrix layout. The case is just a is a normal clean looking case but I added a few elements to it like smoothed edges and I drew out a silly looking shark. I originaly was gonna go for a light design with minimal case but for longevity I chose make a full case and add my little logo of the shark.

<img width="179" height="153" alt="Screenshot 2026-10-07 at 9 30 21 am" src="https://github.com/user-attachments/assets/173937a7-1947-4be7-8858-ae9463e8316a" />

This is my full case it a dimensions are quite weird because of the size of my PCB it 88.5 x 71.5 on the inside which allows me to fit my PCBwith 2.5 mills of tollerance for when it gets 3d printed.The walls are 10 mills thick and the top plate is 3. to get the curves i filleted the conners 5 mills inwards and I think that looked great

<img width="618" height="557" alt="Screenshot 2026-10-07 at 9 36 17 am" src="https://github.com/user-attachments/assets/64dd0d36-35f8-4426-9501-0b25a8d3082e" />

My PCB I created has 9 keys in a 3x3 layout. I wired them in a matrix and connected columns 0, 1 and 2 to pins 8, 9, 10 and rows 0, 1 and 2 to 2, 3, 4. I wired the SK6912MINI-E into the VSS to the ground the din to pin one and the VDD to the pin 14 being the 5v power. You can see this all in the schematic.

<img width="849" height="652" alt="Screenshot 2026-10-07 at 9 44 21 am" src="https://github.com/user-attachments/assets/7da3a19a-8855-40f2-a8a2-1aa4a550ff9c" />

In the PCB Editor I reranged the keys into the right order and put there corresponding diodes in the spaces between then I just wired up the matrix again in the most clean and compact way possible along with the screen. Then I made my boarder and I was set to go.

<img width="424" height="473" alt="Screenshot 2026-10-07 at 9 48 41 am" src="https://github.com/user-attachments/assets/56a791f3-fa09-4399-bd55-102ad21f2a7d" />

For the code I Used QMK and used the basic editor to set up the code because I couldn't download it on my computer because it is a mac. I picked the board and the configuration and added my binds to it.

<img width="149" height="148" alt="Screenshot 2026-10-07 at 9 51 23 am" src="https://github.com/user-attachments/assets/0f353bb1-2b03-4d81-9aa2-91acb042e2fe" />

That is where Im up to so far and I will update this when I recieve my part to build my Hackpad 

