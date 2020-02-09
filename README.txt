# ml-assignment-1

## How to run the notebook [Automatic]
1. Install latest version of Anaconda 3 from https://www.anaconda.com/
2. Clone the project repository from https://github.com/fedme/ml-assignment-1
3. Open an Anaconda 3 prompt
4. From the prompt, browse to the folder where you cloned the repository
5. Run the following command to create the conda environment:
    ```
    conda env create --file=environment.yaml
    ```
6. Activate the newly created environment:
    ```
    activate fmeini3-ml-assignment-1
    ```
7. Start Jupyter lab:
    ```
    jupyter lab
    ```
8. A browser window will open and you will be able to see the notebook.

## How to run the notebook [Manual]
In case the previous automatic method does not work, you can follow these manual steps to create the environment:
1. Install latest version of Anaconda 3 (not Miniconda) from https://www.anaconda.com/
2. Clone the project repository from https://github.com/fedme/ml-assignment-1
3. Open an Anaconda 3 prompt
4. Add the `forge` channel to Anaconda's repository:
    ```
    conda config --add channels conda-forge
    conda config --set channel_priority strict
    ```
5. Update all Anaconda packages by running the following command (this might take several minutes):
    ```
    conda update --all
    ```
6. Install Keras by running the following command
    ```
    conda install keras
    ```
7. From an Anconda 3 prompt, browse to the folder where you cloned the repository
8. Start Jupyter lab:
    ```
    jupyter lab
    ```
9. A browser window will open and you will be able to see the notebook.
