## Project Overview

**Challenge:** Ensuring compliance with Walk-Only Zones at Arizona State University has become increasingly challenging due to the widespread use of e-scooters, skateboards, and bikes. These violations pose risks to pedestrian safety and disrupt the tranquility intended by these zones.

**Goal:** Develop a technological solution to enhance compliance with Walk-Only Zones through the use of a Computer Vision (CV) model, thus improving safety and maintaining the integrity of pedestrian spaces.

## Problem Importance

Addressing non-compliance in Walk-Only Zones is crucial for:
- **Safety:** Preventing accidents that could cause injuries.
- **Order:** Maintaining the designated purpose of Walk-Only Zones.
- **Community Integrity:** Reflecting the university’s commitment to rules and a disciplined environment.

## End-to-End Solution

### Solution Lifecycle Steps:
1. **Identify Areas and Times of Non-Compliance:** Target specific zones and times where violations occur.
2. **System Design:** Implement cameras and sensors integrated with a CV system capable of identifying e-scooters, bikes, and skateboards.
3. **Model Implementation:** Use the YOLO model for object detection, configuring it to recognize prohibited vehicles during restricted times.
4. **Integration and Testing:** Ensure the system accurately identifies non-compliant riders and functions reliably in real-time.
5. **Deployment:** Full system rollout in designated zones to enforce compliance effectively.


## Technical Details

- **Data Source:** Utilized real-time and historical image data of e-scooters, bikes, and skateboards.
- **CV Model:** Employed YOLO V8 integrated with MobileNetV2 for fast and accurate object detection suited for mobile use.
- **Model Training and Validation:** Fine-tuned the YOLO model with ASU-specific datasets to adapt to the unique environment of the campus.

## Model Evaluation

- **Metrics:** Loss, Precision, Recall, and Mean Average Precision (mAP).
- **Results:** Achieved high precision and recall rates, indicating robust detection capabilities across various conditions including weather variations and different times of day.

## Business Impact and Metrics

- **Safety Enhancements:** Reduction in non-compliance incidents and accidents.
- **Operational Efficiency:** Decreased need for manual monitoring.
- **Community Satisfaction:** Improved perception of campus safety.

## Resources and Costs

- **Human Resources:** Technicians, data scientists, and IT staff.
- **Systems:** Cameras, servers, software, and cloud services.
- **Costs:** Initial setup and ongoing operational expenses.

## Privacy and Security

- **Data Privacy:** Strict access controls and adherence to data protection laws.
- **Security Measures:** Robust encryption and cybersecurity protocols.

## Future Scope

- **Scalability:** Potential expansion to other campus areas or adaptation for other compliance-related applications.
- **Innovation:** Ongoing refinement and upgrading of the system as technology advances.
