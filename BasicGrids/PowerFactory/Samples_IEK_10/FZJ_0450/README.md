Export information:
- Tool: PowerFactory 2020 SP2A
- Export way: 
    1. Tools -> CGMES Tools -> Grid to CIM Conversion
        * check the option "Create bus-branch model", otherwise a node-breaker model will be as default generated.
        * Select to convert all profiles or only selected ones.
        * check the box of "Selected" but do not check "Boundary model" (which will cause errors) and give a file name for "Authority URI".
    2. Tools -> CGMES Tools -> CIM Data Export
- Model Description: 110kV/35kV/10kV buses + transmission lines + external grid + transformers