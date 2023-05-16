# learning-pyspark

Steps for running Pyspark using Docker

1. Get the Docker image
   ```
   docker pull jupyter/pyspark-notebook
   ```

2. Run Docker with persistence
   ```
   docker run -it --rm -p 8888:8888 -v $HOME/Projects/repo/learning-pyspark:/home/jovyan jupyter/pyspark-notebook
   ```

3. Test the Docker image
   ```
   Run the notebook test_pyspark.ipynb
   ```