<h1>SoftwareRunActionProfile</h1>

SoftwareRunActionProfile is profile for <a href='../../Types/SoftwareRunAction'>maSMP:SoftwareRunAction</a>

The act of testing an object according to its specifications. For instance, testing a software with a particular testType using a specific testInput and getting a specific testOutput (aka result).

##Minimum properties
      Property Expected Type                                Description Cardinality
0  softwareRun                Software executed by this running action.         one
##Recommended properties
  Property Expected Type                                                                                                                                                    Description Cardinality
0   result                                                                                                                 The result produced in the action. e.g. John wrote *a book*.        many
1   sameAs                URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website.        many
##Optional properties
                Property Expected Type                                                                                                         Description Cardinality
0        operatingSystem                       If the running was done by a direct execution (rather than via a container), indicate the operating system.         one
1  processorRequirements                If the running was done by a direct execution (rather than via a container), indicate the processor specification.         one
2        runtimePlatform                       If the running was done by a direct execution (rather than via a container), indicate the runtime platform.         one
3           runContainer                                              If the running was done using a container, such container should be pointed to here.         one
4               runInput                                                                               Actual input used by this action to run a software.        manythis is it!!!