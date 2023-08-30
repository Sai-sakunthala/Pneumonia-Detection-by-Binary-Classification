# Pneumonia-Detection-by-Binary-Classification
The codes for annealing methods are provided here in the '.ipynb' format

The code can be directly copied and run in google colab. Downloading of data is not required. Instead get the unique 'kaggle.json' file for your account from Kaggle website. The data is directly taken from kaggle using the account specific 'kaggle.json' file

The code 'Simulated_ann_final.ipynb' is the code for implementing binary classification using simulated annealing using D-Wave neal package

The code 'Quantum_ann_final.ipynb' is the code for implementing binary classification using quantum annealing using D-Wave Leap cloud. For using this we need the API token from your Leap account. The API token can be specified while runninthe command '!dwave ping'. In this code we have used 'Advantage_system6.2'. To change the solver, specify the solver name in the following line

DWavesampler = EmbeddingComposite(DWaveSampler(solver='Advantage_system6.2'))

The code 'GAMA_sim_final.ipynb' is the code for implementing binary classification using simulated annealing along with GAMA algorithm using D-Wave neal package

The code 'GAMA_quantum_ann_final.ipynb' is the code for implementing binary classification using quantum annealing along with GAMA algorithm using D-Wave neal package
