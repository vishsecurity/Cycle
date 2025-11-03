# Cycling Smartwatch Dashboard

A sleek, interactive web-based **Cyclist Dashboard** inspired by professional smartwatch interfaces. This app provides a **digital clock, timer, and cycling stats** with motivational features, spinning tyres, and a polished UI.

---

## Features

1. **Digital Clock**

   * Real-time display with glowing effect.
   * Rotating motivational quotes every few seconds.
   * Fat tyres spinning as decoration for immersive cycling feel.

2. **Timer**

   * Start, stop, and reset functions.
   * Timer display in HH:MM:SS format.
   * Tyres spin continuously while the timer runs.

3. **Cycling Stats**

   * Upload GPX files from your bike rides.
   * Calculates distance (km), duration (hrs), and average speed (km/h).
   * Tyres spin speed adjusts dynamically based on GPX-derived speed.
   * Toggleable tyre pedaling sound for immersion.

4. **Polished UI**

   * Glassmorphism style panels with blurred backgrounds.
   * Gradient lighting, soft shadows, and glowing effects.
   * Rounded corners and sleek buttons for modern design.
   * Fully responsive and visually appealing.

5. **Motivation**

   * Rotating cycling-inspired quotes to keep users motivated.
   * Examples: *"Keep pushing forward"*, *"Ride your time"*, *"Every mile is progress"*.

---

## Technologies Used

* **HTML5**
* **CSS3** (Flexbox, animations, glassmorphism, gradients)
* **JavaScript** (Clock, Timer, GPX parsing, animations, audio)
* **Google Fonts**: Orbitron (digital display), Poppins (UI text)
* **Audio**: Cycling pedaling sound effect (looped)

---

## Usage

1. **Open `index.html`** in a modern web browser (Chrome, Firefox, Edge).
2. **Switch tabs** using the top menu:

   * 🕒 **Clock**: Shows real-time clock and motivational quotes.
   * ⏱ **Timer**: Start, stop, reset timer; tyres animate continuously.
   * 🚴 **Stats**: Upload GPX files to view cycling stats and adjust tyre speed.
3. **Tyre Sound**: Click the “🔊 Tyre Sound” button to toggle cycling sounds.
4. **GPX Upload**:

   * Choose a `.gpx` file from your ride.
   * Dashboard calculates distance, duration, and average speed.
   * Tyres spin faster/slower depending on your ride speed.

---

## Customization

* **Quotes**: Add/remove motivational text in the `messages` array in `script`.
* **Tyre Design**: Modify `.tyre` CSS class for size, color, and glow effects.
* **Animation Speed**: Adjust `setWheelSpeed()` to scale spin speed differently.
* **Audio**: Replace `tyreSound` source URLs with your preferred sound files.

---

## Future Enhancements

* Add **dynamic road background** to simulate motion.
* Integrate **live GPS tracking** for real-time speed and distance updates.
* Add **calories burned**, **elevation**, and **heart rate** panels.
* Mobile-friendly **responsive adjustments** and touch gestures.



