# atom-rml-test
Test RML mapping from AtoM2 data schema

## Usage examples with rmlmapper

### N-Quad serialization (default)
    java -jar rmlmapper-4.3.3-r92.jar -m atom-rml-test/information_object.ttl -o information_object.nq

### JSON-LD serialization
    java -jar rmlmapper-4.3.3-r92.jar -m atom-rml-test/information_object.ttl -o information_object.jsonld -s jsonld