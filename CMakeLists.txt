cmake_minimum_required(VERSION 3.22)
project(chronoSQL_poc)

set(CMAKE_CXX_STANDARD 17)

set(CMAKE_EXE_LINKER_FLAGS ${CMAKE_EXE_LINKER_FLAGS} "-static")

add_executable(chronoSQL_poc main.cpp eventWriter/EventWriter.h eventWriter/FSKeyValueEventWriter.h eventWriter/FSMemoryKeyValueEventWriterFactory.h eventWriter/IndexedKeyValueEventWriterFactory.h eventWriter/EventWriterFactory.h eventWriter/FSKeyValueEventWriterFactory.h eventGenerator/EventGenerator.h eventGenerator/KeyValueEventGenerator.h event/Event.h event/KeyValueEvent.h eventGenerator/KeyValueEventGeneratorFactory.h eventGenerator/EventGeneratorFactory.h config/ConfigurationManager.h config/Enumerations.h config/ConfigConstants.h config/ConfigurationValues.h eventWriter/IndexedKeyValueEventWriter.h chronolog/ChronoLog.h common/typedefs.h eventReader/EventReader.h eventReader/FSEventReader.h eventReader/EventReaderFactory.h eventReader/FSEventReaderFactory.h common/Constants.h eventWriter/FSMemoryKeyValueEventWriter.h eventReader/MemEventReader.h eventReader/MemEventReaderFactory.h common/MemoryEventStorage.h)
