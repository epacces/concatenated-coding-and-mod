# Applications and Features of Satellite Communications

## Introduction

Satellite communications provide unique solutions for a variety of communication and strategic applications that are only possible in the satellite environment. These applications typically include:

- Multimedia communications provided to wide geographical areas with low population density. In this case, satellite deployment is less expensive than building a corresponding terrestrial network to provide the same service.
- Maritime communications (e.g., Inmarsat) also associated with radio-navigation systems.
- Television broadcasting: a single signal is broadcasted to a wide community of users, making satellite usage more economically efficient compared to a network of local broadcasting stations to cover the same geographical area.
- Earth observation and monitoring systems offering distinctive potential for strategic (military and commercial) information gathering.

All of the above applications require medium to high data rate communication links, which need to be implemented with the resources typical of a spacecraft. Clearly, the available onboard power, weight, and antenna size are limited. This leads to the need to promote state-of-the-art research in modulation and coding, as well as synchronization techniques, to operate as close as possible to the ultimate limits of performance, at very low signal-to-noise ratios, and to save as much bandwidth as possible. Additionally, this bandwidth has to be shared among various coexisting satellites and terrestrial applications.

Hence, state-of-the-art satellite communications for Earth Observation and Telecommunications, among the most appealing applications requiring high data rate modems, are characterized by the need for both maximum information throughput and minimum power and bandwidth consumption. These requirements are evidently contradictory with a theoretical relationship stated by the Shannon Bound. Additionally, available bandwidth, data rate, and signal-to-noise ratio specifications vary from one specific mission to another. An ideal all-purpose MODEM unit, flexible for any mission application and hence commercially appealing, should have the following features:

- Flexible configurability of data rate and allocated bandwidth.
- High variability of signal-to-noise ratio during operation.
- Performance always at a maximum of 1 dB from the Shannon Capacity Bound (fixed modulation and coding quality).
- Efficient utilization of power and hardware resources for processing.

Such a modem would enable a unique off-the-shelf solution, matching the needs of almost all missions for Earth Observation and extra-high-speed telecommunications.

The novel DVB-S2 modulation and coding scheme, as well as the Modem for Higher Order Modulation Schemes (MHOMS) performance, are so close to the Shannon Bound that they are expected to set the modulation and coding baseline for many years to come. The MHOMS program was financed by the European Space Agency (ESA). The envisaged MHOMS modem application scenarios will encompass, at a minimum:

- High-speed distributed Internet access.
- Trunk connectivity (backbone/backhaul).
- Earth observation high-speed downlink.
- Point-to-multipoint applications (e.g., high-speed multicasting/broadcasting).

Further details on MHOMS are available in references [1] and [2].

## Remote Sensing and Earth Observation

Earth observation satellites play a pivotal role in both the civilian and military sectors, monitoring nearly all aspects of our planet. This technology provides truly global coverage, particularly over vast expanses of the oceans and sparsely populated land areas such as deserts, mountains, forests, and polar regions.

Earth observation data are utilized by over 300 research teams, small high-tech firms, large corporations, and public agencies, including meteorological offices. They use Earth-observation data for operational and commercial purposes.

To provide professional services such as oceanography, meteorology, climatology, etc., Earth observation satellites require a high capacity to acquire and process a large volume of images on a daily basis. For example, in full constellation configuration, COSMO-Sky-Med can acquire up to 560 GB per day, roughly corresponding to 1800 standard images.

COSMO-SkyMed, an interoperable system [3], serves as an excellent example of a telecommunications integrated system capable of supporting data exchange with other external observation systems using agreed modalities and standard protocols. COSMO-SkyMed, a low-orbit, dual-use Earth observation satellite system operating in the X-band, is funded by the Italian Ministry of Research (MIUR) and Ministry of Defense, managed by the Italian space agency (ASI). COSMO-SkyMed 1 successfully launched on June 7th, 2007, and COSMO-SkyMed 2 on December 10, 2007.

Thales Alenia Space is the program's prime contractor, responsible for developing and constructing the entire COSMO-SkyMed system, including the space segment with four satellites equipped with high-resolution X-band synthetic aperture radars (SAR). The ground segment, a sophisticated turnkey geographically distributed infrastructure, is realized by Telespazio. It includes the satellite control segment, mission planning segment, civilian user segment, defense user segment, mobile processing stations, and programming cells. Thales Alenia Space is also responsible for the mission simulator, integrated logistics, and all operations up to the delivery of the constellation.

COSMO-SkyMed's system performance is characterized by three key aspects: the space constellation's short revisit time for global Earth coverage, the short system response time, and the multi-mode SAR instrument's imaging performance. COSMO-SkyMed utilizes satellites equipped with advanced remote sensing technology, offering a resolution of less than one meter, and a complex, geographically distributed ground segment. This high image performance is achieved through the versatile SAR instrument, capable of acquiring images in different modes and generating data with varying scene sizes and resolutions, covering a wide range of applications.

Synthetic Aperture Radars (SARs) are primarily used to acquire high-resolution images in large quantities. Thales Alenia Space played a significant role in the development of the X-SAR (SAR operating in X band) space and ground segments. X-SAR is a joint project between NASA, the German space agency (DARA), and the Italian space agency (ASI) as part of NASA's "Mission to Planet Earth." X-SAR can measure virtually any region of the Earth in all weather and lighting conditions, penetrate vegetation, ice, and dry sand, and map the surface, providing scientists with detailed information on climatic and geological processes, hydrological cycles, and ocean circulation.

X-SAR flew on the U.S. Space Shuttle twice, in April and September 1994, both times on Endeavour. These consecutive flights observed the same Earth sites during different seasons to detect seasonal changes, contributing to more precise and reliable monitoring of renewable and nonrenewable resources. The SIR-C/X-SAR missions observed more than 400 sites. Building on the knowledge acquired during these missions, Thales Alenia Space participated in the Shuttle Radar Topography Mission (January 2000), which reused the X-SAR radars to produce the first three-dimensional map of the Earth's surface.

Regarding applications, the space constellations and the versatility of the multi-mode SAR instrument enable a wide variety of image data products with different sizes, resolutions, elaboration levels, and accuracies (e.g., geo-localization). These products are suitable for various application needs, including environmental monitoring, territory surveillance, intelligence applications, and critical phenomena detection. Interferometric images can be used to create three-dimensional Digital Elevation Model products, which are valuable for rendering cities with buildings, streets, or high-resolution topography.

COSMO-SkyMed mission specifications are compatible with numerous applications in civilian and military/security domains, involving 2D or 3D data. 2D applications are mainly related to cartography, while other applications include:

- Agriculture, for crop mapping and management.
- Landscape classification, for basic land use identification.
- Geology mapping for mineral, oil, and gas resource detection.
- Accurate urban area mapping for urban evolution surveys and management, as well as industrial zone mapping with identification of buildings of interest, port installations, storage zones, airports, etc.
- Road and network (electricity, gas, telecom) identification and mapping, for compiling the Geographic Information System (GIS) database, with relevance for applications like radio navigation and safety of life services.
- Survey mapping.

Other application fields concern hydrology, water resource inventory and detection, coastal zones for erosion and coastal line determination. There are various 3D application possibilities:

- **Decision support:** 3D models serve as powerful tools, allowing citizens, city authorities, and management services to understand and explore territories, and build a database for realistic simulations. For example, architecture, urbanization, and new transport infrastructures can be simulated via a 3D database and presented to different stakeholders.
- **Natural and industrial risk management:** Simulation, prevention, and post-crisis activities can benefit from 3D models. Using a Digital Elevation Model combined with a high-resolution image allows simulating phenomena such as floods, fires, earthquakes, air pollution, etc. These simulations can be used in different risk management phases, including preparation of intervention missions, reports of risky areas to survey, simulation of phenomena and related interventions, crisis anticipation, and post-crisis damage evaluation and reconstruction planning.

In mid-2007, Italy and France activated a bilateral image-trading protocol, providing reciprocal access to Helios 2 and COSMO-SkyMed data. This agreement enabled the French and Italian armed forces to benefit from the complementary optical and radar image capabilities of these systems.

This complex and challenging system delivers outstanding security, international cooperation (for civilians and, within NATO countries, for defense), scalability, and interoperability. In other words, COSMO-SkyMed provides Italy and partner countries with one of the world's most technologically advanced observation systems to guarantee greater security and an improved standard of living.

## The Second Generation of Digital Video Broadcasting System

DVB-S2 is the second-generation DVB specification for broadband satellite applications, built upon the success of the first-generation specifications (i.e., DVB-S for broadcasting and DVB-DSNG for satellite news gathering and contribution services). DVB-S2 benefits from the technological advancements of the last decade.

The DVB-S2 system has been designed for various broadband satellite applications, including:

- Broadcasting services of Standard Definition Television (SDTV) and High Definition Television (HDTV).
- Interactive applications oriented towards professional or domestic services (e.g., Interactive Services including Internet Access for consumer applications).
- Professional services of Satellite News Gathering (SNG).
- Distribution of TV signals (VHF/UHF) to Earth digital transmitters.
- Data distribution and Internet Trunking.

The DVB-S2 standard achieves higher data transmission capacity than the first-generation systems, offers enhanced flexibility, and maintains reasonable receiver complexity. It has been specified around three key concepts: best transmission performance, total flexibility, and reasonable receiver complexity.

To achieve a well-balanced ratio between complexity and performance, DVB-S2 benefits from recent developments in channel coding and modulation. The utilization of novel techniques results in a 30 percent capacity increase over DVB-S under the same transmission conditions.

To achieve top-quality performance, DVB-S2 is based on LDPC (Low Density Parity Check) codes, simple block codes with very limited algebraic structure, discovered by R. Gallager in 1962. LDPC codes have an easily parallelizable decoding algorithm consisting of simple operations such as addition, comparison, and table lookup. Moreover, the degree of parallelism is adjustable, making it easy to trade off throughput and complexity. Their key characteristics, allowing quasi-error-free operation at only 0.6 to 1.2 dB from the Shannon limit, include:

- Very large LDPC code block length, 64,800 bits for the normal frame, and 16,200 bits for the short frame.
- A large number of decoding iterations (around 50 Soft-Input-Soft-Output (SISO) iterations).
- The presence of a concatenated BCH outer code (without any interleaver), defined by the designers as a "cheap insurance against unwanted error floors at high C/N ratios."

Variable Coding and Modulation (VCM) functionalities allow different modulation and error protection levels that can be switched frame by frame. The adoption of a return channel conveying the link conditions enables closed-loop Adaptive Coding and Modulation (ACM).

The high flexibility of DVB-S2 allows it to handle various satellite transponder characteristics, with a wide range of spectrum efficiencies and associated C/N requirements. Furthermore, it is not limited to MPEG-2 video and audio source coding; it is designed to handle a variety of audio-video and data formats, including formats that the DVB Project is currently defining for future applications. Since video streaming applications are subject to strict time constraints (around 100 ms for real-time applications), the significant flexibility of the present standard can be effectively exploited to employ unequal error protection [7] techniques and differentiated service levels (i.e., priority in the delivery queues). These techniques aim to achieve graceful degradation of received video quality even in the worst transmission conditions. More details about these interesting unicast IP services are available in [8].

Taking a closer look at the possible applications and relevant definitions, we can see that the DVB-S2 system has been optimized for the following broadband satellite application scenarios:

- **Broadcast Services (BS):** Digital multi-program Television (TV)/High Definition Television (HDTV) broadcasting services. DVB-S2 is intended to provide Direct-To-Home (DTH) services for consumer Integrated Receiver Decoder (IRD), as well as collective antenna systems (Satellite Master Antenna Television - SMATV) and cable television head-end stations. DVB-S2 may be considered a successor to the current DVB-S standard and may be introduced for new services and allow for a long-term migration. BS services are transported in MPEG Transport Stream format. VCM may be applied to multiple transport streams to achieve differentiated error protection for different services (TV, HDTV, audio, multimedia).
  
- **Interactive Services (IS):** Interactive data services, including internet access. DVB-S2 is intended to provide interactive services to consumer IRDs and personal computers. No recommendation is included in the DVB-S and DVB-S2 standards regarding the return path. Therefore, interactivity can be established either via terrestrial connections through telephone lines or via satellite. Data services are transported in (single or multiple) Transport Stream format or in (single or multiple) generic stream format. DVB-S2 can provide Constant Coding and Modulation (CCM) or ACM, where each individual satellite receiving station controls the protection mode of the traffic addressed to it.
  
- **DTVC and DSNG:** Digital TV Contribution and Satellite News Gathering. Digital television contribution applications by satellite consist of point-to-point or point-to-multipoint transmissions, connecting fixed or transportable uplink and receiving stations. Services are transported in single (or multiple) MPEG Transport Stream format. DVB-S2 can provide Constant Coding and Modulation (CCM) or Adaptive Coding and Modulation (ACM). In this latter case, a single satellite receiving station typically controls the protection mode of the full multiplex.

