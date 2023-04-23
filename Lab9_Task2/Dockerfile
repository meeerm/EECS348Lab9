# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY prog.c .
# Compile the C program
RUN gcc -o prog prog.c
# Set the command to run when the container starts
CMD ["./prog"]
