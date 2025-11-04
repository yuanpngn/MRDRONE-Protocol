---
### NOTES:
## Emergency Procedures

### Drone Emergency Protocols
1. **Participant Distress:**
   - IMMEDIATELY activate kill switch / emergency land
   - Guide participant to remove headset if wearing VR
   - Check for injuries (propeller contact, dizziness, nausea)
   - Document incident timestamp and circumstances

2. **Drone Malfunction:**
   - Activate emergency land command
   - Clear participants from flight zone
   - Disconnect battery immediately if smoking/unusual heat/smell
   - Use backup CrazyFlie if available
   - Document issue for safety report

3. **Battery Emergency (Fire/Smoke):**
   - Evacuate all personnel immediately
   - Do NOT use water on LiPo fire
   - Use fire extinguisher (Class D) or LiPo fire bag
   - Call emergency services if fire spreads
   - Never touch overheated/swollen batteries

4. **VR-Related Issues:**
   - Participant reports severe nausea/dizziness: Stop immediately, remove headset, seated rest
   - Participant trips/loses balance: Spotter catches, stop drone, assess injury
   - Headset malfunction: Switch to Drone-Only condition first, troubleshoot during break

---

## Miscellaneous

**Settings**
- **Venue:** GK401
- **PowerPoint for guide of the workshop:** *Pilot Study PPT*
- **Participant and Study Notes:** *[MR. Drone] User Study Notes and Schedule*

**Materials / Tech Needed in Workshop**

**Documents & Forms:**
- [ ] Consent forms (20 copies + 2 extras)
- [ ] Battery rotation tracking sheet
- [ ] Participant ID and condition order log

**Primary Equipment:**
- [ ] **CrazyFlie Brushless 2.1** (primary unit)
- [ ] Lighthouse positioning system (base stations + mounts)
- [ ] Meta Quest 3 (fully charged, >70%)
- [ ] type c charging cable (for Metaquest)
- [ ] VR lens cleaning cloths (microfiber)
- [ ] Disinfectant spray/wipes

**Battery Management:**
- [ ] **6 labeled LiPo batteries** (B1-B6, fully charged to 4.2V/cell)
- [ ] 3-port LiPo battery charger (balance charger)
- [ ] Extension Cords
- [ ] Battery voltage checker/tester (digital multimeter)
- [ ] Battery storage case (organized compartments)

**Drone Accessories:**
- [ ] Spare propellers
- [ ] Propeller removal tool
- [ ] CrazyFlie radio dongle 
- [ ] crazyflie cables for CrazyFlie programming (backup)
- [ ] Laptop with CrazyFlie client software

**Workspace Setup:**
- [ ] High-visibility tape (for 2×2m boundary marking - bright color)
- [ ] Cameras/phones for recording
- [ ] Camera tripods/mounts (stable positioning)
- [ ] Music playlist
- [ ] Adequate lighting (maybe from joseph)

**Safety Equipment:**
- [ ] First aid kit (band-aids?)

**Participant Comfort:**
- [ ] Snacks (individually wrapped, variety)
- [ ] Water bottles (20+, sealed)
- [ ] Tissues/paper towels
- [ ] Hand sanitizer

**Technical Backup:**
- [ ] Multi-tool (screwdriver set)
- [ ] Spare AA/AAA batteries (for remotes/controllers)

**Documentation Tools:**
- [ ] Stopwatch/timer (for flight duration tracking)
- [ ] Notebook for observations
- [ ] Printed questionnaires (backup to digital)

**Environmental:**
- [ ] Temperature control (room comfortable, 18-24°C)
- [ ] "Study in Progress - Do Not Disturb" door sign  

**Counterbalancing plan**
- Odd participant IDs: **A → B** (MR.Drone first)  
- Even participant IDs: **B → A** (Drone-Only first)  
- Log actual order on the Participant ID sheet.

---

## MEMBERS' NOTES

### Pre-Session Setup (60 minutes before first participant)
1. **Battery Management:**
   - Check all 6 batteries with voltage tester (ensure >3.7V per cell)
   - Fully charge all 7 batteries (each takes ~45-60 minutes)
   - Label batteries B1-B6 for tracking purposes
   - Set up charging station with constant supervision

2. **Workspace Setup:**
   - Tape the 2×2 m flight boundary clearly on floor
   - Place cameras to capture full-body + close-up of upper body (2 angles minimum)
   - Set up Lighthouse positioning system (calibrate and test)
   - Verify CrazyFlie Brushless 2.1 radio link (test range within flight area)
   - dry-run routine once
   - Test emergency stop procedures

3. **VR Setup:**
   - Meta Quest 3: battery >70% (charge during breaks)
   - Casting enabled and verified
   - Volume set to medium
   - check boundaries and floor

4. **Unity App:**
   - Open Unity app to **Start** panel
   - Verify "Stop" button functionality
   - Test co-location of virtual avatar with physical CrazyFlie
   - Verify music sync and timing


### Battery Management Schedule for 20 Participants

**Battery Performance:**
- Each CrazyFlie Brushless 2.1 battery: ~7 minutes flight time
- Each participant session requires: ~6 minutes total flight (2 conditions × 3 min)
- Safety margin: Use each battery for max 5 minutes before rotation
- Cool-down period: 5-10 minutes per battery between uses
- Recharge time: 45-60 minutes per battery

**Rotation Strategy:**

**Session Block 1 (Participants 1-7):**
- Use Batteries B1-B6 (1 or 2 per participant)
- While P1-P7 complete questionnaires and interviews (~15 min), all batteries charge

**Charging Break 1:** 30 minutes
- Continue charging batteries B1-B6
- Setup verification, snack break for team

**Session Block 2 (Participants 8-14):**
- Use freshly charged Batteries B1-B6
- While P8-P14 complete questionnaires and interviews, batteries charge again
- Expected timeline: 2 hours

**Charging Break 2:** 30 minutes  
- Lunch break for team
- Continue charging batteries
- Check equipment condition

**Session Block 3 (Participants 15-20):**
- Use Batteries B1-B6 for P15-P20
- Battery B7 remains as emergency backup
- Expected timeline: 1.5 hours

**Total Session Duration:** ~6.5-7 hours (including breaks)

**Battery Tracking Log Template:**
- log in excel

### Pilot and Usability Testing Structure Notes
- Tape the 2×2 m boundary clearly (use high-visibility tape)
- Calibrate Lighthouse; verify CF link; arm motors **without props** to dry-run routine once
- Meta Quest: battery >70%, casting on, volume medium, interpupillary fit dial ready
- The CrazyFlie Brushless 2.1 battery should be between **80% and 100%** (3.9-4.2V per cell) to ensure it doesn't run out of power during the routine
- Monitor motor temperatures (should be warm, not hot to touch)
- Check propellers for damage after every 3-4 flights

---

### During Study Day

**Voltage Reference Guide:**
- **4.2V/cell (100%):** Freshly charged - optimal
- **3.9V/cell (80%):** Good for flight - safe minimum
- **3.7V/cell (50%):** Retire for charging - do not fly
- **3.5V/cell (20%):** Critical - charge immediately
- **Below 3.3V/cell:** Potential damage - inspect before recharging

**Charging Rotation Protocol:**
1. After each flight, measure voltage with tester/cfclient
2. If voltage >3.9V, battery can fly again after 5-min cool-down
3. If voltage 3.7-3.9V, retire for charging
4. Allow 5-10 minute cool-down before charging
5. Never charge a hot battery (wait until warm to touch)
6. Charge to 4.2V per cell before reuse
7. Expected charge time: 45-60 minutes from 3.7V to 4.2V

### Post-Study Storage
1. Discharge batteries to storage voltage: 3.8V per cell (~50%)
2. Store in fireproof LiPo bag in cool, dry location
3. Check voltage weekly if stored long-term
