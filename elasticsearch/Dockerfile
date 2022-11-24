ARG ELK_VERSION
FROM elasticsearch:${ELK_VERSION}

ARG ELK_VERSION
RUN echo y | elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v${ELK_VERSION}/elasticsearch-analysis-ik-${ELK_VERSION}.zip

EXPOSE 9200 9300
