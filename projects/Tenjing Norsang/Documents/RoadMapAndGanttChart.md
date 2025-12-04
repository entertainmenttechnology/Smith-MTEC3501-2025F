# 🗓️ Sonic Evolution — Updated LVP Development Timeline  
### **December 26, 2025 → May 8, 2026** 

The LVP goal:  
A **fully playable Sonic** with abilities and a test level that showcases speed, mobility, and memory-based progression.

---

# **📅 Phase 1 — Ability Foundations**  
### **Dec 26, 2025 – Jan 22, 2026 (≈ 4 weeks)**

**Goals:** Add all major abilities on top of the existing walk/run.

**Tasks:**
- [ ] Implement Boost mechanic (early version)  
- [ ] Implement Stomp  
- [ ] Implement Bounce
- [ ] Implement Air Dash  
- [ ] Implement Homing Attack
- [ ] Implement Spin Dash
- [ ] Implement Quick Step
- [ ] Add transitions between abilities (using placeholder animations if needed)  
- [ ] Add simple Boost VFX (speed lines, trails)  

**Outcome:**  
Sonic can now do everything expected from a modern Boost-style character movement kit.

---

# **📅 Phase 2 — Movement Polish & Tuning**  
### **Jan 23 – Feb 20, 2026 (≈ 4 weeks)**

**Goals:** Make the new abilities feel tight, responsive, and fun.

**Tasks:**
- [ ] Tune Boost values (acceleration, drift, control, deceleration)  
- [ ] Improve slope behavior & ground detection  
- [ ] Polish camera behavior for high-speed play  
- [ ] Enhance animation blending with new states  
- [ ] Add placeholder SFX for moves (boost, stomp, land, dash)  
- [ ] Fix edge-case movement issues (snapping, wall collisions)

**Outcome:**  
A polished, fun Sonic movement system with reliable controls.

---

# **📅 Phase 3 — Test Level Blockout & Interactables**  
### **Feb 21 – Mar 27, 2026 (≈ 5 weeks)**

**Goals:** Build a functional test level that supports high-speed movement.

**Tasks:**
- [ ] Block out a simple multi-path test course:  
  - Straightaways  
  - Curves  
  - Small ramps  
  - Platforms  
- [ ] Add essential interactables:  
  - [ ] Basic springs (vertical & angled)  
  - [ ] Dash pads  
- [ ] Add falling boundaries & respawn system  
- [ ] Add checkpoints (simple version)  
- [ ] Integrate early Boost pickups (optional)

**Outcome:**  
A practical environment for testing Sonic’s full movement toolset.

---

# **📅 Phase 4 — Memory Fragment System (Prototype)**  
### **Mar 28 – Apr 17, 2026 (≈ 3 weeks)**

**Goals:** Introduce the core narrative mechanic in simple form.

**Tasks:**
- [ ] Create Memory Fragment collectible prefab  
- [ ] Implement simple “Unlock Ability When Collected” logic  
- [ ] Add temporary UI popups for unlocked ability  
- [ ] Add a lightweight Meta/Progression Manager  
- [ ] Place fragments around the test level

**Outcome:**  
A basic narrative progression system that ties abilities to Memory Fragments.

---

# **📅 Phase 5 — LVP Polish & Final Build**  
### **Apr 18 – May 8, 2026 (≈ 3 weeks)**

**Goals:** Finalize the LVP and prepare it for demonstration.

**Tasks:**
- [ ] Tune movement & camera one last time  
- [ ] Smooth out test level geometry for better flow  
- [ ] Fix issues with springs, dash pads, and slopes  
- [ ] Clean up placeholder VFX/SFX  
- [ ] Implement minimal UI:  
  - Speedometer 
- [ ] Remove unused scripts/assets  
- [ ] Export final LVP build  

---

# 🎉 **LVP Completion Target: May 8, 2026**

### **LVP will include:**
- ✔ Existing walk/run movement  
- ✔ Boost / Stomp / Slide / Air Dash / Spin Dash / Quick Step abilities  
- ✔ Basic interactables (springs, dash pads)  
- ✔ A functional test level  
- ✔ Memory Fragment → Ability unlock progression  
- ✔ Basic polish (VFX/SFX/UI)  
- ✔ A playable, demonstrable prototype

---

# 📊 Gantt Chart

Legend: █ = Active work, ░ = No work  
(Each column ≈ 1 week)

| Task / Feature | 1<br>Dec 26–Jan 1 | 2<br>Jan 2–8 | 3<br>Jan 9–15 | 4<br>Jan 16–22 | 5<br>Jan 23–29 | 6<br>Jan 30–Feb 5 | 7<br>Feb 6–12 | 8<br>Feb 13–20 | 9<br>Feb 21–27 | 10<br>Feb 28–Mar 6 | 11<br>Mar 7–13 | 12<br>Mar 14–20 | 13<br>Mar 21–27 | 14<br>Mar 28–Apr 3 | 15<br>Apr 4–10 | 16<br>Apr 11–17 | 17<br>Apr 18–24 | 18<br>Apr 25–May 1 | 19<br>May 2–8 |
|----------------|--------------------|--------------|---------------|----------------|----------------|--------------------|---------------|----------------|----------------|---------------------|-----------------|------------------|------------------|----------------------|------------------|-------------------|-------------------|---------------------|------------------|
| **Boost (prototype)** | █ | █ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Stomp** | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Bounce** | ░ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Air Dash** | ░ | ░ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Homing Attack** | ░ | ░ | ░ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Spin Dash** | ░ | ░ | ░ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Quick Step** | ░ | ░ | ░ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Ability transitions / animations** | ░ | ░ | ░ | █ | █ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Boost VFX (temp)** | ░ | ░ | ░ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Boost tuning (speed, drift, accel)** | ░ | ░ | ░ | ░ | █ | █ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Slope physics improvements** | ░ | ░ | ░ | ░ | █ | █ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Camera polish** | ░ | ░ | ░ | ░ | █ | █ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Animation blending improvements** | ░ | ░ | ░ | ░ | ░ | █ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Collision + movement edge-case fixes** | ░ | ░ | ░ | ░ | ░ | █ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Test level — layout blockout** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Test level — ramps/curves/platforms** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Springs (vertical & angled)** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Dash pads** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | █ | ░ | ░ | ░ | ░ | ░ |
| **Boundaries & respawn system** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | ░ | ░ | ░ | ░ | ░ | ░ |
| **Checkpoints (basic)** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | ░ | ░ | ░ | ░ | ░ |
| **Memory Fragment collectible** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | ░ | ░ | ░ | ░ |
| **Ability unlock logic** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | █ | ░ | ░ | ░ |
| **UI popups for ability unlock** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | ░ | ░ | ░ |
| **Final movement polish pass** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | ░ | ░ |
| **Polish VFX/SFX** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | █ | ░ |
| **Speedometer UI** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | █ |
| **Cleanup & final build export** | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | ░ | █ | █ | █ |

