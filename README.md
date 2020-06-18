# TCR-antigen-LSTM-model
All those ipynb files are largely similar, but modified for different purposes as the file name decribed.TCR-antigen bi LTSM RNN trained with donor 1 CMV final.ipynb has the most detailed explanation for codes. The python script takes the data vdj_v1_hs_aggregated_donor#_binarized_matrix.csv, blosum.txt, and the saved model file in the checkpoint folder as the input.

# training with CMV antigens
TCR-antigen bi LTSM RNN trained with donor 1 CMV final.ipynb contains the python script to train the model using donor 1 data with CMV antigens only. 

TCR-antigen bi LTSM RNN test with donor 2-4-CMV.ipynb contains the python script to use the trained model to test with the donor 2-4 data on CMV antigens only.

The checkpoints folder contains all the historical models I have used and tested.

The best one so far is 'LTSM_with_electro_size_donor1_no_repetition_all_CMV_antigen_complex_form' for CMV.
# training with all antigens
Futhermore, I also trained data with all the antigens with the same model architecture.
TCR-antigen bi LTSM RNN trained with donor 1-all antigen.ipynb includes the training and testing with donor 1 data.
TCR-antigen bi LTSM RNN test with donor 2 -all antigen.ipynb includes the testing result on all antigens from donor 2 data by using the model trained with all antigens.

The best model is 'LTSM_with_electro_size_donor1_no_repetition_all_CMV_antigen_complex_form_trained_with_all_data'
# custom training and testing template
I also generated the scripts for customized combinations of MHC and antigen types to train and test.

The files are:
TCR-antigen bi LTSM RNN trained with donor 1 Template training.ipynb and TCR-antigen bi LTSM RNN test with differenet donor Template.ipynb

These scripts allow you to compare the model specific to the antigens from one disease or the MHC with the generalized model trained with all data.
Please put the MHC and antigen choices in the first coding cell in the script. Please also paste the optimal threshold value from the training script when use the testing script.
