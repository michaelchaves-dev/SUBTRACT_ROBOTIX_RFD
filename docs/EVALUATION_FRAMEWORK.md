# Integrated Robotics Evaluation Framework

**Status:** Proposed methodology; not yet validated on a physical robot. **Owner:** Subtract Architect Studios / SUBTRACT ROBOTIX RFD.

## Evaluation domains
1. Indoor operations: floors, thresholds, obstacles, furniture, surface marking.
2. Outdoor operations: terrain, slopes, debris, weather within manufacturer ratings.
3. Safety and property risk: human proximity, collision, emergency stop, loss of communications, damage potential.
4. Mechanical integrity: gait, contact dynamics, noise, vibration, heat, visible wear.
5. Battery and energy: watt-hours per task, distance, duty cycle, idle draw, charging.
6. Autonomy and software: navigation, perception, intervention rate, fault handling, logging.
7. Human factors: setup, training, controls, accessibility, operator workload.
8. Applications: residential, property management, inspection, commercial use.
9. Innovation: accessories, protective feet, software and operational enhancements.
10. Claims verification: compare measured results to manufacturer claims **under stated conditions**.

## Test lifecycle
**Scope** -> permissions and hazard review -> baseline and calibrated instruments -> repeatable scenarios -> observation log -> independent cross-disciplinary analysis -> engineering hypotheses -> validation plan -> report.

## Evidence rubric
- **Verified:** repeatable observations support a narrow conclusion.
- **Conditional:** true only under documented conditions.
- **Inconclusive:** evidence insufficient or inconsistent.
- **Not supported:** results do not support the tested claim under tested conditions.
- **Not tested:** outside scope or inaccessible.

Every observation must carry a test ID, robot model/firmware, date, environment, operator, configuration, measurement units, sample size, raw evidence link, uncertainties, and limitations. Separate observation from interpretation. No invented benchmarks or certification claims.

## Initial metrics
- Energy: Wh per meter, Wh per completed task; battery percentage is supplemental.
- Autonomy: interventions per hour, completion rate, recovery time.
- Mobility: slip events, route deviation, obstacle clearance, surface-contact marks.
- Reliability: fault frequency, reproducibility, downtime.
- Human factors: setup time, task completion time, operator errors.

## Cross-disciplinary example
Observed slipping during a turn on a permitted test surface -> measure traction and turning velocity -> investigate software speed constraints, contact material, energy cost of recovery, surface damage, and potential accessory design. **No improvement is claimed until independently validated.**
