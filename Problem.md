# Problem

<!--
The content of this markdown file was migrated to the Quarto project. No need to update this file anymore.
-->

<!--Describe the problem that is being addressed here -->

In recent years, the field of medical device systems engineering has gained significant attention due to the increasing complexity of medical devices and the rigorous regulatory requirements they must meet. As a result, there has been a noticeable growth in the number of books and resources dedicated to medical devices <!--this specialized area of systems engineering-->. Topics covered in these books may include regulatory compliance, risk management, quality assurance, and design principles tailored to medical devices. But there is very few books on systems engineering for medical devices.

<!--On the other hand,-->Systems engineering is a broad discipline applied across various industries, including aerospace, automotive, defense, telecommunications, and more. Therefore, there are numerous books available on systems engineering principles, methods, and applications in these fields.

The number of books on systems engineering of medical devices is fewer in comparison to those covering systems engineering in more established industries.

## Problem from the perspective of non-systems engineers

Lack of a clear understanding of what is systems engineering of medical devices

- Colleagues and senior leadership aren’t clear…
- If it is ‘requirements’ (or even models), why does that add value?
- Medical Device Systems Engineering can look like more paperwork (or more modeling work)
- And have a separate function? Why not hire more software and hardware people “who actually deliver things the customer uses”?

## Problem from the perspective of systems engineers

Medical Device Systems Engineers don't seem to agree what it is…but everyone seems sure they know and are right.

<!-- Source: Chris Unger
Chief Systems Engineer, GE Healthcare, ESEP
Colead, INCOSE Healthcare WG Why is Systems Engineering Challenging
in Medical Technology?-->

<!-- Describe how many books on systems engineering are on medical systems versus other fields. Perform a similar comparison with papers. This would be an interesting comparison to show as a visualization. -->

## Problem modeled as a casual loop

 <!--Show a casual loop that a lack of understanding of systems engineering for medical devices contributes to keep systems engineering low in use in the medical device industry.
 -->

 <!--Pending. Show the diagram as a stock and flow
 stock: systems engineers with medical device systems engineering knowledge
 stock: systems engineers with no medical device systems engineering knowledge
 stock: successfull medical devices
 flow: rate of learning medical device systems engineering
 flow: retirement rate
 flow: expierence rate
 stock: medical device systems engineering knowledge
 flow: knowledge obsolence rate
 flow: updated knowledge rate
 
  -->


 
         +---------------+        +-------------------+
        |               |        |                   |
   +---->   Lack of     +-------->   Low Adoption    |
   |    | Understanding +        |   of Systems      |
   |    | of Systems   |        |   Engineering     |
   |    | Engineering  |        |                   |
   |    +-------+-------+        +-------------------+
   |            |
   |            |
   |            |                +-------------------+
   |            |                |                   |
   |            +---------------->   Ineffective     |
   |                             |   Medical Device  |
   |                             |   Development    |
   |                             |   Processes      |
   |                             |                   |
   |                             +-------------------+
   |
   |                             +-------------------+
   |                             |                   |
   +-----------------------------+   Increased       |
                                 |   Incidents of   |
                                 |   Device Failures|
                                 |                   |
                                 +-------------------+



``` mermaid

---
title: Problem statement modeled as a casual loop
---
flowchart LR
    id1(Lack of Understanding of Systems Engineering)
    id2(Low Adoption of Systems Engineering)
    id3(Ineffective Medical Device Development Processes)
    id4(Increased Incidents of Device Failures)

    id1 --> id2
    id1 --> id3
    id4 --> id1
    

```

**Explanation:**

<!-- Cite in this section the book about Business Dynamics -->

- **Lack of Understanding of Systems Engineering:** This is the starting point of the causal loop. If there's a lack of understanding of systems engineering principles among stakeholders in the medical device industry, it can lead to ineffective utilization or implementation of systems engineering methodologies in the development process.

- **Low Adoption of Systems Engineering:** Due to the lack of understanding, there is low adoption of systems engineering practices in the medical device industry. This leads to insufficient incorporation of systems thinking, integration, and optimization in the development process of medical devices.

- **Ineffective Medical Device Development Processes:** Low adoption of systems engineering results in ineffective medical device development processes. Without proper systems engineering practices, the development processes may lack holistic consideration of all system components, leading to inefficiencies, errors, and delays.

- **Increased Incidents of Device Failures:** Ineffective development processes can contribute to increased incidents of device failures. Without robust systems engineering practices, there's a higher likelihood of design flaws, inadequate testing, and safety issues in medical devices, leading to higher failure rates and potential harm to patients.

- **Loop Reinforcement:** The increased incidents of device failures further reinforce the perception of the importance of systems engineering. However, without addressing the root cause of the lack of understanding of systems engineering, this loop perpetuates, keeping systems engineering low in use in the medical device industry.

This causal loop illustrates how a lack of understanding of systems engineering for medical devices can create a reinforcing feedback loop that perpetuates low adoption of systems engineering practices, leading to ineffective development processes and increased incidents of device failures. Addressing this lack of understanding is crucial for improving the utilization of systems engineering in the medical device industry and enhancing the safety and reliability of medical devices.

## Contributing factors

### Lack of books and literature of systems engineering of medical devices

<!--Show that there is only one out of [total] abstracts submitted to INCOSE International Workshop that talk about medical devices.

Show the quantity of papers that talk about medical device systems engineering.

Show the quantity of books of aerospace versus medical device systems engineering

from aerospace
https://www.google.com/search?sca_esv=94e5231ad7b8805c&rlz=1C1ONGR_enUS1070US1070&sxsrf=ACQVn0_Y01M5jvVeIz5BTLD3vTdFQpRlTg:1710735793799&q=books+on+aerospace+systems+engineering&tbm=bks&source=lnms&sa=X&ved=2ahUKEwjty6y6-_yEAxVzG9AFHcW1AQcQ0pQJegQIWxAB&biw=1535&bih=743&dpr=1.25

from automotive

https://www.google.com/search?q=books+on+automobile+systems+engineering&sca_esv=94e5231ad7b8805c&rlz=1C1ONGR_enUS1070US1070&biw=1535&bih=743&tbm=bks&sxsrf=ACQVn09eXVa8QjEFzcWyBGv_H62nJ2EQ-A%3A1710735799224&ei=t8H3ZeunDfGvur8PmcK--A8&ved=0ahUKEwir3_e8-_yEAxXxl-4BHRmhD_8Q4dUDCAk&uact=5&oq=books+on+automobile+systems+engineering&gs_lp=Eg1nd3Mtd2l6LWJvb2tzIidib29rcyBvbiBhdXRvbW9iaWxlIHN5c3RlbXMgZW5naW5lZXJpbmdIgyRQzwRYryJwAXgAkAEAmAHYAaABpRiqAQYwLjExLjW4AQPIAQD4AQGYAgKgAqQDwgIIEAAYgAQYogSYAwCIBgGSBwMyLTKgB-IX&sclient=gws-wiz-books

 -->

### Fields in which systems engineering is mostly used

Some of the top fields where systems engineering is commonly used include:

- **Aerospace and Defense:** Systems engineering plays a crucial role in designing and developing complex aircraft, spacecraft, missiles, and defense systems.

- **Automotive Industry:** In the automotive sector, systems engineering is essential for designing vehicles with integrated and optimized systems for safety, performance, and efficiency.

- **Information Technology:** Systems engineering is utilized in IT for designing, implementing, and managing large-scale computer systems, networks, and software applications.

- **Telecommunications:** Systems engineering is vital for designing and optimizing telecommunications networks, including mobile networks, satellite systems, and internet infrastructure.

- **Healthcare:** In healthcare, systems engineering is used for designing and improving complex healthcare delivery systems, medical devices, and healthcare information systems.

- **Energy Sector:** Systems engineering is employed in the energy industry for designing and managing complex energy production and distribution systems, including power plants, renewable energy systems, and smart grids.

- **Transportation:** Systems engineering is crucial in designing and optimizing transportation systems, including railways, highways, airports, and public transportation systems.

- **Manufacturing:** Systems engineering is used in manufacturing for designing and optimizing production processes, supply chain management systems, and industrial automation systems.

- **Environmental Engineering:** In environmental engineering, systems engineering is applied to design and manage complex environmental systems, such as water treatment plants, waste management systems, and pollution control systems.

- **Robotics and Automation:** Systems engineering is essential for designing and integrating robotic systems and automation solutions across various industries, including manufacturing, healthcare, and agriculture.