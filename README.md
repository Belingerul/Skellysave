Advanced Spawner Protection & Automation Utility

SkellySave Critical is a high-performance Fabric utility designed for players who need elite safety protocols. Whether you are managing high-stakes farms or need a frame-perfect fail-safe for your gear, SkellySave provides a robust suite of tools to handle the heavy lifting and protect your progress.

⚙️ The "Save Sequence": How It Works
The heart of the mod is the Save Sequence—a multi-stage, threaded execution engine that automates the extraction and securing of blocks. When triggered, the mod follows a precision-engineered path:

Silent Tool Swap: The mod instantly scans your hotbar for a Pickaxe. It uses Silent Multi-Name Reflection to bypass game restrictions and force a slot change, syncing the choice with the server immediately via packet.

Locked Extraction: The client pitch is set to 90.0 (Straight Down) while forcing the Attack and Sneak inputs. This guarantees you stay stationary and focused on the block during the entire mining duration.

The Precision Grab: After the timer ends, the mod pivots your view to -90.0 (Straight Up) and sends an interaction packet. This forces the client to "reach out" and grab the dropped item entity immediately.

Inventory Vaulting: The mod performs a high-speed loop through your inventory. Any item with "Spawner" in its name is Quick-Moved (Shift-Clicked) into your main storage.

Safety Exit: Finally, it sends a Safety Disconnect packet, removing you from the world instantly to prevent you from being killed or looted.

🚨 Proximity Defense & Discord Alerts
SkellySave features a built-in Proximity Sensor that acts as your eyes when you aren't looking.

Real-Time Monitoring: The mod constantly scans for nearby players within your configured detection range.

Discord Webhook Alerts: The mod is equipped with dual-channel webhooks.

System Armed: Sends a notification to your Discord when you activate the mod, confirming you are protected.

Player Detected: Sends a high-priority alert the moment an unauthorized player enters your radius, including their name, so you know exactly who triggered the sequence.

⌨️ Controls & Configuration
You can calibrate the mod's behavior in real-time using your keyboard. Feedback for every change appears instantly in your Action Bar (above your health/hunger).

F6 (Arm): Turns the system ON. The mod starts scanning for players and sends an "Armed" alert to Discord.

F7 (Disarm): Turns the system OFF. All automation and sensors stop.

UP ARROW (Range): Adjusts the detection radius. Increases by 5m per click (up to 100m). If a player enters this circle, the Save Sequence triggers automatically.

DOWN ARROW (Time): Adjusts the detection radius. Decreses by 5m per click (down to 5m). If a player enters this circle, the Save Sequence triggers automatically.
