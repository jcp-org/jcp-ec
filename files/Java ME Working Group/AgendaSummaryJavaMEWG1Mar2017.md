<font color="#000000"><font face="Times-Roman, serif"><font size="7" style="font-size: 36pt">**Java ME Working Group Meeting Minutes**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**All [Minutes](https://java.net/downloads/jcp-ec/Java%20ME%20Working%20Group/) for Java ME Working Group:**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Date**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Wednesday, 1 March 2017, 9:00 am PST</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Location**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Teleconference</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Agenda**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Discuss and assimilate materials submitted by Working Group members.</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Attendees**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Heather VanCura</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Leonardo Lima</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Calinel Pasteanu</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Thomas Lampart</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Mike DeNicola</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Mike Milinkovich</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Minutes**</font></font></font>

<font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt">We used the session to incorporate meeting materials into a proposal to discuss at a future EC Meeting (April 4 is target date).</font></font></font>

<a name="docs-internal-guid-56928cb5-9b8a-c858-ccd5-837459becca8"></a><font color="#353744"><font face="Proxima Nova"><font size="7" style="font-size: 36pt"><span style="background: transparent"><font color="#1d2129"><font face="Times New Roman, serif"><font size="5" style="font-size: 18pt"><span style="letter-spacing: normal">Java [ME].Next (Embedded world)</span></font></font></font></span></font></font></font>

<font color="#666666"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Advancing Java on embedded devices</span>**</font></font></font>

# <font color="#353744"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">OVERVIEW</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Java as an IoT platform. Goals and requirements for Java ME, technical and non-technical, including business aspects, market demand and what is preventing adoption of current Java ME platform, Java ME 8\. Why would a Java ME 9 do better in adoption than Java ME 8.</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">We discussed different options today and what have members done with Java ME. What are the differences between Java SE 9 and Java ME and why Java SE 9 might not meet requirements of this market and why Java ME is important. Is there a need for new JSRs? Calinel agreed that there is one gap, and a “low version” is needed, API and semantic parity is needed. There are two possible ways of doing that: new from scratch, or update Java ME. V2COM uses older version, Gemalto doesn’t use Java ME 8\. Why the Java ME licensees haven’t upgraded to Java ME 8\. From the IoT side/libraries, there’s no explicit need of platform support, no need to have a JSR for the protocols, it’s already available from Oracle for download from the website.</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Thomas confirmed that Java ME 3 is proven and stable, clients like it. There’s no market demand for Java ME 8, but that might change in the future - clients don’t want to have two code-bases and so continuing the convergence of java ME/SE is a good thing. There’s no indication of new Java ME work, so using Java ME 8 seems not future-proof. If there's a Java 9 in the works, continuity would improve perception. Java ME 8 adoption issues for Gemalto are just non-technical, technically it is good and everything they wanted is in there. What kept Gemalto from using Java ME 8 were non-technical business reasons. A model like SE development would help Java ME development and adoption, as no one can do any work but Oracle - all others would have to start from scratch.</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">We discussed Java as an IoT platform. Hendrik discussed that we need a version of Java for ow processing power systems. The name is not important, not GUI, but a very small run time would be needed. This version have to be something that is in line with SE, feature wise - gave an example of different String file. Java 9 with its module system might be a better solution; a fork of Java is not a good solution. Requirements: fast startup time, low cost. JAR File format is an aggressor to startup time, for example. There’s no currently suitable solution for 32-bit, 200MHz processors - they go to C/C++. As an alternative to evolving Java ME, can we take Java 9 and make it fit in Java ME specs. Java ME adoption might not be great because of its licensing model. Look at the requirements: why SE 9 does or does not meet the requirements, and look into the future for Java 10\. It’s a lot harder to sell embedded runtime, there’s a need to recompile and conform to processor specs.</span></font></font></font>

# <font color="#353744"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">GOALS</span>**</font></font></font>

1.  <font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Describe technical and non-technical requirements for Java to be relevant and useful in embedded devices and IoT.</span></font></font></font>

2.  <font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Provide grounds for discussion with Java leadership within Oracle on how to improve Java ME, or the next version of Java for Micro devices.</span></font></font></font>

# <font color="#353744"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">USE CASES</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">There’s different set of requirements for each IoT / embedded use cases</span></font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Specialized Device</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">(constrained device, specialized hardware)</span></font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Gateway-class device</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">(less-constrained device, has an OS)</span></font></font></font>

# <font color="#353744"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">TECHNICAL SPECIFICATIONS</span>**</font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Performance</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[Microdoc: Startup time]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[Low core/speed processors]</span></font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Size</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[Total size of VM + application code can important, using Java SE 9 might result in a big VM for lots of environments, <<describe environments>></span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[RAM consumption by Java SE x Java Me]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[Werner Keil]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">In Java 9 the java.base module seems much too big for Embedded or ME:</span></font></font></font>

[<span style="font-variant: normal"><font color="#1155cc"><span style="text-decoration: none"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="font-style: normal"><u><span style="font-weight: normal"><span style="background: transparent">http://download.java.net/java/jdk9/docs/api/java.base-summary.html</span></span></u></span></font></font></span></font></span>](http://download.java.net/java/jdk9/docs/api/java.base-summary.md)

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Shows it contains both java.util with Date/Time and the “new” Date/Time API which Spec Leads claim is too big for ME and modularity wasn’t a requirement.</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Does the java.base module look different in Java SE Embedded 9 or is it identical?</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Could a smaller “base” module be found that’s small enough for Java ME?</span></font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Java ME/SE language level compatibility</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[Microdoc] ME and SE are converging. ME 8/MEEP did a huge step to be more SE like and the SE profiles made SE more like ME. Still I think, that what we get out of this is too static. One can either use a very small runtime without JNI or a bigger runtime without some of the ME frameworks. Although ME now supports most of the SE 8 language features, some are still missing. The situation with class libraries is similar.</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[Some classes like String are different in Java ME and SE]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[V2COM]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Comparing Java ME to Java SE:</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Continue to close the gap between the languages:</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Stream support would be great</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Reflection</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Runtime Annotations</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Concurrency utilities</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Collections and Math APIs</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">(these could be implemented as separate, optional JSRs?)</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Comparing Java SE to ME (MEEP):</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Basically everything that makes MEEP:</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Software provisioning</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Software management</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Application concurrency (MVM)</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Inter-application communication (IMC)</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Events</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Service Provider/Consumer pattern</span></font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Native Code support</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[Microdoc mentioned about JNI:]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">One of the more concrete things I am missing is a better operating system/C/C++ integration, like JNA [1]: Device I/O is a step in the right direction. https://github.com/java-native-access/jna#readme</span></font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">IoT specific or new APIs/JSRs</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[V2COM:]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Support for emerging standards</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">REST client</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Communication protocols such as MQTT and/or COAP</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Expansion of the Device IO capabilities</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Expansion of the OTA for new networks and protocols (such as MQTT/COAP)</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[Gemalto]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">* Evolve Java ME eco system (->JSRs for device IO, security, …) times</span></font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Updating old JSRs</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Gemalto/Thomas expanded on more technical items to evolve the Java ME ecosystem (->JSRs for device IO, security, …).</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">JSR177</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Update/rework of JSR 177: Address topics like access to TEE (Trusted Execution Environment), SE (Secure Element), services like secure storage, handling of credentials for TLS</span></font></font></font>

### <font color="#353744"><font face="Proxima Nova"><font size="3" style="font-size: 13pt"><span style="background: transparent">JSR for MEEP</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Continued support for multi-midlet environments</span></font></font></font>

# <font color="#353744"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">BUSINESS SPECIFICATIONS</span>**</font></font></font>

# <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Licensing</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Current business model does not scale. Dated licensing model licensing. Need a frictionless technology onramp and then standardize.</span></font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Development Model</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Similar development concept for Java ME as for Java SE (→OpenJDK + JSRs)</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">For business reasons would like to see as JSRs – standards are important to ensure safety.</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Development as a JSR protects implementers from litigation.</span></font></font></font>

# <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Board support packages</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Access to the technology blocks adoption. Downloads not available for broad support package. It is not a box package – need easier download availability. Access will increase demand and adoption.</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">There is a need for a binary to download with porting compatibility.</span></font></font></font>

# <font color="#353744"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Other considerations</span>**</font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Different set of requirements</span>**</font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">JSR Leadership</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">Does Oracle want to lead or allow others to lead? It is possible, and others have led JSRs in the JavaME space in the past. Most members are the call would be happy to participate in JSR activity, but not necessarily lead. Mike offered Eclipse as a potential source for communing members interested in leading JSRs.</span></font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Market demand</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[Is there a business demand for Java as IoT platform? Why have this as Java and not OSGi, or any other thing running on top of the Java SE JVM]</span></font></font></font>

## <font color="#00ab44"><font face="Proxima Nova"><font size="4" style="font-size: 14pt">**<span style="background: transparent">Competing technologies</span>**</font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">There is competition from embedded JavaScript, Android and Node.js – perceived as less expensive, hip, mainstream and accessible. [How are they using Node JS on IoT?]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[AndroidThings wants to be Java ME]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[Windows IoT]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">[Ubuntu Snap framework]</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">There are some de facto developer and runtime environments at Android/iOS, so we do not need Java ME in this area.</span></font></font></font>

<font color="#353744"><font face="Proxima Nova"><font size="2" style="font-size: 11pt"><span style="background: transparent">OSGi as a framework to supplement Java SE with Java ME-like services (provisioning, configuration)</span></font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Next Steps:</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Refine to publish for discussion at EC meeting.</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5" style="font-size: 18pt">Next WG Meeting 8 March 9:00 PST.</font></font></font>