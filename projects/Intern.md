---
layout: project
type: project
image: img/Daniel-K-Inouye-International-Airport-Tower-only.jpg
title: "Student Engineering Intern"
date: 2023
published: true
labels:
  - Engineering
  - Airports
summary: "I worked as a student engineering intern at the DOT Airports during the Fall 2023 semester."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

During the fall semester of the 2023-2024 academic year, I worked as a student engineering intern for the Department of Transportation, Airports department. Through this position, I learned more about the daily processes and responsibilities of an engineer. The airports department worked on statewide airport projects which includes routine maintenance of the airports to more special projects. I worked directly with the engineers and secretaries to ensure that these projects would run smoothly.

In terms of my responsilities, I was in charge of ensuring that the change orders for the projects were reviewed and approved in a timely manner. This ensured that the airport projects could process and run as efficiently as possible. I also created projects on our system for the engineers to use so they can upload and access project documents. Minor responsibilities included scanning, uploading, and organizing documents. From this internship, I majorly learned how to work in a team.


```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
