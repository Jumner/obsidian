# Lab: The Pendulum - Justin Frank
---
**Purpose:** To determine the relationship between frequency and the length of a simple pendulum

**Apparatus:** List all the equipment used in the experiment
1. 1m+ String
2. 200g weight
3. Metre stick
4. Stopwatch
5. Retort stand
6. Ring clamp
---
## Method:
1. Set up the apparatus as shown in class. 
2. Set the length of the string to approximately one metre and measure the time for 10 vibrations in seconds, to one decimal place. Measure the actual length of the pendulum to the centre of the mass, in metres.
3. Shorten the string by about 10 cm and repeat step 2.
4. Continue shortening the string and making measurements until the string is less than 10 cm long.
---
## Observations
Record all your data in an appropriate table of your own design.
1. 
| Length of String (m) | Time for 10 Cycles (s) |
| -------------------- | ---------------------- |
| 0.966                | 20.1                   |
| 0.791                | 17.7                   |
| 0.725                | 17.0                   |
| 0.617                | 15.9                   |
| 0.512                | 14.3                   |
| 0.393                | 12.4                   |
| 0.296                | 11.2                   |
| 0.216                | 9.5                    |
| 0.121                | 7.1                    |

2. **Record any problems incurred in the experiment**

There are many error sources that could not be accounted for. One example is that air currents could cause uneven drag which might lead to error.

One other minor source of error could be that the length of the pendulum changes throughout the cycle. This is because the tension on the string rapidly changes due to gravity and centripetal forces. This length change could also cause error.

However, in general, there are no significant problems that majorly affected the data. This is reflected by the $\%_{err}$

## Calculations and Data Analysis
1. **Calculate the frequency of the pendulum for each length. Put the frequency values in a new chart with their corresponding length measurements. Show a formal solution of a sample calculation of the frequency.**

$$
\begin{align}
\text{Time interval} = 20.1\\
\text{\#Cycles = 10}\\\\
\text{Frequency} (\text{Hz}) = \frac{\#Cycles}{Time\,interval\,(s)}\\\\

\text{Frequency}\,(\text{Hz}) = \frac{10}{Time\,interval\,(s)} \\\\

\text{Frequency}\,(\text{Hz}) = \frac{10}{20.1}= 0.497 \,\text{Hz}
\end{align}
$$

| Length of String (m) | Time for 10 Cycles (s) | Frequency (Hz) |
| -------------------- | ---------------------- | -------------- |
| 0.966                | 20.1                   | 0.497          |
| 0.791                | 17.7                   | 0.567          |
| 0.725                | 17.0                   | 0.589          |
| 0.617                | 15.9                   | 0.631          |
| 0.512                | 14.3                   | 0.699          |
| 0.393                | 12.4                   | 0.809          |
| 0.296                | 11.2                   | 0.891          |
| 0.216                | 9.5                    | 1.1            |
| 0.121                | 7.1                    | 1.4            |

2. **Plot a $f$ vs $l$ graph (frequency on the y-axis, length on the x-axis)**
### Frequency (Hz) vs Length of String (m)
![[Pasted image 20220210144354.png]]
3. **Use the log-log method to determine the relationship between $f$ and $l$.  Insert graphs and tables from your Google Sheet ($log f$ vs $log l$ and $f$ vs $l^n$)**
### Log-Log Table

| Log(Length of String (m)) | Log(Frequency (Hz)) |
| ------------------------- | ------------------- |
| -0.0150                   | -0.304              |
| -0.102                    | -0.247              |
| -0.140                    | -0.230              |
| -0.210                    | -0.200              |
| -0.291                    | -0.155              |
| -0.406                    | -0.0920             |
| -0.529                    | -0.0500             |
| -0.666                    | 0.024               |
| -0.917                    | 0.14                |

### Log(Frequency (Hz)) vs Log(Length of String (m))
![[Pasted image 20220210165459.png]]
$$\therefore n = -0.491$$
### $x^n$ vs $y$ Table

| (Length of String (m))^n | Frequency (Hz) |
| ------------------------ | -------------- |
| 1.02                     | 0.497          |
| 1.12                     | 0.567          |
| 1.17                     | 0.589          |
| 1.27                     | 0.631          |
| 1.39                     | 0.699          |
| 1.58                     | 0.809          |
| 1.82                     | 0.891          |
| 2.12                     | 1.1            |
| 2.82                     | 1.4            |

### Frequency (Hz) Vs (Length of String (m))^n
![[Pasted image 20220210165643.png]]
4. **In the form f = k l^n, the accepted value for k is 0.498 units. Determine the units of this constant and also determine your relative percent error.**
### Units of constant k
$$
\begin{align}
\text{frequency} = k \cdot l^n\\\\
f = k \cdot l^n\\\\
k = \frac{f}{l^{n}}= 0.497 \frac{\text{Hz}}{m^{-0.491}}
\end{align}
$$
### % Error
$$
\begin{align}
\%_{err} = 100\% \cdot
\frac
{\text{value}_{\text{experimental}} - \text{value}_\text{accepted}}
{\text{value}_\text{accepted}}\\\\

\%_{err} = 100\% \cdot
\frac
{0.497 - 0.498}
{0.498}\\\\

\%_{err} = 100\% \cdot \frac{-0.001}{4.98} = 100\% \cdot -0.002 = -0.2\%
\end{align}
$$
## Conclusion
In conclusion, the equation that describes the relationship between pendulum length and frequency is measured to be $f = 0.497 \cdot l^{-0.491}$.