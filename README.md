# Lets-Talk-Tempo
HCI (CS 395T) Project, Implementation of an LLM wrapper to make a Conversational Agent who's speech rate adapts to follow the users in a smooth and "natural" manner. This app has only really been testes on Mac and Linux.

## Instructions to run the project locally:
1. Clone the project with the following command: `git clone --recurse-submodules -j8 git@github.com:AbbhinavJayaraman/lets-talk-tempo.git`
2. Make sure to switch to the `final` branch. `git switch final`
3. Install Ollama, which can be done with the Homebrew/Linuxbrew package manager for Mac and Linux. `brew install ollama` 
4. Pull and test the Llama LLM. `ollama pull llama3.2:1b` to download & install, and then try chatting with it with `ollama run llam3.2:1b` to verify functionality
5. Make sure that the portaudio library is installed via your native package manager (for Linux) and via Homebrew (for Mac: `brew install portaudio`)
6. Set up a virtual environment. We made use of python verion 3.9.21 (installed via Homebrew/Linuxbrew), and recommend you do so too.
7. Activate virtual environment.
8. Make sure you have some way to run Jupyter Notebooks. `pip install ipykernel ipywidgets` should do the trick
9. Run the cells of the notebook. The last cell will prompt you to hit the enter key to start voice dictation, and again to end it. 
10. Wait for the response. 
11. When you wish to end the conversation, you will interrupt the last cell while you are being prompted to hit the enter key to start dictation (don't hit the enter key though). Then, you can hit the Escape key exit.

If you want to see our Web App implementation, you can do so [here](https://github.com/i-am-ami/hci-rava-project/tree/deployable)
