FROM omslab/oms:beta

MAINTAINER Francesco Serafin <francesco.serafin.3@gmail.com>, Olaf David <odavid@colostate.edu>

ENV simulation=/work/simulation/Simulation.sim

COPY entrypoint.sh ./
COPY src_extra/ ./src_extra/

RUN set -x \
        && chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
