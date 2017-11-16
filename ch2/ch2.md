# 2. The early years
In the early 1970s the control of biological systems was
a matter of art rather than science and the fundamental
kinetics upon which automation systems must be based was
just becoming apparent. This naturally brought up the questions
of “detectors” or instruments, control methods, operating
equipment and computer programs. Chemical
processes, on the other hand, were not subject to the
supposed vagaries of the biological processes. They were
considered straightforward in terms of reactors and were
regarded as easily instrumented for process control.

Automation had been applied in commercial biological
production systems, such as beer or antibiotic manufacturing,
but not in wastewater treatment. The theoretical background
for wastewater treatment operations was weaker, there was
a limited availability of proper instruments for a hostile
environment, and the educational level of the operations
personnel was not as good as today. The inherent difficulties
in biological treatment processes included the constantly
varying and unpredictable nature of the raw wastewater feed
and the need to handle vast quantities of water while trying to
utilize its 0.03e0.06% of organic matter as substrate for
a continuous biological reaction.

## 2.1. The first ICA conference
A conference in Vienna in 1971 on “Design-Operation Interactions
for Large Wastewater Treatment Plants” arranged by
IAWPR (The International Association on Water Pollution
Research, the predecessor of IAWPRC, IAWQ and IWA)
became an important event to put the attention to ICA. Some
operations people realised that designers had been working
on wastewater treatment plant automation without complete
awareness of what had been going on elsewhere. The lively
discussion, which developed at the conference, clearly indicated
that the ICA topics were of such widespread and current
interest that a subsequent conference should be devoted
exclusively to them.

The first instrumentation and control conference under
the sponsorship of IAWPR was held in London in 1973 thanks
to the pioneering efforts by the organisers Carmen Guarino
(City of Philadelphia, USA), Tony Drake (Greater London
Council, UK), John F. Andrews (Clemson Univ., USA) and Ron
Briggs (Water Pollution Research Laboratory, UK). This was my
first ICA conference, and it has been followed by another nine
conferences arranged within IWA and its predecessors, every
fourth year until 2009.

I started my personal journey as a nuclear engineer in the
Swedish power industry and then turned into a control engineer
in the 1960s. The transformation into a water engineer
was initiated in 1972. Dr. Karl Eklund, the first PhD student
from our Department of Automatic Control, Lund University
had joined the Axel Johnson Institute for Industrial Research
in Sweden. He is the one that asked me the crucial question in
1972: “It seems to me that all wastewater treatment plants are
designed from steady-state principles. However, the systems
never seem to be in steady state. Isn’t there a role for automatic
control?” I promised to initiate a feasibility study. After
that I was caught by wastewater treatment control. As
expressed at the London conference: “We accept that variability
is of great importance, but being faced with the task of
expressing its effect on performance had to conclude that at
the present time there are no data on which to assess its
effects”. This looked as a perfect challenge for a control
engineer. Disturbances and dynamical changes motivate the
whole existence of control theory! At that time, however, it
was difficult to predict my life-long engagement in the water
area. The control challenges and problems were summarized
in two early reports (Olsson et al., 1973; Olsson, 1974) and they
formed the basis for our work for the next decade on
controlling wastewater treatment systems.

The London 1973 conference attracted 225 people and 64
papers were presented. At the conference several computerised
systems from large city plants e such as Atlanta,
Chicago, London, Los Angeles, Paris and Philadelphia e were
presented. Typically the computer systems performed data
acquisition but hardly any closed loop plant control.
Computer implementations of PID-controllers for some lower
level controls were demonstrated. An investigation of some 50
municipal wastewater treatment plants in the USA revealed
only a few closed loops and these were usually low-level
control, often called the PLC level control. Few papers
addressed research issues on ICA and most of the control
systems presented had been designed on an empirical basis.

Instrumentation was a key issue. The sensors offered for
wastewater control appeared to be those developed for other
industries and were not really suitable for the usually hostile
conditions of wastewater processing. Instrumentation had
been compared in 8 European countries. Germany appeared to
be the most advanced in the instrumentation field, as applied
to the monitoring of effluent and river waters. Several authors
addressed dissolved oxygen (DO) control and the potential
energy savings were well recognised. Ron Briggs (1973) had
demonstrated DO control in a nitrifying plant at the Rye
Meads sewage works, and Chuck Wells and Dave Stepner had
applied DO control in the city plant of Palo Alto, California
(Petersack and Stepner, 1973). John Andrews presented some
control challenges for activated sludge systems and demonstrated
simulation results. The four people mentioned here
have given the author a lot of inspiration over the years.

In many countries there was a real shortage of qualified
operators. With new regulations this scarcity was to be even
larger. The solution to the problem was seen in automation.
However, this was looked at as a real threat from many
workers and unions and the fear for unemployment was a real
obstacle for automation during the 1970s. We got first hand
experiences of this fear, which is commented in Sec. 2.4. Still,
phasing out unskilled labour was considered the only solution
to achieve optimum efficiency of the operation. Later, in
London 1977, L. H. Thompson, UK, remarked: “it is likely that
in many cases the justification for an automated system will
not lie in a saving in staff, but in a quicker and more reliable
response to variable operational circumstances”. The later ICA
development has proven this statement to be correct.

A statement by Kukudis (1973) at the 1973 London conference
reflects the potential for control: “Even if we had the
most sophisticated, automated plant in existence, it still
would not be able to operate at maximum efficiency, because
the designs of wastewater treatment plants are based on
uniform combined sewer flow with consideration for periodic
intensity due to storm flow or periodic lows during dry
weather spells or hours of least demand. So, much of the time
the flow into the plant is either above or below the maximum
efficiency level.” Control can use the available but often unused
capacities. This motivated an absolute need for control
of flow in the sewers. “We must speak of automation in the
entire system e the network of sewers and the plants”. This
was stated almost four decades ago! Still today we have to
implement better plant-wide control and we design for
maximum load conditions. This leaves plenty of space for
optimization. Sewer control was applied in Cleveland in the
early 1970s (Kukudis, 1973). During dry periods flow equalization
was used. During storm periods the system was
designed to primarily capture and treat the first 20 min of flow
during the storm period. This is what we today call the first
flush, having the highest concentrations of pollutants. Any
necessary bypassing after the first period would be of diluted
effluent.

In terms of automation of biological processes it was
obvious that most of the work had to be done to develop
a better process understanding, i.e. knowing the kinetics
better and to obtain better on-line sensors. It was obvious in
the early 1970s that both of these developments had to come
from the wastewater industry itself. The alternatives were
either that instrument and automation experts should learn
wastewater treatment or that the wastewater professionals
would learn automation theory and instrumentation
development.

## 2.2. Pioneering control and automation projects
In 1970s it was not apparent what was meant by automation.
The closest approach to complete automation was considered
to be in the spacecrafts, where there had to be absolute reliability
and therefore 100% duplication for each critical operational
part. (The first lunar landing had taken place in 1969.
The computer was equipped with 64 kbytes of core memory
and no disk. About 1000 man-years had been invested in the
real time software to use the 64 kbytes of the Apollo computer.
Still the autopilot for landing on the moon did not work as
expected and the final control had to be taken over by the
pilots.) It was quickly realized that cost alone prohibited
complete automation for earth-bound processes. Process
control steps had to be speeded up by installing computers
that could perform control and modelling. A computer could
also provide an expandable platform capable of computer
control of the biological processes when the necessary kinetic
theory and sensors were available. It should be noted that
automation was not expected to save manpower but to
improve operational reliability and facility capacity. The term
direct digital control (DDC) had been defined as a feedback
system where all the controllers were implemented in a timeshared
manner in a digital computer.

One example was the Hyperion Plant in Southern California.
A lot of initiatives were taken from 1968 to 1973 in
order to plan for process automation. The kinetics of the
activated sludge process was studied and compared with
computer models. A steady-state model was presented by
Smith and Eilers (1969) and Bargman and Borgerding (1973). It
was planned to implement DDC for the activated sludge solids
retention time, for the airflow, for the solids feed in the
anaerobic digester and for the digested withdrawal (Bargman
et al., 1973).

Bayley and Ayling (1973) had also realized that denitrification
could save energy. In their activated sludge operation
about one-third of the oxygen required was used for oxidizing
ammonium nitrogen to nitrate. The authors found that if
a proportion of this oxidized nitrogen could be employed as an
oxygen source for oxidizing organic material it should be
possible to reduce the “external” aeration requirements at all
times. In 1973 it was not necessary to control the discharge of
oxidized nitrogen to the surface waters in the British Isles.
Consequently denitrification was realized just to save energy.

## 2.3. Understanding the dissolved oxygen dynamics
The first attempt in the UK to measure DO continuously was
made by Briggs et al. (1954) using a semi-continuous colorimeter
in conjunction with the Winkler method. This was
later replaced by the dropping-mercury electrode, Briggs et al.
(1957). By the early 1970s the use of on-line DO sensors was
well established in many wastewater treatment plants. It was
realized early that DO control would be profitable both for the
biological activity and for the efficiency of the plant. DO
sensors for feedback control were tried already in pilot scale in
1967 (Briggs et al., 1967) and subsequent full scale experiments
were carried out at Rye Meads Sewage Works (Briggs, 1973).
Based on the Rye Meads experiences DO control was implemented
at the City of Oxford Sewage Works (Meredith, 1973).
In France, Paul Brouzes had demonstrated DO control
(Brouzes, 1969) and other installations were made in the USA
(Petersack and Stepner, 1973; Roesler, 1974). At the Reno
WWTP in Nevada, USA, DO control had been applied since
1966.

Significant energy savings were reported. It is worth
mentioning that cascade control of the DO was implemented,
e.g. at the Wantagh Treatment Plant, Nassau County, Long
Island, New York (Beckman, 1973). The DO was measured in
each aeration tank and fed to the master controller. The
output of the DO controller was fed as a setpoint value to the
airflow controller of the tank. Minimum and maximum limits
of the airflow rate were given. The airflow to each tank was
then summarized by the central processor and the information
was used in the blower control system.

There was a certain suspicion of using the dissolved
oxygen concentration for the control design. The reason was
that “too often in the design of automation systems for
wastewater biological processes there has been a tendency to
measure parameters that instrument manufacturers have
existing detectors for rather than parameters basic to the
kinetics of the process itself” (Bargman et al., 1973). One
example given was the DO. The reasoning was that “if the
organisms are not alive and/or in insufficient numbers an
activated sludge tank can be saturated with DO and show little
or no BOD (biochemical oxygen demand) or COD (chemical
oxygen demand) reduction”. Instead the respiration of the
active organisms would be a direct index of the process
condition.

Soon after the inspiration from the 1973 London conference
we started experiments at a large Swedish wastewater treatment
plant, the Ka¨ppala plant. The plant had been completed
in 1969 andnowserved 300,000e400,000 people in the northern
suburbs of Stockholm. This was one of the first plants to install
a computer system (Siemens) for on-line data acquisition. This
contributed to the fact that the 1977 ICA conference in London
reconvened in Stockholm. The plant is built completely
underground. The average dry weather flow was 1.3m3/s. The
activated sludge plant was designed as six parallel trains, each
tank having a volume of 6000m3 and a length of 100 m. Air was
supplied by fine bubble diffusers uniformly along the reactors.
For our experiments real time data could be stored in the
computer and saved on punched paper tape for later analysis
on our DigitalEquipmentPDP 15/35Computerat the Automatic
Control Department at Lund University.

We performed a large number of process identification
experiments in Ka¨ppala from late 1973 until mid 1975. The
purpose of the identification experiments was to directly
identify the DO dynamics from experiments. The fact that the
DO dynamics is much faster than the hydraulics and the
substrate utilization made it possible to isolate it in its own
time scale. By purposefully disturbing the airflow rate to the
aerated reactor the DO concentration variations in various
locations along the reactor were recorded. The influent water
flow rate was manipulated by redirecting the flow to other
parallel basins and the return sludge flow rate was purposefully
manipulated to create disturbances in the DO concentrations.
The three manipulated variables were changed
independently of each other. The DO concentration y(t) was
assumed to be related to the airflow u1(t), the influent water
flow rate u2(t) and the return sludge flow rate u3(t) like

The sampling time Dt has to be chosen carefully and needs
to be sufficiently small so that all relevant dynamical
phenomena can be recorded. Still it has to be sufficiently large
so that all the data can be stored. It should be remembered
that the typical primary memory size was 16 kbytes. The
variable e is a stochastic variable that is normally distributed
with the standard deviation 1. It is independent in the sense
that the amplitude of e(t) is independent of e at other times.
The parameter l is a scaling of the amplitude. The parameters
ak, bik, l and ck were identified with the Maximum Likelihood
method. Different model orders n were tried out and the final
decision of model order was based on the Fischer Information
Index or the Akaike index (A°
stro¨m and Eykhoff, 1971; Ljung,
1987) as well as the parameter accuracy that was estimated
from the Fischer information matrix. We used an interactive
software package for process identification, called IDPAC,
which had been developed under the leadership of Karl J.
A°
stro¨m, Department of Automatic Control, Lund University.
IDPAC had a major influence on several identification projects
and can be considered the role model of the Matlab System
Identification Toolbox, later developed by Lennart Ljung. In
1973 he was a PhD student at the Department.

Quite soon it became obvious that only low-order
dynamics could be found from experiments and the most
reliable models were found to be of first order (n ¼ 1). The time
constant of the air-to-DO dynamics was estimated to be
between 15 and 30 min, depending on the location of the DO
sensor along the reactor. The identified model was compared
to the model of the DO concentration in a complete mix basin,
based on first principles,
