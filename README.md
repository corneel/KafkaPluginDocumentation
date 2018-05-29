# KafkaPluginDocumentation Plugin

This Github project contains this Wiki as well as Blueprint coding examples for Kafka Plugin.

Please refer to the Wiki for full documentation: https://github.com/corneel/KafkaPluginDocumentation/wiki

Plugin Features:

The plugin wraps some of the Librdkafka API's.
The focus in this version is on the streaming API. It does not implement messaging.
It doesn't wrap API's related to partition management.
The consumer API that is wrapped is the high-level KafkaConsumer class.
The low-level Consumer class has not been wrapped at this stage.
The emphasis in this version is to provide several levels of abstraction to the Unreal Blueprint developer.
The C++ interface is not public at this stage.
Callbacks are only "virtually" implemented (using blueprint events), in order to provide a low-level Blueprint event interface. The reason for this is that the KafkaConsumer class does not implement callbacks at this stage.


Code Modules: 

Librdkafka dlls:

librdkafka.dll

librdkafkacpp.dll

msvcr120.dll

zlib.dll


Number of Blueprints:
KafkaBlueprintClass - a Blueprint class that contains the majority of the plugin blueprint code.

KafkaPluginActor - implements the KafkaBlueprintClass and adds additional blueprint code.

KafkaPluginStarterMap (A map that contains two KafkaPluginActor objects and a map blueprint)

KafkaPluginRequestStructure - a structure used in all blueprints.

KafkaActorWidget - a widget used by the KafkaPluginActor.

KafkaPluginFunctions enumeration - used in all blueprints.

KafkaController - just a default controller.

Augmented_Enterprise_128_Mat - a material used in the KafkaPluginActor.

Augmented_Enterprise_128 - texture used to make the Augmented_Enterprise_128_Mat material



Number of C++ Classes:

No C++ classes will be provided as part of the plugin. 

Network Replicated: (Yes/No)

No 

Supported Development Platforms: (Please include a list of platforms on which the product can be used for development)

Win64 only

Supported Target Build Platforms: (Please include a list of platforms for which the product can be targeted in a packaged build)

Win64 only

Documentation: https://github.com/corneel/KafkaPluginDocumentation/wiki

Example Project: The example map included in the content of the plugin, constitutes a sample project. 

