FROM       ubuntu:14.04
MAINTAINER Shander Lam <shanderlam@gmail.com>

RUN apt-get update && apt-get install -qy curl

RUN echo 'deb http://packages.erlang-solutions.com/ubuntu trusty contrib' | tee /etc/apt/sources.list.d/erlang-solutions.list
RUN curl http://packages.erlang-solutions.com/ubuntu/erlang_solutions.asc | apt-key add -

RUN apt-get update && apt-get install -qy erlang
