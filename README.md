# education-technology-edution-technic-career-saqa-scie-bono
engineering data, education
Gmail	tshingombe fiston <tshingombefiston@gmail.com>
nsaqa diploma technologie
tshingombe fiston <tshingombefiston@gmail.com>	Thu, Apr 25, 2024 at 10:38 AM
To: tshingombe fiston <tshingombefiston@gmail.com>
Synopsys Home Page

    Solutions
    Products
    Support
    News
    Company 



    Contact Sales

What is IC Design?

    Home
    Glossary
    IC Design 

Table of Contents

    Importance of IC Design
    Overview of the different steps in an IC Design Flow
    What solutions does Synopsys offer for IC design?

Definition

Integrated circuit design, or IC design, is a part of a larger body of knowledge known as electronics engineering. In the discipline of electronics engineering, there is a process known as circuit design. The goal of circuit design is to assemble a collection of interconnected circuit elements that perform a specific objective function. The ability to add or multiply numbers is a simple example. The development of a microprocessor that executes computer instructions to perform complex tasks is another example.

The circuit elements used in this process begin with fundamental building blocks such as transistors, resistors, capacitors, and wires. These elements are combined to form more complex functions such as logic gates or precision amplifiers, which are then combined to form more complex functions such as adders and multipliers. This process continues to build on itself, resulting in the availability of increasingly complex circuit building blocks. 

Circuit design utilizes discrete, pre-manufactured elements to form the circuit. In the case of IC design, there is an important difference. Here, the circuit elements are made from miniaturized components that are implemented on a silicon substrate using a process called photolithography. The photolithography process creates various geometric shapes on the silicon substrate where the electrical properties of the region defined by that shape are altered. Basic circuit elements are created when these regions are combined and superimposed over each other.

So, IC design consists of two distinct processes. First, circuit elements are assembled to perform the objective function. Next, the various geometric shapes that implement those circuit elements must be assembled and interconnected on the silicon substrate. The first process is typically called logic, or circuit, design and the second process is called physical design. Based on the type of signal being processed by the IC, a digital or analog methodology is used. In the case of an analog/mixed-signal, or AMS, design, both methodologies are used. In addition, how the various circuit elements fit the requirements of the design is also relevant. When circuit elements must be modified to achieve the requirements of the design, a full-custom design methodology is used.
Importance of IC Design

IC design is a critically important discipline. It forms the basis for the development of all microelectronic devices in use today. This includes the microprocessors that power laptop computers and cell phones, the image processing circuits that power computer monitors and television sets, and the sensors that are used in wearable and implanted medical devices. These microelectronic devices also allow the growing use of artificial intelligence (AI) that is opening new frontiers, such as autonomous driving, machine vision, and natural language processing. 

IC technology deployment has become widespread in our world, and IC design forms the foundational set of disciplines required to create these devices.
Overview of the different steps in an IC Design Flow

The process of IC design can be thought of as a series of hierarchical decomposition steps. High-level requirements are decomposed into more details with the goal of implementing a circuit on a silicon wafer that faithfully performs the objective function. The primary steps that make up an IC design flow include:

    Architectural Design. Here, the required functionality of the IC is specified. The capabilities of the specific IC being contemplated will be considered in the context of the system being built. What functions must the IC deliver? What is the required speed and power consumption? What is the target cost of the device?  The answers to these questions will inform subsequent choices for the specific technology that will be used to implement the device. At this stage, “what” is required is most important.  “How” it will be implemented is still not well defined.
    Logic/Circuit Design. Here, macro-level building blocks are assembled and interconnected to implement the required functionality of the IC. Typically, pre-existing building blocks are used, such as memories, processing units, and sensors. High-level functional descriptions of circuit elements are decomposed into the required low-level circuit elements. This process is automated by software called logic synthesis. The collection of devices is simulated to verify the functionality of the design.  Either a digital logic simulator or an analog circuit simulator will be used, depending on the level of simulation detail that is required. If the macro-level building blocks need to be modified to achieve the requirements of the IC, custom circuit design techniques are used. During this step, “how” the chip will be implemented begins to be defined.
    Physical Design. During this step, the actual layout of the interconnected shapes that implement all the required circuit elements on the silicon wafer are created. The process begins with a chip “floor plan,” which defines where each of the primary functions of the chip will be located and where the primary input and output ports of the design will be located. The final circuit elements are then placed and routed in preparation for manufacturing. If the macro-level building blocks need to be modified to achieve the requirements of the IC, custom layout techniques, employing an IC layout editor tool, are used.  “How” the chip will be implemented is now fully defined.
    Physical Verification. All of the physical effects that the manufacturing process adds to the design can now be modeled. Added resistance from wiring, signal crosstalk, and variability in the manufacturing process itself are some of the many items that must be considered here. Will the circuit still work correctly under these stresses? In addition, there are many design rules regarding how the circuit must be physically laid out on the silicon wafer to ensure it will be manufacturable. These design rules are checked at this step as well.
    Signoff. This is the final step before the design is sent to manufacturing. Here, all of the critical parameters that will impact the performance or manufacturability of the chip are verified against the results of “golden signoff” quality tools. Design rules are fully verified during this step, along with design for manufacturability rules.  The timing, power consumption, and signal integrity of the design are also verified and “closed” during this step. It is critical that accurate parasitic extraction is performed during signoff to ensure the physical effects of the process are well understood. The golden signoff Synopsys tools used during this step include IC Validator, PrimeTime®, PrimePower, and StarRC.

When one considers advanced semiconductor technology, there is another aspect of the IC design flow that becomes important. In advanced manufacturing technology, physical effects and process variability play a major role. For example, the physical resistance of the wires that connect circuit elements can cause significant changes in operating voltages and, thus, overall circuit performance. The variability of the manufacturing process can also create unexpected circuit behavior. To deal with these issues, late effects such as wiring delay and process variation must be modeled and considered early in the design process to ensure these effects are accounted for.

In addition, some aspects of the design, such as how it will be tested and how much power it will consume, need to be modeled and refined at each step of the process. These items are too complex to be dealt with at the end of the design. This process of “looking ahead” is called a Shift-Left approach, and it requires a very sophisticated set of design tools and design flows to support it. 
What solutions does Synopsys offer for IC design?

As the market leader in IC design tools, Synopsys offers a comprehensive suite of capabilities that is fully integrated and able to deliver signoff-quality results and support the sophistication required for Shift-Left  design.

The Synopsys Fusion Design Platform™ delivers the full set of capabilities needed to design, verify, and sign off advanced IC designs. The platform is AI-enhanced and cloud-ready. Tools in the platform include:

    Design Compiler® NXT. This is the latest innovation in the Design Compiler family of RTL synthesis products, extending the market-leading synthesis position of Design Compiler Graphical
    TestMAX™. This family of products offers innovative, next-level test and diagnosis capabilities for all digital, memory, and analog portions of a semiconductor device
    IC Compiler™ II. This is the industry-leading place-and-route solution that delivers best-in-class quality-of-results for next-generation designs across all market verticals and process technologies, while enabling unprecedented productivity
    Fusion Compiler. An innovative RTL-to-GDSII product that enables a new era in digital design implementation, offering new levels of predictable quality-of-results to address the challenges presented by the industry’s most advanced designs
    RTL Architect. Represents the industry’s first physically aware RTL analysis, optimization, and signoff system
    IC Validator. This is a comprehensive and high-performance signoff physical verification solution that improves productivity for customers at all process nodes, from mature to advanced
    PrimeTime®. The suite delivers static timing analysis that offers fast, memory-efficient scalar and multicore computing, distributed multi-scenario analysis and ECO fixing using POCV, and variation-aware modeling
    PrimePower. The family enables accurate power analysis for block-level and full-chip designs starting from RTL, through the different stages of implementation, and leading to power signoff
    StarRC. The EDA industry’s gold standard for parasitic extraction

The figure below summarizes the elements of the platform. 
Fusion Design Platform | Synopsys

If custom design techniques are required, the Synopsys Custom Design Platform provides a unified suite of design and verification tools that accelerates the development of robust custom IC designs. Built on the Custom Compiler™ custom design environment, the platform features industry-leading circuit simulation performance, a fast, easy-to-use layout editor, and best-in-class technologies for parasitic extraction, reliability analysis, and physical verification.

Platform tools include:

    Custom Compiler. Providing design entry, simulation management and analysis, and custom layout editing features
    PrimeSim XA. Featuring the FastSPICE simulator to deliver superior verification performance and capacity for all classes of design
    IC Validator. A comprehensive and high-performance signoff physical verification solution that improves productivity for customers at all process nodes
    PrimeSim HSPICE. The gold standard for accurate on-chip simulation and silicon-to-package-to-board-to-backplane signal integrity simulation and analysis
    StarRC. The gold standard for parasitic extraction
    PrimeSim SPICE.  A multi-core/multi-machine simulator that is well-suited for the simulation of large, complex analog circuits
    PrimeWave Design Environment. A graphical waveform viewer and simulation post-processing tool for analog and mixed-signal ICs
    SiliconSmart. A comprehensive array of library characterization and quality assurance capabilities to generate the models required for digital signoff tools such as PrimeTime
    PrimeSim Reliability Analysis. HSPICE, FineSim, and CustomSim support a comprehensive set of reliability and Monte Carlo analysis features to ensure circuits operate correctly in the face of variability

Custom Design Platform | Synopsys
Continue Reading
News Release
Sondrel Selects Synopsys Fusion Design and Verification Platforms to Displace Legacy Design Tools

Sondrel Accelerates SoC Design and Packaging with Synopsys Solutions
Learn More →
News Release
Synopsys and Samsung Foundry Collaborate to Deliver Fastest Design Closure and Signoff for Process Nodes Down to 3nm

Signoff Flow Enables High-Performance Computing, 5G and AI Advanced Design to Achieve Fastest Time-to-Results with Superior Power, Performance and Area
Learn More →
News Release
Synopsys and Samsung Foundry Collaboration Delivers Optimized Reference Methodology for High-Performance Compute Designs

Synopsys Fusion Design Platform Enables Full-Flow Quality-of-Results and Fastest Design Convergence on Samsung Advanced Process Technology
Learn More →

Footer
Synopsys Home Page
Corporate

    About Us
    Careers
    ESG
    Inclusion & Diversity
    Investor Relations
    View our Office Locations
    Contact Us

Products

    Application Security
    Semiconductor IP
    Verification
    Design
    Silicon Engineering

Resources

    Solutions
    Services
    Support
    Community
    Academic & Research Alliances (SARA)
    Manage Subscriptions

Learn

    Blogs
    Press Releases
    Newsroom
    What is EDA?
    What is Application Security?

Legal

    Privacy
    Trademarks & Brands
    Software Integrity Agreements
    Security
    Copyright

Follow



©2024 Synopsys, Inc. All Rights Reserved

On Thu, Apr 25, 2024 at 10:35 AM tshingombe fiston <tshingombefiston@gmail.com> wrote:















    [MDPI Open Access Journals]

        Journals
        Topics
        Information
        Author Services
        Initiatives
        About 

    Sign In / Sign Up Submit
     
    Search for Articles:
    Advanced
     
    Journals
    Electronics
    Volume 10
    Issue 9
    10.3390/electronics10091032
    electronics-logo
    Submit to this Journal Review for this Journal Propose a Special Issue
    Article Menu

        Academic Editors
        Turchetti Claudio
        Falaschetti Laura
        Subscribe SciFeed
        Recommended Articles
        Related Info Link
        More by Authors Links 

    Article Views 4970
    Citations 3

        Table of Contents
            Abstract
            Introduction
            Proposed GateRL Architecture
            Experimental Results
            Conclusions
            Author Contributions
            Funding
            Conflicts of Interest
            References

    share Share announcement Help format_quote Cite question_answer Discuss in SciProfiles thumb_up Endorse textsms Comment
    first_page
    Download PDF
    settings
    Order Article Reprints
    Open AccessArticle
    GateRL: Automated Circuit Design Framework of CMOS Logic Gates Using Reinforcement Learning
    by
    Hyoungsik Nam
    * [ORCID] ,
    Young-In Kim
    ,
    Jina Bae
    and
    Junhee Lee
    Department of Information Display, Kyung Hee University, Seoul 02447, Korea
    *
    Author to whom correspondence should be addressed.
    Electronics 2021, 10(9), 1032; https://doi.org/10.3390/electronics10091032
    Submission received: 5 April 2021 / Revised: 22 April 2021 / Accepted: 24 April 2021 / Published: 26 April 2021
    (This article belongs to the Special Issue Machine Learning in Electronic and Biomedical Engineering)
    Download keyboard_arrow_down Browse Figures
    Versions Notes

    Abstract
    This paper proposes a GateRL that is an automated circuit design framework of CMOS logic gates based on reinforcement learning. Because there are constraints in the connection of circuit elements, the action masking scheme is employed. It also reduces the size of the action space leading to the improvement on the learning speed. The GateRL consists of an agent for the action and an environment for state, mask, and reward. State and reward are generated from a connection matrix that describes the current circuit configuration, and the mask is obtained from a masking matrix based on constraints and current connection matrix. The action is given rise to by the deep Q-network of 4 fully connected network layers in the agent. In particular, separate replay buffers are devised for success transitions and failure transitions to expedite the training process. The proposed network is trained with 2 inputs, 1 output, 2 NMOS transistors, and 2 PMOS transistors to design all the target logic gates, such as buffer, inverter, AND, OR, NAND, and NOR. Consequently, the GateRL outputs one-transistor buffer, two-transistor inverter, two-transistor AND, two-transistor OR, three-transistor NAND, and three-transistor NOR. The operations of these resultant logics are verified by the SPICE simulation.
    Keywords:
    automated circuit design; CMOS logic gate; reinforcement learning; action masking

    1. Introduction
    Over the past decade, machine learning (ML) algorithms, especially deep learning (DL) approaches, have attracted lots of interests in a variety of applications, such as image classification [1], object detection [2], image/video search [3], super resolution [4], language translation [5], speech recognition [6], stock market prediction [7], and so on, due to their dramatic advances, along with highly increased processing power and huge amount of training datasets [8].
    Besides, there have also been many ML-related research studies on the field of the circuit design [9]. One direction is to implement ML networks in existing or specialized hardware platforms. While various simplification methods have been proposed to alleviate the requirement on processing power and data bandwidth [10,11,12], highly complicated and large size DL networks have been realized based on specialized integrated circuit solutions, such as tensor processing units (TPUs) [13] and general purposed graphics processing units (GPGPUs) [14] that enable the acceleration of DL computations. The other approach is to employ ML algorithms during the course of the integrated circuit design. ML methods optimize transistors’ sizes of a given circuit schematic in various points of view of target performances, including power consumption, bandwidth, gain, and area [15,16]. At the layout stage, MLs automate the placement procedure to avoid the routing errors in advance for the small chip area [17,18]. These approaches lead to the substantial reduction on the overall design time by the much smaller number of iterations in simulation and layout stages. In particular, a Berkeley analog generator (BAG) has been studied as the designer-oriented framework since 2013 [19,20]. BAG contains the whole circuit design procedures, including schematic, layout, and verification. Its schematic design platform selects one architecture for a given specification and optimizes parameters. The DL-based layout optimization for a BAG framework was also proposed in 2019 [21].
    On the other hand, to the best of our knowledge, there have been no research results to devise DL to design the circuit structure from the scratch at the transistor level. These circuit structure generators cannot avoid very large hypothesis space because a transistor have three terminals of source, gate, and drain that can be connected to each other and used as input, output, or internal node. As a result, it is much more difficult to give rise to the custom schematic directly than to use given circuit blocks that have dedicated ports for inputs and outputs. This paper proposes an automated schematic design framework (GateRL) for digital logic gates, such as inverter, buffer, NAND, AND, NOR, and OR, at the backplane of complementary metal on semiconductor (CMOS) transistors. This full custom design scheme is required for special circuits in the situation with limitations, such as thin-film transistor (TFT) shift registers integrated in display panels, where only one-type TFTs are allowed [22,23,24,25]. While most off-the-shelf applications have been based on the supervised learning networks trained with a huge amount of data and labels, the GateRL employs the reinforcement learning (RL) [26] because the schematic design is difficult to provide labels and only whether the resultant circuit works or not can be decided. The remaining parts are organized as follows. In Section 2, the proposed GateRL is explained in detail by addressing overall architecture and variables exchanged between agent and environment. Section 3 demonstrates the experimental results that include the schematics proposed by the GateRL and their simulation results by simulation program with integrated circuit emphasis (SPICE). Section 4 concludes this paper.
    2. Proposed GateRL Architecture
    A proposed GateRL system is based on the RL methodology that consists of agent and environment, as shown in Figure 1. While the agent sends an action (𝑎𝑡
    ) to the environment to add a new connection to the schematic, the environment updates state (𝑆𝑡+1), reward (𝑟𝑡+1), and mask (𝑀𝑡+1
    ) and transfers them to the agent again. Unlike general RL networks, the GateRL makes use of the action masking scheme to take into account several constraints in the circuit design, as well as to reduce the size of the action space [27]. The target logic gate is specified by the truth table (T), where corresponding outputs are described over all the combinations of inputs.
    Electronics 10 01032 g001 550
    Figure 1. Proposed GateRL block diagram.
    2.1. State (𝑆𝑡
    )
    𝑆𝑡
    is extracted from the connection matrix (CM) that is similar to an adjacency matrix of a graph theory [28]. As depicted in Figure 2, all possible nodes of the schematic are equally assigned to columns and rows of CM, leading to the shape of a square matrix. 𝑁𝑖, 𝑁𝑜, 𝑁𝑛, and 𝑁𝑝 are the numbers of inputs, outputs, n-type MOS (NMOS) transistors, and p-type MOS (PMOS) transistors, respectively. Therefore, the total number of columns or rows (𝑁𝐶𝑀) can be obtained by Equation (1). The first two columns and two rows represent connections to supply voltage sources of VDD and GND. In particular, because transistors have three terminals of source (S), gate (G), and drain (D), the numbers of their nodes are calculated by means of the product of the number of transistors and the factor of 3. The connections of their body terminals are omitted by assuming that bodies of all NMOS and PMOS transistors are fixed at GND and VDD, respectively. From here, the node assigned to the i-th row or column is addressed as the node i (𝑖=1,2,…,𝑁𝐶𝑀).
    𝑁𝐶𝑀=2+𝑁𝑖+𝑁𝑜+3𝑁𝑛+3𝑁𝑝.
    (1)
    Electronics 10 01032 g002 550
    Figure 2. Connection matrix (CM) configuration.
    An element of CM at i-th row and j-th column (𝑐𝑚𝑖𝑗
    ) is assigned to 0 or 1, where 0 means no connection, and 1 indicates the connection between two corresponding nodes as expressed in Equations (2) and (3). Therefore, the circuit schematic can be extracted from a given CM. For example, CM of Figure 3a is converted into the schematic of Figure 3b, where 𝑁𝑖, 𝑁𝑜, 𝑁𝑛, and 𝑁𝑝 are 1, 1, 1, and 0. In addition, since all the connections in the circuit schematic are undirected, CM is constructed as a symmetric matrix.
    𝐶𝑀=(𝑐𝑚𝑖𝑗),𝑤ℎ𝑒𝑟𝑒1≤𝑖≤𝑁𝐶𝑀 𝑎𝑛𝑑 1≤𝑗≤𝑁𝐶𝑀,
    (2)
    𝑐𝑚𝑖𝑗={0,1,Without connection between node 𝑖 and node𝑗With connection betweennode 𝑖 andnode𝑗.
    (3)
    Electronics 10 01032 g003 550
    Figure 3. Example of schematic extraction from a given CM. (a) Example CM. (b) Extracted schematic.
    In the connection of circuit elements, there exist constraints on CM. Firstly, direct connections between VDD, GND, inputs, and outputs must not be allowed to avoid shoot-through currents between voltages sources and to guarantee the functionality of outputs according to the combinations of inputs. Thus, the corresponding area of CM is always filled with 0. Secondly, the self-connections described by diagonal elements have no meaning in the circuit, leading to the diagonal elements (𝑐𝑚𝑖𝑖,𝑖=1,2,…,𝑁𝐶𝑀
    ) fixed at 0 all the time. Thirdly, as CM is a symmetric matrix, the full matrix can be reconstructed from the half area over the diagonal. As a result, the whole CM can be represented with the area marked in Figure 4 that is reshaped into 𝑆𝑡 in a form of a vector by flattening. Its length (𝑁𝑠) is calculated as Equation (4) that is derived by dividing the region into a rectangular part and a triangular part.
    𝑁𝑠=(2+𝑁𝑖+𝑁𝑜)(3𝑁𝑛+3𝑁𝑝)+(3𝑁𝑛+3𝑁𝑝−1)(3𝑁𝑛+3𝑁𝑝)2=3(𝑁𝑛+𝑁𝑝)(3𝑁𝑛+3𝑁𝑝+2(2+𝑁𝑖+𝑁𝑜)−1)2=3(𝑁𝑛+𝑁𝑝)(𝑁𝐶𝑀+𝑁𝑖+𝑁𝑜+1)2.
    (4)
    Electronics 10 01032 g004 550
    Figure 4. State definition. Because a symmetric CM does not allow self-connection, as well as connections between VDD, GND, inputs, and outputs, the marked area contains the whole information for CM. They are flattened into a state vector (𝑠𝑡
    ).
    2.2. Mask (𝑀𝑡
    )
    In addition to three above constraints, the proposed algorithm defines two more constraints that can be applied during schematic design steps. The first one is that VDD, GND, and inputs should not be connected to each other through a single transistor. This connection causes the short circuit situation between voltage sources. Thus, any two nodes among them must not be connected to source and drain terminals of the same transistor, respectively. For example, whenever VDD is linked to the source of a transistor, GND and inputs cannot be placed at its drain. The second constraint is that the connection of a single signal to both source and drain of a transistor is not allowed. Because this connection can be replaced with a simple short circuit, that transistor is not necessary.
    𝑚𝑚𝑖𝑗={0,1,if available connection between node 𝑖 and node𝑗if prohibited connection between node 𝑖 and node 𝑗.
    (5)
    In the first place, a masking matrix (MM) is generated with respect to the current CM. MM is also the square matrix of 𝑁𝐶𝑀×𝑁𝐶𝑀
    where each element (𝑚𝑚𝑖𝑗
    ) of 0 or 1 represents whether that connection is available or not, respectively as described in Equation (5). Four masking criteria are reflected on MM as follows. First, since it is not necessary to repeat existing connections, corresponding elements of MM are set to be 1. Second, all direct connections between VDD, GND, inputs, and outputs are blocked. When a node is connected to one of VDD, GND, inputs, and outputs, that node must not be connected to any others of them. Therefore, elements of those short connections are also marked as 1 in MM. Third, when one of source and drain terminals is connected to VDD or GND or inputs, the other terminal of the same transistor must avoid the connection to VDD, GND, and inputs that brings about the drastic shoot-through currents between voltage sources via the transistor turned on. Fourth, it is forbidden to connect a single signal to both source and drain of a transistor. When one of source and drain is connected to a signal, its other terminal should not be assigned to the same signal.
    From the second to the fourth, all possible connections via other nodes are simultaneously blocked. In the circuit, the connection of two nodes through different nodes is equal to their direct connection. Therefore, whenever 𝑚𝑚𝑖𝑗
    is set to 1, it is checked out whether that corresponding i-th row and j-th column include multiple 1s at CM. If so, all connections between nodes linked to node i and node j are taken into account as the connected ones and then, corresponding elements of MM are set to 1. Finally, after MM is updated by processing four resultant matrixs through logical OR operation, 𝑀𝑡 is generated in a vector form, like 𝑆𝑡, by flattening the upper right region of MM. The overall procedure of the mask generation is closely explained in Figure 5, where 𝑁𝑖, 𝑁𝑜, 𝑁𝑛, and 𝑁𝑝
    are 1, 1, 1, and 1.
    Electronics 10 01032 g005 550
    Figure 5. Mask generation scheme. Based on a given CM, MM is generated according to four masking criteria. The red 1s of matrices in the middle are existing connections in CM, and the blue 1s are possible connections via other nodes for each masking criterion. Finally, two vectors of 𝑆𝑡
    and 𝑀𝑡
    are produced by flattening the upper right regions of CM and MM, respectively.
    2.3. Reward (𝑟𝑡
    )
    Since the proposed GateRL simply defines 𝑟𝑡
    as +1 for the correctly working schematic and −1 for others, it is expected that the GateRL proposes the working schematics with the minimum number of connection steps, that is, the minimum number of transistors. Therefore, it is of the most importance to verify whether the schematic represented by CM meets a given truth table or not. For example, the truth table of an inverter regarding CM of 𝑁𝑖=2 and 𝑁𝑜=1 consists of four rows that include combinations of two inputs (𝐼𝑁1, 𝐼𝑁2) and their target outputs (𝑂𝑈𝑇) as illustrated in Figure 6. Even though the inverter has only two cases of −1 and +1 for 𝐼𝑁1, the four-row truth table is composed for the agent to be able to support other two-input logic gates, such as AND, NAND, OR, and NOR, with a common GateRL framework. The high level of VDD and the low level of GND are described as +1 and −1, respectively. 0 indicates the high impedance that is equivalent to a floating node without any connections. The second column filled with 0 describes that the second input (𝐼𝑁2
    ) is not in use for this one-input logic gate.
    Electronics 10 01032 g006 550
    Figure 6. Truth table for an inverter circuit. Because it is an one-input gate, 𝐼𝑁2
    is kept at high impedance by assigning 0, where +1 is VDD, and −1 is GND.
    The verification is conducted with the assumption that CMOS transistors are ideal switches where NMOS and PMOS are completely turned on at gate values of +1 and −1, respectively. The following steps are repeated over from the first row to the last one of a given truth table. First, a vector (𝑆𝑉
    ) of the size of 3𝑁𝑛+3𝑁𝑝 is initialized with elements of 0. Because its elements describe the voltage levels at terminals of transistors, initial nodes are set to be high impedance nodes. Second, for terminals connected to VDD and GND in the current CM, corresponding elements of 𝑆𝑉 are updated by +1 and −1, respectively. Third, for terminals linked to inputs, corresponding elements in 𝑆𝑉 are updated by input levels at the selected row of the truth table. The high impedance inputs are not taken into account. Fourth, when the gate of a NMOS is +1, as well as one of its source and drain is 0, the element of 𝑆𝑉 for the terminal with 0 is modified by the voltage value of the other terminal. This operation is also applied to source and drain terminals of a PMOS in the same way when its gate is asserted with −1. Fifth, updated values at terminals of CMOS transistors are propagated to their connected elements in 𝑆𝑉 according to CM. Sixth, until there is no change in 𝑆𝑉, the fourth and fifth steps are repeated. However, when source and drain are assigned at opposite polarities to each other or both are set to 0, corresponding elements of 𝑆𝑉 are maintained without any changes. Finally, the output is obtained from the 𝑆𝑉 element of its connected terminal. Only when verification outputs for all input combinations are matched to the target outputs of the truth table, 𝑟𝑡 is given as +1. If not, 𝑟𝑡
    is determined as −1. The verification steps for the case of an inverter are illustrated in Figure 7.
    Electronics 10 01032 g007 550
    Figure 7. Verification steps for an inverter. Since outputs for all inputs (𝐼𝑁
    ) are matched to target outputs (𝑂𝑈𝑇), 𝑟𝑡
    is decided as +1.
    2.4. Action (𝑎𝑡
    )
    The agent decides 𝑎𝑡
    based on 𝑆𝑡 and 𝑀𝑡 received from the environment. 𝑎𝑡 contains the position of a new connection in the dimension of 𝑆𝑡
    that is converted into a position of the upper right part of CM by the environment. Then, CM is updated by setting the corresponding element to 1. However, as mentioned in the mask generation, when a row and a column including that connection get multiple 1s, all combinations of those nodes should be directly connected to each other. Finally, the logical OR operation is conducted with CM and its transposed one, resulting in the symmetric matrix.
    The agent is implemented by a deep Q-network (DQN) [29] that is composed of 4 fully connected networks (𝑓𝑐1
    , 𝑓𝑐2, 𝑓𝑐3, 𝑓𝑐4). It takes the concatenation of 𝑆𝑡 and T as the input layer (X) as presented in Figure 8. T is the flattened vector of a given truth table. The range of the 𝑆𝑡 values is changed into from −1 to +1 to become equivalent to that of T. Activation functions are rectified linear units (ReLUs) for 𝑓𝑐1, 𝑓𝑐2, and 𝑓𝑐3, and a linear unit for 𝑓𝑐4. In particular, the multiplication of a mask and a large scalar (𝛽) is subtracted from the output layer of 𝑓𝑐4, guaranteeing that positions corresponding to mask elements of 1 are not available for the action selection. 𝑎𝑡 is decided by selecting the position of the maximum output through an argmax function with respect to actions. The overall network operations are described in Equations (6)–(11). 𝑊1, 𝑊2, 𝑊3, and 𝑊4 are weight matrices, and 𝑏1, 𝑏2, 𝑏3, and 𝑏4 are biases.
    𝑋=Concatenate(2·𝑆𝑡−1,𝑇),
    (6)
    𝑓𝑐1=ReLU(𝑊1·𝑥+𝑏1),
    (7)
    𝑓𝑐2=ReLU(𝑊2·𝑓𝑐1+𝑏2),
    (8)
    𝑓𝑐3=ReLU(𝑊3·𝑓𝑐2+𝑏3),
    (9)
    𝑓𝑐4=𝑊4·𝑓𝑐3+𝑏4,
    (10)
    𝑎𝑡=argmax(𝑓𝑐4−𝛽·𝑀𝑡).
    (11)
    Electronics 10 01032 g008 550
    Figure 8. DQN structure. It deals with the concatenation of 𝑆𝑡
    and T as an input layer. The range of 𝑆𝑡
    elements from 0 to 1 is extended from −1 to +1 in order to be matched to T.
    An episode for a given T starts with an empty CM and continues until the working schematic is extracted or there are no more available connections. Every step (t) in the episode, the episode buffer stores a transition that contains 𝑆𝑡
    , T, 𝑎𝑡, and 𝑟𝑡+1. Then, when the episode is terminated, the return (𝐺𝑡) at 𝑆𝑡 and T is computed, and the revised transition, where 𝑟𝑡+1 is replaced with 𝐺𝑡, is appended to a replay buffer. These episodes are repeated by changing T to address all target logic gates. Then, the agent’s DQN is trained based on mini-batches sampled from a replay buffer to minimize a loss (L) described in Equation (12). This is summarized in Algorithm 1, where Q is the DQN function, W is weights and biases, 𝛾 is the discounting factor, and 𝛼 is the learning rate.
    𝐿=∑𝑇∑𝑡{𝐺𝑡−𝑄(𝑆𝑡,𝑇,𝑎𝑡)}2.
    (12)
    Algorithm 1 DQN

    1:
        for each episode do
    2:
              for each T do
    3:
          Initialize 𝐶𝑀←𝟎

    and 𝑀𝑡 with probability 𝜖:𝑎𝑡← 𝑎𝑟𝑔𝑚𝑎𝑥𝑎{𝑄(𝑆𝑡,𝑇,𝑎)−𝛽𝑀𝑡} and 𝑀𝑡 or 𝑀𝑡=𝟏


    21:
          end for
    22:
              end if
    23:
        end for

    3. Experimental Results
    The GateRL is trained for the target logic gates, such as buffer, inverter, AND, NAND, OR, and NOR. While buffer and inverter are one-input logic gates, AND, NAND, OR, and NOR are two-input ones. Therefore, CM is set with 𝑁𝑖
    , 𝑁𝑜, 𝑁𝑛, and 𝑁𝑝 of 2, 1, 2, and 2, respectively. The resultant 𝑁𝐶𝑀 and 𝑁𝑠 are computed as 17 and 126. The multiplication factor for 𝑀𝑡, 𝛽, is 100. Especially, the truth tables of buffer and inverter are provided with two versions, where one input is used, and the other is a floating node. Truth tables for all target gates are illustrated in Figure 9, leading to flattened vectors (Ts) at the size of 12. BUF1 and INV1 are buffer and inverter that use 𝐼𝑁1 as an input, and BUF2 and INV2 are buffer and inverter which adopt 𝐼𝑁2
    as an input.
    Electronics 10 01032 g009 550
    Figure 9. Truth tables for target logic gates. While BUF1 and INV1 are buffer and inverter with an input of 𝐼𝑁1
    , BUF2 and INV2 are buffer and inverter with an input of 𝐼𝑁2
    .
    For the agent’s DQN, the numbers of units in 𝑓𝑐1
    , 𝑓𝑐2, and 𝑓𝑐3 are assigned to twice as large as the dimensionality of X (𝑁𝑥) that is 138. The size of 𝑓𝑐4 is equal to 𝑁𝑠 of 126. An 𝜖-greedy method is adopted with the random action selection probability (𝜖) of 0.1. The discounting factor, 𝛾, is 0.95 and the network is optimized by Adam with a learning rate of 0.001. In addition, there exist 8 special replay buffers dedicated to target logic gates (S0RB for BUF1, S1RB for BUF2, S2RB for INV1, S3RB for INV2, S4RB for AND, S5RB for OR, S6RB for NAND, S7RB for NOR) that contain the transition (𝑆,𝑇,𝑀,𝑎,𝑅) histories terminated at the reward of +1 and one replay buffers (FRB) for the transitions with the failure where the episode is finished with the reward of −1. All the replay buffers store up to 1024 transitions. On top of multiple replay buffers, the probability of the target logic selection (𝑃𝑇) is adjusted to force the network to focus on the logic gate episodes with more failures, that is, more rewards of −1 at the termination. The network is evaluated at the greedy mode every 64 episodes and the number of extracted working schematics is counted separately for each target logic. Then, those counted values are processed by the Softmax function with the temperature of 0.01 and 𝑃𝑇 is obtained by Equation (13). 𝑆𝐶𝑁𝑇 is a vector of 8 elements that includes the counted values for target logic gates.
    𝑃𝑇=1−Softmax(0.01·𝑆𝐶𝑁𝑇)7.
    (13)
    The numbers of extracted working schematics are plotted in Figure 10a,b for training and evaluation. An x-axis is indicated by the number of 𝑆𝐼𝑀
    s where one 𝑆𝐼𝑀
    is equal to 64 episodes. As expected, BUF1 and BUF2 begin to be extracted first, and then more complicated logics are obtained in the order of AND, OR, INV1, INV2, NAND, and NOR. Especially, because the counted values for BUF1 and BUF2 are much larger than others, their probabilities of the target logic selection are reduced in the training period, which is represented as their smaller slopes in Figure 10a.
    Electronics 10 01032 g010 550
    Figure 10. Plots of the number of extracted working schematics for target logic gates. (a) Training. (b) Evaluation.
    The resultant schematics extracted by the proposed GateRL are presented in Figure 11. BUF1 and BUF2 are constructed by one transistor that is always turned on. Their episodes are terminated in 3 steps. AND and OR are proposed with two transistors, where one NMOS transistor is always on, and the other transistor is controlled by 𝐼𝑁1
    . They are finished in 6 steps. When 𝐼𝑁1 is low and 𝐼𝑁2 is high for AND, the racing problem between 𝐼𝑁1 and 𝐼𝑁2 takes place; however, 𝑂𝑈𝑇
    can be settled at the low level close to GND by increasing the ratio of channel width to channel length of a PMOS transistor (P1). The similar issue on the schematic of OR can be coped with by increasing the channel width-to-length ratio of a NMOS transistor (N2). INV1 and INV2 are composed of one PMOS transistor and one NMOS transistor, and their episodes are done in 6 steps. Lastly, NAND and NOR are built with three transistors (2 PMOS and 1 NMOS for NAND, 1 PMOS and 2 NMOS for NOR), and the episodes end in 9 steps. Like AND and OR, the extracted circuits of NAND and NOR can cause racing problems that would be addressed by manipulating the channel width-to-length ratio. Components and episode lengths of working schematics are summarized in Table 1.
    Electronics 10 01032 g011 550
    Figure 11. Working schematics extracted by GateRL for target logic gates.
    Table 1. Training results for target logic gates.
    Table
    These extracted circuits are evaluated by the off-the-shelf circuit simulator, SPICE, as summarized in Figure 12. The proposed GateRL does not take into account threshold voltages of transistors and racing issues. Therefore, some circuits cannot achieve the rail to rail outputs, even though the channel width-to-length ratio is adjusted. While BUF1 pulls up 𝑂𝑈𝑇
    to the lower voltage than VDD due to the threshold voltage of N1, BUF2 pulls down to the higher voltage than GND due to that of P1. In AND, OR, NAND, and NOR, lower logic-1 than VDD and higher logic-0 than GND are caused by threshold voltage and racing problem. However, all logic-1 and logic-0 voltages are accomplished at higher and lower levels than the center level, respectively. These issues will be further addressed in our future works by revising the verification algorithm for the reward and the network structures.
    Electronics 10 01032 g012 550
    Figure 12. SPICE simulation results.
    To verify the necessity of separate replay buffers and adaptive 𝑃𝑇
    , the GateRL is also trained and evaluated with a uniform 𝑃𝑇 or with only one replay buffer. As depicted in Figure 13a, the uniform 𝑃𝑇 and separate replay buffers cannot provide NOR schematics within 2000 𝑆𝐼𝑀s, and even other logic gates are extracted at the longer 𝑆𝐼𝑀s. In the case of one replay buffer, only BUF1 and BUF2 are designed within 2000 𝑆𝐼𝑀s, as illustrated in Figure 13b,c. Consequently, it is ensured that separate replay buffers can help to find solutions of complicated logic schematics, and the adaptive 𝑃𝑇
    contributes to improve the training speed.
    Electronics 10 01032 g013 550
    Figure 13. Plots of the number of extracted working schematics for target logic gates. (a) With a uniform 𝑃𝑇
    and separate replay buffers (b) With an adaptive 𝑃𝑇 and one replay buffer. (c) With a uniform 𝑃𝑇
    and one replay buffer.
    4. Conclusions
    Although various ML algorithms have been employed in many applications, the area of an automated circuit design has not been addressed yet. This paper demonstrates the first ML approach that automatically designs the circuit schematics.
    The proposed GateRL is an automated digital circuit design framework based on RL at the backplane of CMOS transistors. The connection of circuit elements is described by CM that is transferred in the format of a vector to the agent along with the mask. The mask is used to reduce the dimensionality of the action space. The agent decides the optimum action of a new connection by a DQN that consists of 4 fully connected network layers. The proposed GateRL is successfully trained with separate replay buffers and adaptive selection probability for 6 target logics, such as buffer, inverter, AND, OR, NAND, and NOR. The extracted schematics are verified by SPICE simulation.
    However, the proposed scheme has some limitations. First, all transistors are taken into account as ideal switches by neglecting the threshold voltages. Therefore, the turned-on transistors are dealt with as perfect short circuits regardless of voltage levels at source and drain terminals. Second, some extracted circuits contain the racing problems. These are compensated for to some extent in the SPICE simulation by manipulating the channel width-to-length ratio. Third, only voltage sources and CMOS transistors are included as circuit elements. Even though these limitations, the proposed GateRL will pave the way to the complete ML frameworks of the schematic design over more complicated digital circuits, as well as analog circuits.
    Author Contributions
    Conceptualization, H.N. and Y.-I.K.; methodology, H.N. and Y.-I.K.; software, H.N.; validation, J.B. and J.L.; formal analysis, H.N.; investigation, H.N.; resources, H.N.; data curation, H.N.; writing—original draft preparation, H.N.; writing—review and editing, H.N.; visualization, J.B., J.L. and H.N.; supervision, H.N.; project administration, H.N.; funding acquisition, H.N. All authors have read and agreed to the published version of the manuscript.
    Funding
    This research was supported by IDEC (EDA Tool) and the National Research Foundation of Korea (NRF) funded by the Ministry of Science, ICT & Future Planning (NRF-2019R1F1A1061114).
    Conflicts of Interest
    The authors declare no conflict of interest.
    References

        Rawat, W.; Wang, Z. Deep Convolutional Neural Networks for Image Classification: A Comprehensive Review. Neural Comput. 2017, 29, 2352–2449. [Google Scholar] [CrossRef] [PubMed]
        Zhao, Z.Q.; Zheng, P.; Xu, S.T.; Wu, X. Object Detection with Deep Learning: A Review. IEEE Trans. Neural Netw. Learn. Syst. 2019, 30, 3212–3232. [Google Scholar] [CrossRef] [PubMed] [Green Version]
        Saritha, R.R.; Paul, V.; Kumar, P.G. Content based image retrieval using deep learning process. Clust. Comput. 2019, 22, 4187–4200. [Google Scholar] [CrossRef]
        Wang, Z.; Chen, J.; Hoi, S.C.H. Deep Learning for Image Super-resolution: A Survey. IEEE Trans. Pattern Anal. Mach. Intell. 2019. in Press. [Google Scholar] [CrossRef] [PubMed] [Green Version]
        Otter, D.W.; Medina, J.R.; Kalita, J.K. A Survey of the Usages of Deep Learning for Natural Language Processing. IEEE Trans. Neural Netw. Learn. Syst. 2020, in press. [Google Scholar] [CrossRef] [PubMed] [Green Version]
        Nassif, A.B.; Shahin, I.; Attili, I.; Azzeh, M.; Shaalan, K. Speech Recognition Using Deep Neural Networks: A Systematic Review. IEEE Access 2019, 7, 19143–19165. [Google Scholar] [CrossRef]
        Hoseinzade, E.; Haratizadeh, S. CNNpred: CNN-based stock market prediction using a diverse set of variables. Expert Syst. Appl. 2019, 129, 273–285. [Google Scholar] [CrossRef]
        LeCun, Y. Deep Learning Hardware: Past, Present, and Future. In Proceedings of the 2019 IEEE International Solid-State Circuits Conference-(ISSCC), San Francisco, CA, USA, 17–21 February 2019; pp. 12–19. [Google Scholar]
        Dean, J. The Deep Learning Revolution and Its Implications for Computer Achitecture and Chip Design. In Proceedings of the 2020 IEEE International Solid-State Circuits Conference-(ISSCC), San Francisco, CA, USA, 16–20 February 2020; pp. 8–14. [Google Scholar]
        Zhang, C.; Li, P.; Sun, G.; Guan, Y.; Xiao, B.; Cong, J. Optimizing FPGA-based Accelerator Design for Deep Convolutional Neural Networks. In Proceedings of the 2015 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays, Monterey, CA, USA, 22–24 February 2015; pp. 161–170. [Google Scholar]
        Han, S.; Liu, X.; Mao, H.; Pu, J.; Pedram, A.; Horowitz, M.A.; Dally, W.J. EIE: Efficient Inference Engine on Compressed Deep Neural Network. ACM SIGARCH Comput. Archit. News 2016, 44, 243–254. [Google Scholar] [CrossRef]
        Chang, J.W.; Kang, K.W.; Kang, S.J. An Energy-Efficient FPGA-Based Deconvolutional Neural Networks Accelerator for Single Image Super-Resolution. IEEE Trans. Circuits Syst. Video Technol. 2020, 30, 281–295. [Google Scholar] [CrossRef] [Green Version]
        Jouppi, N.P.; Young, C.; Patil, N.; Patterson, D.; Agrawal, G.; Bajwa, R.; Bates, S.; Bhatia, S.; Boden, N.; Borchers, A.; et al. In-Datacenter Performance Analysis of a Tensor Processing Unit. In Proceedings of the 44th Annual International Symposium on Computer Architecture, Toronto, ON, Canada, 24–28 June 2017; pp. 1–12. [Google Scholar]
        Shin, D.; Lee, J.; Lee, J.; Yoo, H.J. DNPU: An 8.1TOPS/W reconfigurable CNN-RNN processor for general-purpose deep neural networks. In Proceedings of the 2017 IEEE International Solid-State Circuits Conference (ISSCC), San Francisco, CA, USA, 5–9 February 2017; pp. 240–241. [Google Scholar]
        Wang, H.; Yang, J.; Lee, H.S.; Han, S. Learning to Design Circuits. arXiv 2018, arXiv:1812.02734. [Google Scholar]
        Settaluri, K.; Haj-Ali, A.; Huang, Q.; Hakhamaneshi, K.; Nikolic, B. AutoCkt: Deep Reinforcement Learning of Analog Circuit Designs. In Proceedings of the 2020 Design, Automation & Test in Europe Conference & Exhibition, Grenoble, France, 9–13 March 2020; pp. 490–495. [Google Scholar]
        Pui, C.W.; Chen, G.; Ma, Y.; Young, E.F.Y.; Yu, B. Clock-aware ultrascale FPGA placement with machine learning routability prediction. In Proceedings of the 2017 IEEE/ACM International Conference on Computer-Aided Design, Irvine, CA, USA, 13–16 November 2017. [Google Scholar]
        Li, Y.; Lin, Y.; Madhusudan, M.; Sharma, A.; Xu, W.; Sachin Sapatnekar, R.H.; Hu, J. Exploring a Machine Learning Approach to Performance Driven Analog IC Placement. In Proceedings of the 2020 IEEE Computer Society Annual Symposium on VLSI, Limassol, Cyprus, 6–8 July 2020. [Google Scholar]
        Crossley, J.; Puggelli, A.; Le, H.P.; Yang, B.; Nancollas, R.; Jung, K.; Kong, L.; Narevsky, N.; Lu, Y.; Sutardja, N.; et al. BAG: A designer-oriented integrated framework for the development of AMS circuit generators. In Proceedings of the IEEE/ACM International Conference on Computer-Aided Design (ICCAD), Santa Clara, CA, USA, 18–21 November 2013; pp. 74–81. [Google Scholar]
        Chang, E.; Han, J.; Bae, W.; Wang, Z.; Narevsky, N.; Nikolic, B.; Alon, E. BAG2: A process-portable framework for generator-based AMS circuit design. In Proceedings of the IEEE Custom Integrated Circuits Conference (CICC), San Diego, CA, USA, 8–11 April 2018. [Google Scholar]
        Hakhamaneshi, K.; Werblun, N.; Abbeel, P.; Stojanović, V. BagNet: Berkeley Analog Generator with Layout Optimizer Boosted with Deep Neural Networks. In Proceedings of the IEEE/ACM International Conference on Computer-Aided Design (ICCAD), Westminster, CO, USA, 4–7 November 2019. [Google Scholar]
        Song, E.; Nam, H. Shoot-through current reduction scheme for low power LTPS TFT programmable shift register. J. Soc. Inf. Disp. 2014, 22, 18–22. [Google Scholar] [CrossRef]
        Song, E.; Nam, H. Low Power Programmable Shift Register with Depletion Mode Oxide TFTs for High Resolution and High Frame Rate AMFPDs. J. Disp. Technol. 2014, 10, 834–838. [Google Scholar] [CrossRef]
        Song, E.; Song, S.J.; Nam, H. Pulse-width-independent low power programmable low temperature poly-Si thin-film transistor shift register. Solid State Electron. 2015, 107, 35–39. [Google Scholar] [CrossRef]
        Kim, Y.I.; Nam, H. Clocked control scheme of separating TFTs for a node-sharing LTPS TFT shift register with large number of outputs. J. Soc. Inf. Disp. 2020, 28, 825–830. [Google Scholar] [CrossRef]
        Sutton, R.S.; Barto, A.G. Reinforcement Learning: An Introduction, 2nd ed.; MIT Press: Cambridge, MA, USA, 2018. [Google Scholar]
        Huang, S.; Ontanon, S. A Closer Look at Invalid Action Masking in Policy Gradient Algorithms. arXiv 2020, arXiv:2006.14171. [Google Scholar]
        Zhang, S.; Tong, H.; Xu, J.; Maciejewski, R. Graph convolutional networks: A comprehensive review. Comput. Soc. Netw. 2019, 6, 1–23. [Google Scholar] [CrossRef] [Green Version]
        Mnih, V.; Kavukcuoglu, K.; Silver, D.; Rusu, A.A.; Veness, J.; Bellemare, M.G.; Graves, A.; Riedmiller, M.; Fidjeland, A.K.; Ostrovski, G.; et al. Human-level control through deep reinforcement learning. Nature 2015, 518, 529–533. [Google Scholar] [CrossRef] [PubMed]


    	
    Publisher’s Note: MDPI stays neutral with regard to jurisdictional claims in published maps and institutional affiliations.

    © 2021 by the authors. Licensee MDPI, Basel, Switzerland. This article is an open access article distributed under the terms and conditions of the Creative Commons Attribution (CC BY) license (https://creativecommons.org/licenses/by/4.0/).
    Share and Cite
    MDPI and ACS Style

    Nam, H.; Kim, Y.-I.; Bae, J.; Lee, J. GateRL: Automated Circuit Design Framework of CMOS Logic Gates Using Reinforcement Learning. Electronics 2021, 10, 1032. https://doi.org/10.3390/electronics10091032
    AMA Style

    Nam H, Kim Y-I, Bae J, Lee J. GateRL: Automated Circuit Design Framework of CMOS Logic Gates Using Reinforcement Learning. Electronics. 2021; 10(9):1032. https://doi.org/10.3390/electronics10091032
    Chicago/Turabian Style

    Nam, Hyoungsik, Young-In Kim, Jina Bae, and Junhee Lee. 2021. "GateRL: Automated Circuit Design Framework of CMOS Logic Gates Using Reinforcement Learning" Electronics 10, no. 9: 1032. https://doi.org/10.3390/electronics10091032
    Note that from the first issue of 2016, this journal uses article numbers instead of page numbers. See further details here.
    Article Metrics
    Citations
    Crossref
     
    3
    Web of Science
     
    3
    Scopus
     
    3
    Google Scholar
     
    [click to view]
    Article Access Statistics
    Article access statisticsArticle Views27. Jan28. Jan29. Jan30. Jan31. Jan1. Feb2. Feb3. Feb4. Feb5. Feb6. Feb7. Feb8. Feb9. Feb10. Feb11. Feb12. Feb13. Feb14. Feb15. Feb16. Feb17. Feb18. Feb19. Feb20. Feb21. Feb22. Feb23. Feb24. Feb25. Feb26. Feb27. Feb28. Feb29. Feb1. Mar2. Mar3. Mar4. Mar5. Mar6. Mar7. Mar8. Mar9. Mar10. Mar11. Mar12. Mar13. Mar14. Mar15. Mar16. Mar17. Mar18. Mar19. Mar20. Mar21. Mar22. Mar23. Mar24. Mar25. Mar26. Mar27. Mar28. Mar29. Mar30. Mar31. Mar1. Apr2. Apr3. Apr4. Apr5. Apr6. Apr7. Apr8. Apr9. Apr10. Apr11. Apr12. Apr13. Apr14. Apr15. Apr16. Apr17. Apr18. Apr19. Apr20. Apr21. Apr22. Apr23. Apr24. Apr25. Apr0k1k2k3k4k5k6k
    For more information on the journal statistics, click here.
    Multiple requests from the same IP address are counted as one view.
    Electronics, EISSN 2079-9292, Published by MDPI
    RSS Content Alert
    Further Information
    Article Processing Charges Pay an Invoice Open Access Policy Contact MDPI Jobs at MDPI
    Guidelines
    For Authors For Reviewers For Editors For Librarians For Publishers For Societies For Conference Organizers
    MDPI Initiatives
    Sciforum MDPI Books Preprints.org Scilit SciProfiles Encyclopedia JAMS Proceedings Series
    Follow MDPI
    LinkedIn Facebook Twitter
    MDPI

    Subscribe to receive issue release notifications and newsletters from MDPI journals
    © 1996-2024 MDPI (Basel, Switzerland) unless otherwise stated
    Disclaimer Terms and Conditions Privacy Policy
    Back to Top

    4:
          Initialize step counter 𝑡←0
    5:
          repeat
    6:
                    Get 𝑆𝑡
        from environment
    7:
                    Select 𝑎𝑡
    8:
                    𝑡←𝑡+1
    9:
                    Receive 𝑟𝑡
        from environment
    10:
          until 𝑟𝑡=+1
    11:
          𝑅←0
    12:
          for 𝑖=𝑡−1,𝑡−2,…,0
        do
    13:
                    𝑅←𝑟𝑖+1+𝛾𝑅
    14:
                    𝐺𝑡←𝑅
    15:
                    Append (𝑆𝑡,𝑇,𝑎𝑡,𝐺𝑡
        ) to a replay buffer
    16:
          end for
    17:
              end for
    18:
              if every N episodes then
    19:
          for each mini-batch sample do
    20:
                    𝑊←𝑊−𝛼∇(𝐺𝑡−𝑄(𝑆𝑡,𝑇,𝑎𝑡))2


    On Thu, Apr 25, 2024 at 10:33 AM tshingombe fiston <tshingombefiston@gmail.com> wrote:

        City Univ
        ersity of New Y
        ork (CUN
        Y
        )
        City Univ
        ersity of New Y
        ork (CUN
        Y
        )
        CUN
        Y Academic W
        orks
        CUN
        Y Academic W
        orks
        Publications and Research
        LaGuardia Community College
        2014
        T
        eaching Electrical Cir
        cuits Using a Vir
        tual Lab
        T
        eaching Electrical Cir
        cuits Using a Vir
        tual Lab
        Md Zahidur Rahman
        CUNY La Guardia Community College
        How does access to this work benefit you? Let us know!
        More information about this work at: https://academicworks.cuny.edu/lg_pubs/29
        Discover additional works at: https://academicworks.cuny.edu
        This work is made publicly available by the City University of New York (CUNY).
        Contact: AcademicWorks@cuny.edu Teaching Electrical Circuits Using a Virtual Lab
        Md Zahidur Rahman
        Mathematics, Engineering, and Computer Science
        Abstract
        This paper describes an engineering professor’s first attempt at designing and
        implementing a scholarship of teaching and learning (SoTL) study in a basic
        electrical circuits course at LaGuardia Community College. Inspired by his
        understanding of Lee Shulman’s (2005) concept of “signature pedagogy” and
        Eric Mazur’s emphasis on student-centered approaches (2009, November 12),
        and aware that his students did not always understand the electrical theories
        and concepts presented in class, the author decided to change his pedagogy.
        He explains his efforts to train his students to think as engineers, first by mak
        ing them more “visible” and “accountable” in the classroom, and second, by
        offering them hands-on practice through the use of Multisim, a free and open
        source simulation software. The implications for the teaching of the basic
        electrical circuits course are offered as well as the author’s reflection on his
        own growth as a teacher and his developing understanding of the scholarship
        of teaching and learning.
        Keywords: Multisim, simulation, software, engineering, and electrical circuits
        Introduction
        In the early 1990s, when I studied for my Bachelor of Science in Electri
        cal Engineering at Bangladesh University of Engineering and Technol
        ogy (BUET), Dhaka, most of the electrical engineering courses included
        a 1-or 2- credit laboratory. These labs in courses such as Electrical Cir
        cuits, Electronics, Electrical Machines, and Electrical Measurement and
        Instrumentation complemented the 3-credit lecture in electrical theories
        and concepts. Instructors usually discussed theories and presented some
        problems and solutions; they also gave us problems to work on in class
        and circulated around the room as we worked independently. In the lab,
        we performed hands-on experiments to test and verify the theories and
        concepts we had learned in class. Working in groups of two or three
        students, we performed experiments using authentic electrical tools
        such as voltmeters, ammeters, multimeters, and rheostats to design,
        build, and test electrical circuits. 86 • In Transit
        I came to the United States in 1999 to continue my studies in
        engineering. I was surprised to find that professors did not provide
        many opportunities for the hands-on experimenting and independent
        problem-solving that I had experienced in Bangladesh. Instead, they
        primarily lectured and demonstrated solutions to problems on the
        blackboard, a pedagogical approach I adopted as a teacher at City
        College, and later at LaGuardia Community College. Standing at the
        blackboard, I lectured and wrote out solutions to problems, stopping
        periodically to ask my students if they had any questions. They rarely
        did, and I assumed they understood what I was doing. Occasionally,
        I gave students a problem to solve independently in class. I walked
        around the room observing students as they worked, but I did not
        interact with them very much.
        I joined LaGuardia Community College’s Carnegie Seminar on
        the Scholarship of Teaching and Learning (SoTL) seminar because I
        wanted to improve my teaching and my knowledge of SoTL. During
        our discussions of Lee Shulman’s article, “Signature Pedagogies in the
        Professions” (2005), I reflected upon my own experiences in Bangla
        desh and in the United States. Shulman, an educational psychologist
        and past president of the Carnegie Foundation for the Advancement of
        Teaching, describes a typical engineering class as follows:
        Although the teacher faces his class when he introduces the
        day’s topic at the beginning of the session, soon he has turned
        to the blackboard, his back to the students. The focal point of
        the pedagogy is clearly mathematical representations of physi
        cal processes. He is furiously writing equations on the board,
        looking back over his shoulder in the direction of the students
        as he asks, of no one in particular, “Are you with me?” A
        couple of affirmative grunts are sufficient to encourage him to
        continue (p. 53).
        Shulman’s description sounded a lot like my experience as a student
        in the United States and the classes I was teaching, but I was no longer
        sure this approach was effective. Shulman also notes that in lecture
        based teaching, there is “almost no reference to the challenges of prac
        tice … [and] little sense of the tension between knowing and doing”
        (p. 54). Shulman’s critique of the typical engineering class helped me to Rahman • 87
        see that I was not meeting the goal of preparing my students to become
        professionals. Engineers must not only understand theories and con
        cepts, but also devise solutions to real-life problems, test their solutions,
        and troubleshoot those that do not work.
        Furthermore, after viewing a video of Eric Mazur (2009, November
        12) engaging Harvard students in the study of physics, I realized that
        I needed to change the dynamic in my classes. Instead of asking “Are
        you with me?” and turning back to the board while students passively
        watched me derive solutions to problems, I learned to build in more
        opportunities for them to solve problems themselves during our class
        sessions. Now, rather than simply observing as students work and
        waiting for them to ask me questions, I have begun to move around
        the class, crouching so I can see their work, understand where they
        are stuck, and ask questions that help in the discovery of the solution.
        Additionally, I call individual students up to the board as I sit among
        the others. I urge them not to be afraid to try; the other students and I
        will help them as needed. Using these methods, I can detect confusion
        more clearly and offer help more quickly.
        But even with these changes, I felt that my pedagogy was not
        adequate to prepare students for a career in engineering. “Professional
        education is not education for understanding alone;” writes Shulman,
        “it is preparation for accomplished and responsible practice in the ser
        vice of others” (p. 53). In order to more fully address my pedagoical
        goals, I needed to provide my classes with more hands-on experiences
        similar to those I had had as an undergraduate student in Bangladesh.
        Electrical Circuits (MAE213) is a 3-credit course required for all
        civil, mechanical, or electrical engineering majors. Unfortunately, this
        foundational course does not include a lab hour. Furthermore, due to
        space and financial constraints, LaGuardia students currently do not have
        access to an equipped electrical engineering hardware lab. Therefore,
        our Engineering faculty are exploring simulation software. Such “virtual
        labs” engage students in realistic problem-solving activities that require
        the application of theories and concepts learned in the classroom.
        Virtual labs offer many advantages, among them powerful pro
        cessing and simulation facilities, ease of use, and accuracy. Where
        physical labs are not available, virtual labs can provide students with
        useful experience (Hackworth & Stanley, 2001; Hall, 2000; Lee, Li, &
        Cheung, 2002). Moure, Valdés, Salaverría, & Mandado (2004), Butz, 88 • In Transit
        Duarte, & Miller (2006), and Swayne (2012) all note that virtual labo
        ratories also have potential for helping students understand theoretical
        principles. Kollöffel and Jong (2013) studied groups of vocational engi
        neering high school students to assess their understanding of electrical
        theories and concepts, and found that adding virtual lab experiences
        to the traditional lecture and hardware lab approach helped students
        learn theoretical concepts. Their research revealed that students might
        face some difficulties and need more time to construct, design, analyze,
        and verify the electrical circuits assignments using real hardware labs.
        Kollöffel and Jong suggest that virtual labs enable students to perform
        these tasks more quickly.
        MATLAB and Multisim are the two simulation software packages
        in use at LaGuardia. Utilized for numerical computation and program
        ming, MATLAB is a sophisticated and expensive software package
        often employed by professional electrical engineers. Multisim, on the
        other hand, is a free and comprehensive circuit analysis program that
        allows for the design, analysis, visualization, and simulation of electri
        cal and electronic circuits. In addition to an extremely realistic interface,
        Multisim allows students to use a mouse and graphics options to create
        schematic diagrams. Fraga, Castro, Alves, and Franchin (2006) studied
        groups of college engineering students in an electrical circuits class.
        Using two computer simulation software programs, PSpice and Mul
        tisim, the researchers found that Multisim provided students an envi
        ronment closest to a real lab. With Multisim, students can use virtual
        oscilloscopes, multimeters, and ammeters to develop their knowledge
        of electrical behavior.
        Multisim engages students in realistic problem-solving; they can
        build simulated circuits, learn how to construct complex circuits with
        various components, and verify the circuit design. After building their
        simulated circuit, students “turn on the electricity” using Multisim’s
        virtual “switch.” With this last step, students can immediately see if the
        circuit they have designed will function as they planned. If it doesn’t,
        they can continue working on the problem, and utilize their knowledge
        of electrical theories and concepts to troubleshoot design issues and cre
        ate alternatives until they arrive at the correct solution to the problem.
        The Electrical Circuits course proved to be an ideal environment
        in which to begin exploring the pedagogical advantages of Multisim.
        The curriculum focuses on basic components of electrical theory and Rahman • 89
        practice such as resistors, capacitors, and inductors, and reinforces
        fundamental mathematical and electrical concepts needed for designing
        and analyzing electrical circuits. Using Multisim allows my students
        to put their knowledge of theory into practice using a realistic, albeit
        simulated, environment.
        Preliminary Investigation of Multisim
        In the informal study of my Spring I 2013 Electrical Circuits course
        described below, I examined the extent to which Multisim helped 17
        undergraduate students (15 male and 2 female students) solve engineer
        ing problems. Three students were Civil Engineering majors, ten were
        Electrical Engineering majors and four were Mechanical Engineering
        majors. I divided the students into two groups of equal size. For the first
        half of the semester, the students in Group 1 worked on one project,
        performing all calculations and solving all circuit design problems by
        hand without verifying their answers or testing their solutions with
        Multisim. Group 2 students worked on the same assignment, but
        used Multisim to verify the accuracy of their calculations and test the
        viability of their design solutions. In the second half of the semester,
        the groups switched: Group 1 completed two projects using Multisim,
        while Group 2 completed the same two projects without using Mul
        tisim. This arrangement assured that all students would experience
        solving problems both ways:
        1. Using only hand calculations and hand-drawn circuit designs.
        2. Performing hand calculations, and then using Multisim to
        design, build, test, verify, and troubleshoot their solutions.
        As indicated in the Project Scores table below, the median scores
        revealed that students who used Multisim did slightly better than stu
        dents who did not.
        Table 1: Project Scores: Hand Calculation or Multism
        Group 1 Median Score Group 2 Median Score
        Multisim
        91.5
        91.5
        Hand calculations only
        88.5
        89.0
        Percentage increase
        3.4%
        2.8%90 • In Transit
        In an effort to get a better picture of students’ interactions with the
        software, I also asked students to respond to these three questions at
        the end of the semester:
        1. Which topics or projects were most difficult for you?
        2. Which method (hand calculation only or hand calculations and
        Multisim verification) better reinforced electrical theories and
        concepts?
        3. What assignments or activities were most effective?
        Eleven students concurred that using Multisim was the most dif
        ficult part of the projects. Twelve students agreed that performing the
        assignments with the simulation software is a better way of reinforcing
        electrical theories and concepts, three students believed that performing
        hand calculations only is more effective, and two students thought there
        was no difference between the two. Clearly, the majority of the students
        considered the mixture of hand calculation and software simulation the
        most effective way to complete projects and homework assignments.
        Although this experiment was conducted with a small sample of 17
        students, the results suggest that students do indeed benefit from the
        use of Multisim.1 In a short reflection at the end of their projects, one
        student commented, “With the help of Multisim I was able to verify
        my answers and correct the one that I had wrong.” Another student
        observed, “By doing this project I learned how to use Multisim to solve
        circuit problems, I also learned how beneficial it is to use Multisim. It is
        a very simple and quick way to check your answers for any mistakes.”
        Ideally, LaGuardia’s engineering students should be able to test
        their designs of electrical circuits using authentic equipment in a well
        furnished electrical engineering lab such as the one I used in Bangladesh.
        Based on the results of my Spring I 2013 experiment, I believe that
        Multisim offers a next-best solution to the problem of lack of access to
        realistic environments in which students can test their designs. This nec
        essary hands-on experience brings me closer to a principal component
        of engineering’s signature pedagogy and addresses Shulman’s reminders
        about the importance of preparing students for their professional lives.
        In future semesters, I hope to continue my efforts to analyze and report
        upon the effect of using Multisim to help students master electrical
        engineering theories and concepts. Rahman • 91
        Notes
        1. Both of the female students reported that using Multisim was the
        most difficult part of the class and noted that, for them, performing
        the hand calculations was more helpful in fostering understanding of
        electrical circuit theories and concepts, while the male students noted
        that Multisim provided a better way to understand the electrical theories
        and concepts of this course. This difference can potentially be ascribed
        to the assumption that males usually have more experience in dealing
        with various software tools and are not as intimidated by having to use
        software to simulate the circuit.
        References
        Butz, B. P., Duarte, M., & Miller, S. M. (2006). An intelligent tutoring
        system for circuit analysis. IEEE Transactions on Education, 49(2),
        216-223. doi:10.1109/TE.2006.872407
        Fraga, J. R. C. P., Castro, M. C. de, Alves, A. F., & Franchin, M. N. (2006,
        September). Using simulation programs to enhance learning electrical
        circuits classes. Paper presented at COBENGE 2006, Congresso
        Brasileiro de Educação em Engenharia [= 34th Brazilian Congress
        on Engineering Education], Universidade de Passo Fundo, Brazil.
        Retrieved from http://www.abenge.org.br/CobengeAnteriores/2006/
        artigos/1_298_218.pdf
        Hackworth, J. R., & Stanley, W. D. (2001, June). An upper-division virtual
        laboratory in linear electronics. Paper presented at the 2001 American
        Society for Engineering Education Annual Conference & Exposition,
        Albuquerque, NM, Session 2247. Retrieved from http://search.
        asee.org/search/fetch?url=file%3A%2F%2Flocalhost%2FE%3A
        %2Fsearch%2Fconference%2F25%2FAC%25202001Paper1121.
        PDF&index=conference_papers&space=12974679720360579171667
        6178&type=application%2Fpdf&charset=
        Hall, T. M. (2000). Using simulation software for electronics engineering
        technology laboratory instruction. Paper presented at the 2000
        American Society for Engineering Education Annual Conference
        & Exposition, St. Louis, MO, Session 3547. Retrieved from http://
        search.asee.org/search/fetch?url=file%3A%2F%2Flocalhost%2FE%
        3A%2Fsearch%2Fconference%2F24%2FAC%25202000Paper675.
        pdf&index=conference_papers&space=12974679720360579171667
        6178&type=application%2Fpdf&charset= 92 • In Transit
        Kollöffel, B., & Jong, T. de. (2013). Conceptual understanding of electrical
        circuits in secondary vocational engineering education: Combining
        traditional instruction with inquiry learning in a virtual lab. Journal of
        Engineering Education, 102(3), 375-393. doi:10.1002/jee.20022
        Lee, W. B., Li, J..G. and Cheung, C. F. (2002). Development of a virtual
        training workshop in ultra-precision machining. International Journal
        of Engineering Education, 18(5), 584-596. Retrieved from http://
        www.ijee.ie/articles/Vol18-5/IJEE1310.pdf
        Mazur, Eric. (2009, November 12). Confessions of a converted
        lecturer. [Video file]. Retrieved from http://www.youtube.com/
        watch?v=WwslBPj8GgI
        Moure, M.J., Valdés, M. D., Salaverría, A., & Mandado, E. (2004). Virtual
        laboratory as a tool to improve the effectiveness of actual laboratories.
        International Journal of Engineering Education, 20(2), 188-192.
        Retrieved from http://www.ijee.ie/articles/Vol20-2/IJEE1484.pdf
        Shulman, Lee S. (2005). Signature pedagogies in the professions. Daedalus
        134(3), 52-59. Retrieved from http://www.jstor.org/stable/20027998
        Swayne, K. (2012, April). An electrical circuits hybrid course model. Paper
        presented at the 2012 American Society for Engineering Education
        Southeastern Section Annual Conference, Starkville, MS, Session 572.
        Abstract retrieved from http://se.asee.org/proceedings/ASEE2012/
        BoA2012ForProceedings.pdf

        On Thu, Apr 25, 2024 at 10:26 AM tshingombe fiston <tshingombefiston@gmail.com> wrote:

            Skip to main content
            Header top right

                About Primary Connections
                New site coming soon!
                Contact us 

            Header bottom right menu

                Resources and pedagogies
                Professional learning
                Inspiration 

            Breadcrumb
            Home> Resources and pedagogies> Curriculum units> Circuits and Switches
            Circuits and Switches
            Physical sciences | Year 6
            'Circuits and Switches' unit cover image
            Download unit (PDF, 7.48MB)File download icon

            Additional resources
            Assessment resources
            e-Resources (ZIP, 16.51MB)
            Equipment list (PDF, 54KB)
            Australian curriculum alignment (PDF, 356KB)

            Circuits and switches addresses AC Science Understanding ACSSU097 Electrical energy can be transferred and transformed in electrical circuits and can be generated from a range of sources, through the context of simple electrical circuits and their components.

            Circuits and switches provides students with hands-on opportunities to:

                construct and represent simple circuits
                investigate how changing the components of a simple circuits affects how it works
                explore different sources of energy that may generate electricity
                examine the role of switches in a simple circuit

            Students apply their new learning by:

                planning and conducting an investigation into the function of the components of a simple circuit and designing, making and evaluating a circuit that transforms energy from one form to another

            Linking science with literacy

            In the Primary Connections approach, students are supported to create representations that draw on and strengthen their literacy development. In Circuits and switches, students represent and explain their understanding about how electrical energy can be transferred and transformed in electrical circuits and can be generated from a range of sources, by creating these representations:

                Analogy
                Annotated diagram
                Biography
                Circuit diagram
                Cutaway diagram
                Factual text
                Glossary
                Ideas map
                Procedural text
                TWLH chart
                Word wall

            Related content
            Essential energy
            Physical sciences Year 6
            External resources
            Energizer Learning Centre

            Comprehensive information on how batteries work, the history of batteries, battery care and how flashlights work.
            Electric Circuits – An Interactive E-Learning Website

            An Interactive E-Learning Website designed to extend the knowledge and understanding of electricity and electric circuits of 7 - 11 yr olds.
            The Blobz Guide to Electric Circuits

            An interactive flash game for up to five players including information, a hands-on exploration task and a quiz for different aspects of electricity and circuits.
            Crocodile clips

            Provides flexible, easy-to-use modelling software for schools and colleges.
            Sidebar menu 3

                Resources and pedagogies
                Professional learning
                Inspiration
                About Primary Connections 

            Strategies exemplified in this unit

            Students working in collaborative teams is a key principle of the Primary Connections approach.
            Learn more

            A science journal is a record of observations, experiences and reflections. It contains a series of dated, chronological entries. It can include written text, drawings, measurements, labelled diagrams, photographs, tables and graphs.
            Learn more

            Support student development of vocabulary related to a particular topic, and provide a reference for class discussions.
            Learn more

            Create a class glossary as a growing bank of descriptions to support students to understand and use new vocabulary.
            Learn more

            Scientific investigations involve posing questions, testing predictions, collecting and interpreting evidence and, drawing conclusions and communicating findings. When scientists plan and conduct a fair test investigation it is to answer a question or test a prediction. Students emulate this in the classroom as they continue to develop their science inquiry skills.
            Learn more

            Argumentation is at the heart of what scientists do; they pose questions, make claims, collect evidence, debate with other scientists and compare their ideas with others in the field.
            Learn more

            Scientific inquiry and investigation are focused on and driven by questions.
            Learn more
            Visit the Australian Academy of Science website Go back to the Primary Connections homepage

                Home
                Resources and pedagogies
                Professional learning

                Frequently asked questions
                Subscribe
                Contact us

            Primary Connections is supported by the Australian Government Department of Education. The views expressed here are those of the author and do not necessarily represent the views of the Australian Government Department of Education.

                Visit the Primary Connections facebook page
                Visit the Primary Connections instagram page
                Visit the Primary Connections pintrest page

            © 2024 Primary Connections. All rights reserved. privacy policy | legals

            On Thu, Apr 25, 2024 at 10:23 AM tshingombe fiston <tshingombefiston@gmail.com> wrote:

                Skip to main content Turn off continuous scrollingAccessibility help
                Accessibility feedback
                Google
                education technical  <span zeum4c11="PR_1_0" data-ddnwab="PR_1_0" aria-invalid="spelling" class="LI ng">careersaqa</span>  ,
                All
                Images
                News
                Videos
                Shopping
                More
                Tools

                    SafeSearch


                About 39,600,000 results (0.37 seconds) 

                Showing results for education technical careers aqa ,
                Search instead for education technical careersaqa ,
                Results for
                2001
                 ∙ Choose area
                Jobs
                Jobs
                Saved3
                Alerts

                    U
                    Lecturer/Senior Lecturer: Department of Science, Mathematics and...

                University of Pretoria/Universiteit van Pretoria
                South Africa
                via Jooble
                30 days ago

                    Full–time

                Explore jobs
                Feedback
                Learn more
                People also ask
                What qualification is AQA?
                What is the job description of an AQA?
                How much does AQA pay for exam marking?
                What is AQA curriculum?
                Feedback

                Join us
                image.png
                AQA
                https://www.aqa.org.uk › join-us
                Early careers. Work and learn through an apprenticeship or graduate programme. Working at AQA. Temporary ...
                ‎Senior associate vacancies · ‎Temporary vacancies · ‎Become an examiner

                11 AQA Education Jobs
                image.png
                Reed
                https://www.reed.co.uk › jobs › aqa-education
                11 AQA Education Jobs · Programme Director · Head of Programmes · Temporary Service Desk Analyst · Recruitment Marketing Manager · Incident Support ...

                Aqa Education Jobs
                image.png
                Indeed
                https://uk.indeed.com › jobs › q=Aqa+Education
                Aqa Education jobs · Children's Weekend Residential Support Worker · Functional Skills Tutor · Learning Coordinator · Animal-Assisted Programme Lead (including ...

                AQA hiring Education Insights Lead in Manchester Area ...
                image.png
                LinkedIn
                https://uk.linkedin.com › jobs › view › education-insight...
                Education Insights Lead. Manchester: £43,600-£49,500. London: £45,500- £51,500. Permanent. Hybrid. Enjoy working in a fast paced research environment?

                67 Aqa Education Jobs
                image.png
                Reed
                https://www.reed.co.uk › jobs › aqa-education-jobs
                Find Aqa Education jobs with Reed.co.uk. Discover Aqa Education vacancies on offer, across the UK, helping you ❤ Mondays.

                Curriculum, qualifications and standards
                image.png
                AQA
                https://www.aqa.org.uk › aqa-global-assessment-services
                Our team of specialists work alongside subject experts to develop fit-for-purpose qualifications that meet regulations and work for learners and training ...
                Missing: careers ‎| Show results with: careers

                AQA Level 3 Advanced GCE in Design and Technology
                image.png
                GOV.UK
                https://nationalcareers.service.gov.uk › details
                Discover the learning experience and opportunities you can expect from this course. Studying Design and Technology at South Craven offers an exciting challenge ...

                Doublestruck Education Support Officer - Myworkdayjobs.com
                image.png
                myworkdayjobs.com
                https://aqa.wd3.myworkdayjobs.com › en-US › AQA › job
                04 Mar 2024 — At AQA, we're committed to advancing education and we ... technical team using internal ticketing ... careers. Sign In. Search for Jobs.

                AQA Tech levels (interim-reformed)
                image.png
                UCAS
                https://qips.ucas.com › qip › aqa-tech-levels-interim-refo...
                Tech levels give students an opportunity to develop specialist knowledge and skills to help them get an apprenticeship or job, for example in engineering, IT, ...
                Related searches
                Education technical careers aqa salary
                Education technical careers aqa login
                aqa jobs
                aqa job description
                ocr jobs
                edexcel jobs
                pearson jobs uk
                hodder education jobs

                AQA Level 3 Advanced GCE in Design and Technology
                image.png
                GOV.UK
                https://nationalcareers.service.gov.uk › details
                AQA Level 3 Advanced GCE in Design and Technology: Product Design ; Who this course is for. Discover the learning experience and opportunities you can expect ...

                AQA Jobs & Careers - Remote Work From Home & Flexible
                image.png
                FlexJobs
                https://www.flexjobs.com › remote-jobs › company › aqa
                AQA's qualifications include A-levels, GCSEs, IGCSEs, Tech-levels, the AQA Baccalaureate, and the Extended Project Qualification. In addition, AQA offers ...

                News and insight | AQA launches Early Careers Programme
                image.png
                AQA
                https://www.aqa.org.uk › news › early-careers-program...
                22 Oct 2021 — Our exciting plans to become the UK's pre-eminent educational assessment organisation depend upon our ability to attract and retain outstanding ...

                Aqa Education Jobs in London
                image.png
                Indeed
                https://uk.indeed.com › q-aqa-education-l-london-jobs
                aqa education jobs in london · Psychology Teacher · Tutor for GCSE Art and Design - Photography · Construction Tutor · Residential Care Worker · Teacher of Spanish.

                GCSE Information booklet letter and career paths 2020
                image.png
                Issuu
                https://issuu.com › thecryptschool › docs › gcse_inform...
                27 Feb 2020 — CAREERS EDUCATION All pupils will follow a structured programme of Careers Education in Years 10 and 11. This is designed to enable learners ...

                Skills for Life: it all starts with skills - Skills for Careers
                image.png
                GOV.UK
                https://www.skillsforcareers.education.gov.uk › pages
                Today's the day to start exploring skills and careers information. You can look at your qualification and training options or get career ideas that would suit ...
                Missing: aqa , ‎| Show results with: aqa ,

                Researcher - Myworkdayjobs.com
                image.png
                myworkdayjobs.com
                https://aqa.wd3.myworkdayjobs.com › Researcher_R5190
                At AQA, we're committed to advancing education and we're committed to our people. As the largest provider of academic qualifications in the UK, ...

                Qualifications
                image.png
                AQA
                https://www.aqa.org.uk › qualifications
                Computer Science (7517) · Dance (7237) · Design and Technology: Fashion and Textiles (7562) ... Physical Education (7582) · Physics (7408) · Polish ... Jobs · Terms ...

                Careers advice: Why is it important and how to improve it?
                image.png
                AQi.org.uk
                https://www.aqi.org.uk › blogs › careers-advice-why-is-...
                05 May 2022 — ... careers education; one in three secondary ... AQA's resident expert on language teaching ... vocational and technical subjects. Are its shoulders ...

                Professional development | About our training
                image.png
                AQA
                https://www.aqa.org.uk › professional-development › a...
                We realise that as your career develops, the skills and knowledge you need to do your job change. That's why we've designed a range of courses to help you ...

                GCSE Design and Technology
                image.png
                Fulbrook School
                https://www.fulbrook.school › Curriculum › Copy-of-D...
                Pupils will follow the AQA Design and Technology course during years 10 and 11 if they choose GCSE Design and Technology as an option. AQA GCSE Design and ...

                AQA
                image.png
                LinkedIn · AQA
                41.2K+ followers
                ... teaching community too – teachers are in good company with AQA. ... Through our AQA Early Careers Graduate and ... Technology, Business, and Research, there's a ...

                Join us | Become an examiner
                image.png
                AQA
                https://www.aqa.org.uk › join-us › become-an-examiner
                Become an examiner. Advance your career, help your students to achieve and make results happen. Apply now · students celebrating results. Enhance your teaching ...

                Food (GCSE only)
                image.png
                Career Pilot
                https://www.careerpilot.org.uk › job-sectors › subject › f...
                The course gives you a range of skills, like planning and organising, working independently, understanding and applying science and even creative skills. It can ...

                AQA – education charity providing GCSEs, A-levels and support
                image.png
                AQA
                https://www.aqa.org.uk
                AQA provides qualifications that enable students to progress to the next stage in their lives. We also support teachers to develop their professional ...

                Careers lessons push up GCSE grades - BBC News
                image.png
                BBC
                https://www.bbc.co.uk › news › education-48268267
                17 May 2019 — Teenagers taught about the world of work are more motivated to get higher GCSE results, say researchers. A careers charity study found ...

                Lecturers - English - GCSE and Functional Skills - 1 full ...
                image.png
                Jobs.ac.uk
                https://www.jobs.ac.uk › job › DFV238 › lecturers-engl...
                07 Feb 2024 — college.jobs.ac.uk - the new specialist job board for further education ... vocational learners aged 16-18. ... You will have experience of teaching ...

                AQA and TQUK join forces to deliver new Level 3 pathway
                image.png
                AQA
                https://www.aqa.org.uk › news › aqa-and-tquk-join-for...
                13 Sept 2023 — AQA is working with TQUK to combine their respective academic and vocational assessment expertise to develop a new pathway in the mixed study ...

                Pathways after GCSE
                image.png
                Merstham Park School
                https://www.mersthamparkschool.org › pathways-after-g...
                There are many academic or job-related courses to suit ALL ability levels, such as A Levels, BTEC, T Levels and NVQS. Make sure you research the courses ...

                Jobs, Career Choices and Ambitions 1 GCSE Higher Tier ...
                image.png
                twinkl.co.za
                https://www.twinkl.co.za › resource › t4-fr-070-jobs-ca...
                Related Searches · jobs, career choices and ambitions · french · knowledge organisers · school & college extra resources · mobile technology ...

                Explore Careers and Issues - Education in Action
                image.png
                educationinaction.org.uk
                https://educationinaction.org.uk › ...
                Inspire your students this summer with our two-week programme of exciting events for KS3, GCSE, and A-Level students, exploring careers and issues.

                GCSE Options - SKA Careers Portal
                Google Sites
                https://sites.google.com › student-information › gcse-opti...
                This is the first time that pupils get to take control of their education and begin to map out their future aspirations. So just how important are these ...

                Qualifications: what the different levels mean
                nidirect
                https://www.nidirect.gov.uk › articles › qualifications-wh...
                Framework for Higher Education Qualifications for ... GCSE grades D-G (and grades 3 to 1 in England) ... suitable for people working in technical and professional ...

                Pathways after GCSE
                image.png
                Glyn School
                https://www.glynschool.org › pathways-after-gcse
                There are many academic or job-related courses to suit ALL ability levels, such as A Levels, BTEC, T Levels and NVQS,. Make sure you research the courses ...

                Explore Education
                image.png
                Start in Leeds
                https://leeds.startprofile.com › page › education-overview
                Which GCSE subjects and vocational options are available to you? This section will help you make sense of this first moment of choice in your career. Find ...

                GCSE Archives - Career Connect Education & Business
                image.png
                connectedu.org.uk
                https://connectedu.org.uk › tag › gcse
                Chloe Elliott, Career Connect's Education and Business Operations Manager, shares her tips and advice for those starting out as Careers Leads, or any Career ...

                GCSE Design & Technology
                image.png
                Bridgnorth Endowed School
                https://www.bridgnorthendowed.co.uk › gcse-design-tec...
                Future Prospects/Career Options ... GCSE Design & Technology enables students to appreciate the possibilities of further study and progression to courses such as ...

                Why Study History? | Careers in History
                image.png
                Success at School
                https://successatschool.org › Advice › Subjects
                English; History of Art; Law; Politics; Teaching; Religious studies. History GCSE or A-level can also be useful for vocational courses or school ...

                Design & Technology (Lower School/GCSE)
                image.png
                Herts and Essex High School
                https://www.hertsandessex.herts.sch.uk › design--techno...
                All students in Years 7 and 8 pursue a Design & Technology course in four material areas: product design with graphics, resistant materials, food, and textiles.

                Personal Development and Careers
                image.png
                Fulbrook School
                https://www.fulbrook.school › GCSE-Personal-Develop...
                to find out about technical education qualifications and apprenticeships opportunities, as part of a careers programme which provides information on the full ...

                Assessment Graduate - AQA
                image.png
                Bright Network
                https://www.brightnetwork.co.uk › le001-aqa-education
                Technology · Finance ... Join our AQA Early Careers Scheme as an ... AQA are an education charity with over 120 years of assessment expertise and knowledge.

                Teneo Online School | Home
                image.png
                Teneo Online School
                https://www.teneoschool.co.za
                ... GCSE · AS ... It's your child's school career, from start to finish ... At Teneo School, each day is an engaging blend of personalised learning and tech-savvy ...

                AQA 780 | Yearbooks 2022
                image.png
                University of Pretoria
                https://www.up.ac.za › AQA 780 › up-campus-tours
                AQA 780; Up-campus-tours. Yearbooks Home · General Rules and ... Science Mathematics and Technology Education ... Careers@UP | Tenders@UP | Ethics Hotline | PAIA ...

                Business Studies
                image.png
                Career Pilot
                https://www.careerpilot.org.uk › job-sectors › subject › b...
                Food (GCSE only) ... vocational courses related to Business Studies. ... IS Business Analyst - Level:4 (equivalent to certificate of higher education)Typical length ...

                What are my options after GCSEs or National 5s?
                image.png
                UCAS
                https://www.ucas.com › ... › Getting started
                Depending on what qualifications you take, you can go on to further education, training, or employment, or you can go to university. Apprenticeships ...

                STEM Subjects: GCSE Choices | Careers | Beyond - Twinkl
                image.png
                twinkl.co.za
                https://www.twinkl.co.za › resource › stem-subjects-gcs...
                Maths. At school, the list of STEM subjects (GCSE) includes: Biology; Chemistry; Physics; Design and Technology; Maths; Computer Science. Twinkl.
                Rating: 5 · ‎2 reviews

                Maths GCSE
                image.jpeg
                Harlow College
                http://www.harlow-college.ac.uk › Study Options
                ... Education Diploma, or a Level 3 to 6 Vocational Qualification, you could be eligible for an Advanced Learner Loan. Full-time Courses & Career Opportunities 2024 ...

                Design & Technology GCSE
                image.png
                Stephen Perse
                https://www.stephenperse.com › page
                GCSE Design and Technology (DT) prepares students for a life in our ever-changing technological world, providing opportunities to design and make new products ...

                What options are available for students after their GCSEs?
                image.png
                GOV.UK blogs
                https://educationhub.blog.gov.uk › 2022/08/22 › what-...
                22 Aug 2022 — ... education, GCSE results, T Levels. After ... Our Higher education | National Careers ... Vocational education (14), World Book Day (3). Sign up and ...

                Lecturers - English - GCSE and Functional Skills - full time ...
                image.png
                Jobs.ac.uk
                https://www.jobs.ac.uk › job › DGD543 › lecturers-eng...
                23 Feb 2024 — ... jobs and more in higher education on jobs ... GCSE and Functional Skills English within our cross-College provision, primarily to vocational ...

                GCSE Design and Technology
                image.png
                Kingham Hill School
                https://www.kinghamhill.org.uk › academic › gcses › g...
                It is often said that pupils need preparation for jobs that do not yet exist, and the skills developed through the study of Design and Technology help provide ...

                Design & Technology GCSE
                image.png
                Ferndown Upper School
                https://fernup.dorset.sch.uk › curriculum › design-techno...
                This exciting GCSE course allows students to explore, via practical projects and tasks, a variety of different material areas. Students will learn about the ...

                GCSE Sociology (From September 2024)
                image.png
                University Technical College Norfolk
                https://utcn.org.uk › Key Stage 4 Curriculum
                University Technical College Norfolk is an exciting school ... AQA. Content Summary. Sociology is the study of human ... Related Careers. Whilst the skills students ...

                Careers talks can boost GCSE results, study finds
                image.png
                SecEd
                https://www.sec-ed.co.uk › content › news › careers-tal...
                05 Jun 2019 — Dr Elnaz Kashefpakdel, head of research at Education and Employers, said: “This report shows that short interactions with volunteers from the ...

                How do you talk to your child about their GCSE options ...
                image.png
                BBC
                https://www.bbc.co.uk › bitesize › articles
                I don't talk about it much as it seems pressurising and I know they will have careers support and interviews about their plans at school.” Helen has a 17-year- ...

                THE MINSTER SCHOOL Careers Education and Information, ...
                image.png
                The Minster School
                https://www.minsterschool.org.uk › download
                PDF
                ... Education, Further Education, Gap Years, Vocational training, including apprenticeships and employment). Staff throughout the school are expected to support ...

                KS4 (GCSE and Vocational) Options 2024/2025
                image.png
                Workington Academy
                https://www.workingtonacademy.org › Parents’ Info
                All students also have access to Unifrog which will enable them to explore their career options and subjects relating to specific careers or further educational ...

                3 Live GCSE Resit Teaching & Lecturing Jobs
                image.png
                AoC Jobs
                https://www.aocjobs.com › jobs › gcse
                Search 3 live GCSE Jobs with aocjobs.com today Apply for GCSE jobs in FE colleges and other education providers throughout the UK.

                AQA Victoria Jobs in All Australia
                image.png
                SEEK
                https://www.seek.com.au › AQA-Victoria-jobs
                An opportunity is available to join one of the largest listed private education organisations in the role of Quality Assurance Manager.

                Requires improvement: urgent change for 11–16 education
                image.png
                UK Parliament
                https://committees.parliament.uk › documents
                PDF
                12 Dec 2023 — as a GCSE or Technical Award44 but are not mandatory in any school. ... technical-careers-and-those-applying-for ... savings to the education budget ...
                Sponsored
                Career & Technical Education | CTE Courses for Students
                imaginelearning.com
                https://www.imaginelearning.com
                image.png
                Empower Students to Explore Their Interests Across Different Careers and Industries. Deepen Their Experience By Taking Courses Mapped to National Career Pathways. Robust reporting. Adaptable Instruction.
                ‎Core Curriculum · ‎Assessment Programs · ‎Supplemental Solutions · ‎Explore Our Research
                Call us
                More results
                South Africa
                2001, Johannesburg
                 - Based on your past activity
                 - 
                Update loc
                Skip to main content Turn off continuous scrollingAccessibility help
                Accessibility feedback
                Google
                pedagogy fundamental phenomenologie,circuit electrical
                All
                Images
                Videos
                Shopping
                News
                More
                Tools

                    SafeSearch


                About 926,000 results (0.33 seconds) 

                Including results for pedagogy fundamental phenomenologie,circuit electricity
                Only show results for pedagogy fundamental phenomenologie,circuit electrical

                Teaching About Electricity in Primary School Multimodality ...
                Springer
                https://link.springer.com › article
                by CM Preston · 2022 · Cited by 13 — The primary school electricity topic usually involves making simple electric circuits, but learning remains at a phenomenological level without ...

                (PDF) electric pedagogy
                image.png
                Academia.edu
                https://www.academia.edu › electric_pedagogy
                Evaluation, in its dimensions of peer and self-evaluation, is fundamental for a teacher's professional development and in such a context, e-portfolio becomes a ...
                People also ask
                What are the fundamentals of the electric circuit?
                What are the basic principles of electrical circuits?
                What is the basic concept of electrical circuit?
                What are the 5 basic electrical circuits?
                Feedback

                288 teaching electric circuits: teachers' ideas and ...
                image.png
                Unisa Institutional Repository
                https://uir.unisa.ac.za › bitstream › handle
                PDF
                Abstract. This study explored the relationship between teachers' ideas on teaching electricity and their awareness of learners' misconceptions.
                Missing: phenomenologie, ‎| Show results with: phenomenologie,

                Joe L. Kincheloe An Introduction Knowledge and Critical ...
                image.png
                National Academic Digital Library of Ethiopia
                http://ndl.ethernet.edu.et › bitstream
                PDF
                by JL Kincheloe · Cited by 1011 — In today's dominant modes of pedagogy, questions about issues of race, class, gender, sexuality, colonialism, religion, and other social dynamics are rarely ...
                281 pages

                Experiment-centric Pedagogy in Circuits and Electronics ...
                image.png
                ResearchGate
                https://www.researchgate.net › ... › Pedagogy
                28 Mar 2020 — Piazza provides a record of how new pedagogical ideas are being handled by students. ... classroom clearly makes for a better and more authentic ...
                Missing: phenomenologie, ‎| Show results with: phenomenologie,

                Organization and pedagogy of complexity. Volume 4, Systemic ...
                image.png
                WorldCat
                https://worldcat.org › oclc
                After a summary of the architecture proposed by Daniel Krob, president of CESAMES in Paris, France, the book focuses on the sensor and effector equipment ...

                experimental-centric-pedagogy-in-circuits-and-electronics- ...
                image.png
                ASEE PEER
                https://peer.asee.org › experimental-centric-pedag...
                PDF
                by KA Connor · 2016 · Cited by 6 — Kenneth Connor is a professor in the Department of Electrical, Computer, and Systems Engineering. (ECSE) where he teaches courses on electromagnetics, ...
                Missing: phenomenologie, ‎| Show results with: phenomenologie,

                CHAPTER 4
                image.png
                University of New England (UNE)
                https://rune.une.edu.au › web › open › SOURCE05
                PDF
                teaching and learning about fundamental electric and magnetic phenomena. Consideration of the exhaustive descriptions for each of the emergent theme.

                Phenomenon-Based Teaching and Learning through the ...
                image.png
                ResearchGate
                https://www.researchgate.net › publication › 31369675...
                PDF | This paper aims to explore the phenomenon-based approach in teaching and learning, through the pedagogical lenses of phenomenology, the philosophy.
                Missing: circuit ‎electrical

                What claud bernard say about the relation between ...
                image.jpeg
                AI Chat for scientific PDFs
                https://typeset.io › questions
                2 days ago — Furthermore, experiences in pedagogy involve ... The phenomenology of emotion ... electricity, is a fundamental principle in electrical circuits.
                5 answers  ·  Top answer: Claude Bernard emphasized the intricate relationship between experience and theory. He highlighted ...
                Related searches
                teaching electricity in primary school
                google scholar
                Images
                PDF) A studio format for innovative pedagogy in circuits and ...
                PDF) A studio format for innovative pedagogy in circuits and ...
                Academia.edu
                PDF) A studio format for innovative pedagogy in circuits and ...
                PDF) A studio format for innovative pedagogy in circuits and ...
                Academia.edu
                PDF) A studio format for innovative pedagogy in circuits and ...
                PDF) A studio format for innovative pedagogy in circuits and ...
                Academia.edu
                Feedback
                6 more images

                Electrical circuits - Themes - Queen's University
                image.png
                Queen's University
                https://uniweb.research.queensu.ca › themes › people
                Basic medicine and life sciences · Immunology ... English language and literacy curriculum, pedagogy and didactics (except ESL, TESOL, LOTE and sign language) ...

                Circuits and Switches
                Primary Connections
                https://primaryconnections.org.au › curriculum-units › ci...
                Home> Resources and pedagogies> Curriculum units> Circuits and Switches ... electrical circuits and their components. ... Primary Connections is supported by the ...
                Missing: phenomenologie, ‎| Show results with: phenomenologie,

                Paulo Freire's Pedagogy of the Oppressed
                UC Santa Cruz - Environmental Studies
                https://envs.ucsc.edu › internship-readings › freir...
                PDF
                by P FREIRE · 1970 · Cited by 124902 — by any means, electronic ... that the fundamental goal of dialogical teaching is to create a process ... Georg Hegel, The Phenomenology of Mind (New York, 1967), p.
                Missing: circuit ‎| Show results with: circuit

                An Example of Content Knowledge about Electric Circuits
                U.S. Department of Education (.gov)
                https://files.eric.ed.gov › fulltext
                PDF
                by S Degirmenci · 2022 — determining the pedagogy to be used in teaching. ... knowledge about electrical circuits or parallel circuit ... Fundamental Mathematics in China and the. United ...
                Missing: phenomenologie, ‎| Show results with: phenomenologie,

                Courses: Physics (PHYS)College: Natural Sciences & Mathematics
                University of Houston
                https://uh.edu › academics › catalog › colleges › nsm › p...
                The fundamental concepts of quantum physics and relativity. ... Phenomenology will be ... Electronic circuits and devices with applications to scientific research.

                Pedagogy here on the ground
                PESA Agora
                https://pesaagora.com › access › pedagogy-here-on-the-...
                by A Madjar · Cited by 1 — The basic phenomenological question is: 'what is this experience like?' (van Manen, 2017, p. 811). Phenomenology looks at pedagogical situations and asks: What ...
                Missing: circuit ‎electrical

                Stanford University Explore Courses
                Stanford Explore Courses
                https://explorecourses.stanford.edu › print
                Combines pedagogy with modern experimental ... Gaussian quantum information. Quantum theory of electric circuits, electromagnetic components, and nanomechanical ...

                Stanford University Explore Courses
                Stanford University
                https://explorecourses.stanford.edu › search
                APPPHYS 201: Electrons and Photons (PHOTON 201). Applied Physics Core course appropriate for graduate students and advanced undergraduate ...

                Events
                IIT Guwahati
                https://iitg.ac.in › iitg_events_all
                Faculty Development Programme on Fundamentals of Analog Integrated Circuit Design. Date: Jan 23, 2017. 2017. ICoRD'17 International Conference on Research into ...

                In order to show you the most relevant results, we have omitted some entries very similar to the 19 already displayed.
                If you like, you can repeat the search with the omitted results included.
                More results
                South Africa
                2001, Johannesburg
                 - Based on your past activity
                 - 
                Update location
                ation

                On Thu, Apr 25, 2024 at 10:14 AM tshingombe fiston <tshingombefiston@gmail.com> wrote:

                    hh
                    SAQA		All qualifications and part qualifications registered on the National Qualifications Framework are public property. Thus the only payment that can be made for them is for service and reproduction. It is illegal to sell this material for profit. If the material is reproduced or quoted, the South African Qualifications Authority (SAQA) should be acknowledged as the source.
                    SOUTH AFRICAN QUALIFICATIONS AUTHORITY 
                    REGISTERED QUALIFICATION THAT HAS PASSED THE END DATE: 

                    Advanced Certificate: Education: Computers: Telecommunications: Mathematics: Science and Technology 
                    SAQA QUAL ID 	QUALIFICATION TITLE
                    20951  	Advanced Certificate: Education: Computers: Telecommunications: Mathematics: Science and Technology 
                    ORIGINATOR
                    University of Pretoria 
                    PRIMARY OR DELEGATED QUALITY ASSURANCE FUNCTIONARY 	NQF SUB-FRAMEWORK
                    CHE - Council on Higher Education  	HEQSF - Higher Education Qualifications Sub-framework 
                    QUALIFICATION TYPE 	FIELD 	SUBFIELD
                    Advanced Certificate  	Field 05 - Education, Training and Development  	Schooling 
                    ABET BAND 	MINIMUM CREDITS 	PRE-2009 NQF LEVEL 	NQF LEVEL 	QUAL CLASS
                    Undefined  	120  	Level 6  	Level TBA: Pre-2009 was L6  	Regular-Provider-ELOAC 
                    REGISTRATION STATUS 	SAQA DECISION NUMBER 	REGISTRATION START DATE 	REGISTRATION END DATE
                    Passed the End Date -
                    Status was "Reregistered"  	SAQA 091/21  	2021-07-01  	2023-06-30 
                    LAST DATE FOR ENROLMENT 	LAST DATE FOR ACHIEVEMENT
                    2024-06-30   	2027-06-30  

                    In all of the tables in this document, both the pre-2009 NQF Level and the NQF Level is shown. In the text (purpose statements, qualification rules, etc), any references to NQF Levels are to the pre-2009 levels unless specifically stated otherwise.  

                    This qualification does not replace any other qualification and is not replaced by any other qualification. 

                    PURPOSE AND RATIONALE OF THE QUALIFICATION 
                    The purpose of the FDE - Computers and Telecommunications in Mathematics, Science and Technology Education is to develop in South Africa a core of educators who will accept the challenges posed by the poor quality of science education that exists in the country in many areas and be prepared to act accordingly. The specific aims are:

                        To equip teachers with a knowledge underlying contemporary developments in mathematics, science and technology education and the teaching strategies appropriate to outcomes based education, which will enable them to focus on the implementation of selected goals of the new learning area
                        programmes.
                        To enhance the learning of mathematics, science and technology through the effective use of computer technology in the classroom as a tool to support an interactive mediated learning style.
                        To foster the desire for life long learning in mathematics, science and technology by making the resources of the Internet available to learners.
                        To enable teachers to set up and maintain school-based computer networks with Internet connections.
                        To enable teachers to gain curriculum development and assessment skills through the use of computers and their integration into learning area curricula. 


                    LEARNING ASSUMED TO BE IN PLACE AND RECOGNITION OF PRIOR LEARNING 
                    Matriculation certificate
                    First degree: B Sc, B A or equivalent
                    Other:
                    As an alternative to a first degree, a three year teaching diploma qualifying the holder to teach sciences and/or mathematics at the high school level.
                    Basic computer literacy - the ability to use Windows and a word processor. 

                    RECOGNISE PREVIOUS LEARNING? 
                    N 

                    EXIT LEVEL OUTCOMES 
                    FDE

                    Learning outcomes:
                    Perform all basic Internet skills: Searching the World Wide Web and bookmarking of sites, Searches of cyberspace for programmes and data, File transfer protocol and obtaining computer and data files from remote sites; Email, Distributed messages; Newsgroups and chat areas; Finding and using graphics.

                    Display knowledge and evaluate the worth of both international trends and best practice in mathematics, science and technology education and of mathematics, science and technology learning area outcomes of curriculum 2005.

                    Display knowledge and evaluate the worth of the use of selected software and telecommunications in mathematics, science and technology education.

                    Design a curriculum units, including assessment criteria and instruments, based on best practice and selected curriculum 2005 outcomes, and incorporating previously unused resources.

                    Specify and set up a typical school-based network (either at own school or on campus) consisting of a file-server, networked workstations, and a telecommunications link. The set up will include the installation of all relevant software programmes.

                    Critical cross-field outcomes:
                    Identify and solve problems in which responses display that responsible decisions using critical and creative thinking have been made.
                    Organise and manage oneself and one's activities responsibly and effectively.
                    Collect, analyse, organise and critically evaluate information.
                    Communicate effectively using visual, mathematical and/or language skills in the modes of oral and/or written persuasion 

                    ASSOCIATED ASSESSMENT CRITERIA 
                    Practical tasks demonstrating a mastery of these skills.

                    Reaction papers and final examination.

                    Reaction papers and final examination.

                    Test the curriculum units, including the assessment component, in a classroom setting and evaluate its strengths and weaknesses.

                    Set up a LAN with the associated software consisting of at least one server. In addition the planning, negotioation and installation of an internet link must be demonstrated.

                    Integrated assessment:
                    Simulations
                    Written examinations
                    Other:
                    Performance on every outcome of each lesson. Most outcoems require an online, written response 

                    ARTICULATION OPTIONS 
                    Related qualifications:
                    FDE (Mathematics and Science)

                    FDE (Mathematics and Science) provides credits for the related qualification

                    Other articulation possibilities, either generic or specific arrangements:
                    Higher Diploma in Education (Generic) 

                    MODERATION OPTIONS 
                    State measures to ensure that assessment is fair, reliable and valid:
                    Large scale assignments and examination tasks are submitted to an internal moderator. Proof of achievement of specific outcomes is retained and evaluated by the moderator. 

                    CRITERIA FOR THE REGISTRATION OF ASSESSORS 
                    Qualifications required:
                    B Sc (Hons) or higher

                    Career experience required:
                    Three years teaching experience at secondary or tertiary level

                    Other criteria:
                    Proven computer skills 

                    REREGISTRATION HISTORY 
                    As per the SAQA Board decision/s at that time, this qualification was Reregistered in 2006; 2009; 2012; 2015. 

                    LEARNING PROGRAMMES RECORDED AGAINST THIS QUALIFICATION: 
                     
                    NONE 


                    PROVIDERS CURRENTLY ACCREDITED TO OFFER THIS QUALIFICATION: 
                    This information shows the current accreditations (i.e. those not past their accreditation end dates), and is the most complete record available to SAQA as of today. Some Primary or Delegated Quality Assurance Functionaries have a lag in their recording systems for provider accreditation, in turn leading to a lag in notifying SAQA of all the providers that they have accredited to offer qualifications and unit standards, as well as any extensions to accreditation end dates. The relevant Primary or Delegated Quality Assurance Functionary should be notified if a record appears to be missing from here.
                     
                    1. 	University of Pretoria 



                    	All qualifications and part qualifications registered on the National Qualifications Framework are public property. Thus the only payment that can be made for them is for service and reproduction. It is illegal to sell this material for profit. If the material is reproduced or quoted, the South African Qualifications Authority (SAQA) should be acknowledged as the source.
                    SAQA		All qualifications and part qualifications registered on the National Qualifications Framework are public property. Thus the only payment that can be made for them is for service and reproduction. It is illegal to sell this material for profit. If the material is reproduced or quoted, the South African Qualifications Authority (SAQA) should be acknowledged as the source.
                    SOUTH AFRICAN QUALIFICATIONS AUTHORITY 
                    REGISTERED QUALIFICATION: 

                    Bachelor of Education Honours in Technology Education 
                    SAQA QUAL ID 	QUALIFICATION TITLE
                    99644  	Bachelor of Education Honours in Technology Education 
                    ORIGINATOR
                    Durban University of Technology 
                    PRIMARY OR DELEGATED QUALITY ASSURANCE FUNCTIONARY 	NQF SUB-FRAMEWORK
                    CHE - Council on Higher Education  	HEQSF - Higher Education Qualifications Sub-framework 
                    QUALIFICATION TYPE 	FIELD 	SUBFIELD
                    Honours Degree  	Field 05 - Education, Training and Development  	Schooling 
                    ABET BAND 	MINIMUM CREDITS 	PRE-2009 NQF LEVEL 	NQF LEVEL 	QUAL CLASS
                    Undefined  	120  	Not Applicable  	NQF Level 08  	Regular-Provider-ELOAC 
                    REGISTRATION STATUS 	SAQA DECISION NUMBER 	REGISTRATION START DATE 	REGISTRATION END DATE
                    Reregistered  	SAQA 1141/23  	2021-07-01  	2024-06-30 
                    LAST DATE FOR ENROLMENT 	LAST DATE FOR ACHIEVEMENT
                    2025-06-30   	2031-06-30  

                    In all of the tables in this document, both the pre-2009 NQF Level and the NQF Level is shown. In the text (purpose statements, qualification rules, etc), any references to NQF Levels are to the pre-2009 levels unless specifically stated otherwise.  

                    This qualification does not replace any other qualification and is not replaced by any other qualification. 

                    PURPOSE AND RATIONALE OF THE QUALIFICATION 
                    Purpose:
                    The Bachelor of Education Honours Degree in Technology Education is intended to prepare learners for research based Postgraduate study in the field of Technology Education. This will serve to consolidate and deepen the Educator's expertise in Technology Education and develop research capacity in the methodology and techniques in this area. This qualification will demand a high level of intellectual independence and theoretical engagement thus preparing the learner for access to further study for a Master's Degree.

                    Rationale:
                    The School community in general recognises the importance of providing a Postgraduate qualification in Technology Education, a field of study in which there is a great scarcity of teachers with professional knowledge and expertise as well as leadership skills to promote this area of study at school level. Hence the central goal of the qualification is geared towards meeting the needs of Technology Educators who in the light of developments taking place in this field wish to enhance their professionalism.

                    The results of the needs analysis conducted at schools indicated that most Educators feel the need for further studies and expert advancement in the area of Technology Education. This qualification will enable teachers to "Strive for Excellence" in the area of Technology. 

                    LEARNING ASSUMED TO BE IN PLACE AND RECOGNITION OF PRIOR LEARNING 
                    Recognition of Prior Learning (RPL):
                    The department's RPL process is aligned with the Institution's Recognition of Prior Learning Policy and will include representation from industry and appropriate academia from tertiary institutions when reviewing RPL applications.

                    The purpose of the policy is:

                        To provide a framework for the implementation of Recognition of Prior Learning procedures within the Institution.
                        To facilitate access and admission to learning qualifications within education and training and career paths.
                        To accelerate redress of past unfair discrimination in education, training and employment opportunities.
                        To promote and facilitate lifelong learning.
                        To outline general procedures relating to the processing of RPL applications at the Durban University of Technology.

                        RPL may be used to grant access o the qualification to learners who do not meet the minimum entry requirements and/or to grant advanced standing to learners.

                        Entry Requirements:
                        To be admitted to the qualification, a learner must have:
                        A Bachelor of Education, Level 7 preferably with Mechanical Technology or Engineering Graphics and Design as a major.
                        Or
                        A general Bachelor's Degree, Level 7 and a recognised professional Teaching qualification for example a Postgraduate Certificate in Education in the field of Technology Education or a related field. 


                    RECOGNISE PREVIOUS LEARNING? 
                    Y 

                    QUALIFICATION RULES 
                    This qualification consists of compulsory and elective modules at NQF Level 8 totalling 120 Credits.

                    Compulsory Modules:

                        Modern technology and communication in Technology Education, 12 Credits.
                        Understanding Research, 12 Credits.
                        Independent Research Project, 32 Credits

                        Elective Modules (select modules for a total of a minimum of 64 Credits):
                        Principles of Drawing, 16 Credits.
                        International and national perspectives in Technology Education, 16 Credits.
                        Drawing in the context of Mechanical, Civil and Electrical Technology, 24 Credits.
                        Integrated systems in Technology Education, 24 Credits.
                        Materials and structures in Technology Education, 24 Credits.
                        Computer-aided design in the context of mechanical, civil and electrical technology, 24 Credits. 


                    EXIT LEVEL OUTCOMES 
                    1. Demonstrate a sound knowledge base and critical understanding of education in general and in the area of Technology Education.
                    2. Analyse and evaluate knowledge in the area of Technology Education and contribute to systematic and disciplined thinking about educational matters and issues with particular reference to Technology Education.
                    3. Conduct independent inquiry in the field of Technology Education Training and Development and report the findings in academically appropriate ways.
                    4. Act as academic leaders and experts in the field of Technology Education, training and development. 

                    ASSOCIATED ASSESSMENT CRITERIA 
                    Associated Assessment Criteria for Exit Level Outcome 1:

                        Aspects that constitute the field of Technology Education are described.
                        International and national perspectives of Technology Education are analysed.
                        Acquired knowledge is applied in the Technology classrooms to enhance learning.
                        Multiple sources of knowledge in the field of Technology Education are interrogated.

                        Associated Assessment Criteria for Exit Level Outcome 2:
                        Strategies to address complexities and uncertainties in selecting and transferring standard procedures and techniques involved in Technology Education are understood and taken into account when applied in the classroom.
                        The different perspectives of the term Technology Education are critically assessed.
                        The historical development of Technology Education is explained as part of the school Curriculum.
                        International and national views on various aspects of Technology Education are compared.

                        Associated Assessment Criteria for Exit Level Outcome 3:
                        Different types of research are identified.
                        Research questions in the field of Technology Education are formulated.
                        Literature review in the context of Technology Education is done.
                        Data is gathered using a variety of data gathering tools and techniques.
                        Data from various theoretical perspectives is analysed.
                        Conclusions are drawn and data is presented in an academically acceptable manner to a variety of audiences.

                        Associated Assessment Criteria for Exit Level Outcome 4:
                        Various principles for drawing in the context of Mechanical, Civil and Electrical Technology are described.
                        Various principles of drawing to compile engineering drawings in the context of Mechanical, Civil and Electrical Technology are implemented.
                        Mechanical, Civil and Electrical Systems in Technology Education are differentiated and the inter-relationship and integration of these systems is explained.
                        Different materials and structures used in Technology Education are analysed.
                        Computer software of CAD and AutoCAD is used to compile drawings in the context of Mechanical, Civil and Electrical Technology.
                        Proficiency and competencies including information literacy are communicated orally and in written form through numeracy and technology applications in order to exhibit the potential to act as academic leaders and experts in the field of Technology Education.

                        Integrated Assessment:
                        The Assessment Policy of the institution states amongst other aspects that:
                        Learners will be assessed on an on-going basis using appropriate methods which must provide evidence that learners have achieved the stated learning outcomes and the assessment criteria.

                        Assessments will be aligned with stated learning outcomes. The assessment will be systematic, regular and formative in nature. Assessors will design assessments that are relevant and sufficient and promote integration and autonomy of learning.

                        An assessment plan will be included in each Study Guide which will include a schedule of assessments to be conducted during the year, the assessment criteria, assessment methods, weighting and timing of assessment. In accordance with these guidelines an assessment plan is included in all study guides which includes a schedule of assessments with the assessment criteria, assessment methods, assessment tools for example rubrics, weighting of assessments and scheduled dates for assessment. The following table provides information for each module on the description of the number and types of tests/assignments/projects and case studies:
                        Description of the number and types of tests/assignments/projects/case studies.
                        No Formal examination - Presentation of the Research Project 35%.
                        Internal and external moderation/examination.
                        In accordance with the Assessment policy of the institution, the following guidelines regarding internal and external examination and moderation will apply. 


                    INTERNATIONAL COMPARABILITY 
                    International comparability has been conducted with qualifications from institutions in the United Kingdom and Australia.

                    University of Glasgow offers a Bachelor Technology Education. The structure of Honours qualifications in the United Kingdom is different from ours. This is a four-year qualification from which learners exit with an Honours Degree. The qualification focus on preparing teachers' understand of how children learn, as well as appropriate technological subjects such as Electronics, Design, Mechanics, Materials, Energy and Graphics. They also study practical-based subjects so that they can successfully deliver the range of vocational courses encompassed by Technological Education.

                    University of Strathclyde - United Kingdom (UK):
                    The University's mission in the Bachelor of Education Honours Degree is to pursue excellence in research, knowledge exchange and education to the benefit of learners, staff and wider society. The qualification helps learners to generate new ideas, knowledge, skills and approaches in teaching and learning that enable individuals and society to succeed in an increasingly complex technological age and to do so with a social conscience.

                    The University of Technology Sydney in Australia offers a four year Bachelor of Arts: Education (Honours). Through this qualification learners continually develop teaching competence throughout the Degree with a comprehensive and practical engaging professional experience programme. It provides graduates with advanced knowledge of Teacher Education and Research. Graduates undertake a scholarly piece of work, working with an academic supervisor and representing the research community in educational settings.

                    Most subjects are delivered in blended mode. Learners study innovative teaching methods in the key learning areas and explore contemporary issues and applications, including technology-enhanced learning and learning analytics. Learners undertake professional teaching experience totalling 80 days of supervised teaching practice in schools.

                    Conclusion:
                    The qualification compares with these international qualifications in terms of purpose and the focus on technology in teaching and learning. The qualifications also have a strong focus on research in which the technology aspect is tailored. 

                    ARTICULATION OPTIONS 
                    This qualification offers only specific vertical articulation opportunities with the following qualification offered by the Durban University of Technology:

                    Vertical Articulation:

                        Master of Technology in Education, Level 9 (ID No. 73078).

                        The qualification offers systemic articulation with the following qualifications offered by other institutions, provided the learner meets the minimum entry requirements:

                        Horizontal Articulation:
                        Bachelor of Education Honours in Information Communication Technology Education, Level 8.

                        Vertical Articulation:
                        Bachelor of Education in Technology Education, Level 9. 


                    MODERATION OPTIONS 
                    N/A 

                    CRITERIA FOR THE REGISTRATION OF ASSESSORS 
                    N/A 

                    NOTES 
                    N/A 

                    LEARNING PROGRAMMES RECORDED AGAINST THIS QUALIFICATION: 
                     
                    NONE 


                    PROVIDERS CURRENTLY ACCREDITED TO OFFER THIS QUALIFICATION: 
                    This information shows the current accreditations (i.e. those not past their accreditation end dates), and is the most complete record available to SAQA as of today. Some Primary or Delegated Quality Assurance Functionaries have a lag in their recording systems for provider accreditation, in turn leading to a lag in notifying SAQA of all the providers that they have accredited to offer qualifications and unit standards, as well as any extensions to accreditation end dates. The relevant Primary or Delegated Quality Assurance Functionary should be notified if a record appears to be missing from here.
                     
                    1. 	Durban University of Technology 



                    	All qualifications and part qualifications registered on the National Qualifications Framework are public property. Thus the only payment that can be made for them is for service and reproduction. It is illegal to sell this material for profit. If the material is reproduced or quoted, the South African Qualifications Authority (SAQA) should be acknowledged as the source.
                    SAQA		All qualifications and part qualifications registered on the National Qualifications Framework are public property. Thus the only payment that can be made for them is for service and reproduction. It is illegal to sell this material for profit. If the material is reproduced or quoted, the South African Qualifications Authority (SAQA) should be acknowledged as the source.
                    SOUTH AFRICAN QUALIFICATIONS AUTHORITY 
                    REGISTERED UNIT STANDARD THAT HAS PASSED THE END DATE: 

                    Design and develop web-based learning (WBL) 
                    SAQA US ID 	UNIT STANDARD TITLE
                    14304  	Design and develop web-based learning (WBL) 
                    ORIGINATOR
                    SGB Higher Education & Training 
                    PRIMARY OR DELEGATED QUALITY ASSURANCE FUNCTIONARY
                    -  
                    FIELD 	SUBFIELD
                    Field 05 - Education, Training and Development 	Higher Education and Training 
                    ABET BAND 	UNIT STANDARD TYPE 	PRE-2009 NQF LEVEL 	NQF LEVEL 	CREDITS
                    Undefined  	Regular  	Level 7  	Level TBA: Pre-2009 was L7  	10 
                    REGISTRATION STATUS 	REGISTRATION START DATE 	REGISTRATION END DATE 	SAQA DECISION NUMBER
                    Passed the End Date -
                    Status was "Reregistered"  	2018-07-01  	2023-06-30  	SAQA 06120/18 
                    LAST DATE FOR ENROLMENT 	LAST DATE FOR ACHIEVEMENT
                    2024-06-30   	2027-06-30  

                    In all of the tables in this document, both the pre-2009 NQF Level and the NQF Level is shown. In the text (purpose statements, qualification rules, etc), any references to NQF Levels are to the pre-2009 levels unless specifically stated otherwise.  

                    This unit standard does not replace any other unit standard and is not replaced by any other unit standard. 

                    PURPOSE OF THE UNIT STANDARD 
                    A practitioner in higher education who has achieved this unit standard will be able to design and develop web-based learning content for delivery in a web-based learning environment.

                    Practitioners credited with this unit standard are able to contextualise WBL as delivery mode, effectively design and develop web-based learning, utilize the tools of a learning management system for moderation, collaboration and administrative purposes in the learning environment. Higher education students will benefit from well-designed WBL, which will enhance learning and achievement of outcomes. 

                    LEARNING ASSUMED TO BE IN PLACE AND RECOGNITION OF PRIOR LEARNING 
                    The unit standard on interpreting and designing learning programmes, or equivalent competence, is assumed. It is further assumed that the practitioner has keyboard and mouse skills, is able to manage files, do word processing, use databases, communicate electronically (log onto a network, send a message, search and retrieve data from the Internet computers), are familiarised with HTML or editors (elementary) and have the ability to upload to, and download files from the web. 

                    UNIT STANDARD RANGE 
                    The following scope and context applies to the whole unit standard:

                    This Unit Standard is limited to the effective use and development of learning content for WBL and is not targeted at the development of tools for a learning management system.

                    Specific range statements are provided in the body of the unit standard where they apply to particular specific outcomes or assessment criteria. 

                    Specific Outcomes and Assessment Criteria: 

                    SPECIFIC OUTCOME 1 
                    Investigate and evaluate WBL as a delivery mode. 
                    OUTCOME RANGE 
                    Resource usage, cost, availability and appropriateness. 

                    ASSESSMENT CRITERIA 

                    ASSESSMENT CRITERION 1 
                    1. Criteria for the evaluation of the delivery mode are identified, and are consistent with current practice reflected in mainstream literature. 

                    ASSESSMENT CRITERION 2 
                    2. The application of WBL is analysed and evaluated according to documented educational best practice. 

                    ASSESSMENT CRITERION 3 
                    3. Identification of opportunities for WBL in a chosen institution is consistent with the analysis in terms of affordability and appropriateness. 

                    ASSESSMENT CRITERION 4 
                    4. The WBL mode is compared to other modes in terms of resource usage, cost, availability and appropriateness, and conclusions are consistent with evaluation findings. 

                    SPECIFIC OUTCOME 2 
                    Design and develop web-based learning content. 
                    OUTCOME RANGE 
                    Analysis and application of WBL design relates to learner characteristics, technology, navigation, online help strategies, domains of learning, elements of content and context, learning outcomes, learner activities, assessment and reflection. 

                    ASSESSMENT CRITERIA 

                    ASSESSMENT CRITERION 1 
                    1. The differences between WBL contents and printed learning contents are described according to differences stated in mainstream literature. 

                    ASSESSMENT CRITERION 2 
                    2. WBL content design shows clearly that key web features were used to facilitate student learning. 
                    ASSESSMENT CRITERION RANGE 
                    Features include: technology, navigation, online help strategies, domains of learning, elements of content and context, learning outcomes, learner activities, assessment and reflection.
                     

                    ASSESSMENT CRITERION 3 
                    3. Appropriate web design criteria are applied in developing WBL content. 
                    ASSESSMENT CRITERION RANGE 
                    The criteria concern content development tools, typography (microcontent e.g. headlines, page titles, subject lines; short text, scannability, hypertext structure), media integration and optimisation; and interaction (communication) tools.
                     

                    ASSESSMENT CRITERION 4 
                    4. The work process reflects an understanding of and commitment to effective teamwork by using experts in integrating video, graphics, sound and text where appropriate. 

                    ASSESSMENT CRITERION 5 
                    5. Editing/review processes are designed, conducted and evaluated on a formative and summative basis. 

                    ASSESSMENT CRITERION 6 
                    6. The design of WBL makes provision for usability testing and pilot delivery. 

                    ASSESSMENT CRITERION 7 
                    7. Pilot deliveries are evaluated in terms of user (including learners) satisfaction. 
                    ASSESSMENT CRITERION RANGE 
                    Usability testing refers to a team review (alpha testing) and external review (beta-testing).
                     

                    SPECIFIC OUTCOME 3 
                    Select and utilise Learning Management Systems (LMSs). 

                    ASSESSMENT CRITERIA 

                    ASSESSMENT CRITERION 1 
                    1. At least three high quality LMSs are identified according to comparative studies conducted the past two years. 

                    ASSESSMENT CRITERION 2 
                    2. At least six common constituents (components) of enterprise LMSs are identified on grounds of relevance in a WBL environment. 

                    ASSESSMENT CRITERION 3 
                    3. The effective utilisation of a selected LMS is demonstrated in terms of moderation, collaboration and administrative purposes. 

                    SPECIFIC OUTCOME 4 
                    Evaluate processes and products of WBL. 

                    ASSESSMENT CRITERIA 

                    ASSESSMENT CRITERION 1 
                    1. Web-based teaching-learning processes are evaluated in terms of attainment of learning outcomes and quality of study materials (resources). 

                    ASSESSMENT CRITERION 2 
                    2. Instructional design is critically assessed according to documented educational best practices. 

                    ASSESSMENT CRITERION 3 
                    3. Benchmarks (quality measures) essential for ensuring excellence in WBL are taken into account. 
                    ASSESSMENT CRITERION RANGE 
                    Benchmarks in this case relate to institutional support, programme development, teaching-learning, programme structure, student support, academic staff support, evaluation and assessment.
                     

                    SPECIFIC OUTCOME 5 
                    Reflect on opportunities and limitations for WBL by doing a WBL SWOT analysis. 
                    OUTCOME RANGE 
                    Within the practitioners institutional framework. 

                    ASSESSMENT CRITERIA 

                    ASSESSMENT CRITERION 1 
                    1. The institition's readiness for WBL is judged by taking taking the vision, mission and WBL related strategies, processes and policies into consideration. 

                    ASSESSMENT CRITERION 2 
                    2. The institution's network is judged in terms of capacity for WBL. 

                    ASSESSMENT CRITERION 3 
                    3. The academic staff's readiness for web-based learning is established. 


                    UNIT STANDARD ACCREDITATION AND MODERATION OPTIONS 
                    Providers of learning towards this unit standard will need to meet the accreditation requirements of the relevant ETQA.

                    Moderation Option: The moderation requirements of the relevant ETQA must be met in order to award credit to learners for this unit standard. 


                    Critical Cross-field Outcomes (CCFO): 

                    UNIT STANDARD CCFO IDENTIFYING 
                    Solving problems - The specific outcomes 'Design and develop web-based learning content' and Select and utilise LMS's' solve problems. 

                    UNIT STANDARD CCFO WORKING 
                    Work effectively with others and in teams: The specific outcome 'Design and develop WBL learning content' requires a team effort as illustrated in the assessment criteria: 'The work process reflects an understanding of and commitment to effective teamwork by using experts in integrating video, graphics, sound and text where appropriate'. 

                    UNIT STANDARD CCFO COLLECTING 
                    Collect, analyse, organise and critically evaluate information: All specific outcomes require information skills. 

                    UNIT STANDARD CCFO SCIENCE 
                    Use science and technology effectively: all the outcomes in this unit standard on Web-based Learning relate to the effective use of science and technology. 

                    REREGISTRATION HISTORY 
                    As per the SAQA Board decision/s at that time, this unit standard was Reregistered in 2012; 2015. 

                    UNIT STANDARD NOTES 
                    Notes to assessors:

                    Assessors should keep the following general principles in mind when designing and conducting assessments against this unit standard:

                        Focus the assessment activities on gathering evidence in terms of the main outcome expressed in the title to ensure assessment is integrated rather than fragmented. Remember we want to declare the person competent in terms of the title. Where assessment at title level is unmanageable, then focus assessment around each specific outcome, or groups of specific outcomes.
                        Make sure evidence is gathered across the entire range, wherever it applies. Assessment activities should be as close to the real performance as possible, and where simulations or role-plays are used, there should be supporting evidence to show the candidate is able to perform in the real situation.
                        Do not focus the assessment activities on each assessment criterion. Rather make sure the assessment activities focus on outcomes and are sufficient to enable evidence to be gathered around all the assessment criteria.
                        The assessment criteria provide the specifications against which assessment judgements should be made. In most cases, knowledge can be inferred from the quality of the performances, but in other cases, knowledge and understanding will have to be tested through questioning techniques. Where this is required, there will be assessment criteria to specify the standard required.
                        The task of the assessor is to gather sufficient evidence, of the prescribed type and quality, as specified in this unit standard, that the candidate can achieve the outcomes again and again and again. This means assessors will have to judge how many repeat performances are required before they believe the performance is reproducible.
                        All assessments should be conducted in line with the following well documented principles of assessment: appropriateness, fairness, manageability, integration into work or learning, validity, direct, authentic, sufficient, systematic, open and consistent. 


                    QUALIFICATIONS UTILISING THIS UNIT STANDARD: 
                      	ID 	QUALIFICATION TITLE 	PRE-2009 NQF LEVEL 	NQF LEVEL 	STATUS 	END DATE 	PRIMARY OR DELEGATED QA FUNCTIONARY
                    Elective  	23113	  	Post Graduate Certificate: Higher Education and Training  	Level 7  	NQF Level 07  	Passed the End Date -
                    Status was "Reregistered"  	2023-06-30  	As per Learning Programmes recorded against this Qual 


                    PROVIDERS CURRENTLY ACCREDITED TO OFFER THIS UNIT STANDARD: 
                    This information shows the current accreditations (i.e. those not past their accreditation end dates), and is the most complete record available to SAQA as of today. Some Primary or Delegated Quality Assurance Functionaries have a lag in their recording systems for provider accreditation, in turn leading to a lag in notifying SAQA of all the providers that they have accredited to offer qualifications and unit standards, as well as any extensions to accreditation end dates. The relevant Primary or Delegated Quality Assurance Functionary should be notified if a record appears to be missing from here.
                     
                    NONE 



                    	All qualifications and part qualifications registered on the National Qualifications Framework are public property. Thus the only payment that can be made for them is for service and reproduction. It is illegal to sell this material for profit. If the material is reproduced or quoted, the South African Qualifications Authority (SAQA) should be acknowledged as the source.

                    On Thu, Apr 25, 2024 at 9:58 AM tshingombe fiston <tshingombefiston@gmail.com> wrote:

                        Skip to main content Turn off continuous scrollingAccessibility help
                        Accessibility feedback
                        Google
                        education <span zeum4c2="PR_1_0" data-ddnwab="PR_1_0" aria-invalid="spelling" class="LI ng">tehnology</span>  saqa
                        All
                        Images
                        News
                        Videos
                        Shopping
                        More
                        Tools
                        Pdf
                        Requirements
                        Subjects
                        Courses
                        Modules

                            SafeSearch


                        About 466,000 results (0.33 seconds) 

                        Showing results for education technology saqa
                        Search instead for education tehnology saqa
                        Scholarly articles for education technology saqa
                        … light of the South African Qualifications Authority (SAQA … - ‎Sutherland, L., Peckham - Cited by 12
                        … to empower learners and transform education: … - ‎Spady - Cited by 13

                        SAQA
                        image.png
                        SAQA
                        https://regqs.saqa.org.za › viewQualification
                        This programme is ideal for those considering a career in academic development, instructional design, online development and teaching, or leadership in ...
                        People also ask
                        What is NQF Level 6 information technology?
                        What is saqa in education?
                        What is SAQA equivalency certificate?
                        What NQF level is a 3 year national diploma?
                        Feedback

                        99644
                        image.png
                        SAQA
                        https://allqs.saqa.org.za › showQualification
                        Purpose: The Bachelor of Education Honours Degree in Technology Education is intended to prepare learners for research based Postgraduate study in the field ...

                        Specific Outcomes and Assessment Criteria
                        image.png
                        SAQA
                        https://allqs.saqa.org.za › showUnitStandard
                        Use science and technology effectively: all the outcomes in this unit standard on Web-based Learning relate to the effective use of science and technology.

                        qualification title
                        image.png
                        SAQA
                        https://regqs.saqa.org.za › viewQualification
                        SAQA QUAL ID, QUALIFICATION TITLE ; 82086, Diploma in Information Technology ; ORIGINATOR ; Commerce and Computer College ; PRIMARY OR DELEGATED QUALITY ASSURANCE ...

                        96811
                        image.png
                        SAQA
                        https://allqs.saqa.org.za › showQualification
                        Purpose: Learners achieving this qualification are competent in applying advanced research skills to solve a problem within a related educational field and to ...

                        qualification title
                        image.png
                        SAQA
                        https://allqs.saqa.org.za › showQualification
                        Display knowledge and evaluate the worth of the use of selected software and telecommunications in mathematics, science and technology education. Design a ...

                        Registered Qualification
                        image.png
                        SAQA
                        https://regqs.saqa.org.za › search
                        Search for a Registered Qualification. Frequently Asked Questions (FAQ). Important: Leave most of the blocks (search criteria) blank.

                        115436
                        SAQA
                        https://qspe.saqa.org.za › showUnitStandard
                        Its purpose is to develop in these educators/school managers the fundamental knowledge, skills, and values/personal qualities so that they can manage teaching ...

                        SAQA
                        image.png
                        SAQA
                        https://pcqs.saqa.org.za › viewQualification
                        This qualification is designed to provide lecturers at Universities of Technology, training centres, Further Education and Training Colleges and other ...

                        Higher Certificate Educational Technology
                        image.png
                        Berea Group
                        https://bereagroup.co.za › higher-certificate-educational...
                        This qualification has excellent value as it provides potential or practicing teachers, lecturers and corporate trainers with the knowledge and tools to ...
                        Related searches
                        Education technology saqa subjects
                        Education technology saqa requirements
                        Education technology saqa pdf
                        Education technology saqa modules
                        Education technology saqa courses
                        saqa 65858
                        eduvos saqa
                        saqa credits

                        71636
                        image.png
                        SAQA
                        https://allqs.saqa.org.za › showQualification
                        The Minimum/Maximum Duration of the programme for Full-Time; 3 years. Year 1; Learning Components; Subjects; NQF Level; Credits. Fundamental Learning; ...

                        Free Education - National Certificate in Information ...
                        image.png
                        Facebook · Examinations Boards Authority of Africa PTY Ltd
                        3 years ago
                        2:51
                        Free Education - National Certificate in Information Technology : SAQA ID: 61591 · Are you a South African Citizen? Unemployed? Gauteng based?

                        The Education Innovation Department
                        The Foundation for Professional Development
                        https://www.foundation.co.za › education-innovation
                        Quality assurance and improvement of teaching and learning material. Accreditation of qualifications with the CHE and SAQA registration services include:.

                        SAQA BULLETIN Volume 20 Number 1
                        image.png
                        Harambee
                        https://www.harambee.co.za › uploads › 2021/09
                        PDF
                        29 Sept 2021 — Entrepreneurship, Higher Education, Technology, Artificial Intelligence (AI), Learning and Work. ISBN - 978-1-920649-57-9. THE SAQA BULLETIN ...

                        SAQA and the Durban University of Technology (DUT)...
                        image.png
                        Facebook · SAQA
                        20+ reactions · 4 years ago
                        Education and Training (TVET), Higher Education, Work, the booklet outlines the SAQA-DUT programme of research entitled Developing ...

                        110054
                        image.png
                        SAQA
                        https://allqs.saqa.org.za › showUnitStandard
                        PROVIDERS CURRENTLY ACCREDITED TO OFFER THIS UNIT STANDARD ; 31. SANDF COLLEGE OF EDUCATIONAL TECHNOLOGY ; 32. Sebenzisanane Human Capital ; 33. Southern African ...

                        Berea College of Technology – EQUIPPING YOU FOR ...
                        image.png
                        Berea College of Technology
                        https://www.bct.ac.za
                        We specialise in Information Technology and offer a range of higher education ... NQF Level 6 360 Credits. SAQA ID 49077 NQF Level 3 130 Credits ... SAQA ID 24414 ...

                        TERTIARY EDUCATION
                        image.png
                        Richfield
                        https://www.richfield.ac.za › uploads › 2023/04
                        PDF
                        03 Apr 2023 — information-technology/?section=contact-learning ... (SAQA ID number 35954: NQF 7: 400 credits ... Education Institution under the Higher Education ...

                        South African Qualifications Authority
                        image.png
                        Wikipedia
                        https://en.wikipedia.org › wiki › South_African_Qualifi...
                        It is made up of 29 members appointed by the Minister of Education in consultation with the Minister of Labour. SAQA is mandated by legislation to oversee the ...

                        Department of Science and Technology Education ...
                        image.png
                        University of Johannesburg
                        https://www.uj.ac.za › Faculty of Education
                        University Courses - Department of Science and Technology Education (SCITECHED) ; Programme Level: Postgraduate ; NQF Level: 8 ; NQF Credits: 120 ; SAQA ID: 101494.
                        More results

                        	Virus-free.www.avast.com


86 attachments
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
2K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.jpeg
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.jpeg
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
		image.png
1K View Scan and download
