# Lecture buzzwords



[toc]



Buzzwords are terms that are mentioned during lecture which are particularly important to understand thoroughly. This page tracks the buzzwords for each of the lectures and can be used as a reference for finding gaps in your understanding of course material.



## Lecture 1: Introduction and Basics

Level of transformation
	Algorithm
	System software
	Compiler
Cross abstraction layers
Tradeoffs
Caches
DRAM/memory controller
DRAM banks
Row buffer hit/miss
Row buffer locality
Unfairness
Memory performance hog
Shared DRAM memory system
Streaming access vs. random access
Memory scheduling policies
Scheduling priority
Retention time of DRAM
Process variation
Retention time profile
Power consumption
Bloom filter
Hamming code
Hamming distance
DRAM row hammer



## Lecture 2: Fundamental Concepts and ISA

Moore's Law
Algorithm –> step-by-step procedure to solve a problem
in-order execution
out-of-order execution
technologies that are available on cellphones
new applications that are made available through new computer architecture techniques
	more data mining (genomics/medical areas)
lower power (cellphones)
smaller cores (cellphones/computers)
etc.
Performance bottlenecks in a single thread/core processors
	multi-core as an alternative
Memory wall (a part of scaling issue)
Scaling issue
	Transistor are getting smaller
Key components of a computer
Design points
	Design processors to meet the design points
Software stack
Design decisions
Datacenters
Reliability problems that cause errors
Analogies from Kuhn's “The Structure of Scientific Revolutions” (Recommended book)
	Pre-paradigm science
	Normal science
	Revolutionary science
Components of a computer
	Computation
		Communication
		Storage
			DRAM
			NVRAM (Non-volatile memory): PCM, STT-MRAM
			Storage (Flash/Harddrive)
Von Neumann Model (Control flow model)
	Stored program computer
		Properties of Von Neumann Model: Stored program, sequential instruction processing
		Unified memory
		When does an instruction is being interpreted as an instruction (as oppose to a datum)?
		Program counter
		Examples: x86, ARM, Alpha, IBM Power series, SPARC, MIPS
Data flow model
	Data flow machine
		Data flow graph
	Operands
	Live-outs/Live-ins
		Different types of data flow nodes (conditional/relational/barrier)
How to do transactional transaction in dataflow?
Example: bank transactions
Tradeoffs between control-driven and data-driven
What are easier to program?
Which are easy to compile?
What are more parallel (does that mean it is faster?)
Which machines are more complex to design?
In control flow, when a program is stop, there is a pointer to the current state (precise state).
ISA vs. Microarchitecture
Semantics in the ISA
uArch should obey the ISA
Changing ISA is costly, can affect compatibility.
Instruction pointers
uArch techniques: common and powerful techniques break Vonn Neumann model if done at the ISA level
Conceptual techniques
Pipelining
Multiple instructions at a time
Out-of-order executions
etc.
Design techniques
Adder implementation (Bit serial, ripple carry, carry lookahead)
Connection machine (an example of a machine that use bit serial to tradeoff latency for more parallelism)
Microprocessor: ISA + uArch + circuits
What are a part of the ISA? Instructions, memory, etc.
Things that are visible to the programmer/software
What are not a part of the ISA? (what goes inside: uArch techniques)
Things that are not suppose to be visible to the programmer/software but typically make the processor faster and/or consumes less power and/or less complex





