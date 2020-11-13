    ------------- Minecraft Server -------------

Info -

Version : PaperMC 1.16.3 #246
Last Updated : 24/10/2020

Software -

Java 8+ (Required)

	Info -

	Version : 271
	Last Updated : 24/10/2020

Linux x64(Recommended)

	Info -
	
	Version : 18.04 "Bionic Beaver"
	Last Updated : 24/10/2020

Note -

I have added a .iso image of Ubuntu.

Here is how to boot from an .iso. https://www.raymond.cc/blog/how-to-run-livecd-iso-image-file-directly-in-windows/

There's a copy of Java included.

Here is how to install it. https://docs.oracle.com/javase/7/docs/webnotes/install/windows/server-jre-installation-windows.html

	------------- Startup -------------

Note - 

Windows :
Use start.bat to start server.

Linux :
Use start.sh to start server

Change -Xmx and -Xms to amount of RAM you want to allocate.

Always leave the OS at least 2GB of RAM for it to run smoothly.

It is currently set to 1 GB.

Use this table to calculate RAM for this command.

1 GB	1000 MB		1024 MB
2 GB	2000 MB		2048 MB
3 GB	3000 MB		3072 MB
4 GB	4000 MB		4096 MB
5 GB	5000 MB		5120 MB
6 GB	6000 MB		6144 MB
7 GB	7000 MB		7168 MB
8 GB	8000 MB		8192 MB
9 GB	9000 MB		9216 MB
10 GB	10000 MB	10240 MB

The code used is called "Akairs Flags". 
If you have any problems you can contact him here.

https://aikar.co/2018/07/02/tuning-the-jvm-g1gc-garbage-collector-flags-for-minecraft/

Code - 

java -Xms1024M -Xmx1024M -XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 -Dusing.aikars.flags=https://mcflags.emc.gs -Daikars.new.flags=true -jar server.jar

      ------------- Useful Info -------------

For any general problems ask me, or ask here, https://www.minecraftforum.net/forums/servers-java-edition/pc-servers



For RAM calculations consult : https://bit.ly/2TkKrF5


	------------- Plugins -------------

Plugins compatible with 1.16.3

Any problems, note them down and check for an update.

If that does not work, contact the Author with the link provided.

[WARNING] - Always create a Backup of the Server before updating plugins.

DiscordSRV - https://www.spigotmc.org/resources/discordsrv.18494/

	Info - 

	Version : 1.20.0
	Last Updated : 24/10/2020
	
	About : A Discord Integration.

Dynmap - https://www.spigotmc.org/resources/dynmap.274/

	Info -
	
	Version : 3.1 Beta.4
	Last Updated : 24/10/2020

	About : Allows you to view the world as a Webpage Map

	Note - 
	Ignore warning about "markers.yml" on Startup.

ChatControl - https://bit.ly/31H3lea

	Info - 

	Version : 5.9.0
	Last Updated : 24/10/2020
	Plugins Needed : ProtocolLib

	About : An Admin tool to control the chat.

Multiverse - https://www.spigotmc.org/resources/multiverse-core.390/

	Info - 
 
	Version : 4.2.2
	Last Updated : 24/10/2020

	About : Allows Multiple Worlds and easier travel between them.
	
	Note -
	Ignore warning about "Bukkit Adapters" on Startup.

WorldGuard - https://dev.bukkit.org/projects/worldguard

	Info -

	Version : 7.0.4
	Last Updated : 24/10/2020
	
	About : Another Grief Prevention Plugin

WorldEdit - https://dev.bukkit.org/projects/worldedit

	Info -

	Version : 7.2.0
	Last Updated : 24/10/2020

	About : A tool to edit the world.

bPermissions - https://www.spigotmc.org/resources/bpermissions.1053/

	Info -
	
	Version : 2.10.9
	Last Updated : 24/10/2020

	About : Makes permissions easier 

Vault - https://www.spigotmc.org/resources/vault.34315/updates

	Info - 

	Version : 1.7.3
	Last Updated : 24/10/2020

	About : A library for most Plugins.

EssentialsX - https://www.spigotmc.org/resources/essentialsx.9089/
	
	Info -

	Version : 2.18.1
	Last Updated : 24/10/2020

	About : A group of useful tools.

GriefPrevention - https://dev.bukkit.org/projects/grief-prevention/files/3084469/

	Info -

	Version : 16.16.0
	Last Updated : 24/10/2020

	About : Adds Grief Prevention to the Server

ProtocolLib - https://www.spigotmc.org/resources/protocollib.1997/

	Info - 
	
	Version : 4.5.1
	Last Updated : 24/10/2020

	About : A library for ChatControl.

Player Kits - https://www.spigotmc.org/resources/playerkits-fully-configurable-kits-1-8-1-16.75185/

	Info - 

	Version : 2.10.4
	Last Updated : 24/10/2020

	About : Adds Kits for when new people join

Welcome Message - https://www.spigotmc.org/resources/welcome-message.4393/

	Info -
	
	Version : 1.0
	Last Updated : 24/10/2020

	About : Adds a welcome message when a new person joins.

Lag Assist - https://www.spigotmc.org/resources/lagassist-⚡-advanced-performance-solution-⚡-1-8-1-16-compatible.56399/

	Info -

	Version : 2.23.0
	Last Updated : 24/10/2020

	About : Removes Lag from Server.
