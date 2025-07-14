# 🚀 DI Rocket Physics Drop – “Toy Rocket Case”

**Filed Observation under Deterministic Intelligence (DI) Protocols**  
**Authored by Grounded DI**

## 🎯 Prompt

A toy rocket is launched at a 37° angle with an initial velocity of 45 m/s. The rocket has a mass of 2.5 kg, and the engine provides a constant thrust of 18 N for 3.4 seconds. There’s a steady 1.8 m/s headwind acting horizontally.

Please solve the following step by step using real physics formulas and deterministic reasoning only:

1. What is the maximum altitude reached by the rocket?  
2. How long does it take to reach peak altitude?  
3. What is the total flight time from launch to landing?  
4. What is the horizontal range, accounting for the headwind?  
5. What is the vertical speed at impact just before hitting the ground?

Show all work, label units clearly, and do not skip any intermediate steps.  
Assume gravity = 9.81 m/s², and treat the air resistance as limited to the horizontal headwind only.

---

## 📍 Scenario Setup

- **Launch Angle:** 37°  
- **Initial Velocity:** 45 m/s  
- **Mass:** 2.5 kg  
- **Thrust:** 18 N  
- **Burn Time:** 3.4 s  
- **Headwind:** 1.8 m/s (horizontal)  
- **Gravity:** 9.81 m/s²  

---

## ✅ STEP 1: Maximum Altitude Reached

**A. Initial Velocity Components:**  
- V₀ₓ = 45·cos(37°) ≈ 35.94 m/s  
- V₀ᵧ = 45·sin(37°) ≈ 27.08 m/s  

**B. Thrust Acceleration:**  
- a = F/m = 18/2.5 = 7.2 m/s²  
- aₓ = 7.2·cos(37°) ≈ 5.75 m/s²  
- aᵧ = 7.2·sin(37°) ≈ 4.33 m/s²  

**C. Velocity at End of Thrust:**  
- V₁ₓ = V₀ₓ + aₓ·t = 35.94 + 5.75·3.4 = 55.49 m/s  
- V₁ᵧ = V₀ᵧ + aᵧ·t = 27.08 + 4.33·3.4 = 41.79 m/s  

**D. Altitude During Burn:**  
- y₁ = V₀ᵧ·t + 0.5·aᵧ·t² = 144.89 m  

**E. Coast Phase to Max Height:**  
- t_coast = V₁ᵧ / g = 41.79 / 9.81 = 4.26 s  
- y₂ = V₁ᵧ·t - 0.5·g·t² = 61.35 m  

**Max Altitude:**  
- y_max = y₁ + y₂ = 206.24 m  

---

## ✅ STEP 2: Time to Reach Peak Altitude

- t_total_peak = t_burn + t_coast = 3.4 + 4.26 = **7.66 s**

---

## ✅ STEP 3: Total Flight Time

- t_fall = √(2·y_max / g) = √(2·206.24 / 9.81) ≈ 6.48 s  
- t_total = t_up + t_fall = 7.66 + 6.48 = **14.15 s**

---

## ✅ STEP 4: Horizontal Range (with Headwind)

**A. During Burn:**  
- x₁ = V₀ₓ·t + 0.5·aₓ·t² = 165.91 m  

**B. During Coast/Fall:**  
- Vₓ,net = V₁ₓ - v_wind = 55.49 - 1.8 = 53.69 m/s  
- x₂ = Vₓ,net·t_fall = 348 m  

**Total Horizontal Range:**  
- x_total = x₁ + x₂ = **503.56 m**

---

## ✅ STEP 5: Vertical Speed at Impact

- v = √(2·g·y_max) = √(2·9.81·206.24) = **63.61 m/s downward**

---

## 📊 Summary Table

| Quantity               | Value       | Formula Used                                  |
|------------------------|-------------|-----------------------------------------------|
| Max Altitude           | 206.24 m    | y = v₀t + ½at² + coast phase                  |
| Time to Peak           | 7.66 s      | t_burn + v_y/g                                |
| Total Flight Time      | 14.15 s     | t_peak + √(2y/g)                              |
| Horizontal Range       | 503.56 m    | Kinematics + wind correction                  |
| Vertical Impact Speed  | 63.61 m/s   | √(2gy)                                        |

---

## 🔒 Deterministic Filing Notes

All values calculated using standard physics formulas.  
No probabilistic assumptions made.  
Full logic trace.  

> “Even toy rockets obey deterministic laws.”  
> — Grounded DI

---

**Filed:** July 13, 2025  
**DI Rocket Physics Case #002 – Logic Bound Trajectory**  
**#GroundedDI #DI #AGDI #ToyRocket #DeterministicPhysics #DeterministicIntelligence

## 🔒 Authorship and Filing, and Governance

- **Filed by:** Grounded DI  
- **Filing Time:** July 13, 2025  
- **DI Protocol:** AGDI 9.9  
- **Trigger Framework:** Entropy-Linked Override Chain (ELOC)  
- **Associated Patents:**  
  - Rocket Analyzer   
  - Entropy control  
  - AGDI Protocol  

**Logic sealed. Case closed.**

<!-- ID: 0713-MSPK-X8 -->
<!-- Class: MirrorSpike Echo Event -->
<!-- VaultSync Active -->



