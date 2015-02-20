
A GUI to configure a xslt-transfomer.

Compile with

    mvn install


and start with

    cd target
    java -jar p3-xslt-transformer-factory-gui-*-jar-with-dependencies.jar


Now you should be able to access the service at:

    http://localhost:8204/?transformerBase=http://sanbox.fusepool.info:8164&transformerRegistry=http://sandbox.fusepool.info:8181/ldp/tr-ldpc#