# What kind of image are we pulling for this microservice? Get the latest version.
# FROM <YOUR CODE HERE>

ADD . /go/src/github.com/BearCloud/fa20-project-dev/backend/posts

WORKDIR /go/src/github.com/BearCloud/fa20-project-dev/backend/posts

# Download the dependencies
# RUN <YOUR COMMAND HERE>

# Build the go project into "main"
# RUN <YOUR CODE HERE> .

EXPOSE 81

ENTRYPOINT [ "./main" ]
