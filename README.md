# KafkaPluginDocumentation Plugin

This Github project contains this Wiki as well as Blueprint coding examples for Kafka Plugin.

Please refer to the Wiki for full documentation: https://github.com/corneel/KafkaPluginDocumentation/wiki

Plugin Features:

Provides access to Kafka streaming platform.
Provides an actor that can be used to access Kafka without coding.
Provides a blueprint class that can be used in any component.
Provides blueprint accessible wrapping of the C++ functions that access Kafka.
Code Modules:

 UE4Editor-Kafka.dll (Plugin dll)
Librdkafka dlls:
librdkafka.dll
librdkafkacpp.dll
msvcr120.dll
zlib.dll


Number of Blueprints:

KafkaBlueprintClass - a Blueprint class that contains the majority of the plugin blueprint code.
KafkaPluginActor - implements the KafkaBlueprintClass and more blueprint code.
KafkaPluginStarterMap (A map that contains two actor objects and a blueprint)
KafkaPluginRequestStructure - a structure used in all blueprints.
KafkaActorWidget - a widget used by the KafkaPluginActor.
KafkaPluginFunctions enumeration - used in all blueprints.
KafkaController - just a default controller.
Augmented_Enterprise_128_Mat - a material used in the KafkaPluginActor.
Augmented_Enterprise_128 - texture used to make the material


Number of C++ Classes:

No C++ classes will be provided as part of the plugin. 



Network Replicated: (Yes/No)

No 



Supported Development Platforms:

Win64 only



Supported Target Build Platforms: 

Win64 only



Documentation: https://github.com/corneel/KafkaPluginDocumentation/wiki



Example Project: The example map included in the plugin. 



Important/Additional Notes:

