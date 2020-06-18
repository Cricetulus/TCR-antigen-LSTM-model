# TCR-antigen-LSTM-model
TCR-antigen bi LTSM RNN trained with donor 1 CMV final.ipynb contains the python script to train the model using donor 1 data with CMV antigens only. 

TCR-antigen bi LTSM RNN test with donor 2-4-CMV.ipynb contains the python script to use the trained the model to test with the donor 2-4 data on CMV antigens only.

Checkpoints folder contains all the historical model I have used and tested.

The best one so far is 'LTSM_with_electro_size_donor1_no_repetition_all_CMV_antigen_complex_form' for CMV.

Futhermore, I also trained data with all the antigens with the same model architecture.
TCR-antigen bi LTSM RNN trained with donor 1-all antigen.ipynb includes the training and testing with donor 1 data.
TCR-antigen bi LTSM RNN test with donor 2 -all antigen.ipynb includes the testing result on all antigens from donor 2 data by using the model trained with all antigens.
