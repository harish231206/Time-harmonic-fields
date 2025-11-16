# Time-harmonic-fields
1. INTRODUCTION
Electromagnetic fields are generally time-varying in nature, meaning they change with respect to time. Among these, a very important class of fields is called Time Harmonic Fields, which vary sinusoidally with time. These are written in the form:
E(t) = Em cos(ωt + φ)
A time harmonic signal is one that repeats itself periodically and allows electromagnetic engineers to simplify Maxwell’s equations.
Most practical applications in communication, microwave engineering, antenna design, radar, satellite communication, optical fiber systems, and AC power systems are based on time-harmonic (sinusoidal steady-state) waveforms.
To simplify analysis, engineers use phasor representation, which converts time-domain sinusoidal functions into complex exponential functions. This converts differential equations into algebraic equations, making calculations easier.
2. THEORY AND DERIVATIONS OF TIME HARMONIC FIELDS
2.1 Phasor Representation
Any sinusoidal time-varying signal can be written as:
E(t) = Re { Ê e^(jωt) }
H(t) = Re { Ĥ e^(jωt) }
Where:
• Ê = phasor representation of the electric field
• Ĥ = phasor representation of magnetic field
• ω = angular frequency (ω = 2πf)
Why Phasors Are Used?
Converts derivatives into multiplication by jω
Helps solve Maxwell’s equations easily
Makes steady-state AC analysis very simple
Example:
If dE(t)/dt in time-domain becomes jωÊ in phasor-domain.
2.2 Maxwell’s Equations in Phasor Forms
Faraday’s Law
∇ × E = – jωμH
Ampere’s Law
∇ × H = (σ + jωε)E
Gauss Law for Electric Field
∇ · (εE) = 0
Gauss Law for Magnetic Field
∇ · (μH) = 0
These equations describe the behaviour and propagation of time-harmonic electromagnetic fields.
2.3 Derivation of Wave Equation
Starting from:
∇ × E = – jωμH
∇ × H = (σ + jωε)E
Taking curl of the first equation:
∇ × (∇ × E) = – jωμ (σ + jωε) E
Using vector identity:
∇ × (∇ × E) = ∇(∇·E) – ∇²E
Since ∇·E = 0 in a source-free region, we get:
∇²E + ω²με E = 0
This is the wave equation, which shows how EM waves propagate.
Propagation Constant
γ = √(jωμ(σ + jωε))
γ = α + jβ
Where:
• α = attenuation constant
• β = phase constant
3. REAL-TIME EXAMPLES OF TIME HARMONIC FIELDS
Example 1: AC Power Systems
The 50 Hz or 60 Hz AC voltage used in homes is sinusoidal and is a perfect example of time harmonic fields.
Example 2: Radio and Television Broadcasting
AM, FM, and TV signals use electromagnetic waves that are time-harmonic.
Example 3: Mobile Communication
Cellular signals (4G/5G) use sinusoidal carriers in GHz range.
Example 4: Microwave Ovens
They operate at 2.45 GHz which is a time harmonic electromagnetic wave.
Example 5: Optical Communication
Even light wavelength signals behave as time-harmonic fields at very high frequencies.
4. ENGINEERING APPLICATIONS OF TIME HARMONIC FIELDS
• Antenna design and analysis
• Microwave circuit and waveguide systems
• Satellite and radar communication
• Wireless systems such as WiFi, Bluetooth and 5G
• Electromagnetic wave propagation studies
• Resonant cavities, filters, oscillators
• MRI machines which use RF sinusoidal magnetic fields
• Transmission lines carrying AC power
• Electromagnetic interference and compatibility design
Time harmonic fields make it possible to analyze all these systems using simple phasor mathematics.
5. ENERGY, POWER AND POYNTING VECTOR
The power carried by electromagnetic waves is described by the Poynting Vector:
S = E × H
Average power density:
S(avg) = (1/2) Re { E × H* }
This is especially used in antenna design, wave propagation, and microwave engineering.
6. PROBLEM SOLVING
Problem 1
Given: f = 2 GHz
Find: Angular frequency ω
Solution:
ω = 2πf = 2π × 2×10⁹
ω = 12.56 × 10⁹ rad/s
Problem 2
Convert E = 50∠45° V/m into time-domain.
Solution:
E(t) = 50 cos(ωt + 45°)
Problem 3
For σ = 0, μ = μ₀, ε = ε₀ at f = 1 GHz, find propagation constant γ.
Solution:
γ = jω√(με) = jβ
Since σ = 0 → no attenuation
α = 0
Problem 4
Given α = 0.3 Np/m and β = 15 rad/m, find γ.
Solution:
γ = α + jβ
γ = 0.3 + j15
Problem 5
Given E = 10 V/m and H = 0.02 A/m, find average power density.
Solution:
S(avg) = 1/2 × E × H
S(avg) = 1/2 × 10 × 0.02
S(avg) = 0.1 W/m²
7. CONCLUSION
Time harmonic fields form the fundamental basis of modern electromagnetic engineering.
By representing fields in sinusoidal phasor form, the equations become easier to analyze.
This concept is essential in antenna design, wireless communication, microwave engineering, radar technology, satellite systems, and optical fiber communication.
Understanding time harmonic fields enables engineers to design efficient, reliable, and high-performance communication and electronic systems.
