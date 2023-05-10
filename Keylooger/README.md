Keylogger:
keystroke logging, often regarded as keylogging or keyboard capturing, is recording the keys struck on a keyboard,
typically covertly. Usually, the users (i.e., victims) using the keyboard are uninformed that their actions 
are being monitored. Data can then be retrieved by remote hackers that created the logging program.

Why we used java:
 1. Because we know that Java can't read anything outside of JVM (Java Virtual Machine),
  I found a practical API called jNativeHook, making it happends.
 2. Java is cross platform because a program's source code is compiled into an intermediate "bytecode" language.

Build project:
The keys will be written in keys.txt file and application logs will reside inside file.

Don't forget to stop the key logger application after you've done logging.
