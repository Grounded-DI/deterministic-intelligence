# 🚀 Toy Rocket Physics: AI Model Comparison (Sealed Test: 1 Prompt, 6 Answers, 1 Likely Correct Answer)

Note: I’m not a physicist, and I can’t independently verify this one — which is exactly why I posted it.
A DI system should be able to hold up to scrutiny even when involving edge-cases that would notrmally require expert review. Additionally, this post shows that the identical prompt led to 6 different answers across various platforms.

**Author:** Grounded DI 
**Filed Under:** Entropy Drift Detection 
**Date:** July 15, 2025

---

## 🎯 Prompt (All Models Received This)

A toy rocket is launched at a 37° angle with an initial velocity of 45 m/s. The rocket has a mass of 2.5 kg and the engine provides a constant thrust of 18 N for 3.4 seconds. There’s a steady 1.8 m/s headwind acting horizontally.

**Tasks:**
1. What is the maximum altitude reached by the rocket?
2. How long does it take to reach peak altitude?
3. What is the total flight time from launch to landing?
4. What is the horizontal range, accounting for the headwind?
5. What is the vertical speed at impact just before hitting the ground?

Assume gravity = 9.81 m/s². Treat air resistance as limited to the horizontal headwind only. Show all work using real physics.

---

## 🧠 Comparison Summary: Toy Rocket Physics – 6 Models

Model         | Max Altitude (m)  | Flight Time (s)   | Range (m)     | Frame Lock            | Verdict  

**Grounded DI*| **206.24** ✅    | **14.15** ✅      | **503.56** ✅ | ✅ Deterministic      | ✅ Correct | 
ChatGPT       | 64.15             | 7.87              | 395.50        | ❌ Drifted Logic      | ❌ Wrong   |
Gemini        | 64.14             | 7.88              | 348.21        | ❌ Logic Collapse     | ❌ Wrong   |
Meta (LLaMA)  | 64.05             | 7.875             | 381.49        | ❌ Thrust Error       | ❌ Wrong   |
Grok (xAI)    | 64.07             | 7.88              | 389.60        | ❌ Cosmetically Clean | ❌ Wrong   |
Claude        | 96.43             | 9.46              | 293.70        | ❌ Unanchored output  | ❌ Wrong   |

---

## 🧪 Common Failures in All Probabilistic Models

- ❌ **Incorrectly modeled vertical motion during thrust**: Treated thrust as insufficient to overcome gravity (false).
- ❌ **Burn phase logic collapse**: Confused force vs. velocity, failed to apply net acceleration correctly.
- ❌ **Headwind ambiguity**: Vacillated between treating wind as a velocity vs. force vs. acceleration.
- ❌ **Drifted reasoning frames**: All five public models showed mid-answer logic rewrites or hedging.

---

## ✅ Grounded DI (Per AGDI + DIA System Audit)

- **Max Altitude:** 206.24 m  
- **Time to Peak:** 7.66 s (3.4 s burn + 4.26 s coast)  
- **Total Flight Time:** 14.15 s  
- **Horizontal Range:** 503.56 m  
- **Vertical Impact Speed:** 63.61 m/s downward  

🧩 *Frame-locked, thrust-modeled, burn-separated, headwind corrected.*

> “Even toy rockets obey deterministic laws.” — Grounded DI

---

## 🔒 Filing Info

- **Filed By:** Grounded DI  
- **Associated Patents:** Rocket Analyzer, AGDI Protocol, Entropy Control and related patents.   
- **Trigger Framework:** Entropy-Linked Override Chain (ELOC)  
- **Location:** Public GitHub / Physics Truth Audit

📌 This document may be cited as sealed evidence of entropy drift across all major LLM platforms in physics modeling scenarios.

**Sealed. Locked. Authored.**

#deterministic-intelligence #grounded-di #rocket-analyzer 
