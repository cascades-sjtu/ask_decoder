# play_with_ask

* NIS-8016 Lab A

* code:
    * Recv.grc/py: Receive signals and match with ASK button using HackRF and GNU radio
    * Send.grc/py: Send signals using vector source deocded manually
    * Decode.grc/py: Decode signals following ASK/OOK coding rules

* [data](https://jbox.sjtu.edu.cn/l/610CT9):

    * *.txt: manually decoded bit vector of ASK/OOK signals
    * *.cf32: complex format signals received by HackRF, can be analyzed by inspectrum
    * *.bin: binary format stream generated by Recv.grc, follows the same pattern with *.txt 

* [video]: