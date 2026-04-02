# CS 555 – Human Computer Interaction Lab
**Phase 2**: Analysis  
**Name:** Aleeza Fatima  
**Seat No:** B23110006008  
**Date:** 30 March 2026  

---

## 1. Introduction
In this phase, I analyzed the Polyline Editor system using the Interaction Design Process.  
The goal was to understand user needs, system behavior, and task flow before designing the interface.

This phase focused on:
- Understanding the current system interface
- Identifying user requirements
- Analyzing tasks and interactions

---

## 2. System Overview
**Left Sidebar (Control Panel):**
- Displays the app title: Polyline Editor
- Shows current status: Mode (IDLE) and Grid (ON/OFF)
- Lists keyboard controls

**Main Canvas Area:**
- Large white drawing space
- Used for creating and editing polylines

---

## 3. Current System vs User Needs
**Current System:**
- Keyboard-based controls: b, d, m, r, q, g, s
- Mode indicator shows IDLE
- Grid toggle option
- Empty drawing canvas
- Sidebar with instructions

**User Needs:**
- Easy drawing and editing
- Clear mode switching (DRAW / MOVE / DELETE)
- Real-time visual feedback
- Minimal interface
- Efficient use of keyboard and mouse

---

## 4. Scenario-Based Analysis
- **Starting Drawing:** User presses `b` → system enters DRAW mode → connected lines rendered  
- **Moving a Point:** User presses `m` → clicks near a vertex → drags → polyline updates instantly  
- **Deleting a Point:** User presses `d` → clicks near a vertex → point removed, segments reconnect  
- **Grid Toggle:** User presses `g` → grid shows/hides for alignment  

---

## 5. Task Analysis
**Primary Tasks:**
- Begin drawing a polyline
- Add points with mouse clicks
- Move points by dragging
- Delete points
- Toggle grid
- Refresh canvas
- Save drawing

**Task Flow:**
- Begin drawing: press `b`, mode changes  
- Add point: click on canvas, point and line drawn  
- Move point: press `m` and drag, point moves  
- Delete point: press `d` and click, point removed  
- Toggle grid: press `g`, grid appears/disappears  

---

## 6. User Analysis
- **Beginner Users:** Follow sidebar instructions, may struggle with shortcuts  
- **Intermediate Users:** Learn shortcuts quickly, prefer faster interactions  
- **Advanced Users:** Expect efficiency, prefer minimal UI and keyboard control  

---

## 7. Functional Requirements
The system must:
- Display a drawing canvas
- Support polyline creation with clicks
- Detect nearest vertex for editing
- Allow moving and deleting points
- Provide keyboard controls
- Show current mode and grid status
- Allow saving the drawing

---

## 8. Non-Functional Requirements
**Usability:** Easy to understand interface, clear instructions  
**Performance:** Smooth dragging and rendering, instant visual updates  
**Feedback:** Mode display (IDLE, DRAW, etc.), visual changes on canvas  

---

## 9. Constraints
- Users must click the canvas for interaction  
- Keyboard-only control may confuse beginners  
- No visible buttons, only shortcuts  
- Precision depends on mouse accuracy  

---

## 10. Challenges
- **Discoverability:** Users may not know which keys to press → solution: show controls in sidebar  
- **Mode Awareness:** Users may forget current mode → solution: display mode clearly  
- **Point Selection Accuracy:** Hard to click exactly on a vertex → solution: nearest-point detection  

---

## 11. Opportunities for Improvement
- Add buttons alongside keyboard shortcuts  
- Include tooltips for guidance  
- Add Undo/Redo functionality  
- Highlight selected points visually  
- Implement grid snapping for precision  

---

## 12. Conclusion
The analysis phase helped me understand user interactions with the Polyline Editor.  
It identified key tasks, requirements, and usability challenges.  
This understanding will guide the design phase to improve efficiency, usability, and user experience.  

---

## 13. Learning Reflection
I learned how to analyze a real system before designing.  
By studying the interface, I understood user needs, tasks, and potential challenges.  
This knowledge will help me design more user-friendly applications in the future.  
