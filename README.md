# mifid2

https://fasterxml.github.io/jackson-databind/javadoc/2.7/com/fasterxml/jackson/databind/SerializationFeature.html#ORDER_MAP_ENTRIES_BY_KEYS

task testBoth {
    doFirst {
      println 'This is executed first during the execution phase.'
    }
    doLast {
      println 'This is executed last during the execution phase.'
    }
    println 'This is executed during the configuration phase as well.'
}
