# Home Assisant
Collection blueprints for Home Assistant.

## Motion
This Home Assistant automation blueprint turns on a specified light when its associated motion sensor detects continuous movement for at least 3 seconds. This only happens between sunset and sunrise (with configurable time offsets). Once triggered, the light stays on for a minimum of 30 seconds, and then waits for motion to stop before starting a final countdown (configurable duration) to turn the light off. If motion is detected again at any point while the automation is active, the timers restart.

