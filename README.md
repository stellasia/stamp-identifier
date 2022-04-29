# Stamp Identifier


**WARNING** data is not included in this repo, you'll have to build your own dataset.


## Starting Weaviate

Just use the docker-compose file in this folder:

    docker-compose up


## Run Python code


First, install dependencies:

    pip install jupyter weaviate-client opencv-python ipyplot

Then, start jupyter server:

    jupyter notebook
    
And visit: http://localhost:8888/

Two notebooks are available:
- `Feed_Data` will populate the database with some data
- `Stamp_Search_Engine_with_Weaviate` will search the database for the stamp most similar to a user provided image


## Resources

- Weaviate: https://weaviate.io/developers/weaviate/current/getting-started/quick-start.html
- OpenCV: https://github.com/opencv/opencv-python
