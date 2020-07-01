### Begin MATLAB with the TCLab

Welcome to this introductory course on MATLAB! This course is intended to help you start programming in MATLAB from little or no prior experience. There are video tutorials for each exercise if you have questions along the way. One of the unique things about this course is that you work on basic elements to help you with a temperature control project. You will see your MATLAB code have a real effect by adjusting heaters to maintain a target temperature, just like a thermostat in a home or office.

[![Begin MATLAB](https://apmonitor.com/che263/uploads/Begin_Matlab/BeginMatlab00.png)](https://www.youtube.com/watch?v=V8ik7X6I1Sk "Begin MATLAB")

One of the best ways to start or review a programming language is to work on a simple project. These exercises are designed to teach basic MATLAB programming skills to help you design a temperature controller. Temperature control is found in many applications such as home or office HVAC, manufacturing processes, transportation, and life sciences. Even our bodies regulate temperature to a specific set point. This project is to regulate the temperature of the TCLab. Each TCLab has thermochromic (changes color with temperature) paint that turns from black to purple when the temperature reaches the target temperature of 37°C (99°F).

**[Final Project](https://github.com/APMonitor/begin_matlab/blob/master/octave/XX.%20Final%20Project.ipynb)**: Program the TCLab to maintain the temperature at 37°C. Display the heater level with an LED indicator as the program is adjusting the temperature. Create a plot of the temperature and heater values over a 10 minute evaluation period.

To make the problem more concrete, suppose that you are designing a chicken egg incubator. Temperature, humidity, and egg rotation are all important to help the chicks develop. For this exercise, you will only focus on temperature control by adjusting the heater.

**Topics**

There are 12 lessons to help you with the objective of designing the temperature control for the incubator. The first thing that you will need is to [install the required software](https://github.com/APMonitor/begin_matlab/blob/master/octave/00.%20Introduction.ipynb) to open and run the Jupyter notebook files. Any MATLAB-like distribution or Integrated Development Environment (IDE) can be used (MATLAB or GNU Octave) but Jupyter notebook is required to open and run the notebook (`.ipynb`) files. All of the IPython notebook (`.ipynb`) files can be [downloaded at this link](https://github.com/APMonitor/begin_matlab/archive/master.zip). Don't forget to unzip the folder (extract the archive) and copy it to a convenient location before starting.

|**Learning Module**|**Matlab**|**Octave** |
|--|--|--|
| Intro  | [Introduction](https://github.com/APMonitor/begin_matlab/blob/master/matlab/00.%20Introduction.ipynb) | [Introduction](https://github.com/APMonitor/begin_matlab/blob/master/octave/00.%20Introduction.ipynb) |
| 1  | [Overview](https://github.com/APMonitor/begin_matlab/blob/master/matlab/01.%20Overview.ipynb) | [Overview](https://github.com/APMonitor/begin_matlab/blob/master/octave/01.%20Overview.ipynb) |
| 2  | [Debugging](https://github.com/APMonitor/begin_matlab/blob/master/matlab/02.%20Debugging.ipynb) | [Debugging](https://github.com/APMonitor/begin_matlab/blob/master/octave/02.%20Debugging.ipynb) |
| 3  | [Variables](https://github.com/APMonitor/begin_matlab/blob/master/matlab/03.%20Variables.ipynb) | [Variables](https://github.com/APMonitor/begin_matlab/blob/master/octave/03.%20Variables.ipynb) |
| 4  | [Printing](https://github.com/APMonitor/begin_matlab/blob/master/matlab/04.%20Printing.ipynb) | [Printing](https://github.com/APMonitor/begin_matlab/blob/master/octave/04.%20Printing.ipynb) |
| 5  | [Arduino](https://github.com/APMonitor/begin_matlab/blob/master/matlab/05.%20Arduino.ipynb) | [Arduino](https://github.com/APMonitor/begin_matlab/blob/master/octave/05.%20Arduino.ipynb) |
| 6  | [Functions](https://github.com/APMonitor/begin_matlab/blob/master/matlab/06.%20Functions.ipynb) | [Functions](https://github.com/APMonitor/begin_matlab/blob/master/octave/06.%20Functions.ipynb) |
| 7  | [Loops](https://github.com/APMonitor/begin_matlab/blob/master/matlab/07.%20Loops.ipynb) | [Loops](https://github.com/APMonitor/begin_matlab/blob/master/octave/07.%20Loops.ipynb) |
| 8  | [Input](https://github.com/APMonitor/begin_matlab/blob/master/matlab/08.%20Input.ipynb) | [Input](https://github.com/APMonitor/begin_matlab/blob/master/octave/08.%20Input.ipynb) |
| 9  | [If Statements](https://github.com/APMonitor/begin_matlab/blob/master/matlab/09.%20If%20Statements.ipynb) | [If Statements](https://github.com/APMonitor/begin_matlab/blob/master/octave/09.%20If%20Statements.ipynb) |
| 10 | [Arrays](https://github.com/APMonitor/begin_matlab/blob/master/matlab/10.%20Arrays.ipynb) | [Arrays](https://github.com/APMonitor/begin_matlab/blob/master/octave/10.%20Arrays.ipynb) |
| 11 | [Cell Arrays](https://github.com/APMonitor/begin_matlab/blob/master/matlab/11.%20Cell%20Arrays.ipynb) | [Cell Arrays](https://github.com/APMonitor/begin_matlab/blob/master/octave/11.%20Cell%20Arrays.ipynb) |
| 12 | [Plotting](https://github.com/APMonitor/begin_matlab/blob/master/matlab/12.%20Plotting.ipynb) | [Plotting](https://github.com/APMonitor/begin_matlab/blob/master/octave/12.%20Plotting.ipynb) |

**Get TCLab**

You will need a [TCLab kit](https://apmonitor.com/heat.htm) to complete the exercises and they are available for [purchase on Amazon](https://www.amazon.com/TCLab-Temperature-Control-Lab/dp/B07GMFWMRY). 

![Temperature Control Lab](https://apmonitor.com/pdc/uploads/Main/tclab_connect.png "TCLab")

**Install Jupyter Notebook with Matlab or Octave Kernels**

[![Install Jupyter Notebook and Jupyter Lab](https://img.youtube.com/vi/WufMGW5Bv4g/0.jpg)](https://www.youtube.com/watch?v=WufMGW5Bv4g "Install Requirements")

There are additional instructions on how to [install MATLAB](https://apmonitor.com/pdc/index.php/Main/InstallMatlab) or [install Octave](https://www.gnu.org/software/octave/download.html). You will also need the [Matlab kernel](https://pypi.org/project/matlab-kernel) or [Octave kernel](https://pypi.org/project/matlab-kernel) for Jupyter. You can install the kernels with:

```python
pip install octave-kernel
pip install matlab-kernel
```

**Support**

We would love to hear any feedback or problems you would like to send us! We are always trying to improve this course and would like to hear about your experience. We can be contacted at _support@apmonitor.com_.

**Additional Resources**

- [Begin Matlab with the TCLab](https://apmonitor.github.io/begin_matlab)
- [Begin Java with the TCLab](https://apmonitor.github.io/begin_java)
- [Begin Python with the TCLab](https://apmonitor.github.io/begin_python)
- [Temperature Control Lab (TCLab) Kit](https://apmonitor.com/pdc/index.php/Main/ArduinoTemperatureControl)
- [Engineering Programming Course](https://apmonitor.com/che263)
- [Jupyter as interactive environment for Python, Octave, Julia, R](https://jupyter.org/)
