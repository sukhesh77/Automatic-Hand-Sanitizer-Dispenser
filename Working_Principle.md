# ⚙️ Working Principle

The system works on IR proximity sensing:

1. The IR sensor detects when a hand is placed below the sanitizer nozzle.
2. The sensor sends a signal to the Arduino.
3. The Arduino activates a servo motor for a short duration.
4. The motor pushes the sanitizer bottle or nozzle to dispense a fixed amount.
5. After a delay, the motor resets to the original position.

This ensures a contactless, hygienic operation with minimal power usage.
