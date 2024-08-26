QC runtime: Part of QC OS that will provide JRE and JIT like features that allow for the same QC circuit to be reused across different target QC platforms. This works with the differentiable program   
The runtime is a larger module and is part of the QC OS. The runtime hosts various placeholders, lookups, pointers to different software, hardware, system libraries that are part of the OS.
These modules are loaded into the runtime based on the unique project needs. This is similar to a virtual environment or a container, however dedicated to the universal OS and Q program.
