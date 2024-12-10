# ESE5190 Final Project - Team 9-eighty five

## Team Members
- Tian Zhang
- Xinyi Wang

## Project Video
<div align="center">
  <video controls width="100%">
  <source src="./attachments/video_test.mov" type="video/mov">

</video>
</div>


## Project Introduction
  People often experience boredom and decreased concentration during prolonged periods of solitary work and study. This common issue not only affects productivity but also impacts mental well-being, potentially leading to stress and reduced learning efficiency.  

  Our goal is to develop a cat bot which has two modes: one is focus mode, in which the cat bot does not make any sound or move, only subtle facial expressions.
The other is the interaction mode, in which the cat bot will have rich facial expressions and behaviors.  

  We hope to switch between these two modes through timed alarms, using focus mode when people need to focus on work or study. After a fixed period of time, the cat bot will sound an alarm to remind people to rest and interact with them.  


## 3. Results

Instead of using two ATmega boards, we use one ATmega board along with an extended port expander (PCF8574). The PCF8574 is connected to the ATmega via I2C and is used to control the motors. We use two channels of a single ADC, rather than two separate ADCs from two different boards as initially planned, which simplifies the circuit.
  
#### 3.1 Software Requirements Specification (SRS) Results

Based on your quantified system performance, comment on how you achieved or fell short of your expected software requirements. You should be quantifying this, using measurement tools to collect data.

#### 3.2 Hardware Requirements Specification (HRS) Results

Based on your quantified system performance, comment on how you achieved or fell short of your expected hardware requirements. You should be quantifying this, using measurement tools to collect data.

## 4. Conclusion

Reflect on your project. Some questions to consider: What did you learn from it? What went well? What accomplishments are you proud of? What did you learn/gain from this experience? Did you have to change your approach? What could have been done differently? Did you encounter obstacles that you didn’t anticipate? What could be a next step for this project?



