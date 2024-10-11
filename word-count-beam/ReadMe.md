# Beam with Java sample for learning

Running the beam commands - 
1. mvn compile exec:java -Dexec.mainClass=org.apache.beam.examples.WordCount \
   -Dexec.args="--inputFile=sample.txt --output=counts" -Pdirect-runner
2. mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
   -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner
3. gradle clean execute -DmainClass=org.apache.beam.examples.WordCount \
   --args="--inputFile=sample.txt --output=counts"