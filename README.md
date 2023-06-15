<!DOCTYPE html>
<html>

<body>
  <h1>Introducing the World Robot Olympiad (WRO) and Team APROMON</h1>

  <p>
    The World Robot Olympiad (WRO) is an esteemed international robotics competition that brings together talented young students from around the globe. In the "Future Engineers" category of the WRO competition, our team, APROMON (comprised of teammates Jonathan Achkouti, Charbel Estephan, and Jad Mouawad), aims to showcase our hardware and software skills by building an Arduino-based self-driving car. Our goal is to win the national WRO competition held in Lebanon and qualify for the international event in Panama.
  </p>

  <h2>Building the Arduino Self-Driving Car</h2>

  <p>
    <strong>Component Overview:</strong> Our Arduino-based self-driving car features a sturdy chassis equipped with two essential motors: a servo motor for steering the front wheels and a DC motor for propelling the rear wheels forward and backward. To effectively control the DC motor, we utilize an H-bridge module. Additionally, the car is equipped with ultrasonic sensors positioned at the front, left, and right sides, as well as a Pixy Cam version 2.1.
  </p>

  <h2>The Open Challenge: Navigating Between Walls</h2>

  <p>
    <strong>Sensor Integration:</strong> In the open challenge, we leverage the raw values from the left and right ultrasonic sensors and convert them into real-life values (in centimeters). This allows the car to maintain a steady course between the two walls that border it. The front ultrasonic sensor acts as a safeguard, preventing collisions with walls. Furthermore, the programmable Pixy2 Cam serves as a reliable indicator, notifying us when the car completes three laps and guiding it to park in the starting position.
  </p>

  <h2>The Obstacle Challenge: Overcoming Traffic Signs</h2>

  <p>
    <strong>Advanced Approach:</strong> In the obstacle challenge, we apply a similar approach while emphasizing the Pixy2 Cam's role. It assists in detecting and tracking traffic sign obstacles placed on the competition mat. By analyzing the sign's color, we determine the appropriate action for the car. If the sign is red, the car passes on the right, while a green sign requires it to pass on the left. With this strategy, we navigate around the obstacles while aiming for optimal completion time and maximum points.
  </p>

  <p>
    <strong>Conclusion:</strong> With a meticulously designed hardware setup and sophisticated software algorithms, our team aims to showcase our technical prowess in both the national and international stages of the WRO competition. We are dedicated to pushing the boundaries of self-driving car technology and bringing home success for APROMON in the exciting world of robotics.
  </p>
</body>
</html>
