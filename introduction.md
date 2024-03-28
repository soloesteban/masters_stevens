---
title: Introduction
author: "Esteban M. Solórzano Zeledón"
---

<img src="Images/stevens.png" width="100" height="100">

# Introduction

The field of medical device development is rapidly evolving, with advancements in technology and the growing complexity of healthcare systems. Ensuring the safety, efficacy, and compliance of medical devices is paramount to protect patient health and well-being. This project proposes the creation of a comprehensive book that delves into the systems engineering aspects of medical device development.

# Scope

- **Introduction to Medical Devices:** An overview of the medical device industry, its regulatory landscape, and the importance of systems engineering in ensuring device safety and effectiveness.
- **Systems Engineering Fundamentals:** Explaining the core concepts and methodologies of systems engineering, including requirements analysis, design, verification, and validation.
- **Medical Device Lifecycle:** A detailed examination of each phase of the medical device lifecycle, from concept development and design through manufacturing, testing, and post-market surveillance.
- **Regulatory Compliance:** A comprehensive review of the regulatory requirements and standards governing medical devices, such as ISO 13485 and FDA regulations, and how to align systems engineering processes with these requirements.
- **Risk Management:** The integration of systems engineering into risk management.
- **Interdisciplinary Collaboration:** Discussing the importance of cross-functional collaboration among engineers, clinicians, regulatory experts, and other stakeholders in the medical device development process.
- **Case Studies:** Real-world case studies illustrating successful applications of systems engineering principles in medical device projects.

# Background

## Systems Engineering in Medical Device Industry

David M. Cronin from Cognition <!--explain a little bit about the company background-->states that for many, the phrase “systems engineering” is typically associated with large aerospace and defense companies; companies making products that are developed over many years, with long lives in the market, extremely high costs, and a relatively low total number of products manufactured. Many of these companies also employ “large,” permanent teams of systems engineers, which could be daunting to a small device company. Few device engineers are seen at conferences on systems engineering. Instead, these events include transportation, infrastructure, government, space, and of course aerospace and defense. A casual observer might think that systems engineering is not intended for the medical device industry. This is unfortunate!<!-- source: https://blog.cognition.us/medical-product-development-systems-engineering -->

## What is a Medical System?

According to the FDA a medical device (system) is “any instrument, machine, contrivance, implant, in vitro reagent that's intended to treat, cure, prevent, mitigate, diagnose disease”

Source: Section 201(h) of the Federal Food, Drug, and Cosmetic Act

### Examples of medical systems

The following are examples of medical systems. The list is not exhaustive.
<!-- Include photos of examples of medical devices-->

- Spinal Tumor RF Ablation System
- Invasive / Non Invasive Ventilator
- Renal RF Ablation System
- Vascular Compression System
- Intra-Aortic Balloon Pump
- Medical Information Management System
- Endoilluminator
- RF Puncture Generator
- Bleed Monitoring System
- Pulsed Field Ablation System
- Nerve Tissue RF Ablation System

## Medical Device Industry Faces Many Challenges

- Constant time pressure launching safe and effective products
    - ~70% of medical products are delivered late.
    - Time to define requirements has increased 29% and unplanned requirements churn has increased 81%.

- Shifting regulatory landscape
    - E.g., Software as a Medical Device (SaMD), Software in a Medical Device (SiMD), Medical Device Regulation (MDR), In Vitro Diagnostic Regulation (IVDR), etc.
    - Cost of adherence and impact on business strategy.

- Quality issues represent significant fi=nancial impact
    - Non-routine quality events cost the industry between $2.5 and $5 billion per year on average.
    - On average, one company per year has seen a 10% drop in share price after a single, major quality event.

- Constant increasing complexity, particularly with software
    - Software has become the biggest cause of medical device recalls.
    - E.g., The global artificial intelligence/machine learning medical device market was an estimated $4 billion in 2022 and is anticipated to reach $35.5 billion by 2032.
    - E.g., Remote patient monitoring market was valued at $2.1 billion in 2022 and expected to reach $8.1 by 2030.
    - Increasing risk of cybersecurity concerns.

- Heavy focus on acquisition and geographically distributed development teams
    - E.g., The medical devices sector in Q2 2023 witnessed deals worth $33 billion, a growth of 42% compared to Q1 2023 and 87% compared to Q2 2022.

<!-- source:
https://www.mckinsey.com/~/media/McKinsey/McKinsey Solutions/Numetrics/Resources/Insights on  Medical devices Numetrics.pdf , https:/www.mckinsey.com/~/media/mckinsey/dotcom/client_service/public sector/regulatory excellence/the_business_case_for_medical_device_quality.ashx
-->

![alt text](image.png)
<!--Credit to Philip J. O'Keefe, PE, MLE. Image was taken from http://www.engineeringexpert.net/Engineering-Expert-Witness-Blog/systems-engineering-in-medical-device-design-introduction -->

## Medical System Product Life Cycle

- Exploratory: Is there viability to solve a clinical need?
- Technology Development: Can we make this technology?
- Product Development: Create the end product
- Sustaining: Keep a product on the market and enhance the system

Many life saving devices come with significant risk which must be mitigated through a defined system design process. A seamless integration of the design and development process and the safety risk management process will allow devices to be safety used on humans. The development process is described in ISO 13485, the international standard for the development of medical devices. ISO 14971 is the international standard for the evaluation of the safety risk of a medical device.<!--A system engineering approach to the design of medical devices provides a holistic approach to ensuring these devices are safe for their intended use.--> Universities and companies hoping to use their devices in clinical trials on patients are required to follow a well-defined process incorporating design and development planning, design input, design output, design review, design verification, and design validation.
<!--
Source: https://ieeexplore.ieee.org/document/9272015 

M. Wehde, "System Design Approach to Medical Device Development," 2020 IEEE International Symposium on Systems Engineering (ISSE), Vienna, Austria, 2020, pp. 1-3, doi: 10.1109/ISSE49799.2020.9272015. keywords: {Safety;Risk management;Medical devices;ISO Standards;Clinical trials;Standards;Planning;Safety Risk Management;Clinical Trials;Medical Devices},
--->

## Role as Medical Device Systems Engineer

Stakeholders that medical device systems engineers work with:
- Bioinformatics
- Biotechnology
- Biomedical Engineering
- Chemical Engineering
- Clinical Research
- Control Engineering
- Data Science and Analytics
- Design Quality Assurance
- Electrical Engineering
- Finance
- Industrial Engineering
- Materials Engineering
- Mechanical Engineering
- Project Management
- Regulatory Affairs and Compliance
- Software Engineering
- Computer Science
- Supply Engineering
- Systems Engineering

<!--
I could probably put the following in a table format.


Biomedical Engineering: This discipline is at the core of medical system development. Biomedical engineers apply principles of engineering to healthcare and medical fields. They work on devices, imaging technology, prosthetics, and various medical equipment.

Electrical Engineering: Electrical engineers play a crucial role in medical systems, especially in the design of medical devices that involve electronics, sensors, and control systems. They work on everything from circuit design to signal processing.

Mechanical Engineering: Mechanical engineers contribute to the design and development of medical devices, ranging from prosthetics to complex imaging equipment and robotic surgical systems. They focus on mechanics, materials, and product design.

Software Engineering and Computer Science: With the advancement of medical technology, software engineers and computer scientists are essential in developing the software that operates medical devices, manages patient data, and enables communication between different systems.

Bioinformatics and Biotechnology: These disciplines involve the use of computational tools and biological data to develop technologies and software for managing biological information, genomics, and drug development.

Chemical Engineering: In the development of pharmaceuticals, drug delivery systems, and the manufacturing of medical substances, chemical engineers play a significant role in ensuring the efficiency and safety of these elements.

Materials Engineering: Developing new materials that are biocompatible, durable, and safe for medical devices, implants, and equipment is crucial. Materials engineers contribute their expertise in selecting and designing materials suitable for medical use.

Industrial Engineering: Industrial engineers may focus on optimizing healthcare systems, streamlining processes in hospitals or clinics, and improving the overall efficiency of healthcare delivery.

Control Engineering: Control engineers work on systems that require precise control, such as automated drug delivery systems, robotics in surgery, or other systems where accurate control is necessary.


External stakeholders:
Patients
Medicine and Healthcare Professionals
Insurance Companies
Governments

--->

## What is different about Medical Technology Industry versus the “Rest of Systems Engineering”?

<!-- Source: Chris Unger
Chief Systems Engineer, GE Healthcare, ESEP
Colead, INCOSE Healthcare WG Why is Systems Engineering Challenging
in Medical Technology?-->

- Compliance with regulations: Food and Drug Administration (FDA), International Electrotechnical Commission (IEC; French: Commission électrotechnique internationale), International Organization for Standardization (ISO), Health Insurance Portability and Accountability Act (HIPAA), International Classification of Diseases (ICD-10), etc.<!---Provide definitions of the acronyms listed in this sentence -->
- Defects are VERY costly to handle (audit, warning letters, recalls, ...)
- Most products are developed in a geographically distributed way
- Rapid technology evolution is impacting development and delivery
    - AI, IoT, product variants, Mobile Medical Apps, complex deployment models, cloud.
- Extreme time to market pressures: 1st to market usually gains 80% share. <!--Courtesy of Kim Cobb, IBM Rational-->
- Market Driven versus Contract Driven.
    - Customer of “systems engineering” is internal (marketing, product management).
    - Requirements, dates, budgets are more ‘flexible’…success is judged by the market, not by a single customer.


# Project Objectives

The following are the main objectives of this project.

- **OBJ0001**: Design a system that will compile and synthesize knowledge and best practices related to systems engineering in medical device development.
- **OBJ0002**: Provide a comprehensive resource that educates professionals and students in the field of systems engineering about the unique challenges and considerations specific to medical devices.
- **OBJ0003**: Offer practical guidance and tools for applying systems engineering principles throughout the entire lifecycle of medical device development.
- **OBJ0004**: Foster a deeper understanding of the regulatory requirements and standards governing medical devices and how they intersect with systems engineering processes.

<!--March 11, 2024. Probably I need to revisit the objectives. -->

# Impact

The creation of a comprehensive book on the systems engineering of medical devices is essential to bridge the knowledge gap between engineering and healthcare, ensuring the continued development of safe and effective medical technologies. This project aims to contribute significantly to this important field, benefiting professionals, students, and the broader healthcare industry.

This system <!--(book)-->will serve as a valuable resource for:
- Systems engineers looking to specialize in medical device development.
- Healthcare professionals and clinicians seeking a deeper understanding of the engineering processes behind medical devices.
- Regulatory experts striving to align systems engineering practices with compliance requirements.
- Students and educators in systems engineering and biomedical engineering programs.


# Medical Device Systems Engineering

Medical Device Systems Engineering is a multidisciplinary field that encompasses the design, development, and implementation of medical devices. It integrates engineering concepts, medical knowledge, regulatory compliance, and user-centered design principles to ensure the seamless functioning of complex medical systems. This approach bridges the gap between technical innovation and patient-centric care, leading to the creation of advanced devices that address healthcare challenges.
<!--
Citation

C. Nocchi, “Mastering Medical Device Systems Engineering: A Holistic Approach to Healthcare Innovation | LinkedIn.” [Online]. Available: https://www.linkedin.com/pulse/mastering-medical-device-systems-engineering-holistic-chris-nocchi/

 -->

## Components of Medical Device Systems Engineering

- Requirements Analysis and Definition: Understanding the clinical needs and user requirements is the foundation of any medical device. Engineers collaborate closely with medical professionals to define specifications, ensuring that the device aligns with its intended purpose.
- Design and Development: This phase involves translating requirements into tangible design elements, encompassing hardware, software, and user interfaces. Iterative design processes are common, enabling refinements based on feedback and testing.
- Risk Management: Identifying and mitigating risks is essential to ensure patient safety. Engineers assess potential hazards and develop strategies to minimize or eliminate them throughout the device's lifecycle.
- Verification and Validation: Rigorous testing and validation protocols are crucial to verify that the device meets its intended functionality and is safe for use. This includes laboratory testing, simulations, and clinical trials.
- Regulatory Compliance: Adhering to regulations set by authorities such as the FDA, EMA, or other regional bodies is paramount. Engineers ensure that devices meet these standards and navigate the complex landscape of approvals.
- Human Factors Engineering: Designing devices with user experience in mind is critical for healthcare professionals to effectively operate the technology in real-world settings. Ergonomics and usability are key considerations.
- Interoperability and Integration: Many medical devices are part of larger healthcare systems. Ensuring seamless integration and communication between devices is crucial for data exchange and coordinated care.

<!--
Citation

C. Nocchi, “Mastering Medical Device Systems Engineering: A Holistic Approach to Healthcare Innovation | LinkedIn.” [Online]. Available: https://www.linkedin.com/pulse/mastering-medical-device-systems-engineering-holistic-chris-nocchi/

 -->

## Challenges and Best Practices:

- Complexity and Innovation: The integration of diverse technologies, ranging from hardware to software, poses challenges in managing complexity while fostering innovation. Embracing modular design and agile methodologies can streamline the development process.
- Regulatory Compliance: Navigating the regulatory landscape requires a deep understanding of regional requirements. Engaging regulatory experts early in the process and maintaining thorough documentation eases the compliance journey.
- Human-Centered Design: Prioritizing the end user's needs and experience can significantly impact device adoption and success. Regular user testing and feedback loops help refine design elements.
- Risk Management: Identifying and managing risks requires a proactive approach. A thorough understanding of potential hazards, supported by regular risk assessments, is essential.
- Cross-Disciplinary Collaboration: Effective communication among engineers, medical professionals, regulatory experts, and other stakeholders is key. Collaboration fosters a comprehensive understanding of all facets of device development.

<!--
Citation

C. Nocchi, “Mastering Medical Device Systems Engineering: A Holistic Approach to Healthcare Innovation | LinkedIn.” [Online]. Available: https://www.linkedin.com/pulse/mastering-medical-device-systems-engineering-holistic-chris-nocchi/

 -->
