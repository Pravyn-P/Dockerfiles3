### ARG
ARG is used to supply the variables at the time of image creation only. But ENV is used to supply the variables at both image level and container level.
ARG is the only instruction used before FROM. ARG declared before can't be accessed after FROM.