**Thermostat Project Summary – CS350**

The thermostat project for CS350 involved designing and building a functioning smart thermostat prototype using a Raspberry Pi. This system simulated real-world embedded control by managing heating and cooling modes through a state machine. The thermostat used GPIO-controlled LEDs to visually represent states (Off, Heat, Cool), buttons to switch modes and adjust the temperature setpoint, an AHT20 sensor to read temperature, and a 16x2 LCD to display system information. The goal was to solve the problem of managing indoor temperature intelligently, laying the groundwork for connecting future smart thermostats to cloud systems for remote control and analytics.

**What I Did Well:**
I successfully implemented a multi-state system using a clear and functional state machine architecture. My GPIO pin usage, sensor integration, and feedback through LEDs and the LCD display worked reliably. The system responded accurately to button inputs and temperature readings, demonstrating a solid understanding of embedded control and system interaction.

**Areas for Improvement:**
While the system logic was sound, I could improve the physical wiring layout for better reliability and scalability. Adding error handling for sensor failures and input debounce for buttons would enhance robustness. Modularizing code further would also help with testability and maintenance.

**Tools and Resources Added:**
I expanded my toolkit to include libraries like `adafruit-circuitpython-ahtx0` for I2C sensor integration, `RPi.GPIO` for controlling hardware, and threading for managing concurrent LED behavior. I also relied on the Raspberry Pi documentation and open-source forums like Stack Overflow and the Adafruit Learning System.

**Transferable Skills:**
This project helped reinforce my skills in Python scripting, GPIO programming, and hardware-software integration. Understanding state machines, sensor interfacing, and debugging embedded systems will be highly useful in future coursework and real-world IoT or automation projects.

**Maintainability, Readability, and Adaptability:**
I prioritized readable, well-commented code with clear function boundaries for temperature reading, state handling, and display updates. The state machine structure makes it easy to adapt the system for new modes or hardware. I used descriptive variable names and organized logic flow, making the codebase easier to understand and extend.

