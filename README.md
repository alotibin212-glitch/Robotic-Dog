🐕 Quadruped Robot - Initial Design
Prepared by: Noura Abbad Al-Qathami
Technical overview of a Spot-inspired robot dog.
📐 1. Body & Chassis Total Body Length: 200 mm. Chassis Angles: Hip joint tilt is 75° and thigh joint
tilt is 20° for stability. Center of Mass (CoM): Perfectly centered with 
symmetrically oriented knees to prevent tipping.

🦿 2. Legs Design Total Length: 200 mm (0.2 m) per leg. Upper Segment: 100 mm length, 20 mm width, 20 mm height, 5 mm radius. Lower Segment:
100 mm length, 20 mm height, 5 mm radius.

⚙️ 3. Joints & Degrees of Freedom (12 DoF) 3 DoF per leg: Hip Yaw (lateral), Hip Pitch (forward/backward), and Knee Pitch (extension/flexion).

📊 4. Torque Calculation Calculated for the worst-case scenario (supported by 2 legs): Mass (m): 2 kg, Arm Length (L): 0.2 m, Force (F): 9.81 N.
T = F \times L = 9.81 \times 0.2 = 1.962 \text{ N·m} \approx 20 \text{ kg·cm}
Recommendation: RDS3218 servo motors (20 kg.cm), but 30–40 kg.cm motors are preferred for a better safety factor.

🐾 5. Gait Strategy Style: Trot Gait where diagonally opposite legs move simultaneously for balanced motion.

🛠️ 6. Issues & Solutions Problem: Joint vibration or chassis deviation due to low axis precision. Solution: Add ball
bearings to reduce friction, and use 3D-printed resin or rigid plastic to reinforce the structure.
