# digtest1

#Run this command under the same directory of Dockerfile

docker build -t digtest1 .

docker run -p 10001:3000 digtest1
