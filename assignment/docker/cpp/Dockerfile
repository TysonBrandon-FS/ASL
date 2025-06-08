FROM gcc:13.2.0
WORKDIR /usr/src/app
COPY hello.cpp .
RUN g++ hello.cpp -o hello
CMD ["./hello"] 