FROM postgres

RUN apt-get -o Acquire::Check-Valid-Until=false update

# Install other dependencies
RUN apt-get update && \
    apt-get install -y git build-essential postgresql-server-dev-all
