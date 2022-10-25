FROM openjdk:11


# Copy the jar to the production image from the builder stage.
COPY  target/UCS.jar /UCS.jar

# Run the web service on container startup.
CMD java  -jar /UCS.jar
