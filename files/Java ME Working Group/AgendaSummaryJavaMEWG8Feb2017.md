<font color="#000000"><font face="Times-Roman, serif"><font size="7">**Java ME Working Group Meeting Minutes**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Date**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Wednesday, 8 February 2017, 9:00 am PST</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Location**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Teleconference</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Agenda**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5"><span style="font-weight: normal">Review EC Meeting discussion on Java ME from the London JCP EC f2f Meeting. Discuss requirements and importance of Java ME.</span></font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Attendees**</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Heather VanCura</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Patrick Curran</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Leonardo Lima</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Calinel Pasteanu</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Hendrik Hoefer</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Thomas Lampart</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Mike DeNicola</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Michael Berg</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Werner Keil</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="6" style="font-size: 27pt">**Minutes**</font></font></font>

<font color="#000000"><font face="Times New Roman, serif"><font size="5"><span style="font-weight: normal">Leonardo agreed to lead the discussion. We reviewed the discussion of the Java ME item from the January JCP EC f2f Meeting.</span></font></font></font>

<font color="#000000"><font face="Times New Roman, serif"><font size="5"><span style="font-weight: normal">Java as an IoT platform. Goals and requirements for Java ME, technical and non-technical, including business aspects, market demand and what is preventing adoption of current Java ME platform, Java ME 8\. Why would a Java ME 9 do better in adoption than Java ME 8.</span></font></font></font>

<font color="#000000"><font face="Times New Roman, serif"><font size="5"><span style="font-weight: normal">We discussed different options today and what have members done with Java ME. What are the differences between Java SE 9 and Java ME and why Java SE 9 might not meet requirements of this market and why Java ME is important. Is there a need for new JSRs? Calinel agreed that t</span></font></font></font><font color="#000000"><font face="Times New Roman, serif"><font size="5"><span style="font-weight: normal">here is one gap, and a “low version” is needed, API and semantic parity is needed. There are two possible ways of doing that: new from scratch, or update Java ME. V2COM uses older version, Gemalto doesn’t use Java ME 8\. Why the Java ME licensees haven’t upgraded to Java ME 8. From the IoT side/libraries, there’s no explicit need of platform support, no need to have a JSR for the protocols, it’s already available from Oracle for download from the website.</span></font></font></font>

<font face="Times New Roman, serif"><font size="5">Thomas confirmed that Java ME 3 is proven and stable, clients like it. There’s no market demand for Java ME 8, but that might change in the future - clients don’t want to have two code-bases and so continuing the convergence of java ME/SE is a good thing. There’s no indication of new Java ME work, so using Java ME 8 seems not future-proof. If there's a Java 9 in the works, continuity would improve perception. Java ME 8 adoption issues for Gemalto are just non-technical, technically it is good and everything they wanted is in there. What kept Gemalto from using Java ME 8 were non-technical business reasons. A model like SE development would help Java ME development and adoption, as no one can do any work but Oracle - all others would have to start from scratch.</font></font>

<font face="Times New Roman, serif"><font size="5">We discussed Java as an IoT platform. Hendrik discussed that we need a version of Java for ow processing power systems. The name is not important, not GUI, but a very small run time would be needed. This version have to be something that is in line with SE, feature wise - gave an example of different String file. Java 9 with its module system might be a better solution; a fork of Java is not a good solution. Requirements: fast startup time, low cost. JAR File format is an aggressor to startup time, for example. There’s no currently suitable solution for 32-bit, 200MHz processors - they go to C/C++. As an alternative to evolving Java ME, can we take Java 9 and make it fit in Java ME specs. Java ME adoption might not be great because of its licensing model. Look at the requirements: why SE 9 does or does not meet the requirements, and look into the future for Java 10\. It’s a lot harder to sell embedded runtime, there’s a need to recompile and conform to processor specs.</font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5"><span style="font-weight: normal">Next Steps:</span></font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Each WG member to submit list of technical requirements for Java ME, include from perspective of things not provided by current Java ME.</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5">Each EG member to submit list of non-technical market requirements.</font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5"><span style="font-weight: normal">Send lists to Heather before meeting on Wednesday to publish for discussion at WG meeting.</span></font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5"><span style="font-weight: normal">Present progress at the 14 February JCP EC Teleconference at 8:00 PST.</span></font></font></font>

<font color="#000000"><font face="Times-Roman, serif"><font size="5"><span style="font-weight: normal">Next WG Meeting 15 February 9:00 PST.</span></font></font></font>