# DVB-S2 MODEM Concepts and Architecture

## Modulation and Coding Schemes

The coding/modulation (C/M) problem involves finding practical ways to communicate discrete messages reliably on a realistic channel. This challenge encompasses various communication domains, including space and satellite communications, data transmission over telephone wires, cable TV networks, data storage, digital audio/video transmission, mobile communication, terrestrial radio, deep-space radio, indoor radio, and file transfer. The channel introduces transmission quality degradation due to factors such as attenuation, thermal noise, intersymbol interference, multiple-user interference, multipath propagation, and power limitations.

When selecting a C/M scheme, the primary goal is to make the best possible use of available resources for transmission, including bandwidth, power, and complexity, to achieve the required Quality of Service (QoS). Typically, QoS is expressed in terms of error probability, which is inversely related to the signal-to-noise ratio (SNR). Effective C/M design strategies must balance four factors:

- Error probability requirement, indicating transmission reliability.
- Available bandwidth (spectral efficiency), measuring bandwidth utilization efficiency.
- SNR required to achieve the desired QoS, reflecting power efficiency.
- Implementation complexity, representing equipment cost.

### BICM: Achieving Top Performance with a Single Code and Multiple Modulations

Forward Error Correcting (FEC) codes for satellite applications must combine power efficiency and a low Bit Error Rate (BER) floor with flexibility and simplicity for high-speed implementation. Turbo codes and Low-Density Parity-Check (LDPC) codes have emerged as practical, simple, and powerful coding designs for binary modulations.

In parallel, the field of channel coding for non-binary modulations has evolved significantly. Bit-Interleaved Coded Modulation (BICM) offers a pragmatic approach to achieve excellent results with a standard, non-optimized code. BICM also provides flexibility, allowing a single mother code to be used for several modulations, a valuable feature for broadband satellite communication systems requiring various spectral efficiencies.

### Choice of Modulation Scheme

Changing factors in satellite communication, such as the use of higher frequency bands (e.g., X, Ku, Ka, and Q bands) and large deployable spacecraft antennas with high gain, have shifted the focus from traditional modulation schemes like Quadrature Phase Shift Keying (QPSK) to higher-order modulation schemes. These changes are essential to meet the high data rate demands of modern applications like internet via satellite and Digital Satellite News Gathering (DVB DNSG).

Satellite digital transmissions face power and bandwidth limitations. DVB-S2 addresses these challenges by offering multiple transmission modes, including Forward Error Correction (FEC) coding and modulations, which strike a balance between power and spectrum efficiency. The system supports various coding rates and modulation schemes, adapting to diverse system requirements and link conditions.

Modulation formats provided by DVB-S2 include:
- QPSK and 8-PSK, suitable for broadcast applications.
- 16-APSK and 32-APSK, usable for broadcasting but with higher \(C/N\) ratio requirements and the need for pre-distortion techniques.

![QPSK and 8-PSK DVB-S2 constellations](figure-link-here) *Figure: QPSK and 8-PSK DVB-S2 constellations with normalized radius $`\(\rho=1\)`$*

![APSK constellations](figure-link-here) *Figure: APSK constellations with normalized mean energy*

## The Ultimate Bound to Compare Modem Performance

As formulated by Shannon in 1948, the fundamental challenge in communication is to reproduce a message accurately or approximately at another point. Shannon laid the foundations of Information Theory, emphasizing the logarithmic measure of information and its relation to reliable transmission and channel statistics.

From an engineering perspective, Shannon's work established a crucial link between the mean power available at transmitters and communication reliability. One of the central objectives in satellite applications is to strike the right balance between available power and channel bandwidth, given limited on-board power resources. Shannon's theorem defines a limit on communication performance based on channel capacity, characterized by bandwidth, noise power spectral density, and signal power.

This fundamental relationship is expressed as:
$$C = W \log_2\left(1+\frac{P}{N_0W}\right) \text{ bps}$$
where \(C\) is capacity, \(W\) is bandwidth, \(P\) is signal power, and \(N_0\) is noise power spectral density.

The Shannon Bound defines the lowest power threshold required for reliable communication, ensuring that:
\[
\frac{E_b}{N_0} > 0.693\text{ dB}
\]

In practice, the performance of a communication system can be represented as a point on the Shannon Bound curve, with closer points indicating superior system performance. Spectral efficiency and power efficiency are crucial considerations when optimizing communication systems.

For a detailed performance analysis of modulation and coding schemes in the DVB-S2 modulator, refer to Section XYZ.

