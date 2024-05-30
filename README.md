# Project abstract
This work explores different network architectures for keyword spotting (KWS), which has applications in technologies such as smart home devices, automotive systems, and virtual assistants like Siri and Alexa. Since many of the devices that implement these systems demand small memory footprints and low computational requirements, I focused on models that comply with these characteristics. I devised an architecture that combines convolutional operations, recurrent neural networks with an attention mechanism, and deep residual networks. Following a common feature extraction module (the MFCCs), I compared this design against two models: the powerful AttRNN from the literature, and a transformer's encoder adapted for speech command recognition, which I also developed. Despite its reduced parameter count, one version of my hybrid approach outperformed the AttRNN in terms of accuracy and F-score, although the latter model exhibited shorter training times. Additionally, two other variants of my proposed approach demonstrated competitive performance, comparable to the one in the literature, with 20\% fewer parameters.

## Repository description
- A PDF report with a complete explanation of what was done.
- The Jupyter Notebook with the full implementation.

This was the final project for the [Deep Learning and Human Data Analytics](https://en.didattica.unipd.it/off/2022/LM/SC/SC2377/002PD/SCQ2101305/N0) course of my master's degree.
