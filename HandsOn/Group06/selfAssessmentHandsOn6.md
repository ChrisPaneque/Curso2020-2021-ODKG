# Hands-on assignment 4 – Self assessment

## Checklist

**Every RDF file:**

- [X] Uses the .nt extension
- [X] Is serialized in the NTriples format
- [X] Follows the resource naming strategy
- [X] Uses class and property URIs that are the same as those used in the ontology

**Every URI in the RDF files:**

- [X] Is "readable" and has some meaning (e.g., it is not an auto-increased integer) 
- [X] Is not encoded as a string
- [X] Does not contain a double slash (i.e., “//”)

**Every individual in the RDF files:**

- [X] Has a label with the name of the individual
- [X] Has a type

**Every value in the RDF files:**

- [X] Is trimmed
- [X] Is properly encoded (e.g., dates, booleans)
- [X] Includes its datatype
- [X] Uses the correct datatype (e.g., values of 0-1 may be booleans and not integers, not every string made of numbers is a number)

## Comments on the self-assessment
Subclasses of type contract has been added to the ontology (work contract, supplies contract and service contract) but we do not know how to split the contract class in to these subclasses having the contract type column. (if statement in mapping?)
