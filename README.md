# docker-convenience-scripts

This repository will contain different convenience scripts for docker I have gathered over time.

## docker_clone_volume.sh

The purpose for this script is that I can easily create a clone of an existing docker data with
a new name. This will allow me to create a duplicate of an existing data volume I use in the
production environment of my blog for example and take that duplicate to my development version 
to ensure I have the latest production data also at development

## docker_get_data_volume_info.sh

The purpose for this script is that I can easily get a list of details for all data volumes 
that are currently present. The information that is provided to the user as output is per 
data volume the current size of the data volume and a list of stopped or running containers 
that have a link to this data volume, including the image corresponding to the container.
The script allows me to easily see if there are some data volumes on my disk that are taking
up a lot of space and are not needed anymore.
