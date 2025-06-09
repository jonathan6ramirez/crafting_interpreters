# Crafting Interpreters

---

Q: What is a dynamically typed language and give an example of one?
A: A dynamically typed language is one that type checks at runtime not when the code is being
    parsed. An example of this is Python.

Q: Where is the analysis of the program usually stored?
A: It can be stored inside of a symbols table, or stored as attributes on the syntax tree itself.

Q: What is usually the next step after parsing?
A: The next step is usually to make an IR or intermediate representation.

Q: What is the next step after making an IR or optimizing the code?
A: The next step is either deciding to make executable code, or machine code, or to make bytecode
    for a VM (virtual machine). At this step if you make executable code the compiler is very
    dependant on the architecture of the machine. If you make bytecode for a VM then the instructions
    are protable and can work with a variety of architecture right off the bat.

