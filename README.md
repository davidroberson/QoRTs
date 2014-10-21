QoRTs
=====

Quality of RNA-Seq Toolset

INSTALLATION:
The R package can be installed in R using the command:
install.packages("QoRTs_0.0.23.tar.gz", repos = NULL, type="source")
or using the command-line command, in linux:
R CMD INSTALL QoRTs_0.0.23.tar.gz

The java jar file does not need to be installed.
Just execute it using the java command:
java -jar /path/to/jarfile/QoRTs.jar QC input.bam anno.gtf.gz /output/dir/

MORE INFORMATION:
For more information, see the QoRTs vignette, QoRTs-vignette.pdf
Additional options and syntax information for the java utility can be
found using the command:
java -jar /path/to/jarfile/QoRTs.jar QC ?

Options and information about other sub-utilities within the java utility
can be found using the command:
java -jar /path/to/jarfile/QoRTs.jar ?

And for each sub-utility:
java -jar /path/to/jarfile/QoRTs.jar utilname ?

Options and information for individual R functions can be found using
the R command:
help(functionname);

LEGAL:
This software is "United States Government Work" under the terms of the United
States Copyright Act. It was written as part of the authors’ official duties
for the United States Government and thus QoRT Package User Manual cannot be
copyrighted. This software is freely available to the public for use without a
copyright notice. Restrictions cannot be placed on its present or future use.
Although all reasonable efforts have been taken to ensure the accuracy and
reliability of the software and data, the National Human Genome Research
Institute (NHGRI) and the U.S. Government does not and cannot warrant the
performance or results that may be obtained by using this software or data.
NHGRI and the U.S. Government disclaims all warranties as to performance,
merchantability or fitness for any particular purpose.
In any work or product derived from this material, proper attribution of the
authors as the source of the software or data should be made, using "NHGRI
Genome Technology Branch" as the citation.

NOTE: The scala package includes (internally) the sam-JDK library
(sam-1.113.jar), from picard tools. The MIT license and copyright
information can be accessed using the command:
java -jar /path/to/jarfile/QoRT.jar ? samjdkinfo