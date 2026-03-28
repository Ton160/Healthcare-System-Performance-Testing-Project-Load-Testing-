# Healthcare System Performance Testing Project

## Overview
This project demonstrates **performance testing** for a healthcare application scenario using Apache JMeter.  
The goal is to **simulate multiple patient interactions** with an online appointment booking system and evaluate the system behavior under high load, ensuring **efficient service delivery and reliable patient experience**.

---

## Test Plan Details
- **Scenario**: Simulated multiple patients booking appointments and confirming reservations.  
- **Thread Group**: Load_Testing_Group  
  - Number of Virtual Users: 40 patients  
  - Ramp-up Time: 1 second  
  - Test Duration: 5 minutes
- **HTTP Requests (Simulated Healthcare Actions)**:
  1. **Reserve Appointment** (`reserve.php`) – Patients select department and doctor  
  2. **Confirm Appointment** (`purchase.php`) – Patients confirm appointment and payment if needed  
  3. **View Confirmation** (`confirmation.php`) – System provides confirmation details
- **Assertions**:
  - Status code check (200 OK)  
  - Response Data validation (Correct appointment details)
- **Timers**: Constant delays between requests to simulate real user behavior

---

## Project Objectives for BT Role
- Analyze **system performance bottlenecks** for patient booking workflow  
- Evaluate **response time** to ensure minimal waiting time for patients  
- Collect metrics to support **process improvements and digital transformation initiatives** in healthcare operations  
- Demonstrate capability to **link technical testing results with business decision-making**


