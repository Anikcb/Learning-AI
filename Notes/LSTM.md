## How LSTM work?
![LSTM](https://github.com/Anikcb/Learning-AI/blob/main/Readme%20Images/lstm.png?raw=true)

In LSTM, the system stores LTM line along with the short-term memory space. When the system thinks that some specific words are important for long term  then it transfers the words from STM to the LTM. If the words are not important then they will be removed eventually from the LTM  or they will be stored till the end of the process.

![LSTM Basic](https://github.com/Anikcb/Learning-AI/blob/main/Readme%20Images/lstm-normal.png?raw=true)

Need to handle an architecture for the communication between the STM and LTM.

![LSTM Inside](https://github.com/Anikcb/Learning-AI/blob/main/Readme%20Images/lstm-inside.png?raw=true)

Forget gate remove the words that are not important for the future based on current input. Input gate add the new words based on current input. Output gate provide the output at the last based on the current input and the LTM data.
