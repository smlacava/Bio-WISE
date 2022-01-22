# <span style="color:blue">Biometric Recognition With Embedded PAD: Simulator</span>

The diffusion of fingerprint **verification systems** for security applications makes it urgent to investigate the **embedding** of software-based **presentation attack detection algorithms** (**PAD**) into such systems. Companies and institutions need to know whether such integration would make the system more “secure” and whether the technology available is ready, and, if so, at what operational working conditions. Despite significant improvements, especially by adopting deep learning approaches to fingerprint PAD, current research did not state much about their effectiveness when embedded in fingerprint verification systems. We believe that the lack of works is explained by the lack of instruments to investigate the problem, that is, modeling the cause-effect relationships when two non-zero error-free systems work together. 

Accordingly, this [**performance simulator**](https://livdet.pythonanywhere.com/) investigates the fusion of PAD into verification systems based on the probabilistic modeling of the relationships among the Receiver Operating Characteristics (ROC) of the two individual systems when PAD and verification stages are implemented sequentially.

For this reason, we developed a **web application** making the simulator usable by everybody, in a straightforward, flexible, and widespread way which takes into account the prior probability of being attacked by spoofs and the specific operational point chosen for the PAD for analyzing the performance of verification systems with embedded PAD:

<p align="center">
  <img src="https://github.com/smlacava/wapp/blob/main/simulator.png" width="800" title="Web App">
</p>

<p align="center">
  <img src="https://github.com/smlacava/wapp/blob/main/performance.png" width="800" title="Performance">
</p>


Go to the [**Wiki**](https://github.com/smlacava/wapp/wiki) for further information.	        
