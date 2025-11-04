# MR.Drone Study Documentation - Complete Updates Summary

## Overview
This document summarizes the comprehensive updates made to the MR.Drone study documentation, including the pilot study script refinement and the creation of a detailed 1-week user study schedule for 20 participants using **CrazyFlie 2.1 Brushless** drones.

## Documents Updated/Created

### 1. **MRDrone_Pilot_Study_Script.md** (REFINED)
- Comprehensive 40+ page pilot study protocol
- Detailed equipment checklists (80+ items)
- Safety protocols and emergency procedures
- Interview questions (55 total)

### 2. **USER_STUDY_DETAILED_SCHEDULE.md** (NEW - 50+ pages)
- Complete 1-week schedule for 20 participants (4 per day, 5 days)
- Hour-by-hour timeline with team role assignments
- Battery charging schedules for 7 CrazyFlie batteries
- Meta Quest 3 charging and sanitization protocols
- Emergency contingency plans

### 3. **PILOT_STUDY_UPDATES_SUMMARY.md** (THIS DOCUMENT - UPDATED)
- Consolidated summary of all changes

---

# KEY UPDATES & REFINEMENTS

## Hardware Specification
✅ **Confirmed:** Study uses **CrazyFlie 2.1 Brushless** (NOT DJI Tello Edu)
- Lightweight: 28 grams
- Brushless motors: Quiet, smooth, stable flight
- ~7 minutes flight time per battery
- Suitable for close-range human-drone interaction

---

## PILOT STUDY SCRIPT REFINEMENTS

### Enhanced Introduction Section
- Clearer explanation of study context and goals
- Emphasis on "no right or wrong answers"
- Explicit mention of CrazyFlie 2.1 Brushless features (lightweight, quiet)
- Safety reassurance for participants

### Detailed Setup Day Schedule (Day Before Study)
**4:00 PM - 7:30 PM breakdown:**
- 4:00-5:00 PM: Physical room setup (tape 2×2m boundary, position cameras, furniture)
- 5:00-6:00 PM: System calibration (Lighthouse, CrazyFlie radio, Unity app, Meta Quest casting)
- 6:00-7:00 PM: Battery charging (all 7 batteries to 100%)
- 7:00-7:30 PM: Final checklist and secure equipment

### Comprehensive Morning Setup (Study Day - 8:00 AM - 9:00 AM)
**Minute-by-minute breakdown:**
- 8:00 AM: Team arrival, equipment power-on (Yuan: drone/radio, Ju: Meta Quest, Rog: cameras/forms)
- 8:15 AM: Begin charging all 7 batteries (supervised, target 4.2V per cell)
- 8:30 AM: System testing (motor test without props, VR calibration, camera/lighting checks)
- 8:45 AM: Team briefing (emergency procedures, role assignments, participant schedule)
- 8:55 AM: Final walk-through simulation
- 9:00 AM: Ready for Participant 1

### Pre-Flight & Post-Flight Checks (NEW)
**Pre-Flight Check (30 seconds before each flight):**
- Battery voltage verification (must be >3.9V per cell)
- Propeller security check
- Radio link confirmation
- Flight zone clearance
- Participant safety briefing

**Post-Flight Check (30 seconds after each flight):**
- Motor temperature assessment (should be warm, not hot)
- Battery voltage logging
- Propeller inspection for damage
- Anomaly documentation

### Enhanced Safety Protocols

#### Emergency Procedures Added:
1. **Participant Distress:** Immediate kill switch, headset removal, check for injuries
2. **Drone Malfunction:** Emergency land, clear zone, battery disconnect, swap to backup
3. **Battery Fire/Smoke:** Evacuate, Class D extinguisher (NOT water), call emergency services
4. **VR-Related Issues:** Remove headset, seated rest, assess nausea/dizziness

#### Kill Switch Locations:
- Primary: Yuan's controller
- Secondary: Unity app "Stop" button
- Tertiary: Physical power disconnect

#### Emergency Contacts Template:
- Campus Security
- First Aid/Health Center
- Fire Department
- Team Lead cell numbers

### Equipment Checklist Expansion (80+ Items)

**Organized by category:**
- **Documents & Forms:** Consent forms (25 copies), battery logs, emergency contacts
- **Primary Equipment:** CrazyFlie Brushless 2.1 (primary + backup), Lighthouse system, Meta Quest 3
- **Battery Management:** 7 labeled batteries (B1-B7), 4-port balance charger, voltage checker, fireproof LiPo bags (2), discharge equipment
- **Drone Accessories:** Spare propellers (8+ sets), removal tool, cooling fan, spare motors, radio dongle
- **Workspace Setup:** High-visibility tape, floor markers, cameras (2+), tripods, speaker, music playlist
- **Safety Equipment:** First aid kit, Class D fire extinguisher, safety goggles, "Flight Zone" signage
- **Participant Comfort:** Snacks, water bottles (25), tissues, hand sanitizer, chairs, trash bins
- **Technical Backup:** Backup laptop with Unity, extra USB cables, multi-tool, electrical tape, spare batteries
- **Documentation:** Stopwatch, clipboards (2+), pens, notebooks, data backup drive
- **Environmental:** Temperature control (18-24°C), ventilation fan, window shades, door signage

### Battery Management - Deep Dive

**Battery Performance Specs:**
- Full charge: 4.2V per cell = 100% = ~7 min flight time
- Safe flight minimum: 3.9V per cell = 80%
- Storage voltage: 3.8V per cell = 65%
- Critical low: 3.7V per cell = 50% (DO NOT FLY)

**Voltage Reference Guide:**
| Voltage | Percentage | Status | Action |
|---------|------------|--------|--------|
| 4.2V | 100% | ✓ Optimal | Fly |
| 4.0V | 85% | ✓ Good | Fly |
| 3.9V | 80% | ⚠️ Minimum | Fly (monitor closely) |
| 3.8V | 65% | ⚠️ Storage | Do not fly, storage only |
| 3.7V | 50% | ⛔ Critical | Charge immediately |
| <3.5V | <20% | ⛔ Damaged | Inspect before recharging |

**Battery Rotation Strategy:**
- Participant 1-7: Use B1-B7 (one per participant)
- Charging Break 1: Charge all B1-B7 (45-60 min)
- Participant 8-14: Reuse B1-B7 (freshly charged)
- Charging Break 2 (Lunch): Recharge B1-B7
- Participant 15-20: Use B1-B6, keep B7 as emergency backup

**Battery Safety Rules:**
- NEVER charge unattended
- NEVER charge hot batteries (wait 5-10 min cool-down)
- NEVER fly with <3.9V per cell
- NEVER use water on LiPo fire
- ALWAYS charge in fireproof bag
- ALWAYS log battery usage
- ALWAYS check for swelling/damage before use

**Battery Tracking Log Template:**
| Time | Participant | Battery | Pre-Flight V | Post-Flight V | Flight Time | Motor Temp | Notes |
|------|-------------|---------|--------------|---------------|-------------|------------|-------|
| 9:00 | P01 | B1 | 4.2V | 4.0V | 6 min | Warm | OK |

### Meta Quest 3 Management

**Battery Performance:**
- Full battery: 2-3 hours active use
- Per participant VR time: ~6 minutes (MR.Drone condition only)
- 4 participants = ~24 min usage = 20-30% drain

**Charging Schedule:**
- Start of day: 100%
- After 2 participants: ~70-80% (optional quick charge during interviews)
- Lunch break: Charge to 70%+ (40 min charge time)
- End of day: Charge to 70-80% for next day

**Critical Rule:** Never let Meta Quest 3 drop below 20% during active sessions

**Hygiene Protocol:**
- Prepare 4+ clean VR face covers per day
- Sanitize headset with disinfectant wipes between participants (Ju's role)
- Clean lenses with microfiber cloth
- Replace face cover after each participant

**Casting Setup:**
- Casting enabled and tested pre-session
- Connected to external monitor for team observation
- Ju monitors casting for technical issues during flights

### Interview Questions - Comprehensive Refinement

**Total Questions: 55** (organized into 5 sections)

#### **Section 1: Initial Experience (After Each Condition) - 16 questions**
- Presence & Co-Location (MR.Drone): Q1-Q3
- Expressiveness & Perceived Agency: Q4-Q6
- Safety & Proxemics: Q7-Q9
- Workload & Cognitive Demand: Q10-Q11
- Timing, Synchronization, & Music: Q12-Q14
- Design Feedback: Q15-Q16

**Example questions:**
- Q1: "On a scale of 1-5, how 'present' did the virtual drone avatar feel? Why not higher/lower?"
- Q7: "When the avatar/drone approached you closely, what was your immediate physical response? (freeze, reach, step, turn)"
- Q11: "Did you reach a 'flow state' where you felt fully engaged without overthinking?"

#### **Section 2: Drone-Only Condition (After Physical Drone) - 8 questions**
- Perception & Relationship: Q17-Q18
- Safety & Spatial Awareness: Q19-Q20
- Expressiveness: Q21-Q22
- Workload & Focus: Q23-Q24

**Example questions:**
- Q17: "Did the physical drone feel more like a tool, a creature, or a partner? Why?"
- Q22: "If we could add ONE non-VR augmentation (lights, sound design, props), what and why?"

#### **Section 3: Comparative Questions (After Both Conditions) - 27 questions**
Most comprehensive section covering:
- Direct Comparisons (Q25-Q28): Supported feeling, risk-taking, safety, stage readiness
- Transfer & Learning (Q29-Q30): Skill carry-over, confusion points
- Identity & Aesthetics (Q31-Q32): Meaning shifts, style enhancement
- Expressiveness & Readability (Q33-Q35): Clear vs. ambiguous motions, "testing" behavior
- Proxemics & Touch-Imagination (Q36-Q37): Inviting touch areas, kinesphere reactions
- Timing & Musicality (Q38-Q39): Phrasing, leading/following dynamics
- Trust & Safety Development (Q40-Q41): Trust building, early warning signals needed
- Aesthetics & Role (Q42-Q43): Archetype casting, emotion shifts via design

**Example questions:**
- Q25: "In which condition did you feel more supported—MR.Drone or Drone-Only? Example moment?"
- Q35: "Did you ever 'test' the system—like faking a movement, feinting, or pausing—to see if it would respond? What happened?"
- Q37: "When the avatar/drone entered your 'personal space bubble' (kinesphere), how did your body react?"

#### **Section 4: Recommendations & Future Use - 9 questions**
- Stage Readiness (Q44-Q45): Top 3 changes, multimodal enhancements
- Rehearsal Tools (Q46-Q47): Practice modes, control preferences
- Multi-Drone Scenarios (Q48-Q49): Trio dynamics, personality distinctions
- Ethical & Safety Boundaries (Q50-Q51): Performer/crew protocols, audience transparency

**Example questions:**
- Q44: "What are your top THREE changes we should make before this system is ready for a live performance?"
- Q48: "Imagine a trio: you + 2 drones/avatars. How should they relate to you and to each other?"

#### **Section 5: Open-Ended Reflection - 4 questions**
- Q52-Q55: Surprises, one-sentence summary, additional thoughts, future interest

### Timing Guidelines Per Participant (Refined)

**Total per participant: 40-50 minutes**

**Breakdown:**
1. Arrival & Consent: 5 min
2. Introduction & Context: 8 min
3. **Condition 1 (MR.Drone):** 18 min
   - VR setup & tutorial: 4 min
   - Pre-flight check: 1 min
   - Flight routine: 3 min
   - Post-flight check: 1 min
   - Questionnaires: 9 min
4. **Transition/Break:** 3-5 min
5. **Condition 2 (Drone-Only):** 15 min
   - Pre-flight check: 1 min
   - Flight routine: 3 min
   - Post-flight check: 1 min
   - Questionnaires: 9 min
6. Comparative Interview: 8-10 min
7. Wrap-up: 2 min
8. **Buffer between participants:** 5-10 min (battery swap, VR sanitization, equipment check)

### Team Role Clarifications (Detailed)

#### **Rog (Lead Facilitator)**
- Present slides and provide instructions
- Conduct all interviews
- Monitor participant safety during flights
- Take observational notes
- Manage consent forms and questionnaires
- Backup all recordings

#### **Yuan (CrazyFlie Operations & Battery Manager)**
- Charge and manage all 7 batteries
- Pre-flight checks (voltage, props, radio link)
- Arm drone and send flight routine signals
- Monitor telemetry during flights
- Emergency landing ready (kill switch)
- Post-flight checks (motor temps, battery logging)
- Equipment maintenance and troubleshooting

#### **Ju (VR Support & Recording Specialist)**
- Manage Meta Quest 3 (charging, casting, setup)
- Fit headset on participants, guide VR tutorial
- Sanitize headset between participants
- Replace VR face covers
- Manage camera recordings
- Monitor participant comfort during VR use

### Counterbalancing Strategy
- **Odd participant IDs (P1, P3, P5...):** A → B (MR.Drone first, then Drone-Only)
- **Even participant IDs (P2, P4, P6...):** B → A (Drone-Only first, then MR.Drone)
- Log actual order on participant tracking sheet

---

## USER STUDY DETAILED SCHEDULE (NEW DOCUMENT)

### Document Structure (50+ pages)
1. **Week Overview:** 5 days, 4 participants per day
2. **Pre-Study Preparation:** 7 days, 3 days, and 1 day before checklists
3. **Daily Schedule Template:** Repeated for Monday-Friday
4. **Special Schedules & Contingencies**
5. **Emergency Protocols**
6. **Data Management**
7. **Appendices with Quick Reference Guides**

### Week-at-a-Glance

| Day | Date | Participants | IDs | Notes |
|-----|------|--------------|-----|-------|
| Monday | [TBD] | 4 | P01-P04 | First day - extra buffer time |
| Tuesday | [TBD] | 4 | P05-P08 | Standard schedule |
| Wednesday | [TBD] | 4 | P09-P12 | Mid-week maintenance check |
| Thursday | [TBD] | 4 | P13-P16 | Standard schedule |
| Friday | [TBD] | 4 | P17-P20 | Final day, post-study wrap-up |

**Total: 20 participants over 5 days**

### Daily Schedule Template (9:00 AM - 1:00 PM)

#### **Morning Preparation (8:00 AM - 9:00 AM)**
- 8:00 AM: Team arrival, equipment power-on
- 8:15 AM: Battery charging session (all 7 batteries to 100%)
- 8:30 AM: System calibration
- 8:45 AM: Team briefing
- 8:55 AM: Final pre-session check
- 9:00 AM: Ready for Participant 1

#### **Participant Sessions (9:00 AM - 12:50 PM)**
- **9:00 AM - 9:50 AM:** Participant 1 (50 min)
- **9:50 AM - 10:00 AM:** Buffer (10 min)
- **10:00 AM - 10:50 AM:** Participant 2 (50 min)
- **10:50 AM - 11:00 AM:** Buffer (10 min)
- **11:00 AM - 11:50 AM:** Participant 3 (50 min)
- **11:50 AM - 12:00 PM:** Buffer (10 min)
- **12:00 PM - 12:50 PM:** Participant 4 (50 min)

#### **Morning Wrap-Up (12:50 PM - 1:00 PM)**
- Check all used batteries
- Batteries <3.7V → place on chargers
- Log all battery usage
- Inspect CrazyFlie for damage
- Deep clean Meta Quest 3
- Charge Meta Quest 3 for next day
- Save and backup all recordings

#### **Lunch Break (1:00 PM - 2:00 PM)**
- **1:00-1:30 PM:** Equipment charging (supervised - ROTATE team members)
  - Continue battery charging (never unattended)
  - Meta Quest 3 charging (target 70%+)
  - Check motor temperatures
  - Test backup CrazyFlie if issues detected
- **1:30-2:00 PM:** Team lunch (rotate supervision of charging)

#### **Afternoon Debrief (2:00 PM - 3:30 PM)**
- Review video footage from morning
- Discuss observations and insights
- Identify adjustments for next day
- Organize questionnaire data
- Complete battery charging
- Discharge batteries to storage voltage (3.8V)
- Equipment maintenance

#### **End of Day Procedures (3:30 PM - 4:00 PM)**
- Disconnect and store all batteries (3.8V storage voltage)
- Remove propellers from CrazyFlie
- Inspect equipment for damage
- Charge Meta Quest 3 to 70%+
- Save all recordings to TWO backup locations (external drive + cloud)
- Organize forms and questionnaires
- Update participant tracking sheet
- Team debrief
- Lock room

### Minute-by-Minute Participant Flow (Example: Participant 1)

**9:00 AM - Arrival (5 min)**
- Rog: Greet, offer water
- Ju: Start recording once consent signed
- Yuan: Insert Battery B1, check voltage >3.9V, log

**9:05 AM - Introduction & Consent (8 min)**
- Rog: Present Slides 1-3, explain context
- Hand out consent form
- Ju: Begin recording

**9:13 AM - Condition 1: MR.Drone (18 min)**
- 9:13-9:17: VR setup, tutorial, Pre-SSQ (4 min)
- 9:17: Pre-flight check (1 min) - Yuan verifies all systems
- 9:18-9:21: **FLIGHT ROUTINE** (3 min) - Yuan operates drone, Rog encourages movement, Ju monitors VR
- 9:21: Post-flight check (1 min) - Yuan checks motors/battery
- 9:22-9:31: Questionnaires (9 min) - While participant completes forms, Yuan inspects drone, Ju sanitizes headset

**9:31 AM - Transition (5 min)**
- Offer water/snack, restroom break
- Yuan: Check Battery B1, decide reuse or swap
- Ju: Replace VR face cover

**9:36 AM - Condition 2: Drone-Only (15 min)**
- 9:36: Pre-flight check (1 min)
- 9:37-9:40: **FLIGHT ROUTINE** (3 min)
- 9:40: Post-flight check (1 min)
- 9:41-9:50: Questionnaires (9 min)

**9:50 AM - End**
- Thank participant, stop recording
- Yuan: Remove battery, log usage
- Ju: Sanitize Meta Quest 3
- Rog: Save files

**9:50-10:00 AM - Buffer**
- Team sync, prepare for Participant 2

### Battery Management - Complete Daily Strategy

**For 4 Participants per Day:**

| Time | Participant | Battery | Pre-Flight Voltage | Expected Post-Flight | Action |
|------|-------------|---------|-------------------|---------------------|--------|
| 9:00 AM | P1 | B1 | 4.2V (100%) | 3.9-4.0V | Cool 5-10 min |
| 10:00 AM | P2 | B2 | 4.2V (100%) | 3.9-4.0V | Cool 5-10 min |
| 11:00 AM | P3 | B3 or B1* | 4.2V or 3.9-4.0V | 3.8-3.9V | Charge at lunch |
| 12:00 PM | P4 | B4 or B2* | 4.2V or 3.9-4.0V | 3.8-3.9V | Charge at lunch |

*If B1/B2 still >3.9V after cooling, can reuse. Otherwise use B3/B4.

**Lunch Charging (1:00-2:00 PM):**
- Place B1-B4 on chargers
- Monitor continuously (team rotates supervision)
- Charge to 4.2V per cell (45-60 min)
- Keep B5-B7 as emergency backups (remain charged)

**End of Day:**
- Discharge all batteries to 3.8V per cell (storage voltage)
- Store in fireproof LiPo bag
- Log cycle count for each battery

### Meta Quest 3 Charging Strategy

**Daily Pattern:**
- **8:00 AM Start:** 100%
- **After P1 (9:50 AM):** ~94% (6 min use)
- **After P2 (10:50 AM):** ~88% (12 min use)
- **After P3 (11:50 AM):** ~82% (18 min use)
- **After P4 (12:50 PM):** ~76% (24 min use)

**Charging Windows:**
- **Optional:** Plug in during P3 or P4 questionnaires (adds 5-10%)
- **Lunch (1:00-2:00 PM):** Charge to 70%+ (40-60 min charge time)
- **End of Day (3:30 PM):** Charge to 70-80% for next day

**Critical Thresholds:**
- Keep above 20% during active sessions
- If drops to 30%, charge during next buffer period
- Always start day at 70%+ minimum (100% ideal)

### Casting & Recording Protocol

**Casting Setup:**
- Meta Quest 3 casts to external monitor
- Allows team to observe participant's VR view in real-time
- Ju monitors casting for technical issues
- Switch casting off during transitions to save battery

**Camera Recording:**
- Camera 1: Full-body view of participant and flight zone
- Camera 2: Close-up of upper body and facial expressions
- Start recording once consent form signed
- Stop recording after participant departs
- Save files immediately to external drive
- Verify recording quality before next participant

### Emergency Contingency Plans (Detailed)

#### **Scenario 1: Battery Runs Out Mid-Flight**
1. Drone auto-lands (safety feature)
2. Yuan swaps to backup battery B5, B6, or B7
3. Rog apologizes, explains brief technical issue
4. Restart flight routine from beginning
5. **Time impact:** +3 minutes
6. Log: battery ID, participant, timestamp, circumstances

#### **Scenario 2: CrazyFlie Malfunction**
1. Emergency land (kill switch)
2. Swap to backup CrazyFlie Brushless 2.1
3. Quick 30-second motor test
4. Resume session
5. **Time impact:** +5 minutes
6. After session: troubleshoot primary unit

#### **Scenario 3: Meta Quest 3 Battery Dies**
1. Plug in charging cable immediately
2. **Option A:** Wait 5 min for 10-15% quick charge, resume
3. **Option B:** Skip MR.Drone condition, do Drone-Only only, note in log
4. **Time impact:** +5 min (Option A) or -15 min (Option B)

#### **Scenario 4: Participant VR Sickness**
1. **IMMEDIATELY** remove headset
2. Guide to seated position
3. Offer water
4. Stop drone (emergency land)
5. Wait 5-10 minutes for recovery
6. Ask if wants to continue or withdraw
7. If continues: Drone-Only condition only
8. Log incident thoroughly (symptoms, duration, outcome)

#### **Scenario 5: Propeller Breaks Mid-Flight**
1. Drone auto-lands (imbalanced thrust)
2. Yuan: Power off, replace broken propeller (spare props ready)
3. Test motor balance (3-second low-power test)
4. Resume flight
5. **Time impact:** +2-3 minutes

#### **Scenario 6: Battery Fire/Smoke**
1. **EVACUATE IMMEDIATELY** - all personnel
2. **DO NOT USE WATER**
3. Use Class D fire extinguisher or LiPo fire bag
4. Call emergency services if fire spreads
5. Clear room, wait for fire department
6. Document incident for safety report
7. **Study cancelled for the day**

### Data Management Protocol

#### **File Naming Convention:**
```
MRDRONE_P[ID]_[Date]_[Condition]_[FileType]
Examples:
- MRDRONE_P01_20251104_MRDrone_Video1.mp4
- MRDRONE_P01_20251104_DroneOnly_Video2.mp4
- MRDRONE_P01_20251104_NASATLX.pdf
- MRDRONE_P01_20251104_InterviewTranscript.docx
```

#### **Folder Structure:**
```
/MRDrone_UserStudy_Nov2025/
  /P01_Participant_001/
    /Videos/
      - MRDRONE_P01_20251104_MRDrone_Video1.mp4
      - MRDRONE_P01_20251104_DroneOnly_Video2.mp4
    /Questionnaires/
      - MRDRONE_P01_20251104_NASATLX.pdf
      - MRDRONE_P01_20251104_Godspeed.pdf
      - MRDRONE_P01_20251104_MREQ.pdf
      - MRDRONE_P01_20251104_UEQS.pdf
      - MRDRONE_P01_20251104_Circumplex.pdf
    /ConsentForm/
      - MRDRONE_P01_20251104_Consent_Signed.pdf
    /InterviewNotes/
      - MRDRONE_P01_20251104_InterviewTranscript.docx
  /P02_Participant_002/
  ...
  /P20_Participant_020/
  /BatteryLogs/
    - Battery_Usage_Log_Day1.xlsx
    - Battery_Usage_Log_Day2.xlsx
    ...
  /EquipmentLogs/
    - Equipment_Maintenance_Log.xlsx
    - Incident_Reports.docx
  /DailySummaries/
    - Day1_Summary_20251104.docx
    ...
  /TeamDebriefs/
    - Weekly_Debrief_20251108.docx
```

#### **Daily Backup Schedule:**
1. **End of morning session (1:00 PM):**
   - Copy all videos to external drive
   - Upload questionnaires to secure cloud
   - Verify file integrity

2. **End of day (4:00 PM):**
   - Second backup of all videos to cloud
   - Organize files by participant ID
   - Create daily summary document

#### **Backup Locations:**
- Location 1: Research laptop (primary)
- Location 2: External hard drive (portable)
- Location 3: Secure cloud storage (OneDrive/Google Drive)

**Rule:** Never delete files from primary location until confirmed in all 3 locations

### Supplies Restocking Checklist

#### **Check Daily:**
- [ ] VR hygiene face covers (need 4+ per day = 20+ for week)
- [ ] Disinfectant wipes (use ~10 per day = 50+ for week)
- [ ] Water bottles (4+ per day = 20+ for week)
- [ ] Snacks (variety, individually wrapped)
- [ ] Printer paper (for logs and forms)

#### **Check Mid-Week (Wednesday):**
- [ ] Spare propellers (should have 8+ sets)
- [ ] AA/AAA batteries (for any wireless devices)
- [ ] Lens cleaning cloths (have 3+ clean ones)
- [ ] Hand sanitizer
- [ ] Tissues

#### **Order 1 Week Before Study:**
- [ ] 30 VR hygiene face covers
- [ ] 2 large packs disinfectant wipes
- [ ] Case of water bottles (24-pack)
- [ ] Variety snack box
- [ ] Spare CrazyFlie propellers (2 full sets = 8 props)
- [ ] Extra USB cables
- [ ] Backup microSD cards for cameras

### Weekly Maintenance Schedule

#### **Daily (After Each Session):**
- [ ] Inspect propellers for cracks or chips
- [ ] Check motor temperatures
- [ ] Verify battery health (voltage, no swelling)
- [ ] Clean Meta Quest 3 lenses
- [ ] Backup all data

#### **Mid-Week (Wednesday Evening):**
- [ ] Deep clean all equipment
- [ ] Test backup CrazyFlie Brushless 2.1
- [ ] Replace any worn propellers
- [ ] Check battery cycle count (should be <10 cycles/week)
- [ ] Verify Lighthouse calibration accuracy
- [ ] Review data organization

#### **End of Week (Friday Evening):**
- [ ] Discharge all batteries to 3.8V storage voltage
- [ ] Store batteries in cool, dry location
- [ ] Complete data backup to 3 locations
- [ ] Deep clean all equipment
- [ ] Inspect all equipment for wear
- [ ] Complete final participant tracking sheet
- [ ] Compile all consent forms and questionnaires
- [ ] Write team debrief summary

### Team Role Quick Reference Cards

#### **YUAN - Drone Operations & Battery Management**
**Pre-Session:**
- Charge all 7 batteries to 100% (4.2V/cell)
- Test CrazyFlie radio link
- Inspect props and motors
- Position cooling fan near landing zone

**During Session:**
- Pre-flight check: voltage >3.9V, props secure, clear zone
- Arm drone, send routine signal
- Monitor telemetry and participant safety
- Hand near kill switch at all times
- Post-flight check: motor temps, battery voltage
- Log battery usage in tracking sheet

**Post-Session:**
- Battery rotation/charging decisions
- Equipment inspection
- Maintenance as needed

**Equipment:** CrazyFlie Brushless 2.1, 7 batteries, charger, voltage tester, cooling fan, spare props, tools

---

#### **JU - VR Support & Recording**
**Pre-Session:**
- Charge Meta Quest 3 to >70% (100% ideal)
- Test casting to monitor
- Prepare 4+ clean VR hygiene face covers
- Set up recording cameras, test angles

**During Session:**
- Start recording once consent signed
- Fit Meta Quest 3 on participant, adjust IPD
- Guide through VR tutorial (About → Instructions → Onboarding)
- Monitor casting for technical issues
- Watch participant for discomfort or VR sickness
- Remove headset after flight

**Post-Session:**
- Sanitize Meta Quest 3 with disinfectant wipes
- Replace VR face cover
- Save and verify all recordings
- Prep equipment for next participant

**Equipment:** Meta Quest 3, charging cable, face covers (30), disinfectant wipes, lens cleaning cloths, cameras (2), tripods

---

#### **ROG - Facilitation & Interview**
**Pre-Session:**
- Greet participant, offer water
- Present slides (context, study overview)
- Explain informed consent
- Obtain signed consent form

**During Session:**
- Provide clear instructions for each condition
- Monitor participant safety (stop if distress)
- Encourage free, expressive movement
- Take observational notes
- Conduct comparative interviews

**Post-Session:**
- Thank participant
- Review and organize notes
- File consent forms and questionnaires
- Backup data to external drive and cloud

**Equipment:** Laptop with slides, consent forms (25), questionnaires (25), clipboards (2), pens, notebooks, stopwatch

---

### Pre-Study Preparation Timeline

#### **7 Days Before (Monday, Week 0):**
- [ ] Confirm all 20 participants via email (include date, time, location, dress code)
- [ ] Send reminder: comfortable clothing, no loose accessories, remove jewelry
- [ ] Test all 7 CrazyFlie batteries (full charge/discharge cycle to verify health)
- [ ] Inspect both CrazyFlie Brushless 2.1 units (primary + backup)
  - Check frame for cracks
  - Test all 4 motors
  - Verify propeller mounts
  - Test radio dongle connection
- [ ] Order/prepare 30+ VR hygiene face covers
- [ ] Print all forms (25 consent forms, 25 questionnaire sets, 10 battery logs)
- [ ] Create participant schedule spreadsheet with contact info

#### **3 Days Before (Thursday, Week 0):**
- [ ] Complete full dress rehearsal
  - Run through entire protocol with team member as mock participant
  - Time each section (should be 40-50 min total)
  - Practice emergency procedures (kill switch, VR removal, fire protocol)
- [ ] Test Unity app thoroughly
  - Verify avatar co-location accuracy (<5cm error)
  - Test "Stop" button functionality
  - Verify music sync and timing
  - Test Pre-SSQ and questionnaire panels
- [ ] Calibrate Lighthouse positioning system in GK401
  - Mount base stations securely
  - Verify 2×2m coverage area
  - Run accuracy test (should be <1cm precision)
- [ ] Run complete flight routine 5 times
  - Test battery drainage (should be ~6 min flight time per battery)
  - Check motor temperatures after each flight
  - Verify smooth trajectory and hover stability
- [ ] Test Meta Quest 3 casting to external monitor
  - Test on laptop and any backup displays
  - Verify video quality and latency
- [ ] Verify all cameras can record for 1-hour continuously
  - Check storage capacity (need ~10GB per participant)
  - Test battery life or ensure plugged in
- [ ] Prepare and post emergency contact list near GK401 entrance

#### **1 Day Before (Sunday Evening, Week 1):**
**4:00 PM - 7:30 PM: Complete Setup Day**
(See detailed breakdown in Pilot Study Script)

**Key tasks:**
- Physical room setup (tape 2×2m boundary, arrange furniture)
- System calibration (Lighthouse, CrazyFlie, Unity, Meta Quest casting)
- Charge all 7 batteries to 100%
- Print and organize all forms
- Final equipment checklist (verify all 80+ items)
- Lock room, confirm Monday morning access

---

## FINAL PRE-STUDY CHECKLIST

### **1 Week Before:**
- [ ] All 20 participants confirmed (received reply emails)
- [ ] Consent forms printed (25 copies, organized by day)
- [ ] Questionnaires printed (25 sets of 5 questionnaires each = 125 total)
- [ ] All equipment tested (CrazyFlie, Meta Quest, Lighthouse, Unity app)
- [ ] Dress rehearsal completed with full team
- [ ] Supplies ordered and delivered

### **1 Day Before:**
- [ ] Room setup complete (tape, cameras, furniture, signage)
- [ ] All 7 batteries charged to 100% (verified with voltage tester)
- [ ] System calibration verified (Lighthouse, CrazyFlie radio, Unity co-location)
- [ ] Emergency procedures posted visibly in GK401
- [ ] Team briefed on roles and schedule
- [ ] Participant schedule confirmed (sent reminder emails)

### **Morning of Study (Day 1):**
- [ ] Team arrives 1 hour early (8:00 AM for 9:00 AM start)
- [ ] All 7 batteries recharged to 100% (check voltage >4.1V per cell)
- [ ] Equipment final check (CrazyFlie motors test, Meta Quest casting, cameras recording test)
- [ ] Cameras tested and recording
- [ ] Flight zone clear of obstacles
- [ ] Water and snacks available in waiting area
- [ ] First participant confirmed (text/call 30 min before)
- [ ] Team roles confirmed: Yuan = Drone, Ju = VR/Recording, Rog = Facilitation

### **End of Each Day:**
- [ ] All data backed up to 2 locations (external drive + cloud)
- [ ] All used batteries discharged to 3.8V storage voltage
- [ ] Equipment inspected for damage (props, motors, frame, VR lenses)
- [ ] Battery usage logged in master tracking sheet
- [ ] Participant attendance tracked
- [ ] Next day's prep complete (forms organized, batteries ready, room secured)
- [ ] Team debrief: discuss issues, plan adjustments

### **End of Study Week (Friday Evening):**
- [ ] All data backed up to 3 locations (laptop, external drive, cloud)
- [ ] All 7 batteries discharged to 3.8V and stored safely
- [ ] All equipment cleaned and stored (remove props, coil cables)
- [ ] Thank-you emails sent to all 20 participants
- [ ] Consent forms and questionnaires organized by participant ID
- [ ] Battery cycle log complete (track cycles for future use)
- [ ] Equipment condition report written
- [ ] Team debrief completed (what worked, what to improve)
- [ ] Data analysis plan finalized (next steps for processing videos, questionnaires, interviews)

---

## APPENDICES - Quick Reference Guides

### **Appendix A: Battery Voltage Quick Reference**
```
LIPO BATTERY VOLTAGE GUIDE (Per Cell)

4.2V = 100% ✓ OPTIMAL (Freshly charged, ready to fly)
4.1V = 95% ✓ GOOD
4.0V = 85% ✓ GOOD  
3.9V = 80% ⚠️ MINIMUM for flight (safe but monitor closely)
3.8V = 65% ⚠️ STORAGE voltage (for overnight/long-term storage)
3.7V = 50% ⛔ DO NOT FLY - Charge immediately
3.6V = 35% ⛔ CRITICAL - Risk of damage
3.5V = 20% ⛔ CRITICAL - Risk of permanent damage
<3.3V = ⛔ DAMAGED - Inspect thoroughly before attempting to recharge

SAFE FLIGHT RANGE: 3.9V - 4.2V per cell
STORAGE VOLTAGE: 3.8V per cell
NEVER DISCHARGE BELOW: 3.5V per cell
```

### **Appendix B: Motor Temperature Guide**
```
MOTOR TEMPERATURE CHECK (After Each Flight)

HOW TO CHECK:
- Touch motor casing briefly with fingertip
- Hold for 3 seconds to assess temperature

TEMPERATURE SCALE:
✓ WARM (comfortable to hold 3+ sec) = OK
  → Continue use after 2-3 min cool-down
  → Normal operating temperature

⚠️ HOT (uncomfortable to hold 3 sec) = Cooling break needed
  → Allow 5-10 min cool-down before next flight
  → Monitor in subsequent flights

⛔ VERY HOT (painful to touch, can't hold 1 sec) = STOP
  → Immediate inspection required
  → Do NOT fly until issue resolved
  → Check for:
    - Damaged or imbalanced propellers
    - Loose motor mounts
    - Bearing damage
    - Overloaded flight profile

IF MOTORS CONSISTENTLY OVERHEAT:
1. Inspect and replace propellers (check for cracks, chips, imbalance)
2. Verify all motor screws are tight
3. Extend cooling time between flights to 10 min
4. Reduce flight duration to 5 min max per session
5. Consider swapping to backup CrazyFlie
6. Document issue for post-study equipment review
```

### **Appendix C: Emergency Contact Information**
```
=================================
MR.DRONE STUDY EMERGENCY CONTACTS
=================================
Study Location: GK401
Study Dates: [Insert Monday - Friday dates]

TEAM CONTACTS:
- Rog (Lead Facilitator): [Phone Number]
- Yuan (Technical Lead): [Phone Number]
- Ju (VR Support): [Phone Number]

EMERGENCY SERVICES:
- Campus Security: [Phone Number]
- Campus Health Center: [Phone Number]
- Local Emergency (Fire/Medical/Police): 911
- Fire Department (Non-Emergency): [Phone Number]
- Poison Control: 1-800-222-1222

EQUIPMENT SUPPORT:
- CrazyFlie Technical Support: [Email/Phone]
- Meta Quest Support: [Support Number]
- Unity Technical Issues: [Contact]

NEAREST FACILITIES (from GK401):
- First Aid Kit: [Location in GK401 - specify shelf/cabinet]
- Fire Extinguisher (Class D): [Location - e.g., "near entrance, left wall"]
- AED (Automated External Defibrillator): [Building location]
- Emergency Exit: [Direction from GK401]
- Nearest Restroom: [Location]

INCIDENT REPORTING:
- Faculty Advisor: [Name, Phone, Email]
- IRB Office (Human Subjects): [Phone, Email]
- Campus Safety Office: [Phone, Email]

EMERGENCY PROTOCOLS:
1. Participant injury/distress → Stop immediately, call Campus Health
2. Equipment fire/smoke → Evacuate, call 911, use Class D extinguisher
3. VR sickness → Remove headset, seated rest, offer water
4. Drone malfunction → Emergency land, clear zone, swap to backup

POST EMERGENCY:
- Document incident immediately (time, participants, circumstances)
- Notify faculty advisor within 24 hours
- Submit incident report to IRB if participant affected
- Review and update safety protocols as needed
```

### **Appendix D: Participant Consent Form Checklist**
```
INFORMED CONSENT FORM - REQUIRED ELEMENTS

Before participant signs, verify form includes:
- [ ] Study title: "MR.Drone: Mixed Reality Drone-Dancer Interaction Study"
- [ ] Principal investigator names: [Rog, Yuan, Ju]
- [ ] Institution affiliation: [University/Organization name]
- [ ] Contact information (email, phone for all team members)
- [ ] Study purpose clearly explained (exploring drone as dance partner)
- [ ] Procedures described (VR experience, physical drone, questionnaires, interview)
- [ ] Approximate time commitment (1 hour)
- [ ] Risks disclosed (minor: VR discomfort, drone proximity; rare: propeller contact)
- [ ] Benefits explained (contribution to HCI/dance research)
- [ ] Confidentiality statement (data anonymized, stored securely)
- [ ] Right to withdraw at any time without penalty
- [ ] Compensation (if any) or no compensation stated
- [ ] Video/audio recording consent (separate checkbox)
  - [ ] "I consent to video recording"
  - [ ] "I consent to audio recording"
  - [ ] "I consent to use of recordings for research presentations" (optional)
- [ ] Participant signature line
- [ ] Date line
- [ ] Researcher signature line
- [ ] IRB approval number and date (if applicable)
- [ ] Copy provided to participant

PARTICIPANT ID ASSIGNMENT:
- Assign sequential IDs: P01, P02, P03..., P20
- Record on form: "Participant ID: P___"
- Use only ID (not name) in all data files

STORAGE:
- Original signed form → Locked file cabinet in [Location]
- Scanned copy → Encrypted folder on secure server
- Separate from de-identified data
```

### **Appendix E: Condition Counterbalancing Tracker**
```
CONDITION ORDER ASSIGNMENT

RULE:
- Odd Participant IDs (P01, P03, P05...): A → B (MR.Drone first, then Drone-Only)
- Even Participant IDs (P02, P04, P06...): B → A (Drone-Only first, then MR.Drone)

PURPOSE: Controls for order effects (learning, fatigue, carryover)

TRACKING SHEET:
| Participant ID | Assigned Order | Actual Order | Notes |
|----------------|----------------|--------------|-------|
| P01 | A → B | A → B | Completed both |
| P02 | B → A | B → A | Completed both |
| P03 | A → B | A → B | Completed both |
| P04 | B → A | B only | VR sickness, skipped MR.Drone |
| P05 | A → B | A → B | Completed both |
| ...

ACTUAL ORDER: Record what participant actually experienced (may differ if issues occur)

ANALYSIS NOTE: Include order as a factor in statistical analysis to check for order effects
```

---

## SUMMARY OF KEY IMPROVEMENTS

### 1. **Hardware Clarity**
✅ All references updated to **CrazyFlie 2.1 Brushless** (removed DJI Tello Edu)
✅ Hardware specifications clearly documented (28g, brushless motors, 7 min flight time)

### 2. **Practical Scheduling**
✅ Realistic 1-week plan for 20 participants (4/day, 5 days)
✅ Built-in buffer times (10 min between participants)
✅ Strategic charging breaks (morning, lunch, end of day)
✅ Team roles clearly defined and time-synchronized

### 3. **Battery Management Excellence**
✅ Complete voltage reference guide (4.2V to <3.3V)
✅ Detailed rotation strategy for 7 batteries
✅ Charging supervision protocols (never unattended)
✅ Motor temperature monitoring (warm = OK, hot = break, very hot = stop)
✅ Storage voltage protocols (3.8V for overnight)

### 4. **Safety & Emergency Preparedness**
✅ 6 detailed emergency scenarios with step-by-step responses
✅ Battery fire protocol (Class D extinguisher, NO WATER, evacuate)
✅ VR sickness protocol (immediate headset removal, seated rest)
✅ Multiple kill switch locations
✅ Emergency contact template with all necessary numbers

### 5. **Meta Quest 3 Management**
✅ Battery life calculations (2-3 hours = 24-30 participants theoretical max)
✅ Realistic usage per participant (6 min VR time)
✅ Strategic charging windows (lunch break, between participants)
✅ Hygiene protocol (sanitize between participants, fresh face covers)
✅ Casting setup for team monitoring

### 6. **Interview Questions - Comprehensive**
✅ 55 total questions organized into 5 sections
✅ Section 1: Initial experience per condition (16 Q)
✅ Section 2: Drone-only specific (8 Q)
✅ Section 3: Comparative analysis (27 Q)
✅ Section 4: Future recommendations (9 Q)
✅ Section 5: Open reflection (4 Q)
✅ Follow-up prompts for deeper insights
✅ Covers: presence, expressiveness, safety, proxemics, workload, timing, trust, aesthetics

### 7. **Data Management**
✅ Clear file naming convention (MRDRONE_P[ID]_[Date]_[Condition]_[FileType])
✅ Organized folder structure (by participant, then by data type)
✅ Triple backup protocol (laptop, external drive, cloud)
✅ Daily backup schedule (end of morning, end of day)

### 8. **Equipment & Supplies**
✅ Comprehensive 80+ item checklist
✅ Daily restocking needs (face covers, wipes, water)
✅ Weekly supply estimates (30 face covers, 50 wipes, 20 waters)
✅ Pre-order list (1 week advance)

### 9. **Team Coordination**
✅ Role-specific quick reference cards (Yuan, Ju, Rog)
✅ Minute-by-minute participant flow
✅ Clear handoffs between team members
✅ Supervision rotation during charging breaks

### 10. **Participant Experience**
✅ Clear safety explanations (CrazyFlie features, "Stop" command)
✅ Comfortable pacing (40-50 min per participant, includes breaks)
✅ Counterbalancing (odd IDs = MR first, even IDs = Drone first)
✅ Emphasis on "no right or wrong" and voluntary participation

---

## RECOMMENDATIONS FOR IMPLEMENTATION

### Before Starting Study:
1. **Run dress rehearsal 3 days before** (Thursday before Monday start)
   - Full protocol with team member as mock participant
   - Time each section precisely
   - Practice emergency procedures

2. **Test all 7 batteries** (7 days before)
   - Full charge/discharge cycle
   - Measure actual flight time (should be 6-7 min)
   - Inspect for swelling or damage

3. **Create laminated quick reference cards** for each team member
   - Yuan: Battery voltage chart, emergency kill switch location
   - Ju: VR troubleshooting steps, sanitization checklist
   - Rog: Interview question prompts, emergency contact numbers

4. **Set up automated reminders** (phone alarms/timers)
   - Battery charging check every 15 min
   - Buffer time alerts (5 min warning before next participant)
   - Lunch break supervision rotation

### During Study Week:
1. **Daily morning huddle** (8:45 AM, 15 min)
   - Review yesterday's issues
   - Adjust today's plan if needed
   - Confirm participant schedule

2. **Daily debrief** (3:45 PM, 15 min)
   - What went well
   - What to improve
   - Equipment status
   - Tomorrow's prep

3. **Mid-week maintenance** (Wednesday evening)
   - Deep clean all equipment
   - Test backup CrazyFlie
   - Replace worn propellers
   - Verify Lighthouse calibration

### After Study Week:
1. **Friday evening wrap-up** (3:30-5:00 PM)
   - Complete data backup to all 3 locations
   - Discharge all batteries to 3.8V storage
   - Write equipment condition report
   - Send thank-you emails to participants

2. **Following Monday: Data analysis begins**
   - Transcribe interviews
   - Enter questionnaire data into spreadsheet
   - Review video footage for key moments

---

## QUESTIONS TO CLARIFY BEFORE STUDY BEGINS

### Equipment:
1. Do you have a **backup CrazyFlie Brushless 2.1** unit? (Highly recommended)
2. What is the capacity (mAh) of your 7 batteries? (Need to confirm 7-min flight time)
3. Is your 4-port charger a **balance charger** with individual cell monitoring?
4. Do you have a **Class D fire extinguisher** for metal/chemical fires? (Essential for LiPo safety)

### Logistics:
5. Are participants scheduled with exact time slots, or rolling availability?
   - **Recommend:** Exact time slots (e.g., P01 at 9:00 AM sharp)
6. Do participants know the session is ~1 hour, and to arrive on time?
7. Is there a waiting area outside GK401 if a participant arrives early?

### Safety & Ethics:
8. Do you have insurance/liability waivers beyond consent forms?
9. Is there an IRB approval number to include on consent forms?
10. Have you confirmed with GK401 facility manager about:
    - Drone flight permissions
    - Camera recording permissions
    - Room access for full day (8 AM - 4 PM)
    - Locking/securing equipment overnight

### Data:
11. Where will the final data be stored long-term (after study ends)?
12. Who has access to identifiable data (videos with faces)?
13. When will data be de-identified (remove participant names from tracking)?

---

## CONTACT FOR QUESTIONS

If you have questions while implementing this schedule:
- **Technical (CrazyFlie, batteries):** Yuan
- **VR (Meta Quest 3, Unity app):** Ju
- **Protocol (participant flow, interviews):** Rog

---

**Document Version:** 3.0 (Comprehensive Refinement)  
**Last Updated:** November 4, 2025  
**Study Period:** [Insert specific dates]  
**Prepared By:** Rog, Yuan, Ju  
**Total Pages:** 50+ (User Study Schedule) + 40+ (Pilot Study Script) = 90+ pages total

**Status:** ✅ Ready for Study Implementation

---

# FINAL CHECKLIST BEFORE STUDY DAY 1

**48 Hours Before (Saturday):**
- [ ] Confirm all 20 participants (send reminder email with time, location, dress code)
- [ ] Reserve GK401 for full week (Monday-Friday, 8 AM - 4 PM daily)
- [ ] Print all forms (25 consent, 125 questionnaires, 10 battery logs)
- [ ] Charge all devices (laptops, cameras, external batteries)

**24 Hours Before (Sunday):**
- [ ] Complete Setup Day (4:00-7:30 PM)
- [ ] Charge all 7 batteries to 100%
- [ ] Run dress rehearsal (full 50-min participant simulation)
- [ ] Lock room with equipment secured

**12 Hours Before (Sunday Night):**
- [ ] Set alarms for 7:30 AM team arrival
- [ ] Pack any remaining supplies (snacks, water, backup cables)
- [ ] Confirm Monday participants (text message: "See you tomorrow at [time]!")

**Morning Of (Monday, 8:00 AM):**
- [ ] Team arrives at GK401
- [ ] Recharge all batteries to 100%
- [ ] System checks (CrazyFlie, Meta Quest, Lighthouse, cameras)
- [ ] Team briefing (roles, emergency procedures)
- [ ] **9:00 AM: Welcome Participant 1!**

---

**Good luck with your study! This documentation should cover all scenarios. 🚁✨📊**

### 1. **Complete Daily Schedule Added**
- Full 6.5-7 hour timeline for 20 participants
- Three session blocks with strategic charging breaks
- Setup day preparation included
- Recommended timing: ~40-50 minutes per participant

### 2. **Battery Management System (7 Batteries)**

#### Battery Rotation Strategy:
- **Block 1 (P1-P7):** Use batteries B1-B7, then charge all during interviews
- **Block 2 (P8-P14):** Reuse freshly charged B1-B7, charge again during interviews
- **Block 3 (P15-P20):** Use B1-B6, keep B7 as emergency backup

#### Battery Care:
- Voltage monitoring: Must be 3.9-4.2V per cell for flight
- 5-10 minute cool-down between uses
- 45-60 minute recharge time
- Continuous supervision during charging
- Detailed voltage reference guide (100% = 4.2V, 80% = 3.9V, etc.)

### 3. **Comprehensive Safety Protocols**

#### Emergency Procedures:
- Participant distress protocols
- Drone malfunction response
- LiPo battery fire procedures (Class D extinguisher)
- VR-related issue handling
- Multiple kill switch locations

#### Battery Safety:
- Pre-study inspection checklist
- Warning signs for battery retirement
- Storage voltage guidelines (3.8V for long-term)
- Charging temperature requirements (15-25°C)

### 4. **Equipment Checklist Expansion**
Now includes 80+ items organized by category:
- Documents & Forms
- Primary Equipment
- Battery Management (14 items)
- Drone Accessories
- Workspace Setup
- Safety Equipment
- Participant Comfort
- Technical Backup
- Documentation Tools
- Environmental Controls

### 5. **Enhanced Pre-Session Setup (60 minutes)**
Detailed checklist covering:
- Battery management (charging, labeling, voltage testing)
- Workspace setup (2×2m boundary, cameras, Lighthouse)
- VR setup (Meta Quest 3 at >70%, hygiene covers)
- Unity app verification
- CrazyFlie preparation (props, cooling, backup unit)

### 6. **Improved Flow Documentation**

#### Added Pre/Post Flight Checks:
- **Pre-flight (30 sec):** Battery voltage, prop security, radio link, clear zone
- **Post-flight (30 sec):** Motor temperature check, battery logging, anomaly notes

#### Timing Per Participant:
- VR setup: 3-4 min
- MR.Drone condition: 12-15 min
- Transition: 3-5 min
- Drone-Only condition: 12-15 min
- Comparative interview: 8-10 min
- Buffer between participants: 5-10 min
- **Total: 40-50 minutes**

### 7. **Team Role Clarifications**
- **Rog:** Facilitates instructions, guides participants, conducts interviews
- **Yuan:** CrazyFlie operations, battery management, technical monitoring
- **Ju:** VR setup, headset sanitization between participants
- **Recommended 4th member:** Battery charging monitor and logger

### 8. **Participant Safety Enhancements**
- Clearer emergency stop procedures in participant briefing
- Description of CrazyFlie Brushless 2.1 features (lightweight, quiet)
- Motor cooling between flights
- VR hygiene protocols (face covers, sanitization)
- Fatigue monitoring

### 9. **Documentation & Logging**

#### Battery Tracking Log Template:
| Participant ID | Battery Used | Start Voltage | End Voltage | Flight Duration | Notes |
|---------------|--------------|---------------|-------------|-----------------|-------|

#### Additional Logs:
- Battery cycle count tracking
- Equipment condition notes
- Incident/malfunction documentation

### 10. **Environmental Considerations**
- Room temperature control (18-24°C)
- Ventilation requirements
- Lighting control for VR/cameras
- "Study in Progress" signage

## Critical Safety Reminders

### Never:
- Leave charging batteries unattended
- Charge hot batteries (wait for cool-down)
- Fly with battery below 3.9V per cell
- Use water on LiPo fire
- Store batteries fully charged or depleted

### Always:
- Check battery voltage before each flight
- Log battery usage for each participant
- Allow motor cool-down between flights (2-3 min)
- Keep fire extinguisher accessible
- Monitor participant comfort and safety

## Recommended Pre-Study Actions

### One Week Before:
- [ ] Test all 7 batteries (full charge/discharge cycle)
- [ ] Inspect CrazyFlie Brushless 2.1 (motors, props, frame)
- [ ] Calibrate Lighthouse positioning system
- [ ] Test Unity app and avatar co-location
- [ ] Run full dress rehearsal with team member as participant

### Day Before:
- [ ] Full equipment setup in GK401
- [ ] Charge all batteries to 100%
- [ ] System calibration and testing
- [ ] Print all forms and logs (20+ copies)
- [ ] Confirm participant schedule

### Day Of (2 hours before):
- [ ] Team briefing on roles and emergency procedures
- [ ] Final battery charge to 100%
- [ ] Camera and recording tests
- [ ] Clear flight zone
- [ ] Post safety protocols and emergency contacts

## Estimated Timeline Breakdown

- **Setup (pre-study):** 60 minutes
- **Session Block 1 (P1-P7):** 2 hours
- **Charging Break 1:** 30 minutes
- **Session Block 2 (P8-P14):** 2 hours
- **Lunch/Charging Break 2:** 30 minutes
- **Session Block 3 (P15-P20):** 1.5 hours
- **Wrap-up:** 30 minutes
- **Total:** ~7 hours

## Questions to Clarify

1. Do you have a backup CrazyFlie Brushless 2.1 unit?
2. What is the capacity (mAh) of your 7 batteries?
3. Is your 4-port charger a balance charger with cell monitoring?
4. Do you have a Class D fire extinguisher, or should one be obtained?
5. Will participants be scheduled with exact time slots or rolling availability?
6. Do you have insurance/liability waivers beyond consent forms?

---

**Document Updated:** November 4, 2025  
**For Study at:** GK401  
**Total Participants:** 20 dancers  
**Hardware:** CrazyFlie Brushless 2.1 + Meta Quest 3 + Lighthouse
