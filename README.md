Satellite Environmental Performance Simulator (SEPS)
Situation

Satellites in Low Earth Orbit (LEO) are affected by varying solar radiation, eclipse periods, and atmospheric drag. These environmental factors impact satellite power generation and orbital stability, which are critical for mission planning. As a beginner in space systems engineering and data science, I wanted to create a simulation that models these effects using Python.

Task

The goal was to develop a Python-based simulator that:

Analyzes solar radiation over time.

Simulates satellite power output per orbit, including eclipse periods.

Models orbital decay caused by atmospheric drag.

Combines the results in a summary table for visualization and analysis.

Action

To achieve this, I:

Collected or simulated solar flux data and atmospheric density values.

Used NumPy for numerical calculations and mathematical modeling.

Used Pandas to organize data into tables (dataframes) and calculate moving averages.

Simulated satellite power output across orbital phases using the solar panel efficiency formula:

𝑃
=
𝜂
×
𝐴
×
𝐼
×
cos
⁡
(
𝜃
)
P=η×A×I×cos(θ)

Calculated orbital decay due to atmospheric drag using:

𝐹
𝑑
=
1
2
𝜌
𝑣
2
𝐶
𝑑
𝐴
F
d
	​

=
2
1
	​

ρv
2
C
d
	​

A

Created visualizations with Matplotlib to show solar flux trends, power output, and altitude decay over time.

Combined all results into a summary table for easy comparison and analysis.

Result

Successfully simulated a satellite’s power output per orbit including eclipse periods.

Modeled orbital altitude decay due to drag over one year.

Generated clear visualizations that demonstrate environmental impacts on satellite performance.

Built a reusable Python notebook that can be extended with real NASA datasets or used as a learning tool for beginners in space systems and data science.

The project serves as a strong portfolio piece, demonstrating the ability to combine physics, space systems knowledge, and Python programming.

Technologies & Libraries

Python

NumPy

Pandas

Matplotlib
