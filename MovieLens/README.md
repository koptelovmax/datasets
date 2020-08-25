This repository contains MovieLens network

## The folder includes:
- **user_sim.zip** - user similarity network
- **movie_sim.zip** - movie similarity network
- **user-movie_int.zip** - binarised user-movie interaction network

## The data format: *item1* *item2* *value* 
- *item1*, *item2* - *u*+id for a user or *m*+id for a movie, *id* - MovieLens identifier*
- *value* - numeric value from 0 to 1

(*) Note that the identifiers were mapped to consecutive integers, i.e. u0, u1, u2, ... , m0, m1, m2, ... .

For more details see the article submitted to Network Science.
