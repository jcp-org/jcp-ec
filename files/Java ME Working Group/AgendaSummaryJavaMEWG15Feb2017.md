<font color="#000000"><font face="Times-Roman, serif"><font size="7" style="font-size: 36pt">**Java ME Working Group Meeting Minutes**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Date**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Wednesday, 15 February 2017, 9:00 am PST</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Location**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Teleconference</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Agenda**</font></font></font>

<span style="font-variant: normal"><font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">Follow up on action items from last meeting. Review materials submitted by Working Group members.</span></span></span></font></font></font></span>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Attendees**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Heather VanCura</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Leonardo Lima</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Calinel Pasteanu</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Hendrik Hoefer</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Thomas Lampart</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Mike DeNicola</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Werner Keil</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Minutes**</font></font></font>

<font color="#1d2129"><font face="San Francisco, apple-system, system-ui, .SFNSText-Regular, sans-serif"><font size="1" style="font-size: 7pt"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">W</font></font><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">orking Group members shared their technical and non-technical requirements for Java ME.</font></font></font></font></font>

<font color="#1d2129"><font face="San Francisco, apple-system, system-ui, .SFNSText-Regular, sans-serif"><font size="1" style="font-size: 7pt"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">V2COM:</font></font></font></font></font>

<font color="#1d2129"><font face="San Francisco, apple-system, system-ui, .SFNSText-Regular, sans-serif"><font size="1" style="font-size: 7pt"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">Th</font></font><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">ese are the features I miss in Java ME 8 or Java SE 8 that I wanted in an embedded Java platform:</font></font></font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">Comparing Java ME to Java SE:  
Continue to close the gap between the languages:  
Stream support would be great  
Reflection  
Runtime Annotations  
Concurrency utilities  
Collections and Math APIs  
(these could be implemented as separate, optional JSRs?)  
Comparing Java SE to ME (MEEP):  
Basically everything that makes MEEP:  
Software provisioning  
Software management  
Application concurrency (MVM)  
Inter-application communication (IMC)  
Events  
Service Provider/Consumer pattern  
(much of these are provided by OSGi, which we use for our Java SE capable gateways)  
Missing in both platforms (but may be available from others, as pointed by Calinel)  
Support for emerging standards  
REST client  
Communication protocols such as MQTT and/or COAP  
Expansion of the Device IO capabilities  
Expansion of the OTA for new networks and protocols (such as MQTT/COAP)  
Continued support for multi-midlet environments</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">Non-technical:</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">For business reasons would like to see as JSRs</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">Gemalto:</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">Technical:</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">* Keep Java ME up-to-date (-> JSR maintenance release, Java ME 9)</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">* Evolve Java ME eco system (->JSRs for device IO, security, …) times</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">Non technical:</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">* Similar development concept for Java ME as for Java SE (→OpenJDK)</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">MicroDoc:  
ME and SE are converging. ME 8/MEEP did a huge step to be more SE like and the SE profiles made SE more like ME. Still I think, that what we get out of this is too static. One can either use a very small runtime without JNI or a bigger runtime without some of the ME frameworks. Although ME now supports most of the SE 8 language features, some are still missing. The situation with class libraries is similar.</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">I think that the situation could be improved if there was no difference in the language itself and in the class libraries. A class should have the same signature, no matter what runtime it runs on. Features, like class loaders, should be selected by the programmer based on the requirements and available resources. In an ideal world this would work like "make menuconfig" for the Linux Kernel and result in an optimal runtime for the specific application. To some extend this is how it works with C/C++; you link that lib or you don't. The Java 9 module system and to some extend JLink are very promising technologies that could support such an approach.</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">Startup time is one of the key factors for some embedded application and the jar file format might not be the best choice for this, given that unzip, defineClass() etc are very expensive operations. It is likely that this aspect does not require standardization, but will be left to the implementations - but we may want to think about this.</font></font></font>

<span style="font-variant: normal"><font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">I also think that most of these requirements are not specific to embedded, but are important for servers as well, when it comes to MicroServices, elastic scaling and containers.</span></span></span></font></font></font></span>  

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">I apologize for being very generic. One of the more concrete things I am missing is a better operating system/C/C++ integration, like JNA [1]: Device I/O is a step in the right direction. [https://github.com/java-native-access/jna#readme](https://github.com/java-native-access/jna#readme)</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">Fujitsu: There are some de facto developer and runtime environments at Android/iOS, so we do not need Java ME in this area.</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Next Steps:</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Refine lists to publish for discussion at EC meeting.</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Next WG Meeting 22 February 9:00 PST.</font></font></font>