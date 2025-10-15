# Vamsi Krishna Kothapalli

**VLSI Verification Engineer**

📍 Hyderabad, India
<br>
📧 [vamsikkothapalli.99@gmail.com](mailto:vamsikkothapalli.99@gmail.com) | 🔗 [linkedin.com/in/vamsi-krishna-kothapalli](https://linkedin.com/in/vamsi-krishna-kothapalli)

---

### 👋 About Me

I am a detail-oriented VLSI Engineer combining hands-on experience in physical design and static timing analysis (STA) from my internship at **Intel** with a dedicated focus on advanced ASIC verification.

Recognizing the critical link between front-end design intent and back-end implementation, I have spent the last year intentionally upskilling my expertise in UVM and advanced verification methodologies. This strategic focus has allowed me to build a comprehensive, full-chip perspective. My goal is to leverage my unique understanding of STA and physical design to anticipate and solve complex verification challenges earlier in the development cycle. I am now seeking a verification role where I can apply this holistic skill set.

---

### 🛠️ Technical Skills

| Category | Skills |
| :--- | :--- |
| **Verification Methodologies** | UVM, SystemVerilog Assertions (SVA), Functional Coverage, Code Coverage |
| **Protocols** | AXI4, APB, I2C, SPI, UART, FIFO |
| **Languages** | SystemVerilog, Verilog, Python, TCL |
| **Tools** | Synopsys PrimeTime & ICC2, Xilinx Vivado |

---

### 💼 Professional Experience

**Graduate Technical Intern - Design Flow Automation & STA** @ **Intel** (Bangalore, India)
<br>
*Jun 2023 - May 2024*

* Automated extraction and analysis of timing reports from Synopsys PrimeTime, **reducing manual effort by over 80%**.
* Developed Python and TCL scripts to parse multi-gigabyte log files and generate concise summary reports.
* Contributed to the physical design flow using Synopsys ICC2, gaining hands-on experience in a production environment.

---

### 🚀 Project Portfolio

This portfolio showcases key projects completed during my focused upskilling in advanced ASIC verification. Each project demonstrates the practical application of modern, UVM-based methodologies and serves as a testament to the skills I've honed during my strategic transition into the verification domain.

#### **[AXI4 Slave (UVM)](https://github.com/kothapallivamsikrishna/axi4-slave-uvm)**
* Developed a layered UVM testbench to verify an AXI4 slave, featuring a master-emulating driver that handles multi-channel handshaking for constrained-random burst transactions.

#### **[APB Slave RAM (UVM)](https://github.com/kothapallivamsikrishna/apb-slave-uvm)**
* Verifies an APB slave memory using a master-emulating UVM testbench. The environment drives the APB protocol handshake and includes sequences for both valid transactions and error injection to test the `PSLVERR` response.

#### **[Configurable UART Protocol (UVM)](https://github.com/kothapallivamsikrishna/uart-protocol-uvm)**
* A comprehensive project verifying a configurable UART (TX/RX) in a loopback setup. The UVM environment uses multiple targeted sequences to validate various data lengths, baud rates, parity settings, and stop bit configurations.

#### **[I2C Memory Controller (UVM)](https://github.com/kothapallivamsikrishna/i2c-memory-uvm)**
* Verifies an I2C memory system where an I2C master and slave are in a loopback configuration. The testbench drives the system via a parallel interface and uses a predictive scoreboard to validate data integrity.

#### **[SPI Master Controller (UVM)](https://github.com/kothapallivamsikrishna/spi-master-uvm)**
* Verifies an SPI master communicating with a memory slave. The testbench features a stateful scoreboard with a memory model and utilizes targeted sequences for both valid data transfers and error injection with invalid addresses.

#### **[SPI Slave Memory (UVM)](https://github.com/kothapallivamsikrishna/spi-slave-uvm)**
* The counterpart to the SPI master project, this UVM environment emulates a master to verify a slave memory. The driver actively controls the SPI bus, and a predictive scoreboard validates the slave's responses.

#### Functional Coverage Verification of Synchronous FIFO
* Constructed a parameterizable SystemVerilog testbench to verify FIFO functionality at multiple depths.
* Utilized UVM stimulus and monitoring for concurrent read and write operations.
* Defined covergroups and cross-coverage for key FIFO states and transitions.
* *(Note: Full source code is being organized and will be uploaded shortly.)*

#### Assertion-Based Verification of UART Transceiver
* Authored SystemVerilog Assertions (SVA) for protocol checks, including start-bit detection, data sampling, and stop-bit timing.
* Established assertion-based monitors for automatic violation reporting during simulation.
* Implemented covergroups to track error conditions and control events.
* *(Note: Full source code is being organized and will be uploaded shortly.)*

#### **[Baud Rate Generator (UVM)](https://github.com/kothapallivamsikrishna/baud-rate-generator-uvm)**
* A practical project verifying a configurable clock divider used in serial protocols. Features a timing-aware UVM testbench that measures the generated clock period against a golden model with tolerance.

#### **[4-bit Multiplier (UVM)](https://github.com/kothapallivamsikrishna/4-bit-multiplier-uvm)**
* Focuses on verifying arithmetic logic by building a UVM testbench with a golden reference model in the scoreboard for a 4-bit multiplier.

#### **[D Flip-Flop (UVM)](https://github.com/kothapallivamsikrishna/d-flip-flop-uvm)**
* A fundamental sequential element verified with an advanced testbench featuring multiple, targeted sequences to test specific behaviors.

#### **[Sequential Adder (UVM)](https://github.com/kothapallivamsikrishna/sequential-adder-uvm)**
* Demonstrates verification of a clocked, sequential design, including reset sequence management and timing-aware UVM components.

#### **[4:1 Multiplexer (UVM)](https://github.com/kothapallivamsikrishna/4-to-1-MUX-UVM)**
* A classic combinational logic project used to demonstrate a full UVM testbench with randomized stimulus and self-checking scoreboard.

#### **[Combinational Adder (UVM)](https://github.com/kothapallivamsikrishna/combinational-adder-uvm)**
* A foundational project demonstrating a complete UVM environment built from scratch to verify a simple 4-bit adder.

---

### 📚 UVM Cookbook & Verification Patterns

This section highlights focused code examples that implement reusable patterns for advanced UVM features and verification techniques.

* **[UVM Virtual Sequencer Pattern](https://github.com/kothapallivamsikrishna/uvm-virtual-sequencer-pattern)**: Demonstrates the virtual sequencer pattern for synchronizing and coordinating stimulus across multiple, independent UVM agents in a complex testbench.
* **[UVM Scoreboard Synchronization Pattern](https://github.com/kothapallivamsikrishna/uvm-scoreboard-sync-pattern)**: Implements a robust scoreboard using `uvm_tlm_analysis_fifo` to collect and synchronize transactions from a DUT monitor and a reference model before comparison.
* **[UVM Sequence Library Pattern](https://github.com/kothapallivamsikrishna/uvm-sequence-library-pattern)**: Implements the `uvm_sequence_library` pattern for managing, randomizing, and executing collections of sequences—a key technique for building scalable and maintainable test suites.
* **[UVM TLM FIFO Pattern](https://github.com/kothapallivamsikrishna/uvm-tlm-fifo-pattern)**: A focused example of using `uvm_tlm_fifo` to create a buffered, transaction-level communication channel between two independent UVM components (`sender` and `receiver`).

---

### 🎓 Education

**Master of Technology, VLSI Design** (CGPA: 8.46)
<br>
*VIT, Vellore | 2022 - 2024*

---

### 📜 Certifications

*Key certifications from Udemy by instructor Kumar Khandagle:*
* Verification Series Part 1: SystemVerilog Essentials
* Verification Series Part 2: Hands-On SystemVerilog Projects
* Verification Series Part 3: UVM Essentials
* Verification Series Part 4: UVM Projects
* Verification Series Part 6: SystemVerilog Assertions Basics
* Verification Series Part 7: SystemVerilog Functional Coverage
* Verification Series 8: Code Coverage with Vivado 2024.1
* Verilog Lint essentials for RTL Design Engineer
