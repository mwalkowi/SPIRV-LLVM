set(LLVM_LINK_COMPONENTS
  ${LLVM_TARGETS_TO_BUILD}
  Object
  Support
  )

add_llvm_tool(llvm-readobj
  ARMAttributeParser.cpp
  ARMWinEHPrinter.cpp
  COFFDumper.cpp
  ELFDumper.cpp
  Error.cpp
  llvm-readobj.cpp
  MachODumper.cpp
  ObjDumper.cpp
  StreamWriter.cpp
  Win64EHDumper.cpp
  )
