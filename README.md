# plz-help
Need help with CCL. Keeps crashing minecraft
Below is what pops up
---- Minecraft Crash Report ----

WARNING: coremods are present:
  Inventory Tweaks Coremod (InventoryTweaks-1.63.jar)
  XaeroMinimapPlugin (Xaeros_Minimap_20.27.3_Forge_1.12.jar)
Contact their authors BEFORE contacting forge

// On the bright side, I bought you a teddy bear!

Time: 12/30/20 1:54 PM
Description: There was a severe problem during mod loading that has caused the game to fail

net.minecraftforge.fml.common.LoaderExceptionModCrash: Caught exception from CodeChicken Lib (codechickenlib)
Caused by: codechicken.lib.configuration.ConfigFile$ConfigException: codechicken.lib.configuration.ConfigParseException: Invalid value type  , @Line:1,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
	at codechicken.lib.configuration.ConfigFile.load(ConfigFile.java:61)
	at codechicken.lib.configuration.ConfigFile.<init>(ConfigFile.java:43)
	at codechicken.lib.configuration.ConfigFile.<init>(ConfigFile.java:29)
	at codechicken.lib.configuration.ConfigFile.<init>(ConfigFile.java:19)
	at codechicken.lib.CodeChickenLib.preInit(CodeChickenLib.java:50)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at net.minecraftforge.fml.common.FMLModContainer.handleModStateEvent(FMLModContainer.java:637)
	at sun.reflect.GeneratedMethodAccessor8.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at com.google.common.eventbus.Subscriber.invokeSubscriberMethod(Subscriber.java:91)
	at com.google.common.eventbus.Subscriber$SynchronizedSubscriber.invokeSubscriberMethod(Subscriber.java:150)
	at com.google.common.eventbus.Subscriber$1.run(Subscriber.java:76)
	at com.google.common.util.concurrent.MoreExecutors$DirectExecutor.execute(MoreExecutors.java:399)
	at com.google.common.eventbus.Subscriber.dispatchEvent(Subscriber.java:71)
	at com.google.common.eventbus.Dispatcher$PerThreadQueuedDispatcher.dispatch(Dispatcher.java:116)
	at com.google.common.eventbus.EventBus.post(EventBus.java:217)
	at net.minecraftforge.fml.common.LoadController.sendEventToModContainer(LoadController.java:219)
	at net.minecraftforge.fml.common.LoadController.propogateStateMessage(LoadController.java:197)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at com.google.common.eventbus.Subscriber.invokeSubscriberMethod(Subscriber.java:91)
	at com.google.common.eventbus.Subscriber$SynchronizedSubscriber.invokeSubscriberMethod(Subscriber.java:150)
	at com.google.common.eventbus.Subscriber$1.run(Subscriber.java:76)
	at com.google.common.util.concurrent.MoreExecutors$DirectExecutor.execute(MoreExecutors.java:399)
	at com.google.common.eventbus.Subscriber.dispatchEvent(Subscriber.java:71)
	at com.google.common.eventbus.Dispatcher$PerThreadQueuedDispatcher.dispatch(Dispatcher.java:116)
	at com.google.common.eventbus.EventBus.post(EventBus.java:217)
	at net.minecraftforge.fml.common.LoadController.distributeStateMessage(LoadController.java:136)
	at net.minecraftforge.fml.common.Loader.preinitializeMods(Loader.java:629)
	at net.minecraftforge.fml.client.FMLClientHandler.beginMinecraftLoading(FMLClientHandler.java:252)
	at net.minecraft.client.Minecraft.func_71384_a(Minecraft.java:467)
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:378)
	at net.minecraft.client.main.Main.main(SourceFile:123)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)
Caused by: codechicken.lib.configuration.ConfigParseException: Invalid value type  , @Line:1,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
	at codechicken.lib.configuration.ConfigTag.parseTag(ConfigTag.java:92)
	at codechicken.lib.configuration.ConfigFile.load(ConfigFile.java:59)
	... 44 more


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- System Details --
Details:
	Minecraft Version: 1.12.2
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 1.8.0_51, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 556608632 bytes (530 MB) / 805306368 bytes (768 MB) up to 2147483648 bytes (2048 MB)
	JVM Flags: 8 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xmx2G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
	IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
	FML: MCP 9.42 Powered by Forge 14.23.5.2854 17 mods loaded, 17 mods active
	States: 'U' = Unloaded 'L' = Loaded 'C' = Constructed 'H' = Pre-initialized 'I' = Initialized 'J' = Post-initialized 'A' = Available 'D' = Disabled 'E' = Errored

	| State | ID                 | Version                  | Source                                        | Signature                                |
	|:----- |:------------------ |:------------------------ |:--------------------------------------------- |:---------------------------------------- |
	| LCH   | minecraft          | 1.12.2                   | minecraft.jar                                 | None                                     |
	| LCH   | mcp                | 9.42                     | minecraft.jar                                 | None                                     |
	| LCH   | FML                | 8.0.99.99                | forge-1.12.2-14.23.5.2854.jar                 | e3c3d50c7c986df74c645c0ac54639741c90a557 |
	| LCH   | forge              | 14.23.5.2854             | forge-1.12.2-14.23.5.2854.jar                 | e3c3d50c7c986df74c645c0ac54639741c90a557 |
	| LCH   | xaerominimap_core  | 1.12.2-1.0               | minecraft.jar                                 | None                                     |
	| LCH   | autocrafter        | 4.3                      | autocrafter-4.3.jar                           | None                                     |
	| LCE   | codechickenlib     | 3.2.3.358                | CodeChickenLib-1.12.2-3.2.3.358-universal.jar | f1850c39b2516232a2108a7bd84d1cb5df93b261 |
	| LC    | mantle             | 1.12-1.3.3.55            | Mantle-1.12-1.3.3.55.jar                      | None                                     |
	| LC    | jei                | 4.16.1.301               | jei_1.12.2-4.16.1.301.jar                     | None                                     |
	| LC    | tconstruct         | 1.12.2-2.13.0.183        | TConstruct-1.12.2-2.13.0.183.jar              | None                                     |
	| LC    | conarm             | 1.2.5.9                  | conarm-1.12.2-1.2.5.9.jar                     | 2484ef4d131fdc0dca0647aa21b7b944ddb935a1 |
	| LC    | enderstorage       | 2.4.5.135                | EnderStorage-1.12.2-2.4.5.135-universal.jar   | f1850c39b2516232a2108a7bd84d1cb5df93b261 |
	| LC    | inventorytweaks    | 1.63+release.109.220f184 | InventoryTweaks-1.63.jar                      | 55d2cd4f5f0961410bf7b91ef6c6bf00a766dcbe |
	| LC    | ironchest          | 1.12.2-7.0.67.844        | ironchest-1.12.2-7.0.72.847.jar               | None                                     |
	| LC    | testdummy          | 1.12                     | MmmMmmMmmMmm-1.12-1.14.jar                    | None                                     |
	| LC    | tinkertoolleveling | 1.12.2-1.1.0.DEV.b23e769 | TinkerToolLeveling-1.12.2-1.1.0.jar           | None                                     |
	| LC    | xaerominimap       | 20.27.3                  | Xaeros_Minimap_20.27.3_Forge_1.12.jar         | None                                     |

	Loaded coremods (and transformers): 
Inventory Tweaks Coremod (InventoryTweaks-1.63.jar)
  invtweaks.forge.asm.ContainerTransformer
XaeroMinimapPlugin (Xaeros_Minimap_20.27.3_Forge_1.12.jar)
  xaero.common.core.transformer.ChunkTransformer
  xaero.common.core.transformer.NetHandlerPlayClientTransformer
  xaero.common.core.transformer.EntityPlayerTransformer
  xaero.common.core.transformer.AbstractClientPlayerTransformer
  xaero.common.core.transformer.WorldClientTransformer
  xaero.common.core.transformer.EntityPlayerSPTransformer
  xaero.common.core.transformer.PlayerListTransformer
	GL info: ' Vendor: 'Intel' Version: '4.6.0 - Build 27.20.100.8189' Renderer: 'Intel(R) HD Graphics 520'
	Pulsar/tconstruct loaded Pulses: 
		- TinkerCommons (Enabled/Forced)
		- TinkerWorld (Enabled/Not Forced)
		- TinkerTools (Enabled/Not Forced)
		- TinkerHarvestTools (Enabled/Forced)
		- TinkerMeleeWeapons (Enabled/Forced)
		- TinkerRangedWeapons (Enabled/Forced)
		- TinkerModifiers (Enabled/Forced)
		- TinkerSmeltery (Enabled/Not Forced)
		- TinkerGadgets (Enabled/Not Forced)
		- TinkerOredict (Enabled/Forced)
		- TinkerIntegration (Enabled/Forced)
		- TinkerFluids (Enabled/Forced)
		- TinkerMaterials (Enabled/Forced)
		- TinkerModelRegister (Enabled/Forced)
