# specify base image
FROM spmallick/opencv-docker:opencv

# Don't change dir or copy files. Instead use docker run -v to link files
#WORKDIR ~/power_mgmt_infra/src/sorter/docker/
WORKDIR /tmp
#COPY . .

# install dependencies
RUN jupyter notebook
