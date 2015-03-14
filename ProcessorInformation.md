# Introduction #

The information in this structure defines the attributes of a single processor; a separate structure instance is provided for each system processor socket/slot. For example, a system with an 890 IntelDX2™ processor would have a single structure instance while a system with an IntelSX2™ processor  would have a structure to describe the main CPU and a second structure to describe the 80487 coprocessor.

NOTE: One structure is provided for each processor instance in a system. For example, a system that supports up to two processors includes two Processor Information structures — even if only one processor is currently installed.

Software that interprets the SMBIOS information can count the Processor Information structures to determine the maximum possible configuration of the system.

# Sample Code #
http://code.google.com/p/tsmbios/source/browse/trunk/Samples/Table%204%20Processor%20Information/ProcessorInformation.dpr