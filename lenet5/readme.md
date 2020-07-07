# Lenet 5

## Paper

[Gradient-based learning applied to document recognition - Yann Lecun, 1998](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf)

## Execution

1. In terminal, run:

    docker-compose up --build --force-recreate

2. In a second terminal, run:

    docker exec -it lenet5_lenet5_1 /bin/bash

* Notes: The container name `lenet5_lenet5_1` can be varied on difference system. The best practice is to type lenet5_ and then press `Tab` button to get the exact name.

3. The previous command open a new bash. Inside that bash, run:

    python3 -m visdom.server

3. From your host machine, browse:

    http://localhost:8888/model.ipynb