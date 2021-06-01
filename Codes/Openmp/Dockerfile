FROM gcc:latest

COPY . /home/k180279/pdcproject

WORKDIR /home/k180279/pdcproject

RUN gcc -o Open openmp.c -fopenmp

CMD [ "./Open" ]

