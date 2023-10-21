# **Virtual Mouse**

This project implements a virtual mouse system using hand tracking and gestures. A webcam tracks the user's hand and detects different gestures to trigger mouse actions like moving, clicking, scrolling, etc.

**How it Works:**

   * Uses OpenCV and MediaPipe for hand detection and tracking
   * Maps hand landmarks to detect gestures like index finger up, pinching, etc.
   * Translates hand movements to control mouse cursor position on screen
   * Detects clicks based on thumb-index pinch gestures
   * Scrolls by tracking vertical index-middle finger motion

**Requirements:**

   * OpenCV
   * Mediapipe
   * PyAutoGUI

**Usage:**

Run python virtual_mouse.py to start the app. Move your hand in front of webcam to control the mouse cursor. Use pinches and vertical motions to trigger clicks and scrolling.

**Limitations:**

   * Only supports basic mouse functions
   * Gesture detection can be inconsistent
   * Not optimized for extremely fast or precise mouse usage
