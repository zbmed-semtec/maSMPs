<h1>SoftwareTestActionProfile</h1>

SoftwareTestActionProfile is profile for <a href='../../Types/SoftwareTestAction'>maSMP:SoftwareTestAction</a>

The act of testing a software according to its specifications. For instance, testing a software with a particular testType using a specific testInput and getting a specific testOutput (aka result).

##Minimum properties
         Property Expected Type                                           Description Cardinality
0  softwareTested                         Link to the software tested by this action.         one
1        testType                The type of test that it is performed on the object.         one
##Recommended properties
      Property Expected Type                                                                                                                                                    Description Cardinality
0       result                                                                                                                 The result produced in the action. e.g. John wrote *a book*.        many
1  description                                                                                                                                                   A description of the item.         one
2       sameAs                URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website.        many
##Optional properties
    Property Expected Type                                                                                                                                                                                       Description Cardinality
0  testInput                Input used to performed the test. Some tests may not require any input, some may require multiple ones. If order or grouping is important in the case of multiple inputs, a ListItem could help.        many
1     target                                                                                                                                                                    Indicates a target EntryPoint for an Action.        manythis is it!!!