1. Data_Collection: 

   * dataset_collection.ipynb: the code mainly about collecting the datasets including clean some missing data
2. Dataset_Fusion: compare TF-IDF and TINYBERT, and use the best method to fuse two independent datasets
   * datasets_fusion.ipynb: codes about comparing two methods 
3. Data_preprocessing: extract the image features and text features, and then save as H5 files
   * pre_processing.ipynb: codes about extract the features including the transformation of audio form, and even extract Melody objects
4.  EDA: exploratory data analysis for text content
   * EDA.ipynb: codes about text content analysis
5. Models: five models including setting up, training and testing
   * model_Orion.ipynb
   * model_Phoenix.ipynb
   * model_Draco.ipynb
   * model_Lyra.ipynb
   * model_Pegasus.ipynb
   * SoundFont_files: sf3 file in it will be used when convert the NoteSequence into audio
7. Evaluation: mainly for evaluate model Lyra and Pegasus
   * evaluation.ipynb: codes about evaluation
8. trained_models: all the files saved related parameters weights
   * my_vae_weights23.h5 : Model Orion
   * my_vae_weights24.h5 : Model Phoenix
   * my_vae_weights20.h5 : Model Draco
   * my_vae_weights21.h5 : Model Lyra
   * my_vae_weights22.h5 : Model Pegasus