# java-speech-api-demo

A sample app demonstrating the Google V2 speech API

Once built, you should be able to run it as follows (on Linux at least):

    java -cp ./target/hello-world-1.0.0-SNAPSHOT.jar:$HOME/.m2/repository/com/darkprograms/speech/java-speech-api/1.13.0-SNAPSHOT/java-speech-api-1.13.0-SNAPSHOT.jar:$HOME/.m2/repository/org/plwww/java-flac-encoder/0.3.2-SNAPSHOT/java-flac-encoder-0.3.2-SNAPSHOT.jar:$HOME/.m2/repository/org/json/json/20150729/json-20150729.jar org.amplexus.speechdemo.HelloWorld

It will listen on your microphone for a few seconds before sending whatever it hears to Google for recognition, and will display Google's response.
